# Requirements
- ProtonTricks (`protontricks`) via Flatpak or Snap or whatever
- Latest Proton (Proton Experimental/GE-Proton)
- MelonLoader.Installer.Linux from down below
# Instructions
1. Open winecfg for Muse Dash.
  - If using desktop app, select Muse Dash and then select the option to open winecfg.
  - If using the CLI, run `protontricks 774171 winecfg`.
2. If it differs, switch the "Windows Version:" at the bottom to `Windows 10`.
3. In the "Libraries" tab, select the box under "New override for library:" and type `version`. Click "Add" then "OK".
4. Install dotnetdesktop6 into the Muse Dash wineprefix.
  - If using desktop app, click the option to install windows components, and find `dotnetdesktop6`.
  - If using terminal, run `protontricks 774171 dotnetdesktop6`.
5. Run the MelonLoader.Installer.Linux application and follow its instructions.
6. Set Muse Dash to run with the latest version of Proton you have and then launch it.

Thanks <@145846758071599104>
