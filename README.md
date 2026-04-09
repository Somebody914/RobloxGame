# Infinite Code Tycoon

A **script-only** Roblox cyberpunk hacker idle/clicker/tycoon game. Everything — GUIs, buildings, terrain, lighting, effects — is generated entirely through Luau scripts at runtime.

## Structure

```
src/
├── ServerScriptService/    (Server scripts)
├── StarterPlayerScripts/   (Client scripts)
��── ReplicatedStorage/      (Shared modules)
```

## Setup

1. Open Roblox Studio
2. Copy each script into the matching service (ServerScriptService, StarterPlayerScripts, ReplicatedStorage)
3. Update Gamepass IDs in `GameConfig.lua` with your real IDs
4. Publish and play!