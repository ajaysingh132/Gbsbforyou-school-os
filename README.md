# M5 — Guardian / Family Management

M5 छात्र और उसके अधिकृत अभिभावक/परिवार के बीच relationship domain का foundation है।

## Core responsibility
- Guardian profile
- Family relationship
- Student linkage by Student ID
- Primary guardian
- Emergency contact
- Communication consent
- Relationship-scoped access

M4 Student Master Record student identity का source-of-truth है; M5 guardian/family relationship का source-of-truth है।

## Relationship model
One Guardian ↔ Many Students
One Student ↔ Many Authorized Guardians

## Prototype
Browser localStorage आधारित foundation. Production authentication/database/security का विकल्प नहीं।
