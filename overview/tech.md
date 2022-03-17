# Technical Capabilities

Partner Tool implementations may use a combination of modular components, turnkey SaaS applications, and customizations within a CMS.

Here are some considerations for the transition from the Miles Laravel backend to a new Parther Admin interface.  

### Maintenance of Drupal Frontend
Identify Offeror ability and willingness to use the API provided by the existing Laravel system to update the Drupal frontend of our Tourism website prior to when we discontinue the Laravel backend to modify listings, gallery and event layouts. 

### Replace and Upgrade Backend
Detail your proposed solution to replace and upgrade the current partner admin tool within 12-months of the project start including the “Nice to Have” addons listed above and extras beyond the fields listed below in the Partner Tool Overview.  

See [Partner Tool Overview](#overview) below for fields and categories

1.6.5.	The Drupal frontend listings are currently pulled from a MySQL database, which may optionally be carried forward without the Laravel admin interface. Offeror does not need to reproduce the look or layout when reproducing the functionality of the frontend. Will Offeror’s solution reuse portions of ExploreGeorgia’s existing Drupal display process with the new partner admin tools? Y/N

1.6.5.1.	If not, describe the new frontend display process proposed (specific Drupal plugins, other CMS plugins, and/or code component libraries).

1.6.6.	Offerer must provide API documentation as a document or link. The link may be API endpoint documentation provided by a tool like Swagger, or an attached PDF.

1.6.6.1.	CameraReady data is currently pulled daily from the Laravel json API. The data pulled can be viewed in Exhibit 3: CameraReadyListings.csv.  The column names do NOT need to remain the same. Can the API be used to pull similar .json or .csv files  containing location listings and image links for sites developed in-house, including the CameraReady.Georgia.org site?  Y/N

1.6.7.	If your solution includes code for site modules (calendars, maps, social login, D3 charts, etc.) that can be reused with other GDEcD directories, please provide a general list of code types (NodeJS, JavaScript, jQuery, React NextJS, Prisma, etc.). 

1.6.8.	What is the estimated times to prepare migration scripts and conduct the data migration from the Laravel system’s MySQL database to your solution’s data structure? Do not include the time adding new fields not already in Laravel’s MYSQL database or time creating/updating web forms.  Since we do not have the database structure available yet, you can also provide a minimum and maximum time. Since some Offerors might retain the existing MySQL table structure, they may indicate 0 hours for the migration time.
