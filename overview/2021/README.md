
# Partner Tool

Overview of Fields and Functionality

To be consistant with common web terminology, "My Account" refers to an individual.  
Parter "Organizations" have Individusals, Locations and Events.  
Roles set at the Organzation level apply to Locations and Events.  
Roles may also be set directly for Locations and Events.  


## My Account

Name (First and Last)  
Title
Email  

**Sections**
My Organizations (and Roles) - Example: Georgia State Parks
My Locations (and Roles) - Example: Individual Parks
My Events (and Roles)
Sign out

## Roles

A list of individuals for each organization, location and event.

**Sortable columns**
Name (First and Last)  
Email  
Role  

**Functionality**
Row menu: User Details, Remove User  
Add an existing user [As an Editor] [As an Owner]  
Add new user - Not a link on current page, user must add themselves.  

**Current issue**  
Clicking email goes to account detail, row menu needed.  

## User Details

Name
Title
Email

**Location Roles** (list)
Location
Role (Member, Editor, Owner)

## Locations and Events

**Fields**
Type (Location, Event, Deal)
Name - with link to detail
Presenter (Organization or other group) - with link to detail
Category Tags 
ID (under the name rather than columns)
Edited By  
Date Edited  

**Functionality**
Clicking tabs sorts columns.
Search field which filters by Location, Account, Tags
Send filters to the URL (page, sort, order)

**Nice to Have**  
Show the most recently edited items first.  
Include: Edited by [name] on [date] - With the editor's name clickable.  
Include filters from frontend to filter by region, city, category, etc.  
Make the category tags clickable to filter by category.  
Add a small calendar icon to the right of the search field to open a date range filter.  
Include a thumbnail image to the left of each row.  
Omit the Type and ID columns to conserve space. Include these after the name.  

<span class="localX">

**Miles Interface** (Current)  

<img src="img/miles/list.png" style="max-width:822px">

</span>

## Approval Queue

**Columns**
Listing/Event
Presenter (Organization)
Address
Changed
Changed By

**Functionality**
Row menu: Review
Search
Sort columns

**Nice to have**
Data search

<span class="localX">

**Miles Interface** (Current)  

<img src="img/miles/approval-queue.png" style="max-width:1477px">  

</span>


## Brochure Approval Queue

**Miles Interface** (Current)  

<img src="img/miles/brochure-approval-queue.png" style="max-width:1070px">  

## Brochure Approval Detail

**Nice to Have**  
Hide extra cloudinary data under a "More" link.  
Avoid button overlap of right side.  
If correct, rename radio button to: "Send notification email when listing is changed."  
Rename "User Emails" to "Send notification to:"  
The text says "you changed your listing for ABC", but the emails can go to other individuals.  

<span class="localX">

**Miles Interface** (Current) 

<img src="img/miles/brochure-approval-detail.png" style="max-width:876px">  

</span>


## Calendar


**Nice to Have**  
Integration with external partner calendars.  
Display calendar layout in frontend. Try [elfsight calendar widgets](https://elfsight.com/event-calendar-widget/)  


## Performance

**Nice to Have**  
Include additional traffic from cached pages by including charts from our cloudflare.com Content Delivery Network (CDN).  
Make Referral boxes clickable to explore which booking websites are making referrals.  
Add info below charts to explain Website Grid and Website Profile.  
If correct, include: "Directions" indicates the number of requests to view directions to your location from within our website.  
<span class="localX">

**Miles Interface** (Current) 

<img src="img/miles/performance-partner-referrals.png" style="max-width:876px">  

</span>


**Nice to Have**  
Provide a link to website traffic for the entire website when logged in as a staff member.  

<span class="localX">

**Miles Interface** (Current) 

<img src="img/miles/performance-web-traffic.png" style="max-width:876px">  

</span>


**Additional Reporting for Partners**  
What additional Economic Development data sources would we like to cross-relate for partners?  
Examples: Page visitor travel interests, Impacts on local industries and jobs, Positive environmental impacts  


<!--
List of partner locations shows pending changes for admin approval 

Events near partner locations 

Deals for and near partner locations 

Photos for partner locations. Galleries for communities. 

Brochures and documents for partner locations 

Frontend maps for partner locations 

Partner calendar and event detail page 

Places to stay by type, region, city, category 
-->
