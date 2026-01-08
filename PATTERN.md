# Pattern Status

**Roblox Version:** version-5b077c09380f4fe6

Documentation of verified pattern status.

## ✅ Working Patterns

Patterns that were successfully found and validated:

- TaskDefer
- SetSingletonObject
- GetChannelState
- Node
- GetEventEngine
- LuaD_rawrunprotected
- VariantCastInt64
- GetCurrentThreadID
- LuaL_freebuffer
- LuaC_fullgc
- LuaD_precall
- LockViolationInstanceCrash
- ProcessEvent
- KeyID
- AssignedNode
- TaskDelay
- SetProtoCapabilities
- LuaL_checkany
- LuaL_pushresult
- VariantCastFloat
- LuaH_Dummynode
- SetStringEngine
- Lua_newstate
- SetChannelState
- Print
- GetLuaState
- ArgsElement
- LuaO_NilObject
- Register
- KTable
- GetModuleFromVMStateMap
- GetEngineLoadStatus
- Luau_Execute
- SetInstanceObject
- FormatEngineText
- LuaV_Execute
- ValidateBytecode
- HandlerRoutine
- GetValues
- LuaD_throw
- InsertNode
- OpCodeLookUpTable
- Lua_setmetatable
- atomic
- FireTouchInterest
- TaskCancel
- SetEventEngine

## ❌ Not Working Patterns

Patterns that failed to be found or are invalid:

- (None)

## Notes

- Patterns that are not found may be due to:
  - Offset has changed in new Roblox version
  - Pattern is not unique or too generic
  - Memory region is not readable
