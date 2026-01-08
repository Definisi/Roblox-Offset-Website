# Pattern Status

**Roblox Version:** version-5b077c09380f4fe6

Documentation of verified pattern status.

## ✅ Working Patterns

Patterns that were successfully found and validated:

- LuaD_throw
- LuaL_checkany
- GetEventEngine
- FakeDataModelPointer
- RawTaskScheduler
- SetEventEngine
- SetProtoCapabilities
- atomic
- Lua_newstate
- Node
- SetInstanceObject
- GetValues
- VariantCastFloat
- KeyID
- LuaV_Execute
- FireTouchInterest
- InsertNode
- ArgsElement
- LuaL_freebuffer
- OpCodeLookUpTable
- KTable
- Print
- GetCurrentThreadID
- LuaL_pushresult
- FormatEngineText
- LuaH_Dummynode
- TaskCancel
- Register
- LockViolationInstanceCrash
- LuaC_fullgc
- Lua_setmetatable
- TaskDelay
- TaskDefer
- ValidateBytecode
- GetModuleFromVMStateMap
- LuaD_precall
- GetEngineLoadStatus
- SetChannelState
- Luau_Execute
- LuaO_NilObject
- VariantCastInt64
- GetLuaState
- SetStringEngine
- SetSingletonObject
- GetChannelState
- AssignedNode
- LuaD_rawrunprotected

## ❌ Not Working Patterns

Patterns that failed to be found or are invalid:

- call_binTM
- WriteStream
- VariantCastInt
- CacheNode
- Lua_pushfstringL
- Std_setError
- GetCapabilites
- GetCurrentThreadContext
- F_luaopen
- SetFFlag
- PushInstance
- Lua_argerrorL
- LuaM_freearray
- Lua_pushvfstring
- Lua_clock
- LuaV_settable
- LuaC_step
- LuaG_aritherror
- LuaF_freeproto
- GetGlobalState
- FireRightMouseClick
- FireClickDetector
- LuaD_growstack
- GetProperty
- LuaG_concaterror
- Lua_xmove
- BrowserTracker
- Auxopen
- LuaG_errorL
- GetCurrentContext
- CryptoUILogStamp
- GetCurrentFileAsAnsi
- DatabaseEntry
- LuaG_ordererror
- ScriptContextResume
- HandlerRoutine
- Pseudo2addr
- GetFFlag
- LuaO_chunkid
- LuaL_newmetatable
- LuaV_gettable
- SetMemoryInfo
- Impersonator
- LuaL_register
- IdentityPtr
- TaskDesync
- LuaG_runerrorL
- ProcessEvent
- GetIdentityStruct
- GetContextObject
- FireProximityPrompt
- LuaF_newproto
- LuaT_objtypenamestr
- RequestCode
- LuaG_breakpoint
- LuaG_indexerror
- Lua_rawcheckstack
- LuaL_checktype
- FireMouseHoverLeave
- freeblock
- LuaVM_Load
- LuaL_checklstring
- LuaL_getmetafield
- MallocMemory
- ThreadGuardSephamore
- SetDebugOutput
- LuaM_freegco
- FireMouseHoverEnter
- PhantomIndex
- LuaA_toobject
- LuaL_where

## Notes

- Patterns that are not found may be due to:
  - Offset has changed in new Roblox version
  - Pattern is not unique or too generic
  - Memory region is not readable
