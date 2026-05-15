# Open Source Contributions — Sugar Labs Music Blocks

## Contributor
Virendra Sahu  
GitHub: https://github.com/sahu-virendra-1908

Project Repository:  
https://github.com/sugarlabs/musicblocks

---

# Reported Issues

| # | Issue Title | Category | Impact | Issue Link |
|---|---|---|---|---|
| 1 | Auto-save fails to generate thumbnail due to null getBounds() in activity.js | Rendering / Auto-save Stability | Prevented thumbnail generation during auto-save and caused unstable save behavior | https://github.com/sugarlabs/musicblocks/issues/7187 |
| 2 | Restoring start/drum block does not restore companion turtle, breaking onEveryBeatDo after undo | Undo/Redo / Runtime State Restoration | Companion turtles were not recreated after undo operations, breaking beat callbacks | https://github.com/sugarlabs/musicblocks/issues/7189 |
| 3 | DictActions.setValue leaks turtle dictionary state to browser console on every dictionary write | Performance / Debug Logging | Console flooding and performance degradation during repeated dictionary writes | https://github.com/sugarlabs/musicblocks/issues/7268 |
| 4 | sendAllToTrash does not clear companion turtles, causing stale onEveryBeatDo execution across project resets | Runtime Cleanup / Project Reset | Old companion turtles remained active after reset, causing unexpected beat execution | https://github.com/sugarlabs/musicblocks/issues/7220 |
| 5 | onEveryBeatDo interval not cleared on Stop due to bypassing ManagedTimer | Timer Management / Runtime Stability | Intervals continued executing after Stop, causing memory leaks and repeated execution | https://github.com/sugarlabs/musicblocks/issues/7222 |
| 6 | _restoreTrashById fails to regenerate deleted blockArt entries after trash restore | SVG/PNG Export / Artwork Restoration | Restored blocks exported corrupted artwork and broken SVG/PNG files | https://github.com/sugarlabs/musicblocks/issues/7254 |
| 7 | base64Encode crashes with "Maximum call stack size exceeded" for large SVG exports | Encoding / Export Performance | Large SVG exports crashed due to stack overflow from spread usage | https://github.com/sugarlabs/musicblocks/issues/7348 |
| 8 | _renderTrashView recreates per-item closure event listeners on every trash render | DOM Memory Leak / UI Performance | Detached DOM trees retained listeners causing memory accumulation | https://github.com/sugarlabs/musicblocks/issues/7358 |
| 9 | _renderTrashView generates invalid data:image/svg+xml URLs when block.artwork is null | UI Rendering / SVG Handling | Trash panel thumbnails failed to render correctly | https://github.com/sugarlabs/musicblocks/issues/7359 |

---

# Skills Demonstrated

| Area | Skills |
|---|---|
| Open Source | Contribution Workflow, GitHub Issue Reporting |
| Debugging | Advanced JavaScript Debugging, Runtime Analysis |
| Performance | Memory Leak Detection, Performance Profiling |
| Frontend | DOM Optimization, SVG & Canvas Handling |
| Architecture | Undo/Redo Flow Analysis, Runtime State Management |
| Stability | Timer Cleanup, Event Listener Lifecycle Handling |

---

# Project

| Name | Link |
|---|---|
| Sugar Labs Music Blocks | https://github.com/sugarlabs/musicblocks |