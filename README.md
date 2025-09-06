# winows_commands_cheatSheet

- Next tab ctrl+Page down
- Previous tab ctrl+Page up
- Specific tab ctrl+(1-8)
- Last tab ctrl+9
- System information from Win+R(run dialog) msinfo32
- Basic PC properties from run dialog - control system
  ### 🔹 Option 4: Using Visual Studio Code

Open both files in VS Code.

Right-click the first file → Select for Compare.

Right-click the second file → Compare with Selected.

### How to Run

Save the above as DevSetup.ps1 in D:\ (or any folder).

Open PowerShell as Administrator.

Run:
```ps
Set-ExecutionPolicy Bypass -Scope Process -Force
.\DevSetup.ps1
```
