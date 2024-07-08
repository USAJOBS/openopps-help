---
layout: default
redirect_from: /what-is-new/
permalink: release-notes/
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

<<<<<<< HEAD
## Changes made July 5th, 2024
### Opportunities
* Right rail redesign
  * Right Rail Re-design (All right rail changes are behind a toggle and will display when complete.)
  * Updated the right rail status section when specific community tasks are required for Detail and Lateral opportunities.
  * Added a highlight function to the applicant row of the applicants' table when an applicant is checked.
  * Created a modal to be displayed when an opportunity has an apply-by date in the past and a user attempts to publish.
* Updated the "Read more" text button behavior on the application view page.
### Internships
 * Created logic that will move students to the rejected table if confirmed after the review end date when no response is provided.
### Bugs
* Fixed 404 errors around the /api/auth/logout endpoint.
* Fixed an issue with displaying inactive communities in the Networking page community drop-down.
* Fixed an issue where students are not given 7 days to respond to an internship offer when an internship is in progress status.
### Technical
*	Removed Cloud.gov specific code.
*	Researched Redis Cache and how it’s being used in Open Opportunities.


## Changes made June 21st, 2024
=======
## Chanages made June 21st, 2024
>>>>>>> parent of d54598b (Added 20.4 Release Notes (#219))
### Communities 
* Created a function to remove users from federal communities when they change their profile to student.
### Opportunities 
* Created a success snack bar to be displayed to Sitewide admins & opportunity creators when an opportunity is canceled.
* Created a backend data point to store the date the action when a user is marked task complete.
* Updated the application view page to display text "Unselect" in the right rail section when an applicant is in the participants table for detail & lateral opportunities.
* Updated the profile page to: 
  *	display the "Mark complete" button in the right rail section when an applicant is in the participants table.
  *	display text "Unselect" in the right rail section when an applicant is in the participants table.
*	Created a process to set the selected value to null for applicants in applicants table when opportunity is moved to in progress.
### Internships 
*	Created an automated process to move "Submitted" internships to the "Canceled" status when not approved while having an application submission date in the past.
*	Created email notification to Internship creators and co-owners when cyclical internship are moved to the "Canceled" status if not approved while the application submission date is in the past.
### Bugs
* Fixed an issue with secondary community dropdowns not clearing out when the "Remove all filters" is selected.
* Fixed an issue where applicants would show in duplicate when the "limit who can apply to opportunities" toggle is on for community.
* Fixed an issue with transcript information not copying when duplicating an internship application.
* Fixed an issue where resumes were not showing for detailed opportunity applicants and student profiles.
* Fixed an issue where interns selected while an internship was in progress did not have 7 days to accept or decline their internship.



## Changes made June 7th, 2024
### Communities
*	Created a function to restrict access to community profile page URL for users with community profile page toggle set to "Off".
*	Moved email signature block from community configuration to community communication drawer.
*	Moved the "Certificate of completion" toggle and elements to the Community communication drawer.
### Opportunities
* Updated error messages related to "Apply by date" on step 1 create page.
* Removed the "Relevance" option from the "Sort by" dropdown list on the opportunities search page.
* Created a "View application" link on the right rail of the profile page.
* Removed the help link and icon above the progress bar on the right rail of the opportunity detail page.
* Updated "Cancel this opportunity" modal text.
* Created a success snack bar when user leaves a community to acknowledgment of successful action taken.
### Internships
*	Created a backend elastic search that moves students to the available students page when the cycle end date is met.
*	Created email notification to creators and co-owners when an internship moves from "Open" to "Reviewing applicants" status.
*	Updated the text color and removed bookmark icon for applicants moved to rejected table with no internship offer.
*	Created an autofill function to the agency dropdown on the step 1 internship creation page based on user’s profile.
*	Updated the sub-agency or office field to be required when a user selects "Department of State" on the internship step 1 creation page. 
*	Updated text on the cancel internship modal.
*	Created function to hide certificate of completion if a student has been removed from an internship that has status of "Completed".
*	Created function for community managers to duplicate an internship created in their community.
*	Updated text in the informative drawer displayed above the "Selected applicants" table.
*	Updated "Removed Applicants" table title to sentence case.
*	Updated "Student accepted another internship" email with associated internship title.
*	Created a function to automatically delete draft internships after 1 year of being in a draft status.
*	Updated the Internship dashboard to include commas to numbers that displays over 3 digits.
*	Created an "Apply by date in the past" banner to prevent admins from publishing an internship that has an apply by date in the past.
*	Created validation function to prevent internship creators from duplicating internship title within the same cycle.
*	Updated error messages related to "Apply by date" on step 1 create page.
*	Removed "Relevance" option from the "Sort by" dropdown list on the internship search page.
*	Added a "Cycle" column to the created table on the user’s dashboard page.
### Bugs
* Fixed an issue where cycle validation message was not displayed when there are no active cycles.
***






## Changes made May 24th, 2024
### Communities 
* Updated the following reports with new columns: 
  * "Community_internships_[cycle name]" .csv download with "creator_id and  "co_owner" columns.
  * "Search applications" page .csv download with "creator_id" and "co_owner_id" columns.
  * "Student_community_users" .csv download with “user_id column".
  * "Not_selected_applicants" .csv download with " "Student_profile_id" and "Removed_reason" columns.
* Updated the community_internships_VSFS [cycle] .csv “Location” column to include overseas location and display as virtual.
* Created a student cyclical non-member .csv report to account for users that are not members of the VSFS community but have created, co-owned, or applied to an internship within the VSFS community.
* Created a "Non-member" section on the student community dashboard to display non-member metrics.
* Created a "Non-member (.csv)" download link for student cyclical communities. 
### Internships
* Updated text color of applicant’s name to gray when they declined or accepted another internship offer.
* Created the following discussion/comment functionality within the internship detail page:
  * A discussion section. 
  * A comment view within the discussion section.
  * The ability to reply to a comment.
  * The ability to edit a comment.
  * The ability for users to delete their own comments and sitewide administrators to delete all comments.
* Created a warning modal that displays when a user attempts to delete a comment.
* Created an eamil notification that is sent to creators and co-owners of an internship when a comment is posted.
### Bugs
* Fixed an issue where users were unable to update an internship with no active cycles to advance past step 1 of the create/edit page.
* Fixed an issue where the validation error line for the cycle field is not displayed when the field is left blank and user attempts to advance past step 1 of create internship page.
* Fixed an issue where an error occured when a discussion is posted in a community.
***

## Changes made May 10th, 2024
### Technical

* Removed duplicate internship applications from a backend data table.

### Internships

* Created an informative banner to notify internship owners and co-owners that a student did not apply to an internship when selecting a student via the available students page. 
* Added an "Agreement form" column to the following locations:
  * The student dashboard page.
  * The created table of the federal and and contract users dashboard page. 
* Created an agreement form download link in the selected applicants table.
* Created an agreement form download modal for selecting an agreement form by internship participant.
* Created an agreement form page for viewing and downloading the internship agreement form.
* Upated the view link and icon in the tables of the internship detail page.
* Updated the "Removed intern from this internship" section to display for community administrators.

### Sitewide
* Updated the "Budget and Performance" footer link to "Reports and publications".
* Updated the "Privacy policy" footer link to display in a smaller font size.
* Updated the "Terms and conditions" footer link to display in a smaller font size.

### Bugs
* Fixed an issue where users were able to access the community profile page of a community when the profile page was toggled "Off" on the community settings page.
* Fixed an issue where the internship completion certificate was not displayed correctly. 
  

 


[January 2024](jan-2024)  
[December 2023](dec-2023)  
[November 2023](nov-2023)  
[October 2023](oct-2023)  
[September 2023](sep-2023)  
[August 2023](aug-2023)  
[July 2023](jul-2023)  
[June 2023](jun-2023)  
[May 2023](may-2023)  
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
