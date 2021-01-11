# reshade-xhair

A heavily customizable, fullscreen-compatible crosshair overlay shader.

![xhair-gui](./img/xhair_gui.png)

![xhair-small](./img/xhair_small_cross.png)
![xhair-big](./img/xhair_big.png)
![xhair-circle](./img/xhair_circle_dot.png)
![xhair-small-circle](./img/xhair_small_circle.png)
![xhair-small-dot](./img/xhair_dot.png)

| Feature             | Supported               |
| ------------------- | ----------------------- |
| Fullscreen          | :heavy_check_mark:      |
| No input lag        | :heavy_check_mark:      |
| No FPS impact       | :heavy_check_mark:      |
| Customizable        | :heavy_check_mark:      |
| One-time setup      | :heavy_check_mark:      |

## FAQ

Q: Does this work in fullscreen?

A: Yes. Rather than rendering the crosshair outside the game, the injected ReShade overlay renders within the the game.

---

Q: Will this get me banned?

A: No, reshade-xhair will not get you banned by itself. **HOWEVER**, the program that it runs on (ReShade) is blacklisted by some games/anti-cheats. **Make sure you look up whether ReShade can be used safely on the desired game before installing it**.

Use at your own risk!

For EA games such as Battlefield 4, it is against ToS to use an overlay of any type. Punkbuster and Fairfight take screenshots of the overlay and could result in official action being taken to ban your account. Additionally third party anticheats such as GGC, ACI, PBBans and BF4DB will ban you for usage. 

It should be safe to use this on Killing Floor 2 and PayDay 2.

---

Q: How do I uninstall?

A: Uninstall reshade using the installer, or go into your shaders folder and delete the file called `xhair.fx`

---

Q: I'm getting suttering/fps drops/misc issues

A: reshade-xhair is unlikely to be the issue. It's probably a ReShade issue. Google it.

## How to Install (for any game)

1. Install ReShade from [reshade.me](https://reshade.me) (**ReShade 4.x is now supported!**).

    ![reshade-installer](./img/reshade_installer.png)
    1. Click "Select game" and select your game executable (e.g. `steamapps/common/killingfloor2/Binaries/Win64/KFGame.exe` for Killing Floor 2)
    2. Check the appropriate game rendering API. If you don't know which one to pick, try the "Direct3D 10/11/12" option.
    3. Click the Field that says "Enter ZIP download link to custom repository here".
    4. Put this link `https://github.com/Midnoclose/reshade-xhair/archive/master.zip`, then click "Add".
    4. Exit the ReShade installer.

5. Launch your game and open the ReShade overlay by pressing the "Home" key (or Shift-F2 for ReShade <4).
