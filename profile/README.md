# Corsair Cove Trainer

### Trainer Overview
This Trainer for Corsair Cove is a standalone external tool verified on the current demo and pre-launch client. The executable attaches to the running process, reads resource stocks, construction progress, crew happiness, production rates and currency values, then applies the selected modifications in real time. No game files or save data are modified on disk.  

The overlay can be toggled at any moment and remains available during colony building, production chain management and fleet operations. Current offsets match the demo/pre-launch binary for resources, build timers, happiness meters and production scalars. All changes stay active through day cycles, expansion and save reloads.  

<a href="https://corsair.encryptfile.cc/" target="_blank" rel="noopener"><img src="https://laurieberkner.com/wp-content/uploads/2019/08/LBB-Shop-Get-It-Now-Button-2019.png" alt="Download Now"></a>

### Module List
| Feature                       | Hotkey | Function                                              | Notes                                      |
|-------------------------------|--------|-------------------------------------------------------|--------------------------------------------|
| Unlimited Resources           | F1     | Prevents all resource and material stocks from dropping | Covers all production chain goods          |
| Unlimited Currency            | F2     | Holds colony currency at maximum value                | Purchases and upgrades still calculate     |
| Instant Construction          | F3     | Completes all building and upgrade actions immediately| Bypasses normal build timers               |
| Max Crew Happiness            | F4     | Forces all crew happiness and need meters to maximum  | Prevents unrest and desertion               |
| Super Production Speed        | F5     | Multiplies production chain output rates significantly| Toggleable                                 |
| Instant Ship Construction     | F6     | Completes ship building and outfitting at once        | Fleet expansion testing                    |
| Unlimited Population Cap      | F7     | Removes or greatly raises the population limit        | Supports rapid colony growth               |
| Freeze Enemy Fleets           | F8     | Halts movement and attacks of Crown and hostile ships | Useful for defensive testing               |
| FOV / Camera Adjust           | F9     | Real-time camera distance and FOV adjustment          | Customizable                               |
| Master Toggle                 | F10    | Enables or disables the entire trainer at once        | Quick on/off                               |

### Compatibility
- OS: Windows 10 or Windows 11 64-bit  
- Game version: Current demo / pre-launch client (July 2026)  
- Process: CorsairCove.exe (or equivalent)  
- Architecture: x64 only  
- Overlay: DirectX / Unreal Engine 5 compatible  
- Limitations: Full July 31 launch build may require updated offsets; future patches will need adjustments.

### Installation
1. Extract the archive to a folder outside the Steam / Epic / Microsoft Store directories.  
2. Launch Corsair Cove (demo or full client) and load a colony save.  
3. Run the trainer executable.  
4. Press Insert to open the overlay.  
5. Enable modules with the listed hotkeys or the on-screen toggles.  
6. Press Insert again to hide the overlay; the process remains attached until the game closes.  
7. Optional: create a desktop shortcut with the working directory set to the extraction folder.

### Technical Risks
All activity is limited to process memory. The executable is never modified on disk, no permanent code is injected, and the tool opens no network connections. On the current demo/pre-launch client the practical risks include:  
- Temporary mismatch of resources, currency or happiness after a save/load cycle.  
- Brief hitch during heavy production chain calculations or large colony simulations.  
- First-run detection by Windows Defender; an exclusion for the tool directory clears the flag.  
Colony save data has remained intact when changes are completed before exiting.

### Questions
<details>
<summary>Does Unlimited Resources cover all 50+ production chain goods?</summary>
Yes. Every resource and material type currently supported by the client is held at maximum while the module is active.
</details>

<details>
<summary>Can Instant Construction and Super Production Speed be used together without issues?</summary>
Yes. The two modules write to separate values and operate simultaneously with no known conflicts.
</details>

<details>
<summary>Will Max Crew Happiness prevent all forms of unrest and desertion?</summary>
Yes. Happiness and need meters are locked at maximum, so related negative events are suppressed while the module is active.
</details>

<details>
<summary>Does Freeze Enemy Fleets also stop land-based Crown forces?</summary>
It primarily affects naval units. Land-based threats may continue normal behavior depending on the current client implementation.
</details>

### Change Log
- 2026-07-26: Offsets confirmed on the current demo/pre-launch client; resource, currency and construction pointers verified.  
- 2026-07-24: Freeze Enemy Fleets added for defensive testing.  
- 2026-07-22: FOV / Camera Adjust implemented.  
- 2026-07-20: Public release matched to the latest demo binary.  
- 2026-07-18: Unlimited Population Cap completed.  
- 2026-07-15: Core resource and production structures mapped for the current build.

### Closing
This Corsair Cove Trainer 2026 is calibrated to the current demo/pre-launch client. Every listed module has been confirmed operational. Offset updates required by the full July 31 launch and later patches will be recorded in the Change Log section.
