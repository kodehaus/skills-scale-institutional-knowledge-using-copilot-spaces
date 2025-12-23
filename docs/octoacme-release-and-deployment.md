# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Key Roles
- **Release Manager**: Coordinates release activities, schedules, and go/no-go decisions
- **QA Lead**: Provides quality sign-off and ensures testing is complete
- **DevOps Engineer**: Executes deployments and maintains CI/CD infrastructure
- **Developers**: Prepare code, documentation, and assist with deployment verification
- **Project Manager**: Tracks release milestones and stakeholder communication

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release Requirements
- All acceptance criteria met and PRs merged (Developer sign-off)
- Passing CI and security scans (DevOps Engineer verification)
- QA Lead sign-off on testing completion and quality gates
- Release notes drafted (Release Manager)
- Rollback / mitigation plan documented (Release Manager + DevOps Engineer)
- Smoke tests prepared and validated (QA Lead)
- Deployment automation verified (DevOps Engineer)

## Deployment Checklist
- [ ] Deployment window scheduled (Release Manager)
- [ ] Go/no-go meeting held with Release Manager, QA Lead, DevOps Engineer, and PM
- [ ] Backup or snapshot completed (DevOps Engineer)
- [ ] Deploy to staging environment (DevOps Engineer)
- [ ] Run smoke tests in staging (QA Lead)
- [ ] QA Lead provides staging sign-off
- [ ] Deploy to production via automated pipeline (DevOps Engineer)
- [ ] Run post-deploy verification tests (QA Lead + DevOps Engineer)
- [ ] Monitor initial metrics and error rates (DevOps Engineer)
- [ ] Announce release to stakeholders and support (Release Manager + PM)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer)
  - Release Manager coordinates response with QA Lead, DevOps Engineer, and PM
  - Execute rollback to last known-good release if necessary (DevOps Engineer)
  - QA Lead verifies rollback success with smoke tests
  - Triage root cause with Developers and capture action items (PM)
  - Schedule blameless post-mortem (Release Manager + PM)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
