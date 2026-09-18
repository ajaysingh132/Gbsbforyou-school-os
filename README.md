# GBSBFORYOU School/OS — Consolidated M0–M6

This package reorganizes the M1–M6 foundations into one repository structure.

## Repository principle
- GBSBFORYOU School/OS is the platform software.
- Each institution is a separate tenant/workspace.
- Institution operational data belongs to and is managed by that institution.
- GBSBFORYOU maintains software, security, core services, AI and features.
- No institution's operational data is treated as general platform data.
- Cross-institution access must be denied.

## Module ownership
- M1: Institution Profile
- M2: Academic Session & Calendar
- M3: Identity, Users, Roles & Permissions
- M4: Student Information System
- M5: Guardian / Family Management
- M6: Class, Section & Academic Structure

## Important
The `modules/Mx/source/` directories preserve the individual module foundations. The root `app/` is the consolidated application shell. The next development stage should replace prototype localStorage behavior with the shared M26 services and production database/authentication layers.

## Upload note
GitHub does not automatically extract ZIP archives. For true consolidation, upload the extracted contents of this package into the repository root rather than uploading this ZIP as another archive.
