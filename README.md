# Neko Tracker

NekoTracker is a Unity error tracer for non-engineers.

## How to use

1. Import NekoTracker
2. Help > Natsuneko Laboratory > Generate Error Report
3. Paste content to any place (e.g. Discord, PasteBin, Text Editor, others)

## Tracer Format

```
# THIS IS AN AUTOGENERATED FILE. DO NOT EDIT THIS FILE DIRECTLY.
# NatsunekoLaboratory.ErrorTracker V1

Unity Player Version:
    2019.4.31f1 <-- Unity Version

Platform:
    Microsoft Windows NT 10.0.22621.0 <-- OS with Version

Trace:
    [WARN] Visual Studio Editor Package version 2.0.18 is available, we strongly encourage you to update from the Unity Package Manager for a better Visual Studio integration
        at UnityEngine.Debug:LogWarning (object)
        at Microsoft.Unity.VisualStudio.Editor.VisualStudioIntegration:HandleListRequestCompletion () (at Library/PackageCache/com.unity.ide.visualstudio@2.0.11/Editor/VisualStudioIntegration.cs:149)
        at Microsoft.Unity.VisualStudio.Editor.VisualStudioIntegration:OnUpdate () (at Library/PackageCache/com.unity.ide.visualstudio@2.0.11/Editor/VisualStudioIntegration.cs:160)
        at UnityEditor.EditorApplication:Internal_CallUpdateFunctions ()
    +- recent stacktrace, only supported UnityEngine.Debug.Error, Warning, and Exception

Dependencies:
    com.oddworm.heapexplorer@https://github.com/pschraut/UnityHeapExplorer.git#4.1.1 <-- git dependencies
    com.unity.collab-proxy@1.10.2 <-- manifest.json dependencies
    com.vrchat.avatars@3.1.11 <-- vpm-manifest.json dependencies
    com.vrchat.base@3.1.11 <-- embedded package dependencies
    NatsunekoLaboratory.ErrorTracker@unitypackage <-- UnityPackage dependencies (only if asmdef provided)
    jp.lilxyzw.liltoon@1.3.7 <-- UnityPackage dependencies (only if package.json provided)


```

## License

MIT by [@6jz](https://twitter.com/6jz)
