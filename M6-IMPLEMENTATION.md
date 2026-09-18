# M6 Implementation Notes

## Foundation implemented
- Class/section record
- Session linkage
- Program/course and stream
- Class teacher
- Capacity
- Status
- Prototype local persistence
- Mobile-responsive UI

## Production requirements
- PostgreSQL/Supabase schema with institution_id and session_id
- M3 authentication/RBAC/scope enforcement
- Unique constraints scoped to institution + session + program + class + section
- Referential integrity with M2 and M4
- Class teacher relationship to M8
- Subject linkage with M7
- Timetable integration with M10
- Capacity validation
- Audit/version history
- Archive rules without destructive deletion
- Backup/sync through M24
- Server-side authorization and isolation tests

## Source-of-truth
M6 owns class/section academic structure. Student identity remains M4-owned; subjects/curriculum remain M7-owned.
