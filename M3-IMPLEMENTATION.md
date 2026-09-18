# M3 Implementation Notes

## Implemented in this foundation
1. User display name
2. Role selection
3. Role catalogue
4. Permission model
5. Scope hierarchy
6. Security boundary indicators
7. Institution isolation policy
8. AI authorization boundary
9. Mobile-responsive interface
10. Local prototype persistence

## Production implementation required
- Secure authentication provider
- Server-side session validation
- PostgreSQL/Supabase persistence
- Password reset and MFA-ready architecture
- Server-side tenant enforcement on every API/query
- RBAC + relationship + scope policy engine
- Secure token/session rotation
- Audit event persistence
- Rate limiting and abuse controls
- Data encryption and secrets management
- Access review and permission versioning
- Offline authentication/sync policy
- Automated authorization tests
- No client-only authorization trust

## Security invariant
A client request must never be trusted merely because the UI hides or shows a control. Authorization must be enforced server-side, with institution and scope checks before data access.
