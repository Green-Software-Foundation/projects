---
layout: default
title: Project Lifecycle
nav_order: 5
has_children: true
has_toc: false
---
[//]: # (SPDX-License-Identifier: CC-BY-4.0)

# Project Lifecycle

The term "project" within Green Software Foundation refers to a collaborative endeavor to deliver a work item. There are two types of projects at the Green Software Foundation:  Document Projects and Software Projects. Document Projects are consensus-based. They produce a document, such as a requirements or use cases document, a whitepaper, or analysis. Software projects are maintainer-based. They develop a new capability, refactor, or remove an existing capability for the Green Software Foundation technology releases. Such projects may take the form of a new component (e.g. a new repository) or may propose additions, deletions, or changes to an existing repository or repositories.

The Software Project lifecycle process. 

INSERT NEW DIAGRAM

Projects are in one of five possible lifecycle stages:

- [Proposal](#proposal)
- [Incubation](#incubation)
- [Graduated](#graduated)
- [Maintained](#maintained)
- [Archived](#archived)

Projects may not necessarily move through those states in a linear way and may go through several iterations, although the goal for a Software project is to Graduate. 

# Proposal
#### Description 
Any GSF Member may raise a project proposal idea. 

#### Expectation
The proposal should be submitted to a Working Group using the New Project Proposal issue template. 

A Proposal must:
-   Have a clear description
-   Have a well-defined scope
-   Identify committed development resources
-   Identify initial maintainers
-   Be vendor neutral
-   Have idetified any risks
-   Describe what success looks like
-   Know its audience/community

#### Acceptance Criteria
No barriers to entry - any project idea can be proposed to a Working Group. 


# Incubation
#### Description 
The project is in it’s experimental stage, and is being explored by the project team.  

#### Expectation
Every incubation project must have this disclaimer clearly at the top of their repo README and as a banner on every page of any public-facing documentation.

_[!important] Incubation Project
This project is an incubation project being run inside the Green Software Foundation; as such, we *DON’T recommend using it in any critical use case. Incubation projects are experimental, offer no support guarantee, have minimal governance and process, and may be retired at any moment. This project may one day graduate, in which case this disclaimer will be removed._

#### Benefit
- Project home fostering collaborative, open development with a path to maturity via the graduation process. 
- Project receives marketing support from GSF, including being listed on the GSF website, opportunity to participate in GSF events, social media 
- Project will receive mentorship in areas such as, but not limited to, project management, governance, legal, tooling, security best practices and documentation 

#### Acceptance Criteria
The proposed project must meet the following requirements to reach Incubation: 
- Have a representative of at least one GSF member company participating, who is a WG attendee who will champion the project, volunteer to run it as project lead and share updates at the WG
- Have an assigned GSF PM
- Project name should not be trademarked and should have the approval of GSF marketing
- Similar or competitive projects are allowed. Projects are not excluded for reasons of overlap.

#### Lifecycle Stage Approval Process
- Projects seeking to reach Incubation Stage must submit the proposal template issue to the Working Group for consensus approval. 
- Once WG approval is gained, the GSF PM must submit an issue to the Oversight Committee repo for awareness. They have 2 weeks to comment / object. 
- Project proposals which are deemed by the WG/OC to be of high risk, for example potential reputation damage, financial risk, litigation risk, greenwashing concern, must also be reviewed by the Steering Committee.

#### Approving Body
Working Group 


# Graduated
#### Description 
The project is considered mature and stable, and is supported by an active community.  

#### Expectation
- At least version 1 of the project is released and publicly available. 
- Contributors may continue to explore further versions of the project. 

Every project in Graduated Stage must have this disclaimer clearly at the top of their repo README and as a banner on every page of any public-facing documentation. 

_[!important] Graduated Project
This project is a Graduated Project, supported by the Green Software Foundation. The publicly available version documented in the README is trusted by the GSF. New versions of the project may be released, or it may move to the Maintained or Retired Stage at any moment._ 

#### Benefit
- Incubation disclaimer is removed and replace with a banner to show it is a trusted project supported by the GSF. 
- Project receives marketing support to celebrate the graduation of the project. 

#### Acceptance Criteria
The project must meet the Incubation requirements as well as the following:
- Have a active set of contributing members from at least two member organisations
- Have a public GitHub repo with clear project documentation on
  > Project overview (ReadMe)
  
  > How to contribute (contributing.md )
   
  > End User Guide (enablement.md)
  
  >  Test coverage
  > 
  > Fit within GSF Theory of Change
- Have made a release deployment, even a ‘developer preview’
- Evidence of usefulness through real world use cases in the production environment, including testimonials (adopters.md)
- Have 100% of the applicable criteria for the Open SSF Best Practice Badge (security.md)
- Have an incident process agreed with GSF PM.
- Have GSF processes set up including
  > Project meetings and mailing list
  
  > Up to date project documentation on confluence
  
  > Provide regular updates to the relevant WG
  
  > Have defined OKRs agreed by the GSF PM
- Similar or competitive projects are allowed, but the project should not contradict with another GSF Graduated project. 

#### Lifecycle Stage Approval Process
- Projects seeking to reach Graduated Stage must submit an issue to the Oversight Committee repo.
  GSF PM (and Project Leads) should join the next Oversight Committee meeting to showcase their project meets acceptance criteria below for Graduation consensus approval.   
- Once OC approval is gained, the GSF PM must submit an issue to the Steering Committee repo for awareness. They have 2 weeks to comment / object. 

#### Approving Body
Oversight Committee


# Maintained
#### Description 
The project is considered Graduated but new versions aren’t being released, except for bug fix maintenance. 

#### Expectation
- Projects must be maintained by their community. 
- The repo is still open for contributions
- If contributors want to reactivate the project, it can re-enter Incubation Stage
- If maintainers want to stop maintaining the released version, it should progress to the Archived stage 

Every project in Maintained Stage must have this disclaimer clearly at the top of their repo README and as a banner on every page of any public-facing documentation. 

_[!important] Maintained Project
This project is in maintenance being run inside the Green Software Foundation.  Releases are maintained but not improved. This project may be retired, or reactivated back into incubation._

#### Benefit
- Project remains under the GSF umbrella

#### Acceptance Criteria
The Project Team must notify the GSF PM they are no longer actively working on the project, but will continue maintenance. 

#### Lifecycle Stage Approval Process
- Projects seeking to reach Maintained Stage must submit an issue to the Oversight Committee repo, and reach a consensus for approval. 

#### Approving Body
Oversight Committee

# Archived
#### Description 
The project is considered dormant and any releases are no longer being maintained.  

#### Expectation
- Projects are not maintained by their community. 
- If contributors want to restart the project, they must raise a New Project Proposal issue. 

 Every project in Archived Stage must have this disclaimer clearly at the top of their repo README and as a banner on every page of any public-facing documentation.

_[!important] Archived Project
This project is archived and is no longer being run inside the Green Software Foundation. Releases are *NOT maintained or improved. This project cannot be reactivated._ 

#### Benefit
- No longer a GSF project

#### Acceptance Criteria
The Project Team must notify the GSF PM they can no longer commit to maintaining the project. 

#### Lifecycle Stage Approval Process
- Projects seeking to reach Archived Stage must submit an issue to the Oversight Committee repo, and reach a consensus for approval.
  
#### Approving Body
Oversight Committee
