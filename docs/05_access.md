# Access

After a collection has been described, the finding aid needs to be made accessible to users via the Reuther’s website and in the Reading Room. To do this, complete the following steps:

1.	[Export the collection’s PDF from ArchivesSpace](#export-resource-record-to-pdf), attach metadata, and convert it to a [PDF/A](#pdf-to-pdfa). Name the PDF/A according to the Reuther’s electronic [file naming convention](02_arrangement/02_02_special-formats.md#naming-conventions-for-born-digital-materials).

2.	Save the PDF/A to the server: Digital_Hold > Reading_Room > Guides_Processed > PDFAs. The PDF/A version of a finding aid is considered a permanent file (no more edits) and the master file. It is the archival version of the finding aid.  Save the inventory Excel file to the server: Digital_Hold > Reading_Room > Guides_Processed > WordFAs.

3.	[Create an abstract](#creating-a-drupal-collection-abstract) for the finding aid on the Reuther’s website (this can be copied from the resource record’s abstract). [Add new terms](#adding-terms-to-the-drupal-taxonomies) to the existing taxonomies, if needed, to tag the abstract (these should be the same agents and subjects you used in ArchivesSpace).

4.	[Attach the PDF/A](#placing-finding-aids-online) finding aid to the abstract.

5.	Email an electronic copy of the finding aid to the Reference Archivist to be printed, bound, [labeled](https://waynestateprod.sharepoint.com/sites/Libraries/Reuther/Documents/Collections/Arrangement_Description/Labels/FA_coverLabels.doc), and placed in the Reading Room.

## Export Resource Record to PDF

Use ArchivesSpace to export the collection’s resource record to a PDF.

1.	On the resource record page, select Export > Print Resource to PDF
2.	In the Resource to Print drop down, type the resource accession number or title.
3.	Do NOT check “Include Unpublished.”
4.	Select the Queue Job button.
5.	When the job is complete, the Log will state, “All done. Please click refresh to view your download link.” Select the Refresh Page button.
6.	Under the Files header, select the Download PDF link.
7.	In your browser popup window, select Save File. Rename the file to the collection’s accession number and follow the instructions for transforming it into a PDF/A.

## PDF to PDF/A
The instructions below detail how to take the exported PDF finding aid from ArchivesSpace, add metadata, and turn it into a PDF/A using Adobe Acrobat. 

1.	Open the PDF using Adobe Acrobat.
    1. Select **File > Properties**:
        1.	Type the collection title in the **Title** field (e.g. Jerome P. Cavanagh Papers).
        2.	Type finding aid author’s full name in the **Author** field (e.g. Deborah Rice).
        3.	Type Library of Congress subject terms in the **Subject** field. Separate multiple terms with a semicolon. Do not add more than 10 subject terms. Refer to LoC tags used for the online abstract for guidance on what to include.
        4.	Type in terms found in the document in the **Keywords** field. These could be tags from the Reuther online taxonomy or other important keywords that would help identify this file, not necessarily the collection. Do not add more than 10 keyword terms. Use commas to separate multiple terms.
        5.	Use **Save As** to save the file to your desktop, changing the file name to follow Reuther’s Electronic File Names convention, if needed (e.g. LR002070.pdf).
2.	Add additional metadata about the finding aid.
    1.	Open the PDF with Adobe Acrobat.
    2.	Choose **Properties** under the **File** menu.
    3.	In the **Document Properties** pop-up window, verify the metadata you entered in Step 1, in the following fields in the **Description** tab:
        1.	Title [the official title of the finding aid]
        2.	Author [your name]
        3.	Subject [LoC subject terms]
        4.	Keywords [Reuther taxonomy terms or any terms that may be used to identify this file, not the content in the collection]
    4.	Click on the **Additional Metadata** button.
    5.	In the new pop-up window, choose **IPTC Status** in the left-hand navigation menu.
    6.	Fill in the following fields:
        1.	In the **Job Identifier** field, type “Master record.”
        2.	In the **Source** field, type “Finding aid.”
        3.	In the **Copyright Notice** field, type “Walter P. Reuther Library of Labor and Urban Affairs, Wayne State University”
    7.	Click the **OK** button to exit the window.
    8.	Click the **OK** button to exit the **Document Properties** window.
3.	Convert & save as a PDF/A file.
    1.	Choose **Preflight** under the **Edit** menu.
    2.	In the **Preflight** pop-up window, choose **PDF/A compliance**.
    3.	Choose **Convert to PDF/A-1b (sRGB)**.
    4.	Click the **Analyze and Fix** button at the bottom of the window.    
    5.	In the **Save As** pop-up window, click on the **Save** button. You should get another pop-up window that says you already have a file with that name. Click on the **Replace** button to overwrite the previous PDF.
    6.	A status bar on the bottom of the window will indicate it is converting the document. When the program is done running, close the **Preflight** window. Your document should now display a blue bar at the top that tells you that you are viewing the document in PDF/A mode.
    7.	In the left toolbar click on the **PDF icon**.
    8.	Click on **Verify Conformance**. The **Status** should read, “verification succeeded,” when it is done analyzing the document.
4.	Attach the PDF/A to the corresponding abstract on the Reuther Library Web site. See [Placing Finding Aids Online](#placing-finding-aids-online) for detailed steps.

5.	Save the PDF/A to the server in Reading_Room > Guides_Processed > PDF/As.

## Creating a Drupal Collection Abstract
All collections listed on the Reuther website are done so via a collection abstract. 

1.	Log in to the Reuther Web site
    1. In the left-hand navigation bar, click on **Log In**.
    2. Input your user name and password.

2.	Open a blank abstract form
    1. In the left-hand navigation bar, click on **Create Content**.
    2. Click on **Abstracts**
    3. A new, blank abstract form is opened.
3.	Input relevant data in the fields provided
    1. **Alphasort**: Enter the first six letters in your collection title. If the collection were the records of a union, this would be the union acronym, followed by the first couple letters on the collection name (i.e. department, local, etc.), provided there is room available. Use a space after the acronym (ex. UAW De). 
    2. **Title**: Type in the full title of the collection from your finding aid.
    3. **Reuther Names & Subjects**: 
        1. If you have chosen important names and subjects in your finding aid that are a part of the Reuther taxonomy (i.e. not LoC), enter those here.
        2. Choose the terms/names from the drop-down list. To choose more than one term/name, hold down the apple key and then click on the terms/names. If a term/name is not listed, see instructions on how to add terms/names.
    4.	**LoC Subjects**: 
        1.	Enter the LoC subject terms you used in the important subjects you identified for your finding aid. 
        2.	Choose the subjects from the drop-down list. To choose more than one subject term, hold down the apple key and then click on the terms. If a term is not listed, see instructions on how to add terms.
    5.	**LoC Names**: 
        1.	Enter the LoC names you used in the important names you identified for your finding aid. 
        2.	Choose the names from the drop-down list. To choose more than one name, hold down the apple key and then click on the names. If a name is not listed, see instructions on how to add names.
    6.	**Collection Family**: Choose the term that best describes where the collection fits within the Reuther Library’s holdings. 
        1.	It is possible for manuscript papers to have more than one term. 
        2.	If nothing specific fits, choose the generic terms – labor, urban affairs, or WSU – if not repeating terms chosen in the taxonomies above. If you feel there should be a specific term added, please see the Technical Services Archivist.
    7.	**Size**: Corresponds to the extent element in the EAD tag library
        1.	Enter the extent from your finding aid, in this format – ## linear feet (## SB, ## MB, ## OS). Separate each size with a comma within the parentheses.
        2.	Infrequently collections exist in microform format only, or as both manuscript and microform. Disregard calculating linear feet for collections that are microform only. Instead record the number of reels or microfiche, e.g. 5 reels. When a collection is both, record the manuscript extent first within parentheses, followed by the number of reels outside the parentheses, e.g. (3 SB, 16 MB, 2 OS) 5 reels.
        3.	Calculate extent thus: 1 SB = 1 linear feet, 2 MB = 1 linear feet, 1 OS = .5 – 2 linear feet, ½ MB = .5 linear feet
        4.	Small processed collections may be described using quantity of folders, e.g. 3 folders.
    8.	**Accession Number**: Enter the full alpha-numeric accession number following the numbering convention found in Accession Numbers.
    9.	**Date**: Enter the dates from your finding aid, in this format - YYYY-YYYY, bulk YYYY-YYYY. Do not use parentheses around bulk dates.
    10.	**Abstract Body**: Provide a narrative, no longer than two paragraphs, derived from the History and Scope and Content of the finding aid.
    11.	**Physloc**: Enter the bulk stacks location of the collection.
        1.	Begin with Part number when applicable in this format: Pt 1: (Abbreviate” Part” with capital “P” small “t” space number colon ― separate parts with semi-colon) 
        2.	Most **physical locations** are in four main parts
            1.	Floor followed by **building section**, e.g. 4W
            2.	Hyphen followed by **stack**, e.g. -A
            3.	Hyphen followed by **column**, e.g. -6
            4.	Open parentheses followed by **shelf range** and close parentheses, e.g. (10), (3-4)
            5.	EXAMPLE ― Pt 1: 4W-A-6(3-4); Pt 2: 4W-B-6(10) 
        3.	Other locations include reading room and file cabinets, which utilize a less specific, or more specialized formula.
            1.	File cabinet EXAMPLE ― Raya Dunayevskaya Papers http://www.reuther.wayne.edu/node/2480
            2.	Reading Room EXAMPLE ― Wayne State University Commencement Programs http://www.reuther.wayne.edu/node/7418
        4.	Include locations for ALL of the material in a collection, including those items transferred to AV, Library, or the vault.
    12.	**Userestrict**: Enter any restrictions on use of the collections beyond those that apply for all collections. In other words, do not include the statements common to all collections in the Use statement on your guide. 
4.	Attach the finding aid per [Placing Finding Aids Online](#placing-finding-aids-online).
5.	Publish the abstract to the Web site
    1.	Click *Submit* at the page bottom. The public view of the abstract will be presented along with the message, “Your Abstracts has been created,” immediately below the title of your collection.
    2.	Verify the information you created.
        1.	If you need to change anything, click on the Edit tab below the collection title. Click *Submit* after you have made your changes.

!!! note
    If you do not wish to immediately publish your abstract (e.g., there are unresolved restrictions or the abstract is incomplete & will be finished at a later date) you must deselect the check box next to Published in the Publishing options menu at the bottom of the abstract editing screen before you click on Submit.

## Adding Terms to the Drupal Taxonomies
When describing a collection for maximum accessibility, sometimes it is necessary to use subjects and agents that are not already in the in the Drupal taxonomies. The Reuther Library uses a combination of Library of Congress (LoC) subjects and names and local, Reuther-specific, subjects and names. These terms constitute three taxonomies: LoC Subjects, LoC Names, and Reuther Subjects and Names. 

To add terms to any taxonomy[^1]:

[^1]: 
    Only add terms to a taxonomy if you also added the term in ArchivesSpace as agents (LoC Names or Reuther Names) or subjects (LoC Subjects or Reuther Subjects)..

1.	Log in to the Web site (Click **Log In** on the left-hand navigation bar & enter user name & password).
2.	Click **Administer** in the left-hand navigation bar.
3.	Click on Categories.
4.	Find the name of the taxonomy where you want to add the term. Follow instructions below specific to each taxonomy.

To add terms to the Reuther Subjects and Names taxonomy:

1.	Click on **add terms**.
2.	Type your term in the **Term Name** field. Follow LoC style (i.e. capitalize first word only in multiple word term, etc.)
3.	Add description in the **Description** field, if needed, to clarify why you are adding the term.
4.	Add terms in the **Synonyms** field for associated broader or narrower terms or for see and see also terms (i.e. searches on any term listed in the Synonym field will produce results tagged with the term in the Term Name field).
5.	Click on Submit.
6.	To edit existing terms, click on **list terms** either from the main categories list, or if you are in the taxonomy already, by clicking the **List** tab. Click on **edit** next to the desired term.

To add terms to the LoC Subjects or LoC Names taxonomies:

1.	[Search](http://authorities.loc.gov/) the Library of Congress Authorities to verify that the term/name is LoC.
    1. Type search term in field and select search type (subject or name).
    2. Click on the red Authorized, Refs & Notes; Authorized Heading or References button to the left of your term.
    3. Find the link that says Authority Record and click on it.
    4. Click on the term/name and choose the **Labeled Display** tab at the top (unless you prefer to read the MARC record). This shows you the proper heading and any used for/see from references as well as other headings to search under.
    5. If you have found the term/name that you wish to use, follow the remaining steps.
    6. If you have not found the term/name you wish to use, follow the steps above to add it to the Reuther Subjects and Names taxonomy. Sometimes, you may wish to use both the authorized LoC heading, plus add a more natural language heading in the Reuther taxonomy if you feel the user may search under both headings.
2.	Click on **add terms**.
3.	Type your term in the **Term Name** field.
4.	Add description in the **Description** field, if needed, to clarify why you are adding the term.
5.	Add terms in the **Synonyms** field for associated broader or narrower terms or for see and see also terms (i.e. searches on any term listed in the Synonym field will produce results tagged with the term in the Term Name field).
6.	Click on Submit.
7.	To edit existing terms, click on **list terms** either from the main categories list, or if you are in the taxonomy already, by clicking the **List** tab. Click on **edit** next to the desired term.

## Placing Finding Aids Online
The following instructions explain how to attach a PDF/A to the corresponding abstract on the Reuther Library Web site so it is accessible to users:

1.	In the **Edit** tab of the abstract, click **File Attachments**.
2.	Click the Browse button.
3.	In the pop-up window, find your PDF/A file on your desktop and click the Open button.
4.	Click the Attach button.
5.	Append the file name with “_guide” (e.g. LR000555_guide.pdf).
6.	If this is the initial upload of the guide (i.e. it’s brand new), go on to step 9. 
7.	If you are replacing/updating an existing PDF:  
    1.	Click on **Publishing options**.
    2.	Select the check box next to **Create new revision**.
    3.	If the new PDF was the result of minor edits, go on to step 9.
8.	If, however, there were significant changes to the guide, (e.g. an entire Part II was added):
    1.	Click on **Authoring Information**.
    2.	Delete the text in the **Authored on**: field so it is blank (system will auto 	enter today’s date).    
9.	Click the Submit button.
10.	Verify that the PDF/A appears at the bottom of the abstract.
