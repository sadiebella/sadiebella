- 👋 Hi, I’m @sadiebella
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
sadiebella/sadiebella is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Can someone tell me if my iPhone has been hacked please 
I found this and other things in the analytics 

("app_name":"duetexpertd","timestamp":"2021-12-18 14:46:33.00 +0000","app_version":"","slice_uuid":"378b0e13-1d95-392e-948b-ef4f7dc29fdc","build_version":"","platform":2,"share_with_app_devs":0,"is_first_party":1,"bug_type":"309","os_version":"iPhone OS 15.1 (19B74)","incident_id":"C7E7959D-760F-48DD-BB95-5D260C5663A1","name":"duetexpertd"}
{
  "uptime" : 1700,
  "procLaunch" : "2021-12-18 14:22:21.0995 +0000",
  "procRole" : "Unspecified",
  "version" : 2,
  "userID" : 501,
  "deployVersion" : 210,
  "modelCode" : "iPhone9,4",
  "procStartAbsTime" : 5992103091,
  "coalitionID" : 309,
  "osVersion" : {
    "isEmbedded" : true,
    "train" : "iPhone OS 15.1",
    "releaseType" : "User",
    "build" : "19B74"
  },
  "captureTime" : "2021-12-18 14:46:32.6913 +0000",
  "incident" : "C7E7959D-760F-48DD-BB95-5D260C5663A1",
  "bug_type" : "309",
  "pid" : 377,
  "procExitAbsTime" : 40830993635,
  "cpuType" : "ARM-64",
  "procName" : "duetexpertd",
  "procPath" : "\/usr\/libexec\/duetexpertd",
  "parentProc" : "launchd",
  "parentPid" : 1,
  "coalitionName" : "com.apple.duetexpertd",
  "crashReporterKey" : "1fc51a4d130e1de2aca6f6278a719a724a09347d",
  "basebandVersion" : "6.00.00",
  "vmRegionInfo" : "0x28 is not in any region.  Bytes before following region: 4299341784\n      REGION TYPE                 START - END      [ VSIZE] PRT\/MAX SHRMOD  REGION DETAIL\n      UNUSED SPACE AT START\n--->  \n      __TEXT                   10042c000-100430000 [   16K] r-x\/r-x SM=COW  ...c\/duetexpertd",
  "isCorpse" : 1,
  "exception" : {"codes":"0x0000000000000001, 0x0000000000000028","rawCodes":[1,40],"type":"EXC_BAD_ACCESS","signal":"SIGSEGV","subtype":"KERN_INVALID_ADDRESS at 0x0000000000000028"},
  "termination" : {"flags":0,"code":11,"namespace":"SIGNAL","indicator":"Segmentation fault: 11","byProc":"exc handler","byPid":377},
  "vmregioninfo" : "0x28 is not in any region.  Bytes before following region: 4299341784\n      REGION TYPE                 START - END      [ VSIZE] PRT\/MAX SHRMOD  REGION DETAIL\n      UNUSED SPACE AT START\n--->  \n      __TEXT                   10042c000-100430000 [   16K] r-x\/r-x SM=COW  ...c\/duetexpertd",
  "faultingThread" : 3,
  "threads" : [{"id":9023,"queue":"com.apple.main-thread","frames":[{"imageOffset":2832,"symbol":"mach_msg_trap","symbolLocation":8,"imageIndex":0},{"imageOffset":4404,"symbol":"mach_msg","symbolLocation":72,"imageIndex":0},{"imageOffset":27328,"symbol":"__CFRunLoopServiceMachPort","symbolLocation":368,"imageIndex":1},{"imageOffset":43944,"symbol":"__CFRunLoopRun","symbolLocation":1184,"imageIndex":1},{"imageOffset":122236,"symbol":"CFRunLoopRunSpecific","symbolLocation":572,"imageIndex":1},{"imageOffset":98316,"symbol":"-[NSRunLoop(NSRunLoop) runMode:beforeDate:]","symbolLocation":232,"imageIndex":2},{"imageOffset":13316,"symbol":"main","symbolLocation":320,"imageIndex":3},{"imageOffset":98704,"symbol":"start","symbolLocation":444,"imageIndex":4}]},{"id":34175,"frames":[{"imageOffset":18920,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":5}]},{"id":34193,"queue":"ATXUpdatePredictionsManager","frames":[{"imageOffset":49868,"symbol":"-[__NSDictionaryM dealloc]","symbolLocation":144,"imageIndex":1},{"imageOffset":49868,"symbol":"-[__NSDictionaryM dealloc]","symbolLocation":144,"imageIndex":1},{"imageOffset":58316,"symbol":"-[EKObject .cxx_destruct]","symbolLocation":40,"imageIndex":6},{"imageOffset":28432,"symbol":"object_cxxDestructFromClass(objc_object*, objc_class*)","symbolLocation":112,"imageIndex":7},{"imageOffset":16136,"symbol":"objc_destructInstance","symbolLocation":88,"imageIndex":7},{"imageOffset":52668,"symbol":"_objc_rootDealloc","symbolLocation":52,"imageIndex":7},{"imageOffset":173628,"symbol":"-[ATXFallbackActions createAnEventForCurrentDate:]","symbolLocation":796,"imageIndex":8},{"imageOffset":789240,"symbol":"-[ATXFallbackActions suggestionforSpecifiedFallbackActionType:]","symbolLocation":96,"imageIndex":8},{"imageOffset":383984,"symbol":"+[ATXActionBlendingUpdater updateBlendingLayerWithFallbackActions]","symbolLocation":692,"imageIndex":9},{"imageOffset":281588,"symbol":"-[ATXMLActionProducer updateBlendingLayerForHomeScreen]","symbolLocation":272,"imageIndex":9},{"imageOffset":406148,"symbol":"-[ATXMLActionProducer updateBlendingLayerForAllConsumerSubTypes]","symbolLocation":200,"imageIndex":9},{"imageOffset":161608,"symbol":"__77-[ATXUpdatePredictionsManager updateBehavioralPredictionsIfOlderThan:reason:]_block_invoke","symbolLocation":1104,"imageIndex":9},{"imageOffset":410008,"symbol":"_dispatch_client_callout","symbolLocation":16,"imageIndex":10},{"imageOffset":70120,"symbol":"_dispatch_lane_barrier_sync_invoke_and_complete","symbolLocation":52,"imageIndex":10},{"imageOffset":253968,"symbol":"-[ATXUpdatePredictionsManager updateBehavioralPredictionsIfOlderThan:reason:]","symbolLocation":128,"imageIndex":9},{"imageOffset":128908,"symbol":"__ATXUpdatePredictions_block_invoke","symbolLocation":248,"imageIndex":9},{"imageOffset":69064,"symbol":"_dispatch_block_async_invoke2","symbolLocation":104,"imageIndex":10},{"imageOffset":410008,"symbol":"_dispatch_client_callout","symbolLocation":16,"imageIndex":10},{"imageOffset":41172,"symbol":"_dispatch_lane_serial_drain$VARIANT$mp","symbolLocation":644,"imageIndex":10},{"imageOffset":43908,"symbol":"_dispatch_lane_invoke$VARIANT$mp","symbolLocation":408,"imageIndex":10},{"imageOffset":83792,"symbol":"_dispatch_workloop_worker_thread","symbolLocation":632,"imageIndex":10},{"imageOffset":20100,"symbol":"_pthread_wqthread","symbolLocation":284,"imageIndex":5},{"imageOffset":18928,"symbol":"start_wqthread","symbolLocation":8,"imageIndex":5}]},{"triggered":true,"id":34315,"threadState":{"x":[{"value":0},{"value":28747},{"value":28747},{"value":1048576},{"value":117440513},{"value":3},{"value":0},{"value":0},{"value":0},{"value":117440512},{"value":18446744073709535232},{"value":0},{"value":18446744073709551612},{"value":4386486144},{"value":6442063442},{"value":8401779040,"symbolLocation":0,"symbol":"OBJC_METACLASS_$_NSException"},{"value":8007610452,"symbolLocation":0,"symbol":"os_unfair_lock_unlock$VARIANT$mp"},{"value":6498118372,"symbolLocation":0,"symbol":"+[NSException exceptionWithName:reason:userInfo:]"},{"value":0},{"value":0},{"value":8493627104,"symbolLocation":0,"symbol":"__kCFAllocatorSystemDefault"},{"value":6442058960},{"value":0},{"value":8496163744},{"value":0},{"value":0},{"value":0},{"value":0},{"value":0}],"flavor":"ARM_THREAD_STATE64","lr":{"value":6497448236},"cpsr":{"value":1610612736},"fp":{"value":6442058912},"sp":{"value":6442058768},"esr":{"value":2449473542,"description":"(Data Abort) byte read Translation fault"},"pc":{"value":6497448240,"matchesCrashFrame":1},"far":{"value":40}},"queue":"ATXEngagementRecordManager","frames":[{"imageOffset":160048,"symbol":"_CFStringCreateWithFormatAndArgumentsReturningMetadata","symbolLocation":104,"imageIndex":1},{"imageOffset":160044,"symbol":"_CFStringCreateWithFormatAndArgumentsReturningMetadata","symbolLocation":100,"imageIndex":1},{"imageOffset":160452,"symbol":"CFStringCreateWithFormat","symbolLocation":44,"imageIndex":1},{"imageOffset":1447248,"symbol":"couldNotInstantiate","symbolLocation":56,"imageIndex":1},{"imageOffset":830212,"symbol":"+[NSException exceptionWithName:reason:userInfo:]","symbolLocation":32,"imageIndex":1},{"imageOffset":1632688,"symbol":"_CFRaiseMemoryException","symbolLocation":44,"imageIndex":1},{"imageOffset":1623664,"symbol":"__CFStringHandleOutOfMemory","symbolLocation":32,"imageIndex":1},{"imageOffset":186452,"symbol":"__CFStringChangeSizeMultiple","symbolLocation":2652,"imageIndex":1},{"imageOffset":140548,"symbol":"__CFStringAppendBytes","symbolLocation":524,"imageIndex":1},{"imageOffset":35448,"symbol":"__CFStringAppendFormatCore","symbolLocation":7396,"imageIndex":1},{"imageOffset":160112,"symbol":"_CFStringCreateWithFormatAndArgumentsReturningMetadata","symbolLocation":168,"imageIndex":1},{"imageOffset":160452,"symbol":"CFStringCreateWithFormat","symbolLocation":44,"imageIndex":1},{"imageOffset":1447248,"symbol":"couldNotInstantiate","symbolLocation":56,"imageIndex":1},{"imageOffset":315848,"symbol":"+[NSKeyedUnarchiver unarchivedObjectOfClasses:fromData:error:]","symbolLocation":32,"imageIndex":2},{"imageOffset":436468,"symbol":"+[NSKeyedUnarchiver unarchivedObjectOfClass:fromData:error:]","symbolLocation":116,"imageIndex":2},{"imageOffset":130588,"symbol":"-[ATXAction initWithProto:]","symbolLocation":792,"imageIndex":8},{"imageOffset":87604,"symbol":"-[ATXExecutableReferenceManager _loadReferences]","symbolLocation":636,"imageIndex":8},{"imageOffset":51128,"symbol":"-[ATXExecutableReferenceManager performBatchUpdateOfReferencesWithBlock:]","symbolLocation":88,"imageIndex":8},{"imageOffset":33596,"symbol":"__76-[ATXEngagementRecordManager updateForClientModelCacheUpdate:clientModelId:]_block_invoke","symbolLocation":244,"imageIndex":8},{"imageOffset":405908,"symbol":"_dispatch_call_block_and_release","symbolLocation":24,"imageIndex":10},{"imageOffset":410008,"symbol":"_dispatch_client_callout","symbolLocation":16,"imageIndex":10},{"imageOffset":41172,"symbol":"_dispatch_lane_serial_drain$VARIANT$mp","symbolLocation":644,"imageIndex":10},{"imageOffset":43956,"symbol":"_dispatch_lane_invoke$VARIANT$mp","symbolLocation":456,"imageIndex":10},{"imageOffset":83792,"symbol":"_dispatch_workloop_worker_thread","symbolLocation":632,"imageIndex":10},{"imageOffset":20100,"symbol":"_pthread_wqthread","symbolLocation":284,"imageIndex":5},{"imageOffset":18928,"symbol":"start_wqthread","symbolLocation":8,"imageIndex":5}]},{"id":34389,"frames":[{"imageOffset":18920,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":5}]},{"id":34417,"frames":[{"imageOffset":18920,"symbol":"start_wqthread","symbolLocation":0,"imageIndex":5}]}],
  "usedImages" : [
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 7465107456,
    "size" : 204800,
    "uuid" : "28a82cbd-b210-3662-af9e-636819d8909a",
    "path" : "\/usr\/lib\/system\/libsystem_kernel.dylib",
    "name" : "libsystem_kernel.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 6497288192,
    "size" : 4435968,
    "uuid" : "ea9c1df2-94c7-379b-bf8d-970335b1552f",
    "path" : "\/System\/Library\/Frameworks\/CoreFoundation.framework\/CoreFoundation",
    "name" : "CoreFoundation"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 6521659392,
    "size" : 3018752,
    "uuid" : "86d8a58d-b71f-34c6-83e0-014b2b835f1d",
    "path" : "\/System\/Library\/Frameworks\/Foundation.framework\/Foundation",
    "name" : "Foundation"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4299341824,
    "size" : 16384,
    "uuid" : "378b0e13-1d95-392e-948b-ef4f7dc29fdc",
    "path" : "\/usr\/libexec\/duetexpertd",
    "name" : "duetexpertd"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 4302389248,
    "size" : 344064,
    "uuid" : "5e7ef577-1cc5-369a-a04d-28fbba883086",
    "path" : "\/usr\/lib\/dyld",
    "name" : "dyld"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 8007634944,
    "size" : 81920,
    "uuid" : "ce7eb788-5155-3c38-88d8-12f1419fa5fa",
    "path" : "\/usr\/lib\/system\/libsystem_pthread.dylib",
    "name" : "libsystem_pthread.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 6705754112,
    "size" : 1552384,
    "uuid" : "dcbdc480-2589-3463-b536-38a0836375ef",
    "path" : "\/System\/Library\/Frameworks\/EventKit.framework\/EventKit",
    "name" : "EventKit"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 6885462016,
    "size" : 221184,
    "uuid" : "78e77e28-74d0-371a-a246-6d41374ba19a",
    "path" : "\/usr\/lib\/libobjc.A.dylib",
    "name" : "libobjc.A.dylib"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 7133220864,
    "size" : 1634304,
    "uuid" : "f0b82505-2542-32c8-9a0f-61d0453d91bf",
    "path" : "\/System\/Library\/PrivateFrameworks\/AppPredictionClient.framework\/AppPredictionClient",
    "name" : "AppPredictionClient"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 7321731072,
    "size" : 5906432,
    "uuid" : "3d5a198b-2ce9-3220-8229-11fcc8a53918",
    "path" : "\/System\/Library\/PrivateFrameworks\/AppPredictionInternal.framework\/AppPredictionInternal",
    "name" : "AppPredictionInternal"
  },
  {
    "source" : "P",
    "arch" : "arm64",
    "base" : 6494117888,
    "size" : 536576,
    "uuid" : "56aa6e93-8d8e-32fe-ac73-d3e79b1ba2f5",
    "path" : "\/usr\/lib\/system\/libdispatch.dylib",
    "name" : "libdispatch.dylib"
  },
  {
    "size" : 0,
    "source" : "A",
    "base" : 0,
    "uuid" : "00000000-0000-0000-0000-000000000000"
  }
],
  "sharedCache" : {
  "base" : 6493798400,
  "size" : 2275344384,
  "uuid" : "5e534704-8eeb-327b-9d0d-4f8c3777b9a5"
},
  "vmSummary" : "ReadOnly portion of Libraries: Total=531.9M resident=0K(0%) swapped_out_or_unallocated=531.9M(100%)\nWritable regions: Total=32.9M written=0K(0%) resident=0K(0%) swapped_out=0K(0%) unallocated=32.9M(100%)\n\n                                VIRTUAL   REGION \nREGION TYPE                        SIZE    COUNT (non-coalesced) \n===========                     =======  ======= \nActivity Tracing                   256K        1 \nCoreData Object IDs               4112K        2 \nDispatch continuations            2048K        1 \nFoundation                          16K        1 \nKernel Alloc Once                   32K        1 \nMALLOC                            22.5M       27 \nMALLOC guard page                   64K        4 \nSQLite page cache                  512K        8 \nSTACK GUARD                         96K        6 \nStack                             3728K        6 \nVM_ALLOCATE                         48K        1 \n__DATA                            12.5M      474 \n__DATA_CONST                      36.8M      491 \n__DATA_DIRTY                      1644K      406 \n__FONT_DATA                          4K        1 \n__LINKEDIT                       185.8M        6 \n__OBJC_RO                         90.7M        1 \n__OBJC_RW                         3456K        1 \n__TEXT                           346.1M      496 \n__UNICODE                          588K        1 \ndyld private memory               1024K        1 \nmapped file                        3.3G      584 \nshared memory                       64K        4 \n===========                     =======  ======= \nTOTAL                              4.0G     2524 \n",
  "legacyInfo" : {
  "threadTriggered" : {
    "queue" : "ATXEngagementRecordManager"
  }
},
  "trialInfo" : {
  "rollouts" : [
    {
      "rolloutId" : "601d9415f79519000ccd4b69",
      "factorPackIds" : {
        "SIRI_TEXT_TO_SPEECH" : "61b913a253a0785760dd8bbb"
      },
      "deploymentId" : 240000341
    }
  ],
  "experiments" : [

  ]
}
}
