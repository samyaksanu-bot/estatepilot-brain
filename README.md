# EstatePilot Core

This repository contains the conversation intelligence and sales-psychology rules
used by EstatePilot to qualify incoming real estate leads.

This repo intentionally contains:
- No UI
- No WhatsApp logic
- No API integration

Its responsibility is to define:
- What questions to ask
- When to ask them
- How leads are scored
- How human handover is triggered

All channels (WhatsApp, Web, CRM) must consume this logic
and are not allowed to override it.
