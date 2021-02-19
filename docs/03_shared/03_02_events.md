# ArchivesSpace: Events
In ASpace, Event records document actions that an archivist has taken upon a record (e.g., processing, deaccessioning, digitizing), as well as linking records together (e.g., in a “Processed” event, the accession and resource records are linked).

Events in ASpace can be created two ways:
1.	Use the Create menu. Select: Create > Event Record. An empty event record will appear. Fill in and edit the fields as indicated below.
2.	Create an event from within an accession or resource record.
    1.	Select: Add Event dropdown
    2.	Choose the event type (Processing New, Processing In Progress, Processed, Processing Queue, Processing Partial, Temporarily Closed, or Deaccession)
    3.	Select: Add Event. An empty event record will appear. Fill in and edit the fields as indicated below.

Event records in ASpace can be edited (including the type, i.e., changing an event from “Processing New” to “Processing In Progress”) in two ways:

1.	Search/Browse for the event record. In search/browse results. Select: Edit next to the event you wish to edit. The event will open in edit mode.  
2.	Directly within the linked accession or resource record.
    1.	In view mode, scroll down to the Events Subrecord.
    2.	Select: Edit next to the event you wish to edit. The event will open in edit mode.

The record will contain more fields than those listed below, but **do NOT enter/change any information in a field that is not indicated below.**

Edit the information in [ ]s (and delete the brackets). Choose the proper selection from those listed in italics. Note that the result for all “Outcome” fields is “Pass” because the event is created upon completion of the successful action taken by the archivist.

The instructions below can be used both for creating and editing event records. 

Note that for Processing New, Processing In Progress, and Processed, often the event can simply be edited to a different event type rather than creating a brand new event.

The following table shows the possible combination of events in any single ArchivesSpace record (indicated with an X):

| Event: | 	Processing Partial | Temporarily Closed | Deaccession |	Digitization |
| --- | --- | --- | --- | --- |
| Processing New | | | x | |
| Processing In Progress | | | x | |	
| Processed | x | x | x | x |
| Processing Queue | | | x | |	

## Processing New
Processing New events indicate that an accession is new, and not yet processed. A Processing New event must be created and linked to every accession, until the accession is being processed (partially or completed), or deaccessioned.

1.	**Basic Information**
    1. **Type**: Processing New
    2. **Outcome**: Pass
    3. **Outcome Note**: [Any additional information, i.e., if extent to process is different than initial amount accessioned, indicate here]
2.	**Event Date/Time**
    1. **Date/Time specifier:** UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you accessioned); Authorizer (if you supervised accessioning or are cleaning up backlog)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Source
    2. **Record**: [Accession Record] (denoted by gift icon)*
5.	**Save Event**

## Processing in Progress
A Processing In Progress event replaces the Processing New event for an accession that is undergoing processing. If multiple accessions are undergoing processing at the same time to create a single resource record (i.e., the processed collection is made up of several accessions), change one Processing New event to a Processing in Progress event, link all of the accessions to it, and delete the remaining Processing New events.

1.	**Basic Information**
    1. **Type**: processing_in_progress
    2. **Outcome**: Pass
    3. **Outcome Note**: [Any additional information]
2.	**Event Date/Time**
    1. **Date/Time specifier**: UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you processed); Authorizer (if you are supervising processing)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Source
    2. **Record**: [Accession Record] (denoted by gift icon)
    3. **Role**: Outcome
    4. **Record**: [Resource Record] (denoted by grid icon)
5.	**Save Event**

## Processed
Processed events replace the Processing In Progress event for accession(s) that are processed. Additionally, Processed events link all of the processed accessions to the resulting resource record that represents the processed collection. 

1.	**Basic Information**
    1. **Type**: Processed
    2. **Outcome**: Pass
    3. **Outcome Note**: [Any additional information]
2.	**Event Date/Time**
    1. **Date/Time specifier**: UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you processed); Authorizer (if you supervised processing)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Source
    2. **Record**: [Accession Record] (denoted by gift icon) (list ALL accession records processed to created the collection)
    3. **Role**: Outcome
    4. **Record**: [Resource Record] (denoted by grid icon)
5.	**Save Event**


## Processing Partial
A Processing Partial event indicates that only a portion of the accession is processed. This event can be used in conjunction with the Processed event (this does not preclude the accession from being linked to a resource record that has been processed). When this event is used, also edit the accession record and indicate in the Collection Management > Processing Plan field what portion of the material remains unprocessed and why.
 
1.	**Basic Information**
    1. **Type**: processing_partial
    2. **Outcome**: Pass
    3. **Outcome Note**: [Any additional information, i.e., extent processed]
2.	**Event Date/Time**
    1. **Date/Time specifier**: UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you processed); Authorizer (if you supervised processing)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Outcome
    2. **Record**: [Accession Record] (denoted by gift icon)
5.	**Save Event**

## Processing Queue
A Processing Queue event is created instead of a Processed event and indicates that the collection was opened immediately following accessioning (a resource record was created for access, but no processing was done), and although accessible still needs to be processed (i.e., it is in the processing queue). This event links the accession record(s) with the resource record. 
 
1.	**Basic Information**
    1. **Type**: processing_queue
    2. **Outcome**: Pass
    3. **Outcome Note**: [Any additional information]
2.	**Event Date/Time**
    1. **Date/Time specifier**: UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you processed); Authorizer (if you supervised processing)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Source
    2. **Record**: [Accession Record] (denoted by gift icon)
    3. **Role**: Outcome
    4. **Record**: [Resource Record] (denoted by grid icon)
5.	**Save Event** 

## Temporarily Closed
A Temporarily Closed event indicates that the collection is partially or entirely closed due to restriction(s) for a finite time period. It is only applied to processed collections (i.e., resource records) and is used with the Processed event (i.e., the resource record must have a Processed event as well as a Temporarily Closed event).
 
1.	**Basic Information**
    1. **Type**: temporarily_closed
    2. **Outcome**: Pass
    3. **Outcome Note**: [What is closed and when it can be opened and accessible]
2.	**Event Date/Time**
    1. **Date/Time specifier**: UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you processed); Authorizer (if you supervised processing)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Outcome
    2. **Record**: [Resource Record] (denoted by grid icon)
5.	**Save Event**

## Deaccession
A Deaccession event is used when an accession was entirely or completely deaccessioned. It can be used in conjunction with any Processing event.

1.	**Basic Information**
    1. **Type**: Deaccession
    2. **Outcome**: Pass
    3. **Outcome Note**: [indicate extent of collection deaccessioned, why, and any additional information]
2.	**Event Date/Time**
    1. **Date/Time specifier**: UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you deaccessioned); Authorizer (if you supervised deaccessioned or are cleaning up backlog)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Source
    2. **Record**: [Accession Record] (denoted by gift icon)*
5.	**Save Event**

## Digitization
Create a Digitization event when all or part of the processed collection has been digitized.

1.	**Basic Information**
    1. **Type**: Digitization
    2. **Outcome**: Pass
    3. **Outcome Note**: [Indicate portion of collection digitized, and any additional information]
2.	**Event Date/Time**
    1. **Date/Time specifier**: UTC Timestamp
    2. **UTC Timestamp**: [YYYY-MM-DD]
3.	**Agent Links**
    1. **Role**: Implementer (if you digitized); Authorizer (if you supervised digitizing)
    2. **Agents**: [Your accessID, i.e., aorchard]
4.	**Record Links**
    1. **Role**: Outcome
    2. **Record**: [Resource Record] (denoted by grid icon)
5.	**Save Event**

## Component Transfer
A Component Transfer event is automatically generated by ArchivesSpace after resource records are merged, archivists do not manually create Component Transfer events.