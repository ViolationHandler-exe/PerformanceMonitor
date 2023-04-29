# Performance-Monitor
Performance Monitor is a plugin for the video game Rust that is used to monitor your servers entities and plugins. It is originally from [uMod](https://umod.org/plugins/performance-monitor#license) with optimizations.

It took 22 minutes on a fresh 4500 sized server. On a battlefield 3 years ago it apparently took 2 days. It now takes less than a second typically. It has been exponentially optimized and is actually usable. However, I am not sure whether you would find the data useful, if you do, then go ahead and use it, if not, then don't.

Example Output as json File:
```json
{
  "Online players": 1,
  "Offline players": 0,
  "Entities report": {
    "Total": 121026,
    "Owned": 0,
    "Unowned": 121026,
    "List": {
      "birch_medium_temp": {
        "Total": 5221,
        "Owned": 0,
        "Unowned": 5221
      },
      "orebonus_generic": {
        "Total": 3342,
        "Owned": 0,
        "Unowned": 3342
      },
      "codelockedhackablecrate_oilrig": {
        "Total": 2,
        "Owned": 0,
        "Unowned": 2
      },
      "longsword.entity": {
        "Total": 2,
        "Owned": 0,
        "Unowned": 2
      },
      "generic_deploy": {
        "Total": 2,
        "Owned": 0,
        "Unowned": 2
      },
      "grenade.flashbang.entity": {
        "Total": 2,
        "Owned": 0,
        "Unowned": 2
      }
    }
  },
  "Plugins report": [
    "AdvAirstrike (0.1.78), Total Hook Time = 0.3371621",
    "NTeleportation (1.7.1), Total Hook Time = 0.260778900000016",
    "KillCommand (0.0.1), Total Hook Time = 0.0047573",
    "DontTargetMe (1.1.4), Total Hook Time = 0.0022716"
  ],
  "Performance report": {
    "frameID": 1427590,
    "frameRate": 208,
    "frameTime": 4.815318,
    "frameRateAverage": 203.733337,
    "frameTimeAverage": 4.93812275,
    "memoryUsageSystem": 3722,
    "memoryAllocations": 2218,
    "memoryCollections": 177,
    "loadBalancerTasks": 0,
    "invokeHandlerTasks": 12879,
    "workshopSkinsQueued": 0,
    "ping": 0,
    "gcTriggered": false,
    "performanceSample": {
      "UpdateCount": 0,
      "FixedUpdateCount": 0,
      "RenderCount": 0,
      "PreCull": "00:00:00",
      "Update": "00:00:00",
      "LateUpdate": "00:00:00",
      "Render": "00:00:00",
      "FixedUpdate": "00:00:00",
      "NetworkMessage": "00:00:00",
      "TotalCPU": "00:00:00",
      "CpuUpdateCount": 0
    }
  }
}
```
