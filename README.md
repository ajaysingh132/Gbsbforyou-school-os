# M4 — Student Information System (SIS)

GBSBFORYOU School/OS में Student Master Record का foundation.

## Core responsibility
M4 छात्र की institutional identity/master record को संभालता है। Attendance, Fees, Examination, Transport, Documents आदि अपने domain modules में source-of-truth रहेंगे और Student ID से linked होंगे.

## Included
- Admission No.
- Student ID
- Name, DOB, gender, status
- Class, section, academic session
- Parent/guardian information
- Contact/address
- Previous institution
- Notes
- Institution-scoped prototype storage
- Mobile-first interface

## Governance
Student data संस्था के tenant से scoped रहेगा। Cross-institution access निषिद्ध है। AI केवल authorized data scope में कार्य करेगा।
