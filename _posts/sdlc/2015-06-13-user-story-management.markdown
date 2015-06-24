---
layout: item
title:  "User Story Management"
date:   2015-06-13 16:54:46
author: David Larrimore
categories:
- sdlc
img: 
thumb: 
---


In software development and product management, a user story is one or more sentences in the everyday or business language of the end user or user of a system that captures what a user does or needs to do as part of his or her job functio


* User stories must follow the “As A….I need….So I can….” format, and equate to some form of some sort of delivered business value. This includes “Architectural backlog” User Stories.
* User stories must be sized (“points”) based upon relative sizing using the Fibonacci sequence (1, 2, 3, 5, 8, 13, 21, 34, etc…)
* Stale User Stories (3+ releases old) should be re-validated with the business as well as technical team prior to being scheduled
* All user stories must link to a defined Portfolio Management “Feature”.
User Stories that are not completed during a normal sprint must be split. This means that a parent User Story is created, and unfinished work is placed in a new child User Story that is planned in the subsequent sprint.


#### User Story Approvals

* Only Product Owners may create user stories.
* Only Product Owners my “Cancel” a user story.
* Only Product Owners may “Accept” a user story.
* Only Product Owners may “re-open” a cancelled user story.



### Example of a Defined User Story

**User Story**: As a Financial Analyst, I need a report summarizing customer agency business volume with taxes and surcharges so I can reconcile those numbers against pegasys and validate vendor CAF payments.
 
**Acceptance Criteria**

* A new Webi report titled "Summary by Agency of Business Volume w/Taxes Surcharges report" available in Business Objects
* The report should include the following fields:
*     Agency Code
*     Agency Name
* Invoice Date - Fiscal Year
* BV with Taxes
* The report should have a prompt to select a single fiscal year
* Format needs to be a cross-tab
* Data validation against access database
* Report format should match the attached WAN report format provided by ITS


**Rally Tip**: 
    
    Attach any requirements, screen shots, customer feedback, email, picture, or other files related to a User Story directly to the User Story in Rally to provide better traceability and ease of access.




#### User Story States

<div class="container">
    <div class="row">
        <div class="col-lg-10 col-lg-offset-1 himg">
            <img src="{{ "/assets/img/sdlc/" | prepend: site.baseurl }}user-story-states.png" alt="User Story States">
        </div>
    </div><!-- /row -->
</div> <!-- /container -->
