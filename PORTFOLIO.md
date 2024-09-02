# Portfolio

## Percy

Technologies: _Ruby on Rails, EmberJS, MySQL_
Commits: https://gist.github.com/jlindsayDev/c4f3d6b1ef85f1ece0eb0571e56aec34


### [Percy Enterprise](https://percy.io/enterprise)

> October 2022 to March 2023

> Implemented enterprise support and role authorizations to coincide with BrowserStack organizations

> API: 2022-10-26 to 2023-03-03
- 1c6641bf9 2023-03-03 Enable Teams for Newly-created Enterprise Organizations
- 456256b21 2023-03-02 Calculate Usage Stats by Enterprise Team
- 2022-12-05 e50c97455 Implement and consume enterprise `TeamData`
- 7704c4b99 2022-10-26 Migration: Add `enterprise_access` to organizations

> UI:
- d8c790469 2023-03-02 Fix Teams Dropdown for all Dashboard Pages
- 3151fb917 2023-01-13 Dropdown for `visibleOrganizationsInGroup`

- Ironed down specifications with BrowserStack PM and Percy Cofounder
- Lead this project


### Contact Service API and UI Modals

> October 2022 to November 2022

> API: 2022-10-06 (1935d9ee7 and 286db71b1) to (check web-commits)
> UI: 2022-11-16 (12928daaa) Contact Service Functionality

- Front-end focused
- Coordinated with BrowserStack Sales Eng team
- Cross domain support

Project did not have specifications

Took a open-ended project off the hands of overloaded coworkers and drove it to completion


### Major Ruby and Rails Version Upgrades

> July 2022 to September 2022
> 2022-07-28 to 2022-09-15

- Upgrade Rails from `6.1.6.1` to `7.0.3.1` (2022-08-04 f6e091ac7)
- Upgrade Ruby from `2.7` to `3.1` (2022-09-15 5ce972cac)
- Optimize slow-running queries with Bullet
- Remove unused and redundant gems


### Data Deletion Service

> November 2021 to July 2022
> 2021-11-05 to 2022-07-14

> Architected pipeline to safely, efficiently, reliably delete stale customer data


### Upsell Browser Configuration and Automatic Usage Notifications

> August 2021 to September 2021

- Product restrictions via API and paywall modals to upsell browser configuration
- Automatic usage notifications at 75% and 100% for paid plans

UI
> 2021-09-10 691a99d30 Upsell Browser Configuration to New Orgs
> 2021-08-16 e1226f990 Add note about automatically sending usage notifications

API
> 2021-09-10 2fec94e0a Upsell Browser Configuration
> 2021-08-24 0255ac546 Bulk project browser creation/deletion as paid features
> 2021-08-16 03176c5e1 Automatic usage notifications
> 2021-08-04 dc334358d Endpoints for bulk ProjectBrowserTarget creation/deletion


### API Documentation and Strict API Token Management

> July 2021

API
> 2021-07-22 d055a301e Migration for backfilling readonly tokens

UI
> 2021-07-20 e988a01fe Expose ReadOnly token in UI

API
> 2021-07-20 bc8476b86 API Documentation with rswag
> 2021-07-06 db600e01d [Public API] Add Support for Project ReadOnly Tokens


### Diff Sensitivity

> June 2021

UI
> 2021-06-09 1a36792c8 Remove Diff Sensitivity Feature Flag
> 2021-06-04 3ab5f5278 Visual Diff Sensitivity

API
> 2021-06-07 20c9e5500 Do not update Diff Sensitivity if already a custom value
> 2021-06-04 aadccfe93 Update Project Fuzz Factor with Diff Sensitivity


### Azure DevOps Integration

> February 2021 to May 2021

UI
> 2021-05-18 ac529a6dc Azure DevOps Launch

API
> 2021-04-27 d505367ed Better Handle Azure DevOps Errors
> 2021-03-19 84fbecf43 Azure DevOps Service Setup

UI
> 2021-03-10 361dbdf67 Azure DevOps Integration

API
> 2021-02-18 d17c1ea31 db migration to add azure devops to version_control_integrations


<details>
<summary>Other Projects</summary>
- Automated transactional emails for organization plan usage
- Visual diff sensitivity slider
    - TODO: include GIF
- Access token rotation
    - TODO: include GIF
</details>



## Sonder

Technologies: _Ruby on Rails, ReactJS, Postgresql_
Commits: https://gist.github.com/jlindsayDev/18477ed828b39d90b5c65e8c4619c2c2

### Listing Deduplication

- Booking experience A/B tests on sonder.com

### Listing Auditor

### Listings Platform for bulk CRUD operations

### Pricing Change Sets

<details>
<summary>Archive</summary>

## LendUp

- Account Management Service
  - Clock Service
  - Interest Policy
- Loan Origination Workflow

## HotPads

- Reputation Service

## SPARTA

- VM Imaging System Automation
</details>
