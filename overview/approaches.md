# Implementation Approaches

<!--We would like to get a better understanding of your organization’s capabilities and expertise when the time is right to migrate our partner database to a new solution. Please provide a case study of your work in the Partner Admin space, including screenshots, if available. Also review the following and let us know which approach your implementation would involve.-->

Data Migration and Form Development
  
ExploreGeorgia.org currently uses a proprietary Laravel app hosted at Partner.ExploreGeorgia.org to provide a “partner extranet,” allowing our tourism destination partners to update their business listings, events and images through an admin site. These updates are displayed in our Drupal frontend via an API. We would ideally like to allow partners to start from the front-end where the listings reside when making an update.
 
What steps would you implement to move us forward from our existing set-up? You may start with a series of steps below (Turnkey, 100% Drupal, or Hybrid) and modify as you see fit, or propose another approach. Important considerations for us are: site performance speeds less than 2 seconds (like cnn.com), ease of use, security, backups, future flexibility for updates, and the ability to migrate code and data at any time during the contract. Include any additional processes you would use for UX/UI, calendars, maps and analytics.
  
-----------------------------------------
 
#### 1. Turnkey - Implemented using Offeror’s existing forms and existing data architecture

a. Activate a new instance of partner listing database and turnkey site for preview.
b. Update existing partner tool to include Tourism and CameraReady specs.
c. Migrate data from MySQL into existing partner admin database structure.
d. Modify Drupal pages to pull from new APIs or pull into another frontend.
  
------------------------------------------
 
#### 2. 100% Drupal - Updating existing Drupal site to contain both forms and partner data
 
a. Create data structure in Drupal matching Tourism and CameraReady specs.
b. Create Partner Admin forms in Drupal matching specs.
c. Import listing and event data from MySQL into Drupal database. 
d. Update pages in Drupal to pull listings and events from inside Drupal.
  
-----------------------------------------
 
#### 3. Hybrid - Retaining existing database, but replacing Laravel tool with a new form process
 
a. Install existing MySQL database on a new machine.
b. Create new form process and partner login that interacts with existing data structure.
c. Activate APIs to pull listings and events into existing Drupal pages or new CMS.
d. Reinstall a fresh copy of data during migration from Laravel to new form process.
