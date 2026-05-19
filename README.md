# Open Source Contributions — Sugar Labs Music Blocks

## Contributor
Virendra Sahu  
GitHub: https://github.com/sahu-virendra-1908

## Project Repository
https://github.com/sugarlabs/musicblocks

## Pull Request Contributions Repository
https://github.com/sahu-virendra-1908/SUGARLABS_PR_CONTRIBUTIONS
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
| 10 | rationalSum silently swallows zero denominators and returns [0,1], masking corrupted note-duration state in rhythm tracking | Arithmetic Validation / Runtime State Integrity | Division-by-zero state became silently hidden, causing corrupted rhythm timing and debugging difficulty | https://github.com/sugarlabs/musicblocks/issues/7385 |
| 11 | isSafeUrl defined twice — ActionBlocks.js bypasses centralized URL safety utility, creating silent security inconsistency | Security / URL Validation Consistency | Duplicate validation logic caused inconsistent URL sanitization and potential security drift across modules | https://github.com/sugarlabs/musicblocks/issues/7384 |
| 12 | Loading a malformed HTML project file crashes project import when expected `<div class="code">` block is missing | Import Validation / Crash Prevention | Malformed project files caused import crashes and interrupted project recovery workflows | https://github.com/sugarlabs/musicblocks/issues/7386 |
| 13 | Plugin loader keeps injected `<script>` tags in document.head after execution, causing unnecessary DOM and memory growth during long sessions | Plugin Loader / Memory Management | Dynamically injected plugin scripts accumulated in DOM, increasing memory usage over time | https://github.com/sugarlabs/musicblocks/issues/7388 |
| 14 | loadNewBlocks only detects direct self-loops — multi-block circular connections can trigger recursive stack overflow during project load | Graph Validation / Runtime Stability | Circular block references could recursively overflow the stack and crash project loading | https://github.com/sugarlabs/musicblocks/issues/7391 |
| 15 | _performNotes uses raw setTimeout for effect cleanup instead of ManagedTimer, leaving stale cleanup callbacks after Stop | Timer Cleanup / Runtime Stability | Cleanup callbacks survived Stop operations, causing delayed stale execution and timer accumulation | https://github.com/sugarlabs/musicblocks/issues/7400 |
| 16 | prepareExport() mutates live blockList state for nop*Block types during serialization, causing inconsistent export behavior across repeated saves | Export Serialization / State Mutation | Export operation modified live runtime state, causing inconsistent repeated save behavior and serialization drift | https://github.com/sugarlabs/musicblocks/issues/7394 |

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
| Security | URL Validation Analysis, Centralized Sanitization Review |
| Data Integrity | Runtime Arithmetic Validation, Corrupted State Detection |

---

# Project

| Name | Link |
|---|---|
| Sugar Labs Music Blocks | https://github.com/sugarlabs/musicblocks |

---

# Verification

## GitHub Profile
https://github.com/sahu-virendra-1908

## Repository
https://github.com/sugarlabs/musicblocks

## Issue Tracker
https://github.com/sugarlabs/musicblocks/issues
