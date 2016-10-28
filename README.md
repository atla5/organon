# roadmap
Guide, wiki, scripts, and resources for use in the digization and description of printed materials.

## Purpose ##

Provide and/or identify a suite of software tools to aid in each step of digitization and description, 
  and the documentation to guide users and organizations through the process.

## Digitization Workflow ##

#### High Level ####

|  ID   |  NAME       |                TOOLS                    |
|:-----:|:------------|:----------------------------------------|
|   0   | **Render**  | spreads.io |
|   I   | **Resolve** | scantailor, gimp, smoothscan, ... |
|  II   | **Combine** | pdfviewer, pdfbeads, tesseract, _stich3r_|
| III   | **Describe**| DScribe, lib-name-parser, _authconn_, subjest, ...|
|  IV   | **Publish** | crosswalk, DSpace, SAFBuilder, ... |
|   V   |**Circulate**| solr, librarything, collectiveaccess, ... |

#### Granular ####

|  ID   |   Step 01   |   Step 02   |   Step 03   |
|:-----:|:------------|:------------|:------------|
|   0   |  _Split_    |   Render    |  _Rebind_   |
|   I   |  Ordered    | Resolved    |  Enhanced   |
|  II   | Image Set   |Stitched zip |OCR+Bookmark |
| III   | Item-level  | Collection  |   Managed   |
|  IV   | Acquire     | Preserve    |  Accession  |
|   V   | Interpret   | Rate/Review |  Discuss    |  

**references** 
- @[ncraun](https://github.com/ncraun)'s [Linux Guide to Bookscanning](https://natecraun.net/articles/linux-guide-to-book-scanning.html)
- ...

#### Description ####

|  ID  | Marc format type |    Tools    |
|:----:|:----------------:|:------------|
|  01  | Authority Control| lib-name-parser, _auth-conn_ |
|  02  | Bibliographic    | DScribe, crosswalk |
|  03  | Classification   | subjest |
|  04  | Community Info   | ...? |
|  05  | Holdings Records | ...? |

**references**
- [MARC Wikipedia Sub-Entry](https://en.wikipedia.org/wiki/MARC_standards#MARC_formats)
- ...

## Projects ##
- General 
  - _hypervisor_: workflow management and inter-process communication
  - _osi-protocol_: how-to for using and creating FOSS for LAMP
  - _automata_: tool and protocol for posting tasks in need of automation
- Description
  - DScribe: parse, interpret, export bibliographic metadata 
  - crosswalk: interoperability tool for bibliographic metadata
  - lib-name-parser: ongoing management of the logical partitioning of names
  - _auth-conn_: storage and indexing container for lib-name-parser data
  - _subjest_: classification expansion tool for cataloging

## Components per Repo ##
- issues
- wiki
- README
- CONTRIBUTING
- ROADMAP
- LICENSE
- project.json
- lit-review/*.md
- lit-review/.json

## Desired Schedule ##

#### Weekly ####

|time|Sun|Mon|Tue|Wed|Thu|Fri|Sat|
|:----|:--|:--|:--|:--|:--|:--|:--|
|08-10|   | x | x | x | x |   |   |
|10-12|   | x | x | x | x | o |   |
|12-14| o | x | x | x | x | o |   |
|14-16| o | x | x | x | x | o |   | 
|16-18|   | x | x | x | x |   |   | 


#### Time Summary ####

|Sunday |Mon-Thu |Friday | Total  |
|:------|:-------|:------|:-------|
|lib-re |fulltime|lib-re |10 + 40 | 
|4 hours|40 hours|6 hours|50 hours|
