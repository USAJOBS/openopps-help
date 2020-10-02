---
permalink: release-notes/
layout: default
section: release-notes
category: release-notes
title: What's new with Open Opportunities
---

## Changes made October 2, 2020
### Site-wide enhancements

* Added a **Community** link in the top navigation.
* Added profile pages for each community.
* Added markdown to the community manager field in the **Community attributes** page.
* Added a toggle for custom survey links to the community attributes page
* Made the following changes to the **Create opportunity** form:
  * Changed the field label and help text from Series to **Occupational series**.
  * Added placeholder text in the date fields.
  * Updated error messaging for start and end date fields.
* Added a new toggle so administrators can display or not display a community on the **Communities** page.
* Removed **Internships** link from the navigation.
* Made the following changes to the stories and testimonials section:
  * Set image size to 300x300.
  * Added photos to the See what others are saying about Open Opportunities section.
  * Split name into two fields on the testimonials section of community attributes.
  * Changed the link below a testimonial to only display first name.
  * Added featured stories to the main search page.
* Added the ability to invite someone to apply to an opportunity.
* Updated default text on the opportunity detail when no applicants have applied.
* Updated how you select a community during the opportunity creation process.
* Added ability for users to search for members by community.
* Added a field for adding related skills and series to a community.
* Moved **How often do you need this time?** field under **How many hours do you need?** on the **Create opportunity** form.
* Added ability to run reports on applicant statistics.
* Added all new fields to the opportunity csv file.
* Added custom survey links to the complete emails.
* Listed community managers on the community profile page.
* Added an index page listing all communities.
* Added help content for the following:
  * What’s the difference between an in person and virtual opportunity.
  * How to select applicants.
* Updated the modal display when a user applies for a NOAA opportunity.
* Added default help text to the invite to opportunity search box.
* Added the invited to apply section to the signed in dashboard.

### Changes to support the NOAA community

* Updated the NOAA community to include **Line office and Program office** fields:
  * Added ability to search by these fields.
  * Added these fields to the **Manage User** page.
  * Added a banner encouraging users to add these fields to their profile.
  * Added a toggle to require applicants and creators to have a Line office and Program office in their profile.
  * Added warning message for applicants and creators when missing Line office and Program office from their profile

### Bug Fixes

* Fixed issue so users don’t have to select a new image (if there is an existing image) when editing a testimonial.
* Fixed image rendering issue for stories on mobile.
* Fixed punctuation appearing twice in user stories.

## Changes made September 18, 2020

### Site-wide enhancements

- Launched a new feature that lets opportunity creators invite people to an opportunity. The new feature includes:
  - A modal that displays when a user is invited to an opportunity.
  - A success banner that displays when a user is successfully invited to an opportunity.
- Made a few changes to the **Our customers’ stories** section, including:
  - Increased the height of the banner on the stories page.
  - Adjusted the font size of the text in the See what people are saying about us box.
  - Added ability to include **Agency** name in stories.
  - Adjusted the size of the story card and image on the stories preview page.
- Updated the opportunity page to collapse the **Not-selected** section after an opportunity creator clicks **Next steps**.
- Changed the label **Cancel your application** to **Withdraw your application**.

### Changes to support the NOAA community

- Added **Estimated start date** and **Estimated completion date** fields to the **Create opportunity** form.
- Added **Line office** and **Program** fields (if included) to the blue box on the opportunity detail page.
- Changed the **Grade** field label to **Grade/Band** on the **Create opportunity** form.
- Added ability to include multiple **Grade/Bands** and updated how they’re displayed on detail and lateral opportunities.
- Added ability to search detail opportunities by **Grade** range.
- Updated opportunity preview page and duplicate feature to include all new fields.
- Added a toggle to the **Manage community** page so users can turn “optional fields” on or off to display on the **Create opportunity** form.
- Added a toggle to **Community** administration page to specify office naming conventions.
- Added an **Apply confirmation modal** and updated the text for detail and lateral opportunities.
- Added help link for Step 2 on the **Create opportunity** page.
- Updated permissions so that only site-wide administrators can add or edit the following fields on the community attribute table:
  - Community type
  - Target audience
  - Duration
  - Agency
- Added **Community attributes** section to display information on the **Community profile** page.
- Added **Community marketing** content section to the **Administration** dashboard.

### Bug fixes

- Fixed the results page so it’s no longer blank when a user searches for a name on the Manage users page.
- Fixed the preview display of **Estimated start** or **Estimated completion date**.

## Changes made September 4, 2020

### Site-wide enhancements

#### Changes to support the NOAA community

- Added a community **Line Office Manager** toggle within the **Manage Community** feature
- Created an approval email that goes to the **Line Office Manager** when a new opportunity is posted.
- Added a message to community members to include a line office and program in their profile.

#### Changes to the Create Opportunity form

- Changed **Ongoing** to **Recurring** on both **Create opportunity** and **Search**.
- Removed the text **"Requires up to 20% of a participants…"** if the creator selects **Recurring**.
- Removed the text **"Allow virtual participation"**.
- Added a **Negotiable** option to the **Where** section.
- Removed sample **Estimated completion date**.
- Added new field for **Host office will pay for travel expenses?**
- Added new **Line office** dropdown.
- Added new **Program office** dropdown.

#### Changes to opportunity overview page:

- Added a link so the opportunity creator can email all non-selected applicants.
- Moved the warning text above the **Next step** button.
- Removed the **Cancel** link (next to Edit).
- Updated the location text to say **“Virtual and/or [location]”** when both are selected on the create opportunity form.
- Updated the blue box to display a new **Travel Expenses paid** section.

#### Other changes

- Added markup to the **Stories** section.
- Added co-owners to the emails that go to opportunity creators.
- Updated the text in the **Do you want to participate?** modal.
- Added text-based versions of all emails.
- Added the number of results beside each filter on the **Search** page.
- Changed the label from **Total assigned** to **Total selected** in the interactions section of the **Administrator** dashboard.
- Added ability for site-wide admins to change the community on any opportunity.
- Added **Line office and Program** to the **Manage opportunities** dashboard.

### Bug Fixes

We fixed the following issues:

- Slow response time on **Manage Opportunities** for administrators.
- 508 issues on the opportunity card and home page.
- Renew column not displaying for co-owners (for opportunities with 91+ days of inactivity).
- Overflowing content in the **What happens next** box on the opportunity page
- Incorrect sizing of the detail icon on the **Create an opportunity** form.
- Long opportunity title overlapping the Save link on the opportunity results page.
- Displaying incorrect selectee count and name information in opportunities export from a certain community.
- Slow page load when navigating to manage opportunities within a certain community.

<<<<<<< HEAD
## Changes made August 21, 2020

### Site-wide enhancements

- Added the ability to display user stories and testimonials on the site.
- Added ability for a user to save another user’s profile to a **Saved People** page.
- Updated metrics for sitewide admins to include the number of laterals.
- Updated the saved search feature to require unique name.
- Added ability to save an opportunity from the search results page.
- Added help content for saved searches.
- Updated the applicant section on an opportunity so it expands when **Continue accepting applications** is toggled on.
- Updated the location field on the **Create opportunity** page to use autocomplete.
- Increased the character limit in the community description field.
- Added markdown to the title and subtitle fields on the community administration page.
- Made several changes to support the **NOAA community**. Added the following:
  - A **Line Office and Program** section to the Manage Community page.
  - The ability to add, edit and delete an existing **Line Office or Program**.
  - A **Community LOM** column to the **Manage** users section.
  - A **Line Office and Program** section to the profile for NOAA community members.
  - The Line Office and Program field to the user csv.

### Bug Fixes

- Fixed issue so that the saved search message displays when an additional filter is added to a search.
- Fixed issue to include a community image in the email for a new opportunity.

=======
[August 21, 2020](aug-21-2020)  
>>>>>>> 382825a6ff40a7e384f1d4b7cf9ecdc800a6db38
[August 7, 2020](aug-07-2020)  
[July 24, 2020](jul-24-2020)  
[July 10, 2020](jul-10-2020)  
[June 26, 2020](jun-26-2020)  
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
