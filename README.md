# IAR

# Creating a project

- Start by making a directory (e.g. user/Documents/$(project file))
- Under the `project file` create a directory called "Sources"
- Add all the relevant files  
- After these, run the <a href="https://www.iar.com/iar-embedded-workbench/">IAR workbench</a> software 

- Choose the `Project menu`and `Create New Project`
- Select the `project file` and name the project `project-file.ewp`
- Select the project in the Workspace window on the left of the application area
- Then, select the `Project menu`item `Add Files`
- Add all the named files to your project except `*.h` files (these files are included implicitly during compilation).

- With the project name highlighted in the workspace window
- Select `Project` -> `Options`
- Under `General Options`set the appropriate provessor device (e.g. `MSP430F5308`)
- Under the `Debugger` Category choose `FET Debugger` Which is the connection to the hardware.
- When this has been done click `OK`
