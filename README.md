code-archive
============

### About

This is the MIC Code Archive Repository, where old or inactive client projects and code collections are stored. Typically these projects will be collected into folders or ZIP files and added to this Repository. The specifics of each folder or ZIP will be maintained in this document, serving as a full catalog of the system.

If you have questions about this Repository and how to use it please contact [developer@marketingincolor.com](mailto:developer@marketingincolor.com)

### Catalog

#### MSP Server Change

This ZIP file in the Code Archive contains 3 folders of content which were utilized during the MoreSpacePlace server transition. Initially the original hosting setup was copied from the server via FTP and saved in the MSP Archive directory. The full working Database was dumped from the original hosting setup as well and worked with locally until a cleaned working version could be gleaned from the original. This work and the SQL files are stored in the MSP Install Folder, along with the multi-site specific contents of the wp-content folder which needed to be transferred to the new hosting environment as well.

When completed, the client's "main site" had been removed from their multi-site Wordpress installation to a new hosting setup. 

* __msp archive folder__ - a "full dump" of site from the original hosting setup before ANY work was done or files changed.
* __msp install folder__ - mostly SQL files of data pulled from the system which was then recompiled via MySQL on EJT's local development host, and transitioned from a WP Multisite setup to a single site configuration for the "main" site.
* __msp transfer folder__ - the install or transfer of what was setup on the new hosting setup for the client

