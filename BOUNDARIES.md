# A2A-SIN-SMS Boundaries

## Role
`A2A-SIN-SMS` owns SMS messaging integration, delivery workflows, and SMS-specific contracts.

## This repo should own
- SMS messaging, routing, and delivery workflows
- SMS evidence, recovery, provider handling, and delivery automation
- SMS contracts used by downstream communication automation agents
- runbooks tied to text delivery, notifications, and SMS automation

## This repo must not own
- generic messaging ownership outside SMS
- unrelated social, meeting, or chat platform behavior
- organization SSOT docs or architecture canon

## Hard rules
- Keep changes scoped to SMS messaging and delivery workflows.
- Move non-SMS behavior back to the repos that own those surfaces.
- Keep reusable contracts focused on SMS delivery, notifications, and automation.
