# ArchivesSpace Instances - Containers and Digital Objects

ArchivesSpace Instances are used to indicate the box/folder number (for physical materials) or filepath/URL (for digital materials) of the materials being described. Generally, Instances are added at the lowest level of description -- that is, to the level of description that corresponds to manifestations of the materials being described.

## Adding Instances

Instances can be added by clicking the "Add Container Instance" or "Add Digital Object" button as appropriate within the Instances sub-record of an Accession, Resource, or Archival Object.

!!! note
    Instances should almost always be added to Archival Objects, not Resources or Accessions. Exceptions include collections for which only Resource-level description exists.

## Container Instances

Container Instances are used to identify the physical container in which materials are located. Generally, this will be something like "Box 1," "Box 2," "Folder 12," etc. 

### Instance Type

Container Instances require an Instance Type, selected from a controlled value list drop down menu. This should almost always be Mixed Materials, but can be a more specific material type if known (e.g., Audio, Text, etc.) Instance Type is not the ideal place to indicate this information, however, and this information should generally be indicated elsewhere (in an Extent sub-record, a Physical Description note, etc.)

### Top Container

Container Instances require a linked Top Container record. Top Containers are standalone record-types in ArchivesSpace that can be linked to from one or more Accessions, Resources, or Archival Objects. In this way, Top Containers are similar to Agent and Subject records -- they provide a method for managing the same entity in one record and linking to it where necessary. This allows for many collection management activities to be undertaken in ArchivesSpace -- containers can be barcoded, locations can be managed, boxes can be renumbered, and so on. Therefore, it is important that you create and link to the appropriate Top Container record within Container Instances. Avoid creating duplicate Top Container records.

Top Containers will generally be unique to a given Resource and will be numbered sequentially beginning with 1. In some cases, a Top Container may be shared between Resource (e.g., a single box that holds several small collections)

#### Creating a Top Container

Top Containers need only be created once for each distinct Top Container. To create a Top Container, click the down arrow next to the Top Container field in the Container Instance sub-record and select "Create." A blank Top Container template will appear. Enter the following information:

- **Container Type**: Box, Folder, Volume, etc.
- **Indicator**: The container number (1, 2, 3... 54, 55, etc.)

Then click the "Create and Link to Top Container" button

![Create Top Container](../img/aspace_create_top_container.png)

#### Linking a Top Container

Once a Top Container has been created, it should then be linked to all subsequent Container Instances to which it applies. To link an existing Top Container record, search in the Top Container search box within the Container Instance for the container type and number and select the appropriate container from the displayed results.

![Link Top Container](../img/aspace_link_top_container.png)

### Child Containers

Child containers are used within Container Instances to indicate second-level containers in which the material being described is located. Child containers will most commonly be used for indicating specific folders within boxes, but may also be used to indicate individual items, volumes, audio cassettes, and so on. Child containers require the following information:

- **Child Type**: Folder, Item, etc.
- **Child Indicator**: The child container number (1, 2, 3, etc.). If describing multiple folders at once, this can also be a range of numbers (e.g., 3-7)

![Container Instance](../img/aspace_container_instance.png)

ArchivesSpace allows for adding grandchild containers to describe yet another level of container-within-container; these will rarely be used.