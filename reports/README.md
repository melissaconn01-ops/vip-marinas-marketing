# Reports

This folder is reserved for AI-generated reports and summaries for the VIP Marinas marketing portfolio.

---

## Purpose

Reports in this folder are generated from repository data. They are intended to support decision-making, leadership communication, and periodic review. They are not the source of truth for any project, task, or tracker.

---

## Types of Reports This Folder Can Hold

The following types of reports can be generated and stored here:

**Monthly Marketing Reports**
Summaries of portfolio-wide marketing activity, project status, campaign performance, and tracking improvements for a given month.

**Marina Status Reports**
Individual marina summaries covering active projects, open issues, tracking status, campaign activity, and upcoming priorities.

**Campaign Reviews**
Post-campaign or mid-campaign reviews covering performance, tracking quality, creative output, and recommendations.

**Tracking Audits**
Summaries of conversion tracking, lead tracking, GA4, Google Ads, phone, form, Kenect, and CRM tracking status across one or more marinas.

**Leadership Updates**
Executive-level summaries prepared for leadership review. Should align with the leadership-review.md file.

**Quarterly Planning Documents**
Portfolio-level planning documents for the upcoming quarter, including project priorities, campaign calendar, resource needs, and strategic recommendations.

---

## Naming Convention

Use descriptive, date-stamped filenames so reports can be found easily. Examples:

- 2026-06-monthly-report.md
- - 2026-q2-quarterly-plan.md
  - - lake-travis-campaign-review-2026-06.md
    - - tracking-audit-2026-05.md
      - - leadership-update-2026-06-02.md
       
        - ---

        ## Important: Source of Truth

        Reports generated and stored here should always reference the source data files. The source of truth for all project and tracking data remains:

        | File | Contains |
        |------|----------|
        | marina-index.csv | Portfolio-level marina status |
        | project-index.csv | Major projects by marina |
        | project-tasks.csv | Specific tasks, approvals, blockers, and next steps |
        | campaign-tracker.csv | Active and planned marketing campaigns |
        | tracking-issues.csv | Conversion, lead, and CRM tracking issues |

        Do not use reports in this folder to override or replace the CSV source files. Always update the source CSV files first, then regenerate reports as needed.

        ---

        ## Future Integrations

        This folder is designed to be compatible with future integrations. Reports stored as markdown files can be consumed by:

        - Airtable integrations
        - - Google Drive syncs
          - - Custom dashboard tools
            - - Stakeholder-facing documentation portals
             
              - The goal is to keep GitHub as the source of truth while enabling flexible reporting across platforms.
             
              - ---

              _This folder is currently empty. Reports will be added here as they are generated._
