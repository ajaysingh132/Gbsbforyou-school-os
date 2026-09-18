# M4 Implementation Notes

## Foundation implemented
- Student master record form
- Automatic prototype Student ID
- Academic/session linkage fields
- Family/contact fields
- Student status
- Local prototype record list
- Mobile-responsive UI
- Institution isolation governance notes

## Production requirements
- PostgreSQL/Supabase schema with institution_id on every tenant-owned record
- Server-side tenant enforcement
- M3 authentication/RBAC integration
- Unique constraints for institution-scoped admission numbers/IDs
- Data validation and normalization
- Audit/version history
- Secure document references through M19
- Relationship links to M5, M6, M7, M8, M11, M12, M13, M14, M15 and other domains
- Import/export controls
- Duplicate detection with human confirmation; never silent deletion
- Backup, sync and recovery through M24
- Privacy/retention policies
- Automated authorization and data-isolation tests

## Source-of-truth rule
M4 owns the student's master identity/profile. Domain-specific facts remain owned by their respective services.
