# Common issues

### Out of memory

1. Your computer has been on for a very long time and physical memory has become fragmented, or
2. A process or driver is using a large portion of physical memory.

Try closing programs that are using a lot of memory, or just restart your computer.

### Antivirus

Some antivirus vendors perform very intensive real-time monitoring/sandboxing that can interfere with the client. You don't need to disable Windows Defender. Whitelisting may not work. Make sure the antivirus is closed and its drivers are unloaded. You can re-open them after loading the cheat.

**Known incompatible vendors:** Avast Anti-Virus, Trend Micro, F-Secure, MalwareBytes

### Unsupported version of Windows

Windows 10.10.0.14393  or newer is required. Some older versions of Windows 10 may not work. Update to the latest version of Windows 10. If you are on Windows 10.0.14393 or newer and you receive this error, restart your computer and try again.

### Anti-cheat

Some anti-cheat drivers (particularly BattlEye) protect game/Steam processes which can lead to problems.

### Overlays / third party tools

Any program that interferes with the game rendering can cause issues.

**Known incompatible software:**  [Fraps](https://fraps.com/), [SweetFX](https://github.com/CeeJayDK/SweetFX), [discord](https://discord.com/) overlay, [NZXT CAM](https://nzxt.com/en-US/software/cam)

**Error codes produced:** none, your game will crash

### "Virtual machine not supported"

Some anti-virus vendors run programs in a virtual machine. If you aren't using an anti-virus, then make sure Hyper-V is disabled.

**Known incompatible vendors:** HitmanPro.Alert

### Client not opening?

If nothing happens when you open the client, then try enabling UAC and restarting Steam. Set it to its default setting, which is one notch from the top.

### Menu shows as a solid black rectangle

Go to CS:GO settings and enable "multi core rendering".

### Menu not displaying or flickering

Remove 'nod3d9ex' from your launch options.

Make sure the Steam overlay is enabled. Check it is enabled in both of these places:
    - Steam > Settings/Preferences > In-game tab. Check the box next to Enable the Steam Overlay while in-game.
    - Right-click CS:GO in your Library > Select Properties > Under the General tab, check the box next to Enable the Steam Overlay while in-game.

### "Hide from OBS" not working

Turn off or disable Razer Synapse.

In your NVIDIA Control Panel, go to 'Manage 3D settings' and be sure the following options match your Global Settings:
    - Antialiasing - FXAA - Off
    - Antialiasing - Mode - Application-controlled
    - Multi-Frame Sampled AA (MFAA) - Off
    - Shader Cache - On
    - Texture filtering - Anisotropic sample optimization - Off
    - Texture filtering - Negative LOD bias - Allow
    - Texture filtering - Quality - Quality
    - Texture filtering - Trilinear optimization - On
    - Threaded optimization - Auto
    - Triple buffering - Off
    - Vertical sync - Use the 3D application setting

Be sure you do not have conflicting settings for CS:GO in the Program Settings tab.

### Initialization Failed *

Can happen if you played a Battleye or EAC protected game, Restart PC or disable the BE/EAC service.

### Client closing right after you open it
Install the game that your subscription is for.
Make sure invitees understand that Windows 10 or newer is required.

## No game found (previously "Game not found")

Happens if the loader is unable to locate game path your subscription is for.
This is something we are going to improve significantly soon. As of now, the easiest way to fix this is installing the game on same disk as your [Steam](https://store.steampowered.com) client lies under.

## Common error codes

Codes | Description
----- | -----------
  D0001409 | [Out of memory](#out-of-memory)
  C000009A |
  C000005B | Out of quota. Make sure to have at least 8.4 GB of free space on the system drive.
  D0000001 |
  D0001600 | [Antivirus](#antivirus)
  D0002001 |
  A000001L |
  C0000022 | Incompatible vendor (Read: [Antivirus](#antivirus)). Note: Whitelisting from MalwareBytes might not work. Make sure the antivirus is closed and its drivers are unloaded. You can re-open them after loading the cheat.
  C00000F1 |
  C0000043 |
  C0000077 | [Unsupported version of Windows](#unsupported-version-of-windows)
  D0002103 |
  D0001418 | [Anti-cheat](#anti-cheat)
  D000210A |
  D0002201 | Connection problem
  D0001434 | Game is taking too long to load, use -novid or wait until the main menu to inject
  C0000225 |
  C0000005 | No game found. Make sure you have Counter-Strike: Global Offensive installed and up to-date. Error codes produced: C0000004, C0000005, C0000006
  D0001442 | Game crashed while loading
  D0001012 | ["Virtual machine not supported"](#virtual-machine-not-supported)
  D0002370 | Incompatible vendor. Fix: Completely uninstall Malwarebytes and restart your computer.
  C0000490 | Unable to locate system path.
  C0000872 | Process integrity check failed. In this case, contact an administrator.
  D0000020 | Process integrity check failed. In this case, contact an administrator.
  C0000004 | No game found. [No game found (previously "Game not found")](#no-game-found-previously-game-not-found)
  C0000005 | No game found. [No game found (previously "Game not found")](#no-game-found-previously-game-not-found)
  C0000006 | No game found. [No game found (previously "Game not found")](#no-game-found-previously-game-not-found)
  D0000660 | Contact an administrator.
