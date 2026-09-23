# BASE Creator System

## BASE Tier 2 Creator Template v1

### Creator-Owned by Design

BASE Tier 2 Creator Template v1 is a proprietary creator system designed for configuring, deploying, operating, and maintaining independent Creator Deployments.

It allows creators to control their identity, branding, content, audience, communications, and deployment while providing a consistent system for managing and publishing their creator experience.

BASE is a system, not a platform.

The BASE Tier 2 Creator Template v1 is proprietary software and is governed by its accompanying LICENSE.

---

# Philosophy

Creators should own their home.

Platforms are discovery.

Creator Deployments are home.

BASE exists to provide creators with an independent system for managing their own creator presence.

The system is designed to preserve creator independence while allowing BASE itself to continue evolving through future releases.

---

# System Principles

BASE Tier 2 is built around several core principles.

- Creator control
- Direct creator-to-audience relationships
- Deployment independence
- Hosting independence
- Repository independence from public deployment location
- Privacy by design
- Long-term sustainability
- System evolution

These principles describe how Creator Deployments operate.

They do not grant redistribution, sublicensing, resale, derivative-template, or software-development rights to the BASE Tier 2 Creator Template v1.

Rights to the Tier 2 Software are governed exclusively by the accompanying LICENSE.

---

# System Structure

BASE Tier 2 consists of two primary parts:

- Creator Dashboard
- Fan App

The Fan App is the creator's user-facing application.

The Creator Dashboard is the control interface used to configure and publish the Creator Deployment.

The Creator Dashboard and Fan App operate as parts of the same Creator Deployment while remaining separate in function.

---

# Creator Dashboard Connection

The Creator Dashboard connects to a Creator Deployment using three separate pieces of configuration:

- Repository identifier (`owner/repository`)
- Public `content.json` URL
- Creator Key (repository access token)

Each serves a different purpose.

The repository identifier tells the Creator Dashboard which authorized repository it may update.

The public `content.json` URL tells the Creator Dashboard where to load the current deployed application data.

The Creator Key provides the authorization required to publish permitted changes to the configured repository.

The repository identifier and public deployment URL are configured separately.

The repository is not determined by the URL where the Creator Dashboard or Fan App is running.

---

# Creator Dashboard Setup

To connect the Creator Dashboard to an authorized Creator Deployment:

1. Open the Creator Dashboard.
2. Enter the Creator Key.
3. Enter the repository as `owner/repository`.
4. Enter the public `content.json` URL for the Creator Deployment.
5. Select **Load Current State**.
6. Make the permitted creator configuration changes.
7. Select **Publish** when ready.

The Creator Dashboard remembers the Repository, Creator Key, and `content.json` URL in that browser so the authorized configuration remains available when the dashboard is reopened.

These saved connection settings are local browser configuration. They do not make the Fan App dependent on the Creator Dashboard remaining open.

---

# Hosting Independence

BASE Tier 2 is independent of any specific public hosting provider.

Creators may deploy their authorized Creator Deployment using compatible hosting environments.

Examples may include:

- GitHub Pages
- Cloud hosting
- Private or custom server infrastructure
- Other compatible hosting environments

The hosting provider is infrastructure.

It is not BASE.

Changing the public hosting location does not transfer ownership of the Tier 2 Software and does not change the licensing terms governing it.

The public location of the Fan App does not determine the repository configuration used by the Creator Dashboard.

---

# Repository Configuration

Repository identity is configured independently from the public location of the Creator Deployment.

For compatible GitHub repository deployments, the Repository field uses:

`owner/repository`

Example:

`creator-name/creator-app`

The public `content.json` URL is entered separately.

This separation allows a Creator Deployment to use a custom domain or another compatible public hosting configuration without requiring the Creator Dashboard to determine repository identity from the public URL.

Repository access and publishing remain subject to the permissions of the configured repository and Creator Key.

---

# Privacy by Design

BASE Tier 2 is designed to operate without requiring audience accounts, framework-level audience tracking, or framework-level data collection.

Creators may choose to integrate independent third-party services.

Those services may have their own functionality, accounts, data practices, privacy policies, licenses, and terms.

Those services remain independent of BASE.

---

# What BASE Tier 2 Provides

- Creator Dashboard
- Fan App
- Creator Deployment System
- Publishing Workflow
- Progressive Web App (PWA) Architecture
- Direct Creator-to-Audience Connection
- Creator Presentation Features
- Compatible Third-Party Service Integration
- Deployment Configuration
- System Documentation
- Deployment Documentation

Availability and configuration of individual features may depend on the Creator Deployment and compatible third-party services.

---

# Creator Deployments

Every authorized Creator Deployment remains independent.

Creators control their own:

- Creator Identity
- Creator Branding
- Creator Content
- Creator Media
- Creator Audience Relationships
- Creator Communications
- Creator-Owned Assets
- Public Deployment Configuration

Creators may also control their repository, hosting, domain, and connected third-party services where applicable to their deployment.

BASE Tier 2 provides the software used to operate the Creator Deployment.

Creator ownership of their content, branding, assets, accounts, or deployment does not transfer ownership of the BASE Tier 2 Creator Template v1.

---

# Proprietary Software

BASE Tier 2 Creator Template v1 is proprietary software.

Possession or authorized use of the Tier 2 source files does not make the Tier 2 Software open source and does not transfer ownership of the software.

The Tier 2 Software may not be redistributed, resold, sublicensed, repackaged, or used as the foundation for another software system, template, framework, platform, or competing commercial creator system except where expressly authorized in writing by William Smith McClinton.

Customization of an authorized Creator Deployment does not grant rights to create or distribute another software product from the Tier 2 Software.

See the accompanying LICENSE for the complete software rights and restrictions.

---

# Third-Party Services

Creator Deployments may connect to compatible independent third-party services.

Third-party services remain subject to their own:

- Terms
- Licenses
- Privacy policies
- Availability
- Pricing
- Technical requirements

Use of a third-party service does not make that service part of BASE and does not transfer responsibility for that service to BASE or its creator.

---

# Repository Purpose

This repository contains the BASE Tier 2 Creator Template v1.

It is provided for authorized use under the accompanying proprietary LICENSE.

Creator Deployments configured from an authorized licensed copy remain independent deployments while the underlying BASE Tier 2 Creator Template v1 remains proprietary software.

Future Tier 2 releases may expand or modify the system.

Future releases, upgrades, support, maintenance, or additional services are not automatically included unless separately provided.

---

# Documentation

Additional documentation may be included within this repository.

Current repository documentation includes:

- README.md
- RIGHTS.md
- NOTICE
- COPYRIGHT
- LICENSE
- VERSION
- CREATOR_DEPLOYMENT.md
- BUILDER_GUIDE.md

Each document should be read together with the applicable LICENSE where relevant.

---

# Ownership

BASE Tier 2 Creator Template v1 was created by:

William Smith McClinton

The BASE Tier 2 Creator Template v1 and its proprietary software remain subject to the ownership and licensing terms contained in the accompanying LICENSE.

Creator-specific identity, branding, content, media, communications, audience relationships, and creator-owned assets remain the property of their respective owners.

---

# Version

System Version:

**BASE Tier 2 Creator Template v1**