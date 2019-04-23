*********************************************
Linux Foundation Networking Project Lifecycle
*********************************************

Introduction
------------

The Linux Foundation Networking umbrella consists of multiple projects. This
document describes the lifecycle of those LFN projects.

Each LFN project governs itself. LFN projects may consist of multiple
subprojects with their own lifecycles. This document's scope is limited to
top-level LFN projects.

Project Lifecycle
-----------------

LFN projects have a lifecycle. That lifecycle is characterized by Project
States and State Transitions.

Project States
==============

+---------------+-------------------------------------------------------------+
| Project State | State Summary                                               |
+===============+=============================================================+
| none          | Project does not exist or exists outside of LFN.            |
+---------------+-------------------------------------------------------------+
| Sandbox       | Project is admitted to LFN but does not have direct funding |
|               | from LFN.  The intent is to enable new projects to gain     |
|               | visibility and participate in the LFN with minimal impact   |
|               | on existing projects until they are ready for a subsequent  |
|               | state.                            			      |	
+---------------+-------------------------------------------------------------+
| Incubation    | Project has matured beyond sandbox and may receive some     |
|               | funding but does not yet have a representative on the TAC.  |
+---------------+-------------------------------------------------------------+
| TAC Project   | Project is granted TAC representation.                      |
+---------------+-------------------------------------------------------------+
| Archived      | Project is no longer active.                                |
+---------------+-------------------------------------------------------------+

Project State Transitions
=========================

+--------------+-------------------+----------------------+-------------------+
| From State   | To State          | TAC Review           | Board Review      |
+==============+===================+======================+===================+
| none         | Sandbox           | LFN Entry Review     | LFN Entry Review  |
|              |                   | Quarterly Health Rvw |                   |
+--------------+-------------------+----------------------+-------------------+
| Sandbox      | Incubation        | Incubation Review    | Incubation Review |
+--------------+-------------------+----------------------+-------------------+
| Incubation   | TAC               | TAC Admission Review | TAC Admission Rvw |
+--------------+-------------------+----------------------+-------------------+
| *            | Archived          | Archival Review      |                   |
+--------------+-------------------+----------------------+-------------------+
| *            | none              | LFN Exit Review      | LFN Exit Review   |
+--------------+-------------------+----------------------+-------------------+

Project Reviews
===============

For each review, the project must instantiate the Project Data Template. If the
project has already submitted a template for a past review, they can update it
(taking in to account any changes to the base template) for the new review.

Additionally, a project must publicly announce their intention to undergo a
review at least two weeks prior to the date of the review. The announcement
must include a link to the instantiated Project Data Template for the review.
The public may comment on the document. The project must engage with comments,
answer questions and address feedback.

Reviews must be conducted in a manner that allows a global community to
participate. For example, at a time that is amenable to as many stakeholders as
possible and using tooling that is generally accessible.

LFN Entry Review
****************

The Board and the TAC both review proposals for new LFN projects.

TAC LFN Entry Review
++++++++++++++++++++

Review by the TAC for creating new projects under the LFN or admitting existing
non-LFN projects into the LFN.

TAC LFN Entry Reviews should happen before, and provide input into, Board LFN
Entry Reviews.

Required Information for TAC LFN Admission Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

An up-to-date instantiation of the Project Data Template is required for an LFN
Entry Review.

Criteria for TAC LFN Admission Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Mandatory criteria for successful completion of the LFN Entry Review is
documented governance that is clear, complete, and easily and obviously
accessible (such as a link from of the project's main page). That governance
must minimally specify:

* Project Roles.
* How people come to fill project roles.
* How people are removed from project roles.
* Who currently fills all project roles.
* How disputes are definitively resolved (usually by majority vote).
* How the governance evolves over time.
* What is the top level technical decision making body for the project,
  analogous to a TSC, to which the TAC should look for interfaces.

Additionally, the review will confirm that the incoming project scope is within
scope of the LFN.

Outcome for TAC LFN Admission Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

As an outcome of the TAC's LFN Entry Review, the TAC will provide the following
feedback to the LFN Governing Board for use as input to the LFN Board's LFN
Entry Review:

* Summary of findings
* Recommendation to accept the project into LFN or not.

Board LFN Entry Review
++++++++++++++++++++++

It is up to the Board to define its own criteria and process of the Board's LFN
Entry Review. Such review may include legal, trademark, and license reviews. The 
TAC recommends the Board make its LFN Entry Review criteria and process public 
and accept design input from the public.  

Budget Guidance: The TAC recommends that the governing board allocate no funding 
to Sandbox projects and that those projects cannot use cross-project funding
buckets.

Quarterly Health Review
***********************

The TAC should review all projects in the Sandbox state on a quarterly basis. 
The goal of the quarterly health review is to assist the projects in their 
participation in LFN and ensure the project's community remains healthy.

Incubation Review
*****************

The Board and the TAC both review proposals for projects to advance to the 
Incubation state.

TAC Incubation Review
+++++++++++++++++++++

TAC Incubation Reviews should happen before, and provide input into, Board 
Incubation Reviews.

Required Information for TAC Incubation Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

An up-to-date instantiation of the Project Data Template is required for an 
Incubation Review.

Criteria for Incubation Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Mandatory criteria for successful completion of the Incubation review is
the documented demonstrable progress since induction toward open source best practices. This would include but is not limited to contributor diversity and 
open governance.

As an additional (non-mandatory) guideline, the project should show demonstrable
progress in marketplace adoption.  This may be measured by instances of the
project in production or the project being embedded in other open source 
projects.

As part of the Incubation Review, the TAC should identify how the project fits
with other LFN projects, including any overlap or harmonization potential.

Outcome for Incubation Admission Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

As an outcome of the TAC's Incubation Review, the TAC will provide the following
feedback to the LFN Governing Board for use as input to the LFN Board's 
Incubation Review:

* Summary of findings
* Recommendation to accept the project into the Incubation stage or not.

Board Incubation Review
+++++++++++++++++++++++

It is up to the Board to define its own criteria and process of the Board's 
Incubation Review. The TAC recommends the Board make its Incubation Review 
criteria and process public and accept design input from the public.  

Budget Guidance: The TAC recommends to the board that any new Incubation 
project not erode existing TAC project budgets.

 
TAC Admission Review
*****************

The Board and the TAC both review proposals for projects to advance to the 
TAC project state.

TAC Admission Review
+++++++++++++++++++++

The TAC Admission Review is intended for the TAC to consider whether an
Incubation Project should have a representative on the TAC. It is initiated 
by a TAC Admission Request from an Incubation Project.

Required Information for TAC Admission Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

An up-to-date instantiation of the Project Data Template is required for a TAC
Admission Review.

Criteria for TAC Admission Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Mandatory criteria for successful completion of the TAC Admission Review are
maintenance of the mandatory criteria for LFN Entry and demonstration of
adequate project Diversity, a clear statement of how the Project will select
its TAC Representative and adherence to the LFN Principles.  

The project should also show demonstrable progress in integrating with other 
LFN projects, participating in cross-LFN initiatives and/or contributing to 
extending or strengthening the total scope of the LFN.

As an additional (non-mandatory) guideline, the project should show continued
progress in marketplace adoption. 

Outcome for TAC Admission Review
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

As an outcome of the TAC Admission Review, the TAC will provide the following
feedback to the LFN Governing Board for use as input to the LFN Board's 
TAC Admission Review:

* Summary of findings
* Recommendation to accept the project into the TAC Project stage or not.

Board TAC Admission Review
+++++++++++++++++++++++++++

It is up to the Board to define its own criteria and process of the Board's 
TAC Induction Review. The TAC recommends the Board make its TAC Admission Review 
criteria and process public and accept design input from the public.  

Budget Guidance: The TAC recommends to the board that any new TAC project 
receive funding through the existing board and TAC process for determining
budget priorities. 

Archival Review
***************

A Project may be Archived if it has received no significant commits within the
previous 12 months or by a majority vote of the Project's TSC to request the
project be Archived. Prior to TAC initiation of an Archival Review of a
Project, a good faith effort must be made to contact the Project's TSC and
initiate a dialog about the future of the Project.

Criteria for Archival Review
++++++++++++++++++++++++++++

Mandatory criteria for Archiving a project are one of:

* A clear request from the Project to be archived.
* Clear evidence of the project has received no significant commits within the
  previous 12 months and demonstration of a good faith effort by the TAC to
  contact the Project's TSC and come to a positive resolution.

Outcome for Archival Review
+++++++++++++++++++++++++++

The TAC will notify the Board immediately of any decision to Archive a project.

LFN Exit Review
***************

A Project may request to leave the LFN by majority vote of its TSC.

Should a project request to leave the LFN, it is the obligation of the TAC to
forward that request to the Board immediately upon notification.

The Board may cause a project to exit LFN at their discretion.

Recommendations to Candidate Project
------------------------------------

The TAC will provide the following feedback to the candidate projects for all
reviews.

* If TAC recommends that the candidate project lifecycle state transition be
  approved, the TAC will provide recommendations for improving the project.
* If TAC recommends that the candidate project lifecycle state transition not
  be approved, the TAC will give feedback about which criteria the project did
  not adequately meet and what changes to the candidate project would be
  required to change the TAC's recommendation.

Disposition of Existing Projects
--------------------------------

OpenDaylight, OPNFV, FD.io, and ONAP are in state TAC. PNDA, SNAS, and Tungsten
Fabric are in state Incubation (?).

Amendment of Technical Governance
---------------------------------

This Technical Governance may be amended by a 2/3 vote of the TAC subject to
approval by the LFN Board.
