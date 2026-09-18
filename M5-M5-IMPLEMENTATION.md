# M5 Implementation Notes

## Foundation implemented
- Guardian profile
- Relationship type
- Student ID linkage
- Primary guardian flag
- Emergency contact flag
- Communication consent flag
- Contact/address fields
- Prototype local persistence
- Mobile-responsive interface

## Production requirements
- PostgreSQL/Supabase schema with institution_id
- M3 authentication/RBAC integration
- Relationship authorization policy
- Guardian-to-student many-to-many relation
- Unique scoped identifiers
- Consent history/versioning
- Audit trail for relationship and permission changes
- Secure contact-data handling
- Parent portal integration through M22
- Communication integration through M18/M21
- Backup/sync through M24
- Server-side tenant and relationship enforcement
- Automated authorization/isolation tests

## Source-of-truth
M5 owns guardian/family relationship records. Student identity remains owned by M4. Domain records remain owned by their respective services.
