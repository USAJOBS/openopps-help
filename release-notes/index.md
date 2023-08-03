---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

## Changes made August 4, 2023
### Sitewide

* Updated the primary navigation and secondary navigation menu bars.
* Updated the banners that display when a sitewide administrator is viewing another user’s profile to view the type of user the profile belongs to.
* Removed opportunity data from the sitewide administrator **Manage internships.csv**.

### Communities

* Updated the **cycle selection** dropdown on the **Community dashboard** so it defaults to the most recently created active cycle.
* Updated the search bar on the **Search applications** page for cyclical communities to persist when no search results display.
* Updated the **Add member to community** modal to include searching by a user’s email address.

### Opportunities

* Updated the color and text of the following status icons:
  * Applied
  * Not assigned
  * Assigned
  * Submitted
  * Not open
  * Draft
  * Open
  * In progress
  * Completed
  * Reviewing applicants

* Added markdown functionality to the **Statement of interest** field on the **Opportunity application** page for lateral and detail opportunities.
* Changed the **Opportunity renewal** success banner to a display as a snack bar.

### Internships

* Updated the color and text of the following status icons:
  * Application started
  * Withdrawn
  * Submitted
  * Not open
  * Draft
  * Open
  * In progress
  * Completed
  * Reviewing applicants

* Updated the design of the success banner that displays when a creator completes an internship.
* Added modals that display when an internship applicant’s resume or transcript is not downloadable.

### Bugs

* Fixed an issue with the **postal code** field on the **Profile edit** and **Create a profile to join** pages so the system recognizes valid postal codes.
* Fixed an issue with the tooltip for the **Selected_students.csv** so it displays in the correct location on the **Community dashboard** page.

## Changes made July 21, 2023
### Sitewide

* Performed technical debt tasks to remove code that is no longer used.
* Updated the data check method between USAJOBS and Open Opportunities prompting users to update their USAJOBS profile when critical information is missing.
* Updated the text on the **Inactive account** page to be clearer about actions a user needs to take.
* Completed several technical debt clean-up tasks.
* Updated the sign in process to check for a guest account on USAJOBS. 

### Communities

* Removed the ability for creators and co-owners to update the cycle of an internship when the internship is in progress.
* Updated the **student_community_internships.csv** download to include the federal email address of co-owners.
* Added a cycle dropdown to the **Applications** page of cyclical student communities.
* Updated the community cards to display **Pending approval** when a user has requested to join a community and is still waiting for approval.
* Updated the banners that display at the top of the page when a community administrator is viewing the profile page of federal, contract and student users. 

### Bugs

* Fixed an issue where users could not continue when adding profile information on the **Create an account** page.

## Changes made July 7, 2023  
### Sitewide

* Made several backend updates to remove code that is no longer used.

### Communities

* Updated the **Certificate of Completion** to include a custom signature name and title. A user receives this certificate when they complete an internship or opportunity task.
* Enabled the **Join community** button to display for closed communities.
* Created a modal that displays when a user tries to join a closed community.
* Created an email that is sent to community administrators when a user tries to join a closed community.
* Added a notification that displays when a user successfully requests to join a closed community.
* Updated the student community **Manage cycles** page to uncheck the **Active cycle** checkbox when the internship dates of a cycle have past.

### Internships

* Created an email that is sent to community and sitewide administrators when an internship has not been approved and is approaching the application due date.

### Opportunities

* Added a notification that displays when a user has successfully applied to a one-time or recurring opportunity.
* Updated the **Who can apply** text to display “Open to all federal employees” when an opportunity is open to all federal employees.
* Created a modal that displays when an applicant's resume fails to download or does not display.

### Bugs

* Fixed an issue with the internship detail page so it now loads for internships created outside of a community.
* Fixed an issue so users who have an incomplete profile do not get an error page.
* Fixed an issue so community administrators who click on a user’s name will go to the correct page.
* Fixed an issue on the **Recommended internships** page so both **Approved** and **Open** internships display.

## Changes made June 23, 2023
### Sitewide

* Added a **Find communities** button to the landing page.
* Added a **Find communities** check box to the landing page drawer of the content tab for sitewide administrators—the check box controls whether the **Find communities** button appears on the landing page.
* Updated the following banners to use the USWDS slim banner design:
  * Renew opportunity
  * Get recommend opportunities
  * Enhance your profile

### Communities

* Created a toggle for communities to limit opportunities to only community members.
* Added text to the **Who can apply** section on the **Opportunity detail** page and **Step 4 review** page to indicate when a community is limited to community members.
* Updated the opportunities that are limited to community members to only display on the search page for community members.
* Added text above the **Apply** button to indicate when an opportunity is only available for community members.
* Added a modal that displays when a user is not a member of a community and applies to an opportunity that is limited to community members.
* Added text and a check box to the **Step 1 opportunity creation** page telling creators if an opportunity will be limited to community members.
* Updated duplicated opportunities to have the limit to community members checkbox checked if the opportunity being duplicated has the checkbox checked.
* Updated the user dashboard to remove communities that have the **Limit who can apply** toggle turned on from the **Search opportunities by** section.
* Updated the **Invite to opportunity** modal to only display community members in the dropdown when an opportunity is limited to community members.
* Created a **Related communities** toggle on the **Community settings** page.
* Added a **Related communities** field to the **Community settings** page when the related communities toggle is turned on.
* Added a **Related communities** section to the **Community profile** page of communities with the related communities toggle set to on.

### Internships

* Added an information “i” icon to the **Student internship ranking table** to describe how to use the ranking table.
* Disabled the **Student internship ranking table** for inactive cycles.
  
## Changes made June 9, 2023
### Sitewide

* Added an **Internships created** infographic to the top contributor’s section of the sitewide administrator dashboard page.
* Added a **.csv download link** to download the data in the **Internships created** infographic.
* Added a **Community** column to the **Created** table on the dashboard.
* Added ability to **sort by Community** to the **Created** table on the dashboard page.
* Removed the **agency heading** from the student user profile page.

### Communities

* Updated the **Applicant cap** functionality to calculate the number of applicants using a multiplier.
* Updated the instructional text for the **Applicant cap** toggle to describe how the multiplier works.
* Updated the **student_community_internships.csv** to include the federal email address of community members.
* Updated the **Manage internships .csv** to display data based on what the user selects in the cycle dropdown.
* Made several updates to **student communities**:
  * Updated the dashboard to remove the opportunity metrics and add internship metrics.
  * Updated the settings page to include an Internship page and Internship status drawer.
  * Updated the settings page to include new toggles to:
    * Display the community’s logo on the internship page.
    * Display the community’s name on the internship page.
    * Allow internship creators to end an internship before the estimated end date.

* Added a snack bar success message that displays when a user deletes a cycle from a community.
* Added user type icons to the **Manage users** page for student communities.

### Internships

* Updated the **Step 1 internship creation** page to include new text below the **Interns needed** field to describe the applicant limit.
* Removed the **Applicant cap** validation text that displayed when a user included a number in the **Interns needed** field that was higher than the applicant cap set by a community administrator.
* Added a **Cycle** column and the ability to sort by cycle to the **Manage internship** page for sitewide administrators.
* Updated the behavior of the **View application** link and icon on the student dashboard page.

### Bug fixes

* Fixed an issue so pay grades display in the correct order on the opportunity detail.
* Fixed an issue with the sort by functionality on the applicants table of an internship.  
* Fixed an issue with the search button so it displays in the correct place on the **Search applications** page of a cyclical community.

## Changes made May 26, 2023
### Sitewide

* Performed backend technical work to update how a user can sort applications when apply or withdraw from an internship.

### Communities

* Updated the **Expected graduation date** toggle on the **Community settings** page.

### Internships

* Updated the internship creator and co-owner view of the **Applicants table** to include a new column for **Rank** and ability to sort by ranked.
* Added the cycle name and community name of an internship to the right rail of the **Application** pages.
* Added a community name and cycle name dropdown to the **Rank your recent internships table** on the **student dashboard** page.
* Updated the validation text for the **Expected graduation date** field on the **Step 1 internship application** page.
* Created an approval email that will go to creators and co-owners of cyclical internships when the sitewide or community administrator approves their internship(s).
* Created several downloadable .csv files, including:
  * All students who were selected for an internship in a cyclical community.
  * The data that displays on the **Search applications** page of a cyclical community.
  * All internships created sitewide (for sitewide administrators).

* Updated the tracker banner on the **Internship creation** and **Internship application** pages to navigate between the pages.
* Added the cycle name to the **Internship creation step 4 review** page and the internship detail page.

### Bug fixes

* Fixed several 508 issues.
* Fixed an issue so when a community administrator clicks a student name on the **Manage users** page, they do not go back to their homepage.
* Updated a typo that read applicant, instead of application.
* Fixed an issue to not display HTML codes in a .csv file.
* Fixed an issue on the **Create an event** page to not display a modal or navigate a user away when they click enter in the text fields.

## Changes made May 12, 2023
### Sitewide

* Updated a backend table to keep a record of when a creator clicks the **Confirm applicant selection** button for auditing purposes.
* Added the ability for sitewide administrators to view and use the action buttons on the applicant tables of an internship and on the **Application view** page of an applicant.
* Added an **information icon (i)** with alt-text on the **Demographics** page to describe specific selections.

### Communities

* Updated the **Search applicants table** for student cyclical communities, to include a new column called **Application submitted date** and added the ability to sort by this date.
* Updated the **Manage users table** for student communities with the following:
  * Added a column with the login.gov email address of community members.
  * Added a sort by for sorting by the login.gov email address of users in alpha order.
  * Revised the placeholder text of the search bar and enabled searching by login.gov email address.Created an internship ranking toggle for student cyclical communities.

### Internships

* Changed the **Update application** button to **Update draft application** if the user has started an application but not submitted it yet.
* Added functionality to not display the **Update draft application** button when a user has reached the application limit for a cycle.
* Added functionality to not display the **Apply** button when an internship has a status of **Approved**.
* Created an **Auto-fill** option for internship applicants to import data used on a previous internship application.
* Added the following to the **Internship application step 4 review** page:

  * A field to capture the Expected graduation date.
  * A field to capture the Degree or level attained.
  * A checkbox for confirming acknowledgement of the rules and requirements of applying.
  * Text informing the applicant when there are no languages to display and a link to the Add a language page.\

* Added an **internship ranking table** to the **student dashboard** page.
* Added text below the internship ranking table to display the number of applications that a user can submit in the internship cycle.
* Added functionality to display a **Search for open internships** button instead of the **Apply** button when an applicant reaches the application limit. The revised button takes the applicant to the **Internship search** page.
* Updated the internship applicant cap and count to display on the internship detail page when a user is signed out.
* Updated the internship right rail section to display text informing the user when they have reached the application limit for a cycle.
* Added functionality to the **References** section to not display the **Phone** or **Email** headings when that information is not provided.
* Updated the **Participated table** on the **student dashboard** page to add a column for **Application submitted date**.
* Added the **Expected graduation date** and **Degree or level attained** to the **Application view** page.
* Added functionality to automatically move an applicant to the **Rejected table** when they decline an internship offer.
* Updated the **Selected applicants table** and the **Application view** page to display **Applicant has accepted** when an applicant accepts an internship offer.

### Bug fixes

•	Fixed an issue so the cycle selection dropdown will now display when editing an internship.

[April 2023](apr-2023)  
[March 2023](mar-2023)  
[February 2023](feb-2023)  
[January 2023](jan-2023)  
[December 2022](dec-2022)  
[November 2022](nov-2022)  
[October 2022](oct-2022)  
[September 2022](sep-2022)  
[August 2022](aug-2022)  
[July 2022](jul-2022)  
[June 2022](jun-2022)  
[May 2022](may-2022)  
[April 2022](apr-2022)  
[March 2022](mar-2022)  
[February 2022](feb-04-2022)  
[January 21, 2022](jan-21-2022)  
[January 7, 2022](jan-07-2022)  
[December 10, 2021](dec-10-2021)  
[November 26, 2021](nov-26-2021)  
[November 12, 2021](nov-12-2021)  
[October 29, 2021](oct-29-2021)  
[October 15, 2021](oct-15-2021)  
[October 1, 2021](oct-01-2021)  
[September 17, 2021](sep-17-2021)   
[September 3, 2021](sep-03-2021)  
[August 20, 2021](aug-20-2021)  
[August 6, 2021](aug-06-2021)  
[July 23, 2021](jul-23-2021)  
[July 9, 2021](jul-09-2021)  
[June 25, 2021](jun-25-2021)  
[June 11, 2021](jun-11-2021)  
[May 28, 2021](may-28-2021)  
[May 14, 2021](may-14-2021)  
[Aoril 30, 2021](apr-30-2021)  
[April 19, 2021](apr-19-2021)  
[March 19, 2021](mar-19-2021)  
[February 5, 2021](feb-05-2021)  
[January 22, 2021](jan-22-2021)  
[December 11, 2020](dec-11-2020)  
[October 30, 2020](oct-30-2020)  
[October 16, 2020](oct-16-2020)  
[October 2, 2020](oct-02-2020)  
[September 18, 2020](sep-18-2020)  
[September 4, 2020](sep-04-2020)  
[August 21, 2020](aug-21-2020)  
[August 7, 2020](aug-07-2020)  
[June 12, 2020](jun-12-2020)  
[May 29, 2020](may-29-2020)  
[May 15, 2020](may-15-2020)  
[May 1, 2020](may-01-2020)  
[April 17, 2020](apr-17-2020)  
[March 31, 2020](mar-31-2020)  
[March 23, 2020](mar-23-2020)  
[March 6, 2020](mar-06-2020)  
[February 21, 2020](feb-21-2020)  
[February 7, 2020](feb-07-2020/)  
[January 27, 2020](jan-27-2020/)  
[January 13, 2020](jan-13-2020/)  
[December 30, 2019](dec-30-2019/)  
[December 2, 2019](dec-02-2019/)  
[November 4, 2019](nov-04-2019/)  
[October 21, 2019](oct-21-2019/)  
[October 7, 2019](oct-07-2019/)  
[July 15, 2019](jul-15-2019/)  
[June 19, 2019](june-19-2019/)  
[January 11, 2019](jan-11-2019/)  
[November 16, 2018](nov-16-2018/)  
[June 29, 2018](june-29-2018/)  
[May 18, 2018](may-18-2018/)  
[March 9, 2018](mar-09-2018/)
