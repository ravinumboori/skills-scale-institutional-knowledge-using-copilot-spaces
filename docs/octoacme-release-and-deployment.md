# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (validated by Product Owner)
- Passing CI and security scans
- QA Lead sign-off on test results
- Release notes drafted (PM with Product Owner input)
- Rollback / mitigation plan documented
- Smoke tests prepared and executed (QA Lead)
- UX Designer validation for UI changes

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) with Stakeholder Representatives
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Lead)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications (QA Lead and Developers)
- [ ] Announce release to stakeholders and support (PM with Product Owner)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
