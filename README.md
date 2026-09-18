# M3 — Identity, Users, Roles & Permissions

GBSBFORYOU School/OS का security and access-control foundation.

## Scope
- Institution-scoped identity
- Users and profiles
- Roles
- RBAC foundation
- Relationship-based access
- Scope-based authorization
- Deny-by-default
- Audit-ready permission changes
- AI authorization boundary

## Scope hierarchy
Institution → Campus → Department → Program → Class → Section → Subject → Individual Record

## Governance
GBSBFORYOU software/core को update करता है। संस्था अपने users और operational data को नियंत्रित करती है। Cross-institution access निषिद्ध होना चाहिए।

## Prototype
यह package UI/foundation है और browser localStorage का उपयोग करता है। इसे production authentication/database/security का विकल्प न माना जाए।
