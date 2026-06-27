# AI Help Desk Lab Roadmap

## Project Rule

For the next phase, only learn tools and concepts that directly help build the AI Help Desk.

Avoid distractions such as Kubernetes, cloud complexity, advanced cybersecurity platforms, and unrelated frameworks until the foundation is complete.

## Phase 1: Build the IT Lab

Goal: Create a realistic small-business Windows environment.

Tasks:

- Install Windows Server 2022
- Configure static IP addressing
- Install Active Directory Domain Services
- Promote server to domain controller
- Create the domain `khanaltech.local`
- Create OUs, users, and groups
- Join a Windows client to the domain
- Create shared folders and permissions

## Phase 2: Practise Help Desk Tasks

Goal: Learn the real IT support actions the AI agent will later assist with.

Tasks:

- Reset a user password
- Unlock a user account
- Add a user to a group
- Remove a user from a group
- Create a new user account
- Disable a departed user account
- Troubleshoot shared folder access

## Phase 3: Build the Help Desk App

Goal: Create a basic ticketing portal.

Tasks:

- Create a ticket form
- Store tickets in a database
- Show ticket status
- Add ticket categories
- Add admin notes
- Add approval workflow

## Phase 4: Add AI Classification

Goal: Use AI to understand ticket requests and suggest next actions.

AI should classify:

- Password reset
- Account locked
- Shared folder access
- Software request
- Printer issue
- VPN issue
- Suspicious email

## Phase 5: Add Automation

Goal: Connect approved tickets to safe automation workflows.

Automation examples:

- Unlock account
- Reset password
- Add user to group
- Create onboarding checklist
- Disable account

## Phase 6: Build Portfolio Demo

Goal: Produce a professional demo that can be shown to recruiters or small businesses.

Demo flow:

1. Employee submits issue.
2. AI classifies issue.
3. AI searches knowledge base.
4. AI recommends action.
5. Admin approves.
6. Automation completes the task.
7. Ticket is updated and logged.
