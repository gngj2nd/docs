# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains documentation for the EVO product team development flow process at Haier Russia. The company develops IoT home appliance solutions including mobile applications (hiHome, hiCinema, hiShop) and backend services. This is a collection of Wiki pages (in Russian) that describe the complete product development lifecycle from initiation to release.

## Documentation Structure

The documentation follows a structured product development flow:

1. **Initiation (Инициация)** - Requirements gathering and feasibility assessment
2. **Planning (Планирование задачи)** - PO prioritization and resource allocation
3. **Analysis** - Analytics and design preparation
4. **Team Deep Dive (Погружение)** - Technical design and decomposition
5. **Development** - Implementation with platform integration
6. **Testing** - QA validation and release preparation
7. **Release** - Production deployment and completion

### Key Templates
- **Requirements Template (Draft Шаблон требований)** - Standardized requirement documentation
- **Platform Decomposition Template (Draft Шаблон декомпозиции на платформу)** - Technical implementation planning

## Key Workflow Components

### Task Management
- Projects are managed in Yandex Tracker project portfolios with full lifecycle from initiation to release

### Team Structure
Working groups consist of 5 roles:
- **Project Manager** (required) - Coordinates team, manages requirements, handles escalation
- **QA** (required) - Tests requirements, creates test cases, validates features
- **BE** (optional) - EVO backend development
- **BE WAS** (optional) - WAS IoT backend development
- **FE** (optional) - Mobile development (iOS/Android)

### Development Process
1. **Analysis Phase**: Analytics and design preparation
2. **Team Deep Dive**: Technical design and decomposition
3. **Development**: Implementation with platform integration
4. **Testing**: QA validation and release preparation

## Tools and Platforms
- **Yandex Tracker**: Task management and project tracking
- **Yandex Wiki**: Documentation, requirements storage, and team knowledge
- **Development Environments**: Feature branches → Test → Stage → Production

## Key Principles
- **Single Source of Truth**: Requirements documented once in Yandex Wiki, referenced everywhere
- **Cross-functional Collaboration**: Working groups remain stable from planning to release
- **Approval Workflows**: Management approval required for initiation, technical leader approval for technical designs
- **Self-Testing**: Developers complete test cases before QA handoff
- **Backward Compatibility**: Strict requirements for API/contract changes

## Documentation Standards
- All requirements are documented in Yandex Wiki and linked to Yandex Tracker epics
- Requirements are NOT copied to development epics - always reference the original documentation
- User stories follow the format: "As [role], I want [action], so that [goal]"
- Technical decomposition includes schemas, risks, and backward compatibility considerations

## Communication Patterns
- **Weekly**: PM and leads meetings for task initiation
- **Daily**: Standups within product teams during development
- **Bi-weekly**: Retrospectives with product team
- **Regular**: Demo sessions with mandatory lead participation
- **Async**: Comment resolution and requirement clarification

## Decision-Making Authority
- **PO**: Feature prioritization, business requirement approval, final feature sign-off
- **PM**: Resource coordination, timeline management, requirement facilitation
- **Технический лидер**: Technical design approval, architectural decisions, escalation resolution
- **Working Group**: Technical implementation decisions, integration planning

## File Naming Convention
All files use Russian naming with spaces and "Wiki.md" suffix, indicating they are exported from a Wiki system.

## AI Assistant Guidelines
When working in this repository:
1. **Identify the project phase** and required artifacts for that stage
2. **Consider cross-team dependencies** and communication needs
3. **Reference the appropriate tools** (Yandex Tracker, Yandex Wiki) for documentation
4. **Suggest templates or processes** from the established framework
5. **Think about approval workflows** and who needs to be involved
6. **Consider technical constraints** like backward compatibility and integration points