Normal log:
```
[Message:   BepInEx] Chainloader initialized
[Info   :Il2CppInterop] Registered mono type Il2CppInterop.Runtime.DelegateSupport+Il2CppToMonoDelegateReference in il2cpp domain
[Info   :   BepInEx] 2 plugins to load
[Info   :   BepInEx] Loading [VampireCommandFramework 0.8.2]
[Message:VampireCommandFramework] VCF Loaded: 0.8.2
[Info   :   BepInEx] Loading [Bloodstone 0.1.6]
[Info   :Il2CppInterop] Registered mono type Bloodstone.Hooks.GameFrame in il2cpp domain
[Info   :Bloodstone] Detouring NetworkEvents_Serialize.SerializeEvent at 7FFEEAEB0D30
[Info   :Bloodstone] Detouring NetworkEvents_Serialize.DeserializeEvent at 7FFEEAEA40B0
[Info   :Bloodstone] Bloodstone v0.1.6 loaded.
[Info   :VcfErrorExposure] Plugin VcfErrorExposure version 1.0.0 is loaded!
[Info   :Bloodstone] Loaded plugin VcfErrorExposure.Plugin
[Message:   BepInEx] Chainloader startup complete
```

Log when an interface is in the project:
```
[Message:   BepInEx] Chainloader initialized
[Info   :Il2CppInterop] Registered mono type Il2CppInterop.Runtime.DelegateSupport+Il2CppToMonoDelegateReference in il2cpp domain
[Info   :   BepInEx] 2 plugins to load
[Info   :   BepInEx] Loading [VampireCommandFramework 0.8.2]
[Message:VampireCommandFramework] VCF Loaded: 0.8.2
[Info   :   BepInEx] Loading [Bloodstone 0.1.6]
[Info   :Il2CppInterop] Registered mono type Bloodstone.Hooks.GameFrame in il2cpp domain
[Info   :Bloodstone] Detouring NetworkEvents_Serialize.SerializeEvent at 7FFEEAEB0D30
[Info   :Bloodstone] Detouring NetworkEvents_Serialize.DeserializeEvent at 7FFEEAEA40B0
[Info   :Bloodstone] Bloodstone v0.1.6 loaded.
[Info   :VcfErrorExposure] Plugin VcfErrorExposure version 1.0.0 is loaded!
[Error  :Bloodstone] Plugin VcfErrorExposure.Plugin threw an exception during initialization:
[Error  :Bloodstone] System.NullReferenceException: Object reference not set to an instance of an object.
   at VampireCommandFramework.CommandRegistry.IsGenericConverterContext(Type rootType)
   at VampireCommandFramework.CommandRegistry.RegisterConverter(Type converter)
   at VampireCommandFramework.CommandRegistry.RegisterAll(Assembly assembly)
   at VampireCommandFramework.CommandRegistry.RegisterAll()
   at VcfErrorExposure.Plugin.Load()
   at Bloodstone.Features.Reload.LoadPlugin(String path)
[Message:   BepInEx] Chainloader startup complete
```