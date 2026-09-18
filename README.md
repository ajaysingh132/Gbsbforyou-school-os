# M2 — Academic Session & Institutional Calendar

M2 manages the institution's academic time structure inside its own tenant scope.

## Core records

- Academic session
- Term / semester
- Working day
- Holiday
- Examination date
- Admission / enrollment period
- Institutional event
- Important deadline

## Governance

Every calendar record must carry institution scope. One institution must not read or modify another institution's calendar.

The institution controls its own academic calendar. GBSBFORYOU controls the software capabilities used to manage it.

## Planned capabilities

- Create and edit academic sessions
- Define session start and end dates
- Configure terms/semesters
- Mark working and non-working days
- Add holidays
- Schedule examinations
- Add institutional events
- Record admission/enrollment windows
- Track important deadlines
- Calendar day/month/list views
- Audit important changes
- Offline queue and synchronization foundation

## Source of truth

M2 is the source of truth for institutional calendar configuration. Other modules may reference calendar records but should not silently create conflicting calendar state.
