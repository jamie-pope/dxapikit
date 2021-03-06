# Change Log 

## December 5, 2018

Starting with Delphix Release 5.3.1.#, the login API call should be changed to get a new session id (JSESSIONID) upon a successful login <br />
<br />
change from just using the session cookie SESSIONID<br />
/login -b "cookies.txt"<br />
<br />
to regenerating a new cookie only upon a successful login ...<br />
/login -b "cookies.txt" -c "cookies.txt<br />
<br />
NOTE: this change is backwards compatible.<br />
<br />

## July 3, 2018
 <br />
<ul>
 <li>Added and Updated Masking API's</li>
 <ul>
  <li> Masking_Powershell    - Powershell API's Examples</li>
  <li> Masking -> Profile    - sample scripts to Profile one or many environments</li>
 </ul>
 <li>New APIs: Delphix Reporting (formerly Mission Control)</li>
 <li>Updated Linux Shell API Examples</li>
     <ul>
     <li>vdb_init.ps1        - updated to support other Delphix Data Sources</li>
     <li>vdb_operations.ps1  - updated to support other Delphix Data Sources </li>
    </ul>
</ul>
<br />
<br />

## January 7, 2018
 <br />
<ul>
 <li>Updated API's to support Delphix J Release 5.2.#</li>
 <li>New API: jetstream_container_users_jq.sh	 --  List Users per Jetstream Containers</li>
 <li>Updated and Added New Powershell API's to match more of the Linux Shell API Examples</li>
    <ul>Key APIs
     <li>vdb_init.ps1</li>
     <li>vdb_operations.ps1</li>
     <li>... plus others </li>
     <li>NOTE: All Powershell Examples are now for Powershell Version 3.# or later. For Powershell v2.# environments, functions are provided, see respective README file</li>
    </ul>
</ul>
<br />
<br />

## December 3, 2017
 <br />
<ul>
 <li>All the jetstream APIs where either updated or added ... </li>
 <li>Added the vdb_oracle_template.sh to manage the Delphix template (init parameters) objects for Oracle VDBs</li>
 <li>Added provision_oracle_i.sh for interactive and command line arguements for provisioning an Oracle VDB</li>
 <li>Added provision_hana.sh for provisioning a HANA database</li>
 <li>Added to the jqJSON_subroutines.sh a get API version function</li>  
</ul>
<br />
<br />

## October 9, 2017
 <br />
New APIs Added ... <br />
 <br />
List Bookmarks per Branch and provides option to Delete Bookmark  <br />
Filename: jetstream_list_bookmarks.sh <br />
 <br />
 <br />
List Branches per Container and provides option to Activate/Delete Branch <br />
Filename: jetstream_list_branches.sh <br />
 <br />
 <br />
Creates a Branch within a Container using the latest Branch Timestamp <br />
Filename: jetstream_create_branch_from_latest.sh <br />
 <br />
 <br />
Creates a Branch within a Container per Bookmark Selection <br />
Filename: jetstream_create_branch_from_bookmark.sh <br />
 <br />
 <br />
Display Snapshot Details; Database, Snapshot, Size, Timeflow Dependency, VDB Dependency with option to delete non-dependent snapshots <br />
Filename: snapshot_details.sh <br />	
 <br />
 <br />
 
## August 12, 2017

This is a new repository, thus the initial publishing of the scripts

Please see each folders respective README file for details

