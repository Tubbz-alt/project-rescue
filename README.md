# Project Rescue Plan

This repository stores formulae and data for the Project Rescue Plan that I use
when working with companies to save failing projects from certain doom. Primarily
this is where I store some formulas for Google Sheets, but also some of basic 
information on the philosophy and implementation of the plan will be saved here
as well.

# Spreadsheet Overview
Following is an overview of the tabs in the Project Rescue Plan Master Spreadsheet.
More information, including [definitions of terms](DEFINITIONS.md), is available 
throughout this repository. This is a work-in-progress and will be updated as
the plan evolves.

## Dashboard
Ten-Thousand foot view of the project's overall health and status. This view is
used by Stakeholders to get a "real-feel" for the project's current state. This
view is also useful to post on a TV or monitor near where teams sit so that they
have visibility into the current project state.

## Release Plan
This tab in the spreadsheet includes the deliverables, estimates and proposed
dates for task execution. It also includes resource comparisons and calculations,
current task status, risk and debt indicators and call-outs for blockers. This 
data can either be manually entered by the project team, or it can be imported
from JIRA directly.

## Incidents
This tab catalogs events that happen throughout the lifecycle of a project that 
impact the team's ability to meet goals and perform work. Incidents are not 
project-specific, but are rather environmental, organizational or technological 
events that block a team's ability to be productive. Examples include internet 
outages, VPN issues, resource availability, dependency failures, etc. Incidents 
are tracked on the Incidents tab in the master spreadsheet and log issues in 
order to identify common problems or recurring issues that need further 
root-cause analysis.

## Debt
This tab is a filtered view of the Release Plan that shows tasks marked as having
some level of Technical Debt. This enables teams to visualize which tasks have
to be revisited in order to clear the debt.

## Team Data
This is a Sprint-by-Sprint view of available team resources and the number of
hours that each team member will be available. Times marked are in _productive_
time only with the expectation that most resources will only be productive for 
five (5) to six (6) hours each day, depending on their meeting load and allotted
schedule.

## Sprint Overview
Retrospective data for each Sprint is captured here along with a few key metrics
that help us determine if the Rescue Plan is on-target and if the team is making
progress toward their goals.

## Sprint Data
This tab stores data about the Sprint schedule, duration, current Sprint and some
[configuration settings](SETTINGS.md) that help to drive the spreadsheet.

## Cost Forecasting
This tab helps managers understand the cost of the current project from a resource
and personnel perspective. It allows one to see the impact of overhead and of
team resources across the life of the project.