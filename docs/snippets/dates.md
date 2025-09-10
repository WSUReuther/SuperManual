The Reuther uses an ArchivesSpace plugin called [timewalk](https://github.com/alexduryee/timewalk), developed by Alexander Duryee at the New York Public Library, to automatically parse Date Expressions into structured Begin and End dates when an ArchivesSpace component is saved. In order for this to work properly, create one Date subrecord for each distinct individual or range of dates and enter the information in a consistent, standardized way. For example, if an ArchivesSpace component contains materials from August 17, 1945 and 1957-1965, create two separate Date subrecords with the following Expressions:

1. `1945 August 17`: This will be automatically parsed into a Single date with a Begin value of 1945-08-17
2. `1957-1965`: This will be automatically parsed into an Inclusive date with a Begin value of 1957 and an End value of 1965

If exact dates cannot be determined, but approximate dates can be inferred, enter the Date Expression as `circa [date]`. If no dates can be determined or inferred, enter a Date Expression of `undated`. Alternatively, for lower-level Archival Objects, do not add any Date subrecords; this will result in ArchivesSpace inheriting down the closest parent record's Date information for display and search in the Public User Interface. For example, an Archival Object with no Date subrecords that is a child of a Sub-Series with a date range of `1950-1970` will have that Date range associated with it.

At the Resource level, record one Inclusive or Single Date and, if applicable, one Bulk date. At the Archival Object/component level, record as many Inclusive or Single dates as necessary, favoring one or two inclusive ranges when possible, and one Bulk date if applicable.

For each date:

**Select**: Add Date or + if necessary to add a new Date subrecord

  1. **Label**: Creation
  2. **Expression**: [Date]
  3. **Type**: Choose one:
      1. Inclusive
      2. Single
      3. Bulk
