## critical user stories

Searching by keywords, attributes.
- search results page, options on sidebar

Find excerpts to use in presentations, classes.
- search results page, excerpts option

Find out how a previous study was done, viewing stimuli and videos.
- study page, documents tab

Full citation, permanent URL, download, citing.
- study page, citation section

Access statistics: # of views/downloads, most viewed, most cited, etc.
- statistics on study page
- dashboard lists top

Recode/expand coding spreadsheet for existing video.
- participant page, example of this having been done already

Grant access to new lab member, add to study.
- dashboard: shows request, links to...
- user authorization page

## Use cases from conversation with Karen (2013-04-03):
- re-use is key: Investigator wants determine if available data can be used for new study
  - review at study protocol, how was the study performed?
  - find number of participants
  - view video excerpts 
- labs may want to create excerpts for internal use  
  - e.g., clip showing how to put an eye tracker on a baby

## list of wireframes and flow for presentation

### General Questions
- [x]:?: what to use for "User contributions licensed under ???": can we leave this out for now?
- [x]:?: do we need a "logged-in" view of various pages? if so, which ones?: only study needs both views, everything else is either agnostic or logged-in only
- [x]:?: what username to use for logged-in view?: Karen Adolph
- [x]:?: do we still need "study-public-request" wireframe/image?: we might want something like it, "pending investigator authorization", but I think we can leave it out for now.

### Discovery/Browsing

CREATED : Databrary home page (add search box, full color)   
- ala current databrary.org
- search box
- login/register link
- [image: home page](./home-page.png)
- [x]: fix NSF link with grant #


CREATED: Search Initiation Page
- [x] let's drop this if it's a pain to maintain; it doesn't add much
  - image file deleted, bmml file marked as deprecated

UPDATED: Search results page   
- search for "walking" and/or "Adolph"
- refine by: age/race/ethnicity of participant, excerpts available, number of participants (range)
- example results: http://scholar.google.com/scholar?q=adolph+walking
- [x]:ds: could you provide a list of sample data set names, or should I just use paper titles?: if you can copy the google scholar abstract excerpts that's probably sufficient
- [ ]:stretch goal: and maybe add some random details about # of participants, videos, etc. (random numbers 10~50)
- [image: basic search results](./search-basic-results.png)
- [x] reorder left column: Excerpts, Species, Participant Data (which is really conditional on "human")


UPDATED: Study page (Public View)

- Documents tab: Study manual, IRB protocol, Blank consent form, Coding manual   
- [image: study, public view, documents tab active](./study-public-view-documents.png)
- Data tab: Table of participants: participant ID, age at test, # videos, # data files   
- [image: study, public view, data tab active](./study-public-view-data.png)
- [image: study, public view, excerpts tab active](./study-public-view-excerpts.png)
- [x]: citation format, instructions, download in RIS/bibtex/etc.
- [x]: change "Shared on November 2000" to "Shared November 2011"
- [x]: reduce # video file to 1 each participant, data files to 2
- [x]: change to "Download citation in this format: "
- [x] we can drop these and focus on authorized view if these are hard to maintain separately : 
- [x] probably documents/data will be links but since we don't have pages for them don't bother

UPDATED: Study page (Authorized View)

- Documents tab: Study manual, IRB protocol, Blank consent form, Coding manual, Video display
  - [image: study, authorized view, documents tab active](./study-authorized-view-documents.png)
- Data tab: Table of participants: participant ID, age at test, # videos, # data files   
  - [x] remove labels/comments from participant list
  - [x] add comments/tag template on bottom of page (maybe just cut off top)
- [x] Excerpts tag with a couple videos, description, view

- [image: study, authorized view, data tab active](./study-authorized-view-data.png)
- [x] change "# of Files" columns to "Sex" column ("M"/"F") and "Contents" column with "1 session video, 1 coding spreadsheet, 1 data file, ..."
- [image: study, authorized view, excerpts tab active](./study-authorized-view-excerpts.png)

- comment/tagging template
  - [x]:?: sign-in to tag / comment: Yes.
  - [x]:?: comment/tagging granularity? at study level, or data/file level?: For now, separate comments/tags at both levels, but the only need to visible on each page.
  - [x]:jgp: So: the study page, participant page, and video/datafile page each have their own tags and comments, but they don't need to visible from elsewhere; we may want to consolidate later, but we don't have to decide that now.
- [x]:?: does "request access" workflow via e-mail still hold? or should user sign-in first?: Let's require logins
- [x]:?: is "collection details" the correct term?: I think we can use the word "study"; perhaps "study contents"
- [x]:jgp: logged-in view: make filenames "links" for download, and also add "download all documents as zip file" link.
- [x] rename "label" to "tag"
- [x] removed comment "This dataset contains the identities of children and infants, video can be used for research under certain conditions."
- [x] change comment filler text everywhere to "This is a great study/video/data!"



CREATED : Login/Register page

- [image: sign-in](./sign-in.png)
- [image: registration page](./register.png)
- [x]: fields on registration page: "Full Name", "Institution" (search/dropdown/other), "Postal address", "Email", "Phone #", password, continue button is "View User Agreement"



CREATED : Study:Participant page

- age at test/race/ethnicity
- acquisition date
- permissions: "shared on databrary", "excerpts allowed"
- video "Session"
- data file "Summary measures.xls"
- coding spreadsheet "Datavyu"
- download all as zip file
- comment/tagging template
- [x] breadcrumbs added, 
  - [x] do we need breadcrumbs everywhere? if so, spacing will be tight on study page: as is looks fine now
- [x] change "preview" to "view"
- [image: study-participant](./study-participant.png)
  
  
CREATED : Video page (viewer, download link)

- comment/tagging template
- breadcrumbs back to participant, study
- representative still frame
  - [x] please provide different still frame if desired
- [image: study-participant-viewer](./study-participant-viewer.png)


### Contribution

NEEDS UPDATES : Dashboard (post login)

- studies
- search
- user authorization
- [image: investigator dashboard](./investigator-dashboard.png)
- [x]: please provide links to stills. following link above I found two images that might be useful for "Adolph walking" search results.  Also, need stills for dashboard.
- [x] Change "My Databrary" buttons to "Add/Edit studies", "Authorize users" (maybe highlight this somehow to indicate pending requests?), "Edit this page"
- [x] Change "My Activity Feeds" to "Popular on Databrary"


REQUEST INPUT : Blank study page (base on Study page)

- same as study page with blank fields, edit links
  - [x] what is work flow? create study (title, abstract) then add files/participants?
    - if so, then only need title and abstract input fields to create study (and thus assign study id)
	  - potential workflow: 
	    - add study (enter study title and abstract)
		- Databrary assigns study ID
		- Owner visits "manage study" page
		  - "manage study" page is basically authorized study view with the following changes:
		    - no tags / comments
			- Study Contents table with links to add files / edit file metadata / remove files
			- links to add / edit / remove participants
			- links to add / edit / remove study permissions
			- [x]:?: do you need ability to add / edit / remove co-authors?
			- co-authors are managed in study access management
	  - simpler option:
	    - create new study
	    - Databrary assigns study ID, fills title with "New Study"
	    - Owner visits study page, which is "manage study", as above
    - for the purpose of wireframes, we can just use the existing study page or "New Study", "Enter Description Here" with added edit buttons that turn text into editable text fields
	
- Documents tab: "new document" 
- Data tab: "new participant"
- link to access management
- [image: add study](./study-authorized-new.png)
- [x] change "Manage" globally to "Edit"
- study authorized edit is gone


UPDATED: Blank participant page

- same as participant page with blank fields, edit links
- highlight permissions settings: 2 checkboxes
- "add new file" link
  - [x]:?: Is workflow: add participant, then have a "manage participant" view with "add new file" link?
  - just replace everything on current participant page with text fields/drop downs/edit buttons
- [image: add participant](./study-participant-new.png)
- racial categories from NIH: http://grants.nih.gov/grants/guide/notice-files/not-od-01-053.html
- [x] remove permissions from this page (really on files)

CREATED : Upload page

- description
- acquisition date
- [x]: is this on participant page or for all file types? Is this a dialog or a separate page? 
- a separate page, basically like the video page with edit links and an upload/replace file field
- [image: upload page](./study-upload-page.png)
- [x] Move "permissions" to top, change to "Type and permissions" with options: "Public", "De-identified data", "Identified data shared with Databrary", "Identified data shared with Databrary and public excerpts allowed" (selected), "Private"
- [x] remove participant 2 data table
- [x] change "Upload Data" to "Add File"
- [x] move permissions down closer to upload, add acquisition date next to upload (both are logically associated with the uploaded file)

### Access management

UPDATED : Study view: Access management

- expandable tree with columns: "Name" (text/textbox), "Permissions" (dropdown), "Individual only" (checkbox)
- each row color-coded by (greatest inherited) permission
- "All Databrary Users", "View Only", unchecked (green)
  - "NYU", blank, blank (green)
    - "Me", "Owner", checked (purple)
      - "Jane Postdoc", "Member", unchecked (red)
      - "Mary Gradstudent", "Member", checked (red)
      - "Pete Undergrad", blank, blank (green)
  - "PSU", blank, blank (green)
    - "Rick Gilmore", "Share Data", unchecked (yellow)
  - Search box with add button, blank, blank
- Key at bottom with permissions:
  - No Access: cannot see this study (white/none)
  - View Only: can see the study but no data (green)
  - Share Data: can see the entire study and data, unless participant permissions specify otherwise (yellow)
  - Member: can edit and upload data (red)
  - Owner: full access and responsibility for study (purple)
  - Individual only: should only this person be granted access, or everyone in the group?
  - [x]: figure out how to handle tree structure...
- [image: study permissions tree](./study-permissions-management-tree.png)


CREATED : User view : Access management

- expandable tree with columns: "Name" (text/textbox), "Databrary Access", "Granted Permission", "Expiration", "Action"
- two sections:
  - Permissions granted to me:
    - "Databrary", blank
      - "NYU", "2 years", "Investigator", "None", reapply
    - Search box with request button
  - Permissions granted by me:
      - "Joe Labmanager", "1 year", "Affiliate", "Admin", renew/remove
      - "Jane Postdoc", "1 year", "Affiliate", "Contribute", renew/remove
      - "Mary Gradstudent", "8 months", "Affiliate", "Contribute", renew/remove
      - "Pete Undergrad", "2 weeks", "Affiliate", "None", renew/remove
      - "New Gradstudent", "requested", none, none, accept/reject
    - Search box with grant button
- Key to Databrary Access:
  - Investigator: full access to Databrary as an authorized investigator
  - Affiliate: standard browse access to Databrary as an affiliate investigator
- Key to Granted Permissions: As a full Investigator, you may delegate the following permissions and must take responsibility for any granted actions
  - None: standard access to Databrary, but no access to my data
  - Access: view any studies I have access to
  - Contribute: create and edit studies I own
  - Admin: delegate all my permissions to edit and authorize users
- [image: user permissions tree](./user-permissions-management-tree.png)
- [x] change key and make permissions two columns, as above

-------------------------------------------------------------------------------

### Roles:
- Suzanne Q. Researcher: logs in and sees activity
                         navigates through study "Toddler social referencing with ambiguous toy"
						 
- Henry Jones:           investigator sharing data in Suzy Q's dashboard
                         investigator whose studies show up in search results

- Jeffrey T. Investigator: investigator sharing data set "Toddler social referencing with ambiguous toy"
                           investigator managing permissions
						   investigator adding data to study
						   
- Tiberius Smith:          commenter on JT Investigator's data set


------------------------------------------------------------------------------
# presentation
- wireframe dims    :  750 x 731
- wireframe location:  260 x  19

- questions:
-- should we have acquisition date on participant page?
-- should new study flow be for a new study created by Suzy Q?
