# 🌍 AI-Powered NGO Donation & Impact Management System

## 📌 Overview
A Salesforce CRM that helps NGOs manage donors, track donations, run campaigns, and measure impact — all in one place.  
Uses **Einstein AI** (in future phases) for donor scoring and campaign recommendations.

---

## 🎯 Problem
NGOs face challenges like:
- Missed or untracked donations  
- Duplicate donor records  
- No automated follow-up or thank-you process  
- Difficulty showing donors how funds are used  
- Lack of real-time reports for decision-making  

---

## 💡 Solution
Our Salesforce solution:
- Centralizes donor data  
- Tracks donations & auto-generates receipts  
- Sends instant thank-you emails/SMS  
- Manages campaigns & shows progress in real-time  
- Provides dashboards for quick insights  

---

## 📌 Project Phases

### Phase 1 ✅ – Requirement Gathering & Analysis
- Stakeholder analysis  
- Business process mapping  
- Data model design (Donor, Donation, Campaign objects)

Docs/Phases-Documentation.md

## Phase 2: Org Setup & Configuration
- User role management
- Profiles, Permission sets
- OWD & Sharing rules

## Phase 3: Data Modeling & Relationships
- Objects: Donor, Campaign, Donation
- Lookups, Formula fields
- Schema Builder

## Phase 4: Process Automation
- Validation rules
- Record-Triggered Flow (High-value donation notification)
- Formula calculations

## Phase 5: Apex Programming
- Optional advanced automation
- Batch Apex, Scheduled jobs
- Triggers for donation updates

## Phase 6: User Interface Development
- Lightning App (NGO Donation System)
- Record pages, Tabs, Home page
- Rich text overview

## Phase 7: Integration & External Access
- Potential integration with payment gateway
- Named credentials
- REST/SOAP APIs

## Phase 8: Data Management & Deployment
- Data Import Wizard / Data Loader
- Duplicate rules
- Change sets, SFDX

## Phase 9: Reporting, Dashboards & Security Review
- Reports: Donations by Campaign
- Dashboards: Donation Overview
- Role-based security & FLS

Docs/UseCases.md

# Use Cases by Phase

## Phase 2
- Role-based access for Fundraising Officers
- Profiles and sharing rules to protect donor data

## Phase 3
- Link donations to donors and campaigns
- Accurate donor contribution tracking

## Phase 4
- Auto-notify officers on high-value donations
- Formula fields to calculate totals

## Phase 5
- Batch Apex for mass updates
- Triggers for campaign roll-up

## Phase 6
- App Launcher access
- User-friendly donation entry pages

## Phase 7
- Payment gateway integration (future)
- External donor data sync

## Phase 8
- Bulk import of donors & donations
- Deployment between sandbox and prod

## Phase 9
- Reports for campaigns, donors
- Dashboards for trends
- Role-based security review


docs/DemoScript.md

# Demo Script – AI-Powered NGO Donation System

## Introduction
- Self intro
- Problem NGOs face
- Our Salesforce-based solution

## Steps
1. Open **App Launcher → NGO Donation System**
2. Home Page → Rich Text (Problem, Solution, Benefits)
3. Donations Tab → create new donation record
   - If > $10,000 → trigger notification
4. Reports Tab → run “Donations by Campaign”
5. Dashboards → open “Donation Overview”
6. Security → switch list view by Fundraising Officer
7. Wrap-up with benefits

## Conclusion
- Saves time
- Improves accuracy
- Real-time insights
- Secure & role-based



