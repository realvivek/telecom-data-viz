# Project 2: Fiber Opportunity Tracker — MVP Draft

## 1. Initial Grant Tracking Index (NTIA/BEAD)
Using the **Fiber Tracker** skill, I’ve identified these current/upcoming high-value milestones:

| Grant Type | Description | Milestone / Deadline |
| :--- | :--- | :--- |
| **BEAD (NTIA)** | Federal broadband funding for unserved/underserved areas. | **Early 2026:** NTIA to approve final state proposals. |
| **Middle Mile (NTIA)** | Infrastructure for the backbone network connecting cities. | **Ongoing:** Finalizing buildout for awarded projects. |
| **Tribal Broadband (NTIA)** | Specifically for infrastructure on tribal lands. | **Q1 2026:** Award announcements for the latest round. |

## 2. Decision Intelligence: Key Data Sources
*   **FCC National Broadband Map:** Overlaying existing "served" areas with grant-eligible areas.
*   **State Broadband Offices:** Pulling specific RFP data (e.g., Texas Broadband Development Office).
*   **Fiber Route Data:** Mapping dark fiber/backbone routes from public/OpenSource sources (e.g., OpenCellID for backhaul).

## 3. Dashboard MVP Mockup
*   **Map Interface:** An interactive map with layers for:
    *   🔵 Existing Fiber Routes (Publicly known).
    *   🔴 Unserved Areas (Digital Divide focus).
    *   💰 Grant Opportunities (Active RFPs).
*   **Opportunity Feed:** A sidebar with a list of active grants, bid deadlines, and estimated award amounts.
*   **Alerting Toggle:** "Email me when a new RFP is posted for [State/County]."
