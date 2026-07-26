# Sales & Marketing Performance Dashboard — Power BI

Capstone project: analyze several years of orders and completed projects for a digital-marketing
agency and deliver a decision-ready Power BI report for management.

## Objective

The agency owner provided a multi-year database export of client orders and completed projects.
The brief: build a data model, calculate a defined set of business measures, and deliver an
interactive report that management can use without touching the underlying data.

## Data model

- Loaded the source tables into Power BI and defined the relationships between them
- Built a custom calendar table (year, month, month number, weekday name, weekday number) and linked
  it to the transactional data, with the calendar sorted by month number rather than month name

## Measures (DAX)

- Share of revenue by acquisition channel (social/marketing source), relative to total revenue across
  all sources
- Client count for a specific month (October 2021)
- Project ranking by revenue
- Share of revenue by account manager, relative to total revenue
- Total revenue for the top 3 cities by sales
- All measures grouped into a dedicated measures table, kept off the report canvas

## Report

- Multi-page interactive report including:
  - a ranked table of projects
  - a bar chart of revenue share by account manager
  - a pie chart of revenue share by project, with decluttered labels
  - a map visual of sales by geography, with conditional formatting from lowest (red) to highest (blue)
  - a KPI gauge for October revenue
  - a call-out panel for the top 3 cities by revenue
  - cross-filtering configured so the manager-revenue chart does not affect the project-ranking table

## Tools

Power BI Desktop · DAX · Power Query · Microsoft Access
