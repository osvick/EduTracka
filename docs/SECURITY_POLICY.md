# EduTracka Security Policy

## Authentication
Supabase Auth is used for login.

## Roles

Admin
Teacher
Exam Officer

## Access Rules

Admin:
- full access

Teacher:
- manage assigned class
- mark attendance

Exam Officer:
- manage results only

## Database Security

All tables must have:

- Row Level Security enabled
- Access policies enforced