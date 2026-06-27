# AI Help Desk Lab

This repository documents the process of building an AI-powered IT Help Desk from scratch while learning real-world systems administration skills.

## Project Goal

Build a realistic small-business IT environment and then create an AI help desk agent that can classify tickets, search a knowledge base, recommend fixes, request approval, and eventually trigger safe automation workflows.

## Fake Company

**KhanalTech Solutions** is the simulated business environment for this lab.

The business has:

- 25 employees
- Windows laptops
- Windows Server Active Directory
- Shared folders
- Microsoft 365-style workflows
- Printer and VPN support scenarios
- Basic cybersecurity support needs

## Skills Practised

- Windows Server administration
- Active Directory
- DNS, DHCP, and domain joining
- Users, groups, OUs, and permissions
- File share management
- Help desk ticket workflows
- PowerShell automation
- Knowledge base writing
- AI ticket classification
- Secure approval-based automation

## Repository Structure

```text
01-Documentation/   Learning logs, company overview, roadmap
02-Diagrams/        Network and architecture diagrams
03-PowerShell/      PowerShell scripts for IT support tasks
04-KnowledgeBase/   Help desk articles used by the AI agent
05-Screenshots/     Evidence of lab progress
06-Projects/        Application build notes and future code plans
```

## Current Phase

**Phase 1: Build the fake company IT environment**

The first milestone is to create a basic Windows Server domain with users, groups, shared folders, and a domain-joined Windows client.

## End-State Demo

The final demo should show:

> An employee submits an IT issue. The AI understands the problem, checks the knowledge base, suggests a fix, asks for approval, and then runs the correct IT workflow safely.
