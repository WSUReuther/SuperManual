# Arrangement and Description: General

## Opening Accessions
Post-accessioning, if collections cannot be immediately processed at one of the three [processing levels](#processing-levels), they may instead be minimally described at the collection level, added to the processing queue, and opened. This involves the following:

1. **Collection Archivist** opens the collection within 90 days.
   
    1. Create an [ArchivesSpace resource record](02_03_archivesspace.md) using collection-level description (copy and paste any relevant info from [ArchivesSpace accession record](../01_accessioning.md#archivesspace-accession-records)).

    !!! note
        - *If the collection is an addition*, the existing ArchivesSpace resource record will be edited instead, to incorporate the new part. ArchivesSpace will amalgamate a new inventory onto the end of the current inventory list. 
        - *If the collection is an accrual*, only an accrual note (extent, date) should be placed in the existing ArchivesSpace resource record. Restricted accruals may be published at the discretion of the collection archivist.

    2. If an inventory exists in electronic format, it can be copied and pasted into the [EAD template](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/FA_EADtemplate_InventoryOnly.xml), [imported into ArchivesSpace](02_03_archivesspace.md#import-ead-inventory-into-archivesspace) as a resource record, and merged.
    3. If no inventory exists, the archivist determines whether the collection warrants series descriptions and/or box inventory and adds these to the ArchivesSpace resource record. List individual boxes separately.[^1]  
    4. All ArchivesSpace exported PDFs are placed in a folder on server as the master preservation copy.
    5. **Reuther Coordinator** is notified.

[^1]: This is necessary for forthcoming ArchivesSpace physical space management.

2. For analog-only / hybrid collections:
    1. **Reuther Coordinator** assigns stacks location.
    2. **Collection Archivist** prepares box labels and labels boxes. Any material being physically transferred to AV* is designated as such and an AV archivist is notified.
    3. **Reuther Coordinator** moves collection to its permanent location and delivers any material to AV.
3. For digital collections: Stabilization (performed by **Field/Collection Archivist** during accessioning) and [AIP creation](02_02_special-formats.md#all-digital-materials) are sufficient, there is no need to pair digital objects to the ArchivesSpace resource record inventory (that is full processing- if the collection is fully processed later, the AIP can be reingested of necessary). 
4. **Collection Archivist** makes notes regarding actions (discards, transfers, etc.) in the [ArchivesSpace resource record](02_03_archivesspace.md) and specifies if the collection (or parts thereof) needs processing, to what level it should be processed, and what priority status should be assigned. Assuming further processing is needed, a [Processing Queue](02_03_archivesspace.md#processing-queue) event is created to indicate the collection is part of the processing queue rather than fully processed and completed.

If no further processing is determined, further action is not required beyond the archivist creating a [Processed](02_03_archivesspace.md#processed) event. The collection is considered complete until such time as reappraisal is deemed necessary.

!!! info "AV Transfers"
    ***AV transfers** should adhere to processing procedures (i.e., material too large for stacks shelves and machine-dependent media – see [Audiovisual Formats](02_02_special-formats.md#audiovisual) for specifics).

## Processing Levels
*Collections or individual series, are processed according to one of three levels:*

| Level | Description |
| --- | --- |
| Level I | folder inventory; full arrangement & description |
| Level II | box or folder inventory; series level arrangement & minimal description |
| Level III | box or folder inventory; collection level arrangement & minimal description |

On average, it takes 1-2 hours per box to open a Level II or III collection and 4 hours per box for a Level I collection.

Regardless of level, processing should generally follow the steps outlined in the sections below.

## Preliminaries
1.	Consult the Stacks & Case Files located in 3N/3S (if you remove a folder, fill out an OUT card) for provenance and supplementary information about a collection.
    1. Check for any donor restrictions on access and/or use of the collection.
    2. Check the donor agreement (if one exists) or correspondence to determine how duplicates, non-historical materials, and non-manuscript materials (e.g., AV, library) are to be disposed.
    3. Note any existing inventory.
    4. Make notes of any pertinent information that can be used in the finding aid (i.e., accession date).
2.	Consult ArchivesSpace for additional information (accession record, agent(s), etc.) and updated records: 
    1. Revise (or create) an [ArchivesSpace resource record](02_03_archivesspace.md), and begin recording information in the fields, including the [Collection Management](02_03_archivesspace.md#collection-management) subrecord (Processing Priority, Processing Plan, Processor, and Processing hrs/unit Estimate), Note that not all fields can be filled out until processing is completed, and some will change (e.g, dates, extent).
    2. Update the associated event(s):
       1. From the resource record, select the Related Accession record (if there are multiple Related Accession records, select the first one).
       2. In the Related Accession Record, select Events from the side nav.
       3. Select Edit in the [Processing New](02_03_archivesspace.md#processing-new) event 
       4. In the Processing New event’s edit screen, change event type to [Processing In Progress](02_03_archivesspace.md#processing-in-progress), and link the related resource record.
       5. If there are multiple accessions being processed:
          1. Link all of these Related Accessions to this single Processing In Progress event record.
          2. Delete the individual Processing New event records linked to each Related Accession.[^2]

[^2]: Processing New events indicate that accessions are not processed and part of the backlog. Therefore, to maintain an accurate backlog and processing statistics, these events must be deleted.

3.	Read pertinent literature for information about the donor, creator or subject of the collection. Keep notes for use in the resource record’s History note.
4.	After obtaining location information, pull desired boxes from the stacks area. Enlist a page, if available. Inform the Reuther Coordinator of the number of boxes (and types) you pulled from each shelf locations so the Physical Location spreadsheet can be updated.
5.	Review the collection.
    1. Examine existing inventories to determine original file order and related files in separate locations. If none exists, you may find conducting a brief (i.e., box level) inventory useful. 
    2. Examine, briefly, the collection as a whole.  Become acquainted with the scope of the collection (completeness), years covered, possible topics, present arrangement, and types and sizes of materials.
6.	Determine arrangement plan.
    1. Review any previously processed parts, if any, to the collection or similar collections (e.g. other union offices, if processing union records) to assist in determining arrangement.
    2. Keep in mind extent, research value and donor relations (e.g., the terms and conditions in the donor agreement), in deciding to what level to process the collection (or part/series within the collection).
    3. If there is a previous part with series arrangement, the new part will continue the series numbering where it left off. **(Skip this step for Level III processing)**.
    4. If there is no existing discernable order that can easily be maintained, establish series, if needed, by format, subject matter, creating office, document type, or time period depending on what most logically reflects the history of the creator or most useful to the researcher. **(Skip this step for Level III)**.
    5. If there is no arrangement system, decide what is most logical for the entire collection or series-by-series (e.g. chronological, subject, alphabetical, etc.). **(Skip this step for Level II or Level III)**.
7.	Determine if any materials need to be deaccessioned. (Materials that duplicate holdings, fall outside established collecting scopes, are non-historical, subject to donor agreements and legal restrictions).
    1. Follow the prescribed actions set forth in the donor agreement (i.e., set aside to return materials to donor) from the case file.
    2. If there is no donor agreement, adhere to deaccessioning section of the *Collection Policy*[^3].  Actions include attempting to contact the donor to ask about returning materials, transferring materials to another repository, and destruction.
        1. For non-historical materials that may have monetary value, where you cannot establish contact with the donor, materials may be donated or transferred to another institution. If you are unclear discuss with the director and/or the Collections Team.
        2. Materials that pose a potential threat to staff and researchers should be transferred to Wayne State University’s Department of Public Safety or Office of Risk Management.
    3. Document the deaccession: Create and link a [Deaccession Event](02_03_archivesspace.md#deaccession) to the resource record, explaining how and why the material was deaccessioned. If returning materials to the donor, include [Certificate of Records Return to Donor](https://waynestateprod.sharepoint.com/:w:/r/sites/Libraries/Reuther/Documents/Collections/Collection%20Management/Donor_return_certificate.docx), which documents the material being returned (i.e., type of material and amount), and have both the donor and Reuther Library representative sign. Retain a signed copy in the case file.
    4.  Remove the box(es) from your processing area. Contact the Reuther Coordinator to take the boxes to receiving. If materials will be returned to the donor, or sent to Public Safety/Office of Risk Management contact the appropriate individual(s), and ensure materials arrive safely.

[^3]: SharePoint: Reuther Library > Active Records > Collections > Acquisitions_Accessions >  2018 Final > CollectionPolicy_2019Review.pdf

## Processing
The following guidelines give a comprehensive approach. Depending to what level a collection is being processed, not all of the recommendations are applicable. For Level II & III processing, item level investigation is discouraged and thus many of these steps are unnecessary.

### General Rules
1.	Do not arrange material within the folders.

2.	Work in storage boxes until final refoldering. For the most part, try to avoid reading through the collection more than one time.

3.	If a document requires identification with notations regarding date, place, or author, those notations should be penciled in lightly in the upper right hand corner in brackets to indicate that the archivist made the notation.

### Arrange the Collections
**Determine the processing level:**

1. For Level III: simply leave the collection as it stands, physically arranging only to consolidate folders within a single box. 
2. For Level I or II: Separate the collection into series, if not already determined by creator, separate the collection into 2 or more series. Do not create a collection with only 1 series. Don’t try to work with the entire collection at once.
    1. For Level II, leave each series as it stands, physically arranging only to consolidate folders within a single box. 
    2. For level I, impose (or leave existing) system of arrangement.

#### Discards
The following items should be removed from the collection:	

- Blank paper
- Duplicate copies: retain originals and any duplicates with handwritten notes or different formats.
- Unimportant items such as grocery lists, minor receipts, etc.
- Housekeeping items such as bills and cancelled checks
- Travel, equipment, etc., brochures 
- Routine forms, such as those for travel expenses
- Papers with only doodles, phone numbers with no names, etc.
- Empty folders – set aside those suitable for reuse.
- Envelopes, unless they contain important information
- Magazines unrelated to the subject content of the collection (but tear out any relevant article and retain) 
- Government documents, unless removing them would destroy the integrity of the file/collection
- Illegible materials 
- Summarize discards in the resource record's Collection Management > Processing Plan > Discard section. 

#### Preservation
1.	Remove *rusted* metal fasteners and replace with vinyl paper clips, if necessary to preserve the integrity of the document. 

2.	Discard rubber bands.

3.	Place acid-free (bond) paper between deteriorating items.

4.	Note the box location and type of low-grade paper (e.g., newsprint, telegrams, carbon paper, Thermofax) in the resource record’s Collection Management > Processing Plan > Conservation Description/Location section for future action.
 
5.	Remove binders and report covers. If necessary, remove all old envelopes and all other unnecessary items.  If they contain titles or information not included in the letter or report, trim and retain that portion.

6.	For items with water and/or mold damage[^4],  do the following:
    1. Air-dry small amounts of wet materials. For extensive amounts of wet materials, contact an environmental company to come in and freeze the material to prevent mold growth.
    2. Documents bound together via water damage, should not be physically separated. If separating is deemed necessary given the material’s historical value, find a conservator to do so.
    3. Material with mold:
        1. When dealing with mold, wear protective clothing (gloves, respirators/masks, goggles, disposable aprons or  smocks, etc.)
        2. Isolate the moldy material from the rest of the collection.
        3. Determine if the mold is active. If so, the physical environment where the material was stored must be [evaluated](https://waynestateprod.sharepoint.com/:w:/r/sites/Libraries/Reuther/Documents/Collections/Preservation_Disaster/Manual_Small-Scale_Disaster_Recovery_20150323_DRAFT.doc).   Dispose of the material and record in the Resource record, or if the material is of substantial historical value, place the material in a secure, and dry environment to stop mold growth until mold is inactive.
        4. For material with inactive mold, do one of the following:
            1. If the material is not of substantial historical value, dispose of the material and record in the resource record.
            2. If the material is important enough to remain in the collection, clean.
7.	Flag or list items that are torn, soiled, or need flattening. Follow appropriate preservation measures.

[^4]: This information came from Mary Lynn Ritzenthaler, Preserving Archives & Manuscripts second edition Chicago.2010: 254-256.

#### Physical Foldering
1.	Do not arrange material within the folders.

2.	Divide the contents of folders thicker than one inch. Try to make logical divisions, e.g. dividing by months or years or by chapters.

3.	Where more than one folder has the same heading, indicate multiple folders of the same material.

4.	Replace folders that are in poor condition with new or good-quality used ones of a size appropriate for the collection (i.e., letter or legal size). Turn used folders inside out and write on the blank side of the tab. 

5.	Organize and folder loose material by subject, format, correspondent, or some other logical grouping. 

6.	Remove hanging folders (Pendaflex) and if necessary, folder their contents. If the Pendaflex tab insert accurately describes the material, use it as the folder heading.

7.	Remove and folder material from 3-ring binders, report covers, and envelopes.

8.	Use existing headings if they accurately describe the folder contents. These may be taken directly from any existing inventory listing (may or may not include dates – usually not necessary for Level II or III). Compose appropriate folder headings, where needed, including dates.  Be consistent, specific and concise.

9.	Print legibly in pencil.

10.	When processing is complete and inventory is being created, list box number and then folder number on the upper left corner of the folder tab.  Number folders consecutively within each box: Box 1 might contain folders 1-1 through 1-28; Box 5 might contain folders 5-1 through 5-8.

11.	If you have unfoldered, bound items, assign them numbers just as you would folders. If possible, lightly pencil the number on the front, or inside cover of the item.

#### Folder Headings
As the description of the materials in each folder of the collection is the key to that collection for the researcher, it is important that the folder headings be as accurate, consistent, complete and concise as possible. DACS standards applied in the creation of collection-level description also apply to folder headings, when devised by the archivist. Note that it is acceptable to use fuller description in the ArchivesSpace inventory, and abbreviate on the physical folders.

These headings should be written legibly in pencil on the folder tabs.

##### Terminology and Abbreviations
1.	Care should be used in selecting words that describe exactly what is in each folder. Library of Congress Subject Headings should be used wherever possible. Try to avoid the use of “miscellaneous” and “etc.”

2.	In general, in the case of names of organizations which are usually abbreviated, such as the UAW, AFL-CIO, etc., it is not necessary to write the name in full, if it is preceded in the guide front matter or a previous folder heading by the name written out in full.  In collections with an unusually large number of abbreviations and acronyms a glossary can be provided at the end of the scope & content (or abstract).

3.	Do not abbreviate the names of people.  An exception can be made in the case of the creator of the papers for specific references in folder headings such as: “WPR Notes” to indicate the notes made by Walter P. Reuther.

4.	For states use Post Office codes, such as MI.

##### Dates
Each folder heading should indicate the dates of materials in the folder if possible (Level II & III collections may be the exceptions).

1.	Write single dates as follows without punctuation: 1945 April 25. Expression of dates should not be given in all numerals. 

2.	Standard abbreviation can be used for months, but it is recommended that they be spelled out in their entirety on the guide.

3.	 Indicate inclusive dates as follows: 1935-1939

4.	If there is a significant gap in chronological sequence of the documents in a folder, use commas to separate the dates or date ranges: 1999, 2005-2010

5.	If bulk dates are needed to clarify folder contents use “, bulk YYYY-YYYY” after the inclusive dates. Do not use parentheses.

6.	If the document is not dated, but you have been able to determine its age, use one of the following statements preceding the estimated date:
    - approximately
    - circa
    - after
    - before
 
7.	If no date can be determined, write “undated.”

##### Punctuation and Format
1.	Do not subdivide a folder heading with a semi-colon unless the secondary information provides added insight into the folder contents. For example, use semicolons to separate the main heading from the subheading, such as:  “Region 3; Correspondence” 

2.	Use commas before the date or when appropriate to separate words, for example: “Carey, James, Secretary-Treasurer, 1955-1968”

3.	Do not use a period at the end of folder headings.
4.	Folder headings may be composed using any existing inventory, provided the heading accurately reflects the folder contents. In Level II or III processing this may or may not include dates. 

5.	When composing entirely new headings, include as much information as possible in the space available. 

6.	The type of material (correspondence, minutes, etc.) and dates should be indicated where appropriate. 

7.	Where more than one folder has the same heading, indicate multiple folders as such: (1 of 2), (2 of 2), etc. 

8.	Box and folder numbers are written on the upper left corner of the tab (or alternatively, the upper extreme right corner of full tab folders). If using an existing heading and there is no room on the tab, write the numbers just below the tab.

##### Examples 
See also [DACS](https://www2.archivists.org/groups/technical-subcommittee-on-describing-archives-a-content-standard-dacs/describing-archives-a-content-standard-dacs-second-) by SAA

- Incorporation; Correspondence and Research, 1950-1951
- Board of Directors; Meetings, 1951 January 13
- Bylaws; Student, approximately 1993
- Policy and Interpretation; Correspondence, 1957-1976, 1984-1986, 1990
- Procedures, undated, 1978-1979
- Conferences; National Convention (1996: Detroit, Mich.), 1994-1996
- Conferences; Upward Mobility Conference for Women Engineers (3rd), 1976
- Correspondences; Carey, Ernestine Gilbreth, 1977-1995
- Serial Number Lists (FY 1978), after 1977 September
- Achievement Award (1965), circa 1965
- The Four Decades of the Society of Women Engineers, 1990
- The Woman Engineer (Precursor to Journal of the Society of Women Engineers), May 1949-Summer 1950
- College Newsletters, 1943-1944, 1951-1957, 1965, 1970-1977, 1982, 1992-1996

#### Boxing
1.	Rebox the collection in new or structurally sound used storage boxes, if necessary. The standard is a Paige box. Collections deemed significant in some way may be boxed in Hollinger manuscript boxes.

2.	If reboxing with used boxes, make sure one box end is free of old labels and writing, that the information on all old labels has been crossed out, and that the folders are facing the new front end of the box. 

3.	Put a sufficient number of folders in a manuscript box so that they fit snugly enough to support each other but can still be removed with ease.  Place folders in boxes according to the arrangement scheme. Do not leave room in a box because it is the end of a series.  Begin the next series in the same box. Use blue “e-flute” spacers to fill any extra space in your last box. 

4.	Contact the Reuther Coordinator to ask for a physical location for the collection. Provide the number and type of boxes.

5.	As the last step in processing, label the front end of each box using the appropriate label template ([ALUA](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_ALUA.doc) or [WSU](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_WSU.doc)). Labels should include accession number, box number (optional: append “of [total box#]” if collection is unlikely to have accrual or addition), collection title (including part #, if applicable), and location. If you are processing an addition or part to an existing collection, your numbering will begin not with Box 1, but where the original collection left off. Do not reformat the labels (unless you need to adjust font size in the title only) or add any other information. If you are labeling a box containing [AV](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_AV_blue.doc), fragile, [closed](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_CLOSED_yellow.doc), and/or [restricted](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_RESTRICTED_pink.doc) materials (restrictions are: [box must remain at reference desk](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_BOXREFDESK_pink.doc) and/or [box must be used at table directly in front of reference desk](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_BOXUSREFDESK_pink.doc)), or materials that [should not be duplicated](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/Processing_Labels_NO DUPLICATION_green.doc), the corresponding color coded label(s) should also be included (contact AV department for fragile labels). Affix labels to boxes using pH neutral adhesive to prevent the labels from falling off over time.

When all folders have been arranged and titled, write a draft of the series descriptions in the ArchivesSpace Resource Record > Notes > Scope and Content **(Skip this step for Level II & III.)** while all the information is still fresh in your mind.

Make note of important subjects or names and biographical or historical information about the creator, as you go through the collection, to be used in the finding aid. 

## Description Workflow
When a collection has been processed (i.e. arranged), the next step is to create a finding aid (i.e., description) so it can be made accessible. To do this, complete the following steps:

1.	Create a DACS compliant description and enter into the collection’s [ArchivesSpace resource record](02_03_archivesspace.md), using the appropriate template text based on the processing level (1, 2, or 3).

2.	[Create an inventory](02_03_archivesspace.md#create-inventory-in-excel) (box/folder list) using the [Excel inventory template](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/FA_Inventories.xlsx), and follow the instructions to create an [inventory-only EAD](02_03_archivesspace.md#turn-text-inventory-into-ead).

3.	[Import](02_03_archivesspace.md#import-ead-inventory-into-archivesspace) the inventory-only EAD into ArchivesSpace. Then merge  the newly created inventory-only resource record into the original ArchivesSpace resource record. A [Component Transfer](02_03_archivesspace.md#component-transfer) event is automatically created by ASpace, recording that the inventory-only resource record successfully merged into the description-only resource record.

4.	Update the [Processing in Progress](02_03_archivesspace.md#processing-in-progress) event to [Processed](02_03_archivesspace.md#processed). If the collection has any restrictions that requires all or a portion of it be closed, add a [Temporarily Closed](02_03_archivesspace.md#temporarily-closed) event. If the collection was only partially processed, add a [Processing Partial](02_03_archivesspace.md#processing-partial) event.

5.	Complete the [Collection Checklist](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Collection Management/Collection_checklist.doc), and place it in the digital case file (Digital_Hold > Central > Collection_Management_Tools > Accessions > CaseFiles), and hard copy case file, if applicable. 

## Finding Aid
1.	Complete collection description based on the Level I, Level II or Level III procedures and template text provided in the ArchivesSpace: Resource Record.

2.	Describe your arrangement scheme and create the [inventory](02_03_archivesspace.md#inventories-for-archivesspace). Number folders and boxes as you go.

3.	Consult the reference file you’ve created from notes taken during the [preliminaries](#preliminaries) and processing, as well as your inventory, to complete the front matter of the finding aid (e.g. title through scope & content). 

4.	For Level I, complete a full History and Scope & Content note. For Levels II & III, these notes may be shortened or summarized in an abstract only.

5.	Edit and revise the drafts of your series descriptions written up while processing **(Skip this step for Level II & III)** within the Resource Record > Notes > Scope and Content.

## Completion
1.	Complete the ArchivesSpace Resource Record [Collection Management Subrecord](02_03_archivesspace.md#collection-management) (Processing Total Extent, Extent Type, Total Processing Hours, Funding Source).

2.	Discarding Sensitive Materials and Materials to remove from collection (duplicates, blank pieces of paper, irrelevant materials, etc.):
    1. Shred Sensitive materials:
        1. Write “SHRED,” the date, and your initials on the box(es) containing material needing to be shredded. Tape box lids shut.
        2. Add the boxes to the Room 19 Shred List.
    2. Contact Reuther Coordinator to remove the boxes from your area. Shred boxes go to room 19. Discard boxes go to Receiving.
    3. Document the discards/shredded materials: Fill out the Resource Record > Collection Management > Processing Plan field > Discard section and indicate the type and amount of material discarded/shredded.
3. Arrange for transfer of any AV or vault materials.
4. Record locations of all material (regardless of physical location in separate departments, e.g., AV and digital materials) in the ArchivesSpace resource record.


