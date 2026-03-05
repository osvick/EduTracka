🏢 EduTracka Engineering Guide

Version 1.0

🎯 Mission

Build a simple, reliable, and secure school management system optimized for Nigerian schools.

1. Core Engineering Principles
Product First

Simplicity over complexity

Performance over animations

Usability over aesthetics

Build for teachers under exam stress

Security First

No secrets in Git

Use Supabase RLS

Every route must be protected

Never trust frontend validation

Clean Code Culture

No any types

Small functions

Reusable components

Clear naming conventions

2. Git Rules
Branching Model
main → production
dev → staging
feature/* → new features
fix/* → bug fixes
refactor/* → improvements

Rules:

Never push directly to main

Every feature goes through Pull Request

At least one review before merge

3. Commit Convention

Use Conventional Commits:

feat: add attendance module
fix: correct results calculation bug
refactor: optimize dashboard layout
docs: update engineering guide
4. Folder Structure
src/
 ├── app/
 ├── components/
 ├── hooks/
 ├── services/
 ├── lib/
 ├── types/

Rules:

components = UI only

services = business logic

lib = external integrations

No mixing responsibilities

5. Code Review Checklist

Before merging:

Code is readable

No duplicated logic

RBAC respected

Performance checked

No console logs left