# Pattern Status

**Roblox Version:** version-5b077c09380f4fe6

Documentation of verified pattern status.

## ✅ Working Patterns

Patterns that were successfully found and validated:

- TaskCancel
- Luau_Execute
- GetChannelState
- LuaL_pushresult
- GetCurrentThreadID
- LuaH_Dummynode
- Lua_setmetatable
- LuaV_Execute
- RawTaskScheduler
- ValidateBytecode
- FakeDataModelPointer
- FireTouchInterest
- SetChannelState
- SetInstanceObject
- GetEventEngine
- GetValues
- Lua_newstate
- LuaD_precall
- GetEngineLoadStatus
- LuaL_checkany
- GetLuaState
- OpCodeLookUpTable
- atomic
- Register
- TaskDelay
- LuaC_fullgc
- SetEventEngine
- TaskDefer
- SetStringEngine
- SetSingletonObject
- LuaO_NilObject
- ArgsElement
- LuaD_throw
- GetModuleFromVMStateMap
- LuaD_rawrunprotected
- VariantCastInt64
- VariantCastFloat
- LockViolationInstanceCrash
- Print
- Node
- KTable
- SetProtoCapabilities
- AssignedNode
- FormatEngineText
- KeyID

## ❌ Not Working Patterns

Patterns that failed to be found or are invalid:

- LuaL_freebuffer

## Notes

- Patterns that are not found may be due to:
  - Offset has changed in new Roblox version
  - Pattern is not unique or too generic
  - Memory region is not readable
