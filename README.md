# GIOS `/.vscode` gdb Configuration Files

This repository contains VS Code debugger configuration files for GIOS projects, organized by projects and corresponding target location for corresponding parts-wise directories `.vscode/`. The respective projects' directory hierarchies are as follows:

```
# Project 1 ← .vscode/ placed in respective sub-parts subdirectories
/pr1
  ./echo
    ../.vscode
  ./transfer
    ../.vscode
  ./gflib
    ../.vscode
  ./mtgf
    ../.vscode

# Project 3 ← .vscode/ placed in respective sub-parts subdirectories
/pr3
  ./server
    ../.vscode
  ./cache
    ../.vscode

# Project 4 ← .vscode/ placed at top-level directory of project (for BOTH parts)
/pr4
  ./.vscode
```
**Note**: To use debugger configurations in VS Code, copy corresponding directory `.vscode/` to appropriate sub-part target and then open that location as a VS Code project (i.e., ***File*** → ***Open Folder***, terminal command `code /prX/<sub-part>`, or equivalent). This will add corresponding debugger configurations in view `Run and Debug` in the dropdown (i.e., for server and/or client apps, as applicable).


For further information regarding runnning the VS Code debugger, see companion guide [here](https://docs.google.com/document/d/1U55jP_KEGCW2O_GMHIR1KJ6YJNAG6T9Bk27BzYVMybI).