# CHoRUS Bridge2AI Tooling Team

## Progress Tracking for Tooling Team

### Purpose
This framework provides contributing sites and developers an easy way to review the tools being developed for the project.

This framework provides a **workspace** where developers can manually track progress tools, keep notes, and reach out to the Tooling Team for assistance. It also equips the Tooling Team with tools for overseeing the progress and challenges of multiple sites at once when tools get distrubuted across sites.

### Quickstart Guide
The repository supports multiple use cases:

1. Identifying or updating granular details about how a tool is working at a site or how the cloud is interacting on various elements of the Bridge2AI data
    - Head over to the [repositories page]([(https://github.com/orgs/chorus-ai/repositories)] and search different tools that are being generated
    - Current tools are:
        - Privacy check
        - Clinical NLP
        - Integrated viewer - IVe
        -  Cohort adjudication and data annotation - CADA
        -  Telemetry Physiology Data Conversion
        -  EEG Physiology Data Conversion
        -  Imaging data conversion
        -  Site-specific practice-pattern metadata
        -  Interpretable Machine Learning Toolbox
        -  Predictive model evaluation
        -  MONAI for critical care
        -  Develop Canonical Notebooks
        -  Collaborative workflow
        -  SOPs

2. Viewing the overall progress of the consortium with regard to Tooling
    - Head over to the [project page](https://github.com/orgs/chorus-ai/projects/11) and select a relevant view to see how Tools are progressing
3. Posing questions, searching for answers, or responding to outstanding issues related to StandardsModule topics
    - Check out the [discussions page](https://github.com/chorus-ai/StandardsModule/discussions) for active discussion and collaboration
    - **Please note that any discussion for specific tools can be also taken to the tool repos.**

### Overview
This framework solves three problems for the Tooling and the Bridge2AI contributing sites:
1) **Major milestones**: Tooling seeks to provide sites with a list of major milestones involved in the tools necessary to de-identify, privacy, and upload data for contribution to CHoRUS Bridge2AI.
2) **Progress monitoring**: Tooling needs to understand the overall status of sites' progress in order to better tailor support to the entire group and specific sites.
3) **Discussion platform**: Tooling wants to host a discussion board or forum where sites can post questions or present topics for discussion with other sites and SM simultaneously.

To address these challenges, the Tooling Team introduces the following solutions:
1) **Major milestones**: The Tooling Team provides a high-level Roadmap of general tasks to show sites what is the status of tools.
2) **Progress tracking**: Tooling makes the Roadmap accessible. This visibility enables support when needed when tools are distrubuted.
3) **Discussion forum integration**: The framework integrates with GitHub Discussions, offering a platform for sites to post questions and receive answers from SM or other sites. This integration connects discussions to issues in the Progress Tracker and allows the creation of new topics from posted questions.

### Developer Instructions
This framework uses a progress tracking system categorized into two main categories:
1) **Milestone issues**: these issues are those that are tracked for NIH completion
2) **Progress Tracker issue**: this single issue serves as smaller issues that are to be completed to be the critical path to the Milestone

### Engagement and Benefits
The benefits a site and developer gains from this framework are directly related to its level of engagement.
Here's how to get the most from the framework:

1. **Progress tracking**: sites/developers should assign representatives to track their progress. Regularly updating if you have a tool that you are working on.
2. **Regular comments**: sites/developers should leave comments on the issues at regular intervals or whenever encountering challenges. These comments help Tooling provide tailored support.
3. **Status labels**: sites/developers should use the issue labels to report their status. Labels include:
    - Blocked: indicates that a task cannot proceed with work. Comments can specify whether the blockage is external or something the Tooling can assist with.
    - Help Wanted: signals that a task needs other team assistance. The reason for help can be explained in a comment.
    - Under Review: marks that a task has requested feedback and progress is paused until feedback is received.

Using these labels in conjunction with comments helps the Tooling Team understand a site's current situation and support needs.

Ultimately, any interaction with the issues, whether it is simply progress updates via comments on the Progress Tracker issue, checking boxes in the milestone issues, utilizing labels, or a combination of these methods, provides useful feedback to Tooling on where Tasks are in their standardization process.
