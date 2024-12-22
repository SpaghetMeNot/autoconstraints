### 1.4.1

- Fix for an error when rotating while the built-in rotation tool is active

### 1.4.0

- Can install as an extension. Simply drag the zip file into Blender (Remember to disable previous add-on first!)
- Documentation site now live: https://spaghetmenot.github.io/autoconstraints
- Hotkey-able autoConstraints! A new operator can control various autoConstraints behavior. See Documentation for more information
- Axis overrides are now displayed in the toolbar making it a more accessible workflow
- Fixed error that sometimes occurred in edit mode with "Normal" orientation

### 1.3.6

- Fixed rare bug causing new hotkeys to be added every blender session

### 1.3.5

- Constraints will now respect the gizmo's orientation in tool modes
- Fixed "repeat last" not working for duplicate and extrude tools
- Fixed custom hotkeys with "release confirm" not working
- Fixed a couple of Right Click Select issues
- Fixed bug with objects rotated exactly 45 degrees to viewing angle

### 1.3.1

- Added support for 3D Tools where "Drag" is set to "Tweak"/"Active Tool"
- Fixed Icons not showing up in rare cases

### 1.3.0

- Added support for "Normal" orientation for edit modes, handy for many things especially when used with axis overrides.
- Fixed dropdown being disabled in toolbar when in viewport header

### 1.2.2

- Added option to disable automatic keymap assignment (each operator will have to be assigned manually)
- Added option for a sidebar with a button for every operator to make remapping a bit easier

### 1.2.1

- Fixed "Shift+RightMouse-Drag" Cursor shortcut not working
- Added catch for rare toolbar hotkey bug

### 1.2.0

- New look! Added custom icons for autoConstraints toggle and planes to better tell them apart
- Added preferences to use colored variants of plane icons or use the original icons
- Changing autoConstraint options will no longer add undo steps (they will still be restored per .blend file though)
- Context specific naming for extrude vert/edge option
- Re-naming custom orientation used for multiple objects in local orientation to "Last Multi-Local"
- Added support for Grease Pencil extrude

### 1.1.0

- Added support for Edit Armature and Pose modes
- Move Rotate Scale supported for both modes
- Extrude and Duplicate supported in edit mode
- Bone transforms supported ('Normal' in edit mode, 'Local' in pose mode)
- Option to toggle Sidebar Panel in add-on preferences, off by default. Avoids unnecessary clutter