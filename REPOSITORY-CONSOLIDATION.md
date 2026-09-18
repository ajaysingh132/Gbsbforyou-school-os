# Repository Consolidation — M0–M6

## Why
Earlier module packages were uploaded as ZIP archives. This is useful for backup but does not create an integrated source tree. This package provides the extracted/reorganized source tree.

## Target structure
```
app/
modules/
  M1/
  M2/
  M3/
  M4/
  M5/
  M6/
docs/
package.json
README.md
```

Each module keeps its domain source under `modules/Mx/source/` so the six prototypes do not overwrite the unified root `app/`.

## Important security note
The module source files are foundations/prototypes. Client-side localStorage is not production security. M3 authorization must eventually be enforced server-side, with institution and scope checks before data access.

## Next gate
Do not delete the original ZIP archives until the extracted source tree has been verified in GitHub and the application builds successfully.
