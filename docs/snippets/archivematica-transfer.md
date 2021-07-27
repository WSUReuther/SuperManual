Note: these instructions were previously part of the Accessioning documentation and are being saved here temporarily to potentially be reused elsewhere

!!! note "Optional"
    1. Makes a disk image of digital materials (8A):
        1. Transfers the media to the Digital Resources Specialist (DRS) for imaging or contacts the DRS to obtain the Cheat Sheet to image the media her/himself.
        2. If the proper hardware exists, duplicates the storage media as an .iso file and place on the server at: Hold02 > Central > Collections > Collections > Collection_Management_Tools > Accessions > CaseFiles > [Record Group Folder] > [accession number folder] > [accession number_alphanumeric object identifier].iso (e.g. LR002204.A001.iso) 
!!! success "Required"
    2. Includes digital case file documentation (9A): 
        1. Create folder: “submissionDocumentation” within the top-level folder of the digital archival collection 
        2. Add all digital case file material(s) (if a disk image was created, add it to the digital case file) 
    2. Transfers materials to Archivematica (10A): 
        1. Select: “Standard” 
        2. Select: “Browse” 
        3. Choose the material to transfer: 
            1. To open a directory select: folder icon 
            2. To select the folder to transfer, select: folder title (this is the folder containing all of the archival collection material and submissionDocumentation) 
            3. Select: “Add” 
        4. Name the transfer: 
            1. “Transfer Name” field type: Enter DACS Compliant collection title 
            2. “Accession no.” field type: Enter the full accession number 
            3. Select: “Start Transfer” 
        5. Job: Approve standard transfer: Actions – “Approve Transfer” 
        6. Create SIP(s): - Actions – “Send to backlog”   
    3. Reviews materials for sensitive information to determine potential restrictions (11A)*: 
        1. Select “Appraisal” 
        2. Copy and paste the name of the transfer from the Transfer page into the text field and select “Search transfer backlog” 
        3. Collection is listed in the Backlog window. 
        4. Select the collection. 
        5. Select: “Examine contents” 
            1. Select “PII” to reveal a list of filenames identified as containing personally identifiable information (e.g., social security numbers). Select a filename to reveal the list of social security numbers found in the file.[^1] 
            2. Select “Credit card numbers” to reveal a list of filenames identified as containing credit card numbers. Select a filename to reveal a list of credit card numbers found in the file. 
        6. Weeds and removes discards[^2] (12A)*: 
            1. Select: Arrangement 
            2. Select: “Add directory” 
            3. Enter: Collection Title 
            4. Select the top-folder in the Backlog box and drag it into the top-level folder in the Arrangement box 
            5. Open folders as needed in the Arrangement box. Select each file that is to be discarded and select Delete selected, then OK. 
        7. Creates SIP (13A) (note, if step e. was performed, i.-iv. are already done): 
            1. Select: “Arrangement” 
            2. In the Arrangement box, select: “Add Directory” 
            3. In the pop up window, name the directory the collection title. 
            4. Drag and drop the top-level collection folder from the backlog box to the folder in the Arrangement box. 
            5. Select: “Create SIP” 
            6. SIP is created and can be ingested at a later time 
            7. Proceed based on processing next steps: 
                1. Immediately opening material (no restrictions): [Opening Accessions](../02_arrangement/02_01_general.md#opening-accessions)
                2. Processing material: Arrangement and Description: [Born Digital Materials](../02_arrangement/../02_arrangement/02_02_special-formats.md#born-digital-materials)
                3. Leaving as backlog per restrictions: Update accession record (see step g.) with restriction information and date when material can be processed and opened.  
        8. In ArchivesSpace, updates the accession record to include information obtained during digital material stabilization (Fill out what is applicable) (14A): 
            1. Basic Information > Content Description: Overview of what the material is about 
            2. Basic Information > Condition Description:  File formats and file structure 
            3. Basic Information > Inventory: File list 
            4. Basic Information > Access Restrictions: PII review information impacting access 
            5. Basic Information > Use Restrictions: PII review information impacting use 
            6. Dates 
            7. Extent: extent of digital portion of collection

    * Steps 4d and 4e may not always be necessary (e.g., if the archivist created the digital materials themself, or if material is being reingested).

[^1]:
    Archivematica only identifies the PII and credit card numbers, it does not remove the content from the digital objects. How to handle it (restrictions, removal of the digital files, etc.) is up to the archivist.
[^2]: 
    Materials can be viewed in Archivematica via the preview pane or (recommended) more thoroughly reviewed by creating a working copy, and reviewing those working copy files (NEVER open/work with original digital materials). Note any that should be discarded, and then delete those in Archivematica following these instructions.