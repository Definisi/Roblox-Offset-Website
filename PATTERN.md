# Pattern Status

**Roblox Version:** version-5b077c09380f4fe6

Documentation of verified pattern status.

## ✅ Working Patterns

Patterns that were successfully found and validated:

- GetModuleFromVMStateMap
- GetEventEngine
- Luau_Execute
- LuaH_Dummynode
- SetStringEngine
- LuaL_freebuffer
- FakeDataModelPointer
- Register
- Lua_setmetatable
- KTable
- LuaL_checkany
- LuaD_throw
- OpCodeLookUpTable
- SetProtoCapabilities
- SetSingletonObject
- LockViolationInstanceCrash
- Node
- VariantCastInt64
- GetLuaState
- Lua_newstate
- TaskDefer
- GetValues
- LuaC_fullgc
- GetEngineLoadStatus
- FireTouchInterest
- VariantCastFloat
- GetCurrentThreadID
- SetInstanceObject
- GetChannelState
- Print
- KeyID
- atomic
- SetChannelState
- ValidateBytecode
- ArgsElement
- LuaD_rawrunprotected
- LuaL_pushresult
- TaskDelay
- SetEventEngine
- LuaD_precall
- LuaV_Execute
- FormatEngineText
- RawTaskScheduler
- LuaO_NilObject
- TaskCancel
- AssignedNode

## ❌ Not Working Patterns

Patterns that failed to be found or are invalid:

- LuaG_ordererror
- GetIdentityStruct
- LuaL_newmetatable
- freeblock
- LuaM_freegco
- RequestCode
- LuaL_where
- LuaC_step
- ScriptContextResume
- LuaL_checktype
- ProcessEvent
- LuaV_settable
- DatabaseEntry
- Lua_rawcheckstack
- FireProximityPrompt
- LuaL_register
- CacheNode
- SetDebugOutput
- TaskDesync
- LuaG_concaterror
- IdentityPtr
- LuaL_checklstring
- LuaL_getmetafield
- PhantomIndex
- LuaO_chunkid
- LuaVM_Load
- GetCurrentFileAsAnsi
- GetFFlag
- GetCurrentThreadContext
- GetContextObject
- Lua_clock
- HandlerRoutine
- Lua_pushfstringL
- LuaF_freeproto
- LuaF_newproto
- LuaT_objtypenamestr
- FireClickDetector
- LuaA_toobject
- GetGlobalState
- call_binTM
- WriteStream
- GetCapabilites
- Std_setError
- MallocMemory
- Pseudo2addr
- Lua_xmove
- LuaG_errorL
- GetCurrentContext
- LuaG_runerrorL
- Auxopen
- Lua_pushvfstring
- LuaM_freearray
- BrowserTracker
- LuaG_breakpoint
- VariantCastInt
- InsertNode
- LuaV_gettable
- PushInstance
- FireMouseHoverLeave
- SetMemoryInfo
- ThreadGuardSephamore
- GetProperty
- LuaG_aritherror
- FireMouseHoverEnter
- Lua_argerrorL
- LuaG_indexerror
- Impersonator
- LuaD_growstack
- CryptoUILogStamp
- SetFFlag
- FireRightMouseClick
- F_luaopen

## Notes

- Patterns that are not found may be due to:
  - Offset has changed in new Roblox version
  - Pattern is not unique or too generic
  - Memory region is not readable
