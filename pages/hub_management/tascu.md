---
title: "TasCu"
tags: [hub]
# keywords: release notes, announcements, what's new, new features
last_updated: 
# summary: ""
sidebar: mydoc_sidebar
permalink: tascu.html
folder: hub_management
contributors: ["Peter Blomberg"]
---

The **DBTL-P Task Curator ([TasCu](https://tascu.vtt.fi)** is an IBISBA tool for defining steps constituting industrial biotechnology projects, and for selecting required execution steps for individual projects. 

TasCu contains a sequential set of steps and tasks logically grouped into hierarchical subsets covering the DBTL-cycle for strain engineering. The same steps, tasks, and subsets constitute reusable building blocks for assembling a vast array of other project types. The defining of steps is enabled by the Universal Plan Editor functionality and steps selection by Project Planner functionality of TasCu. The Universal Plan Editor allows for defining project-agnostic steps of projects at different levels of granularity. 

TasCu-IBISBAHub integration formalises project plans, linking them with execution modules according to best practises, up to reporting. While the DBTL cycle has been commonly associated with metabolic engineering, the TasCu structure matches with most steps of other types of industrial biotechnology projects as well. For instance, a project on protein production in bioreactor cultivation followed by analytics can easily be described? as specific steps along the modules of the DBTL-P cycle.
The hierarchical layout of the tree with collapsible and expandable branches allows the steps/leafs to be viewed at different levels of granularity/depth. Steps at coarse-granularity specify modules while steps at finest levels of granularity are executable and are linked to individual Protocols. The coarse-granularity steps are meant to be associated with Metaprotocols, which explain the constituent steps and give recommendations on the execution of projects using these steps. Furthermore, the metaprotocols describe the required input and output files and define quality criteria that need to be fulfilled for each executed step. Contents of any step (i.e. lower level steps under it) can be conveniently hidden from view or revealed by clicking the corresponding step. Thus, TasCu provides the Project Planner tool as a user-friendly selector for project steps. Once the user selects the steps to be included in a project, the export function maps the selected steps to Investigation-Study-Assay (ISA) entries and generates a comma-separated values (CSV) file of the project plan, which can then be imported into IBISBAHub to populate, i.e. create, the project.

The project plans exported by TasCu, with steps mapped to ISA standard, can be imported by IBISBAHub project populator tool to initialize a project in IBISBAHub. The Protocols and Metaprotocols are stored at IBISBAHub with links to TasCu modules and identifiers. Accumulated know-how can be collected in the form of Metaprotocols and Protocols and remains directly available when new projects are planned due to links to steps in TasCu. Model project plans and standardised workflows can also be created and added as optional execution routes to the universal TasCu system later.
