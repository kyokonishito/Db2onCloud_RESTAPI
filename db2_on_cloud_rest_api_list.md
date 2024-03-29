# Authentication
- [Request a new access token](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#authenticate)
- [Returns public key of Json Web Token](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getpublickey)
- [Sets a new password using dswebToken](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#setpassword)

# Backup and restore
- [List currently available backups](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getbackups)
- [Restore](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#restore)
- [Create a backup](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#createbackup)
- [Get backup setting](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getbackupsetting)
- [Update backup setting](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#updatebackupsetting)

# Copy
- [Copy database to a new provision database](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#copydatabase)

# Connection
- [Get Db2 connection information](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getconnectioninfo)

# Data load
- [Lists all data load jobs using Db2 load utility technology](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#listloadjobs)
- [Creates a data load job](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#createloadjob)
- [Returns details about a load job including its progress](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getloadjobbyid)
- [Removes load job from history](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#deleteloadjobbyid)
- [Dowloads log file for a data load job](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getloadlogs)

# Db2 update
- [Checks for any available database update](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#checkupdate)
- [Trigger database update](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#triggerupdate)

# Disaster recovery
- [List disaster recovery enablement information](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getdrenablementdetails)
- [Enable disaster recovery](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#enabledr)
- [List disaster recovery remotes pair information](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getdrremotesstatus)
- [Perform disaster recovery takeover](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#takeoverdr)
- [Resync disaster recovery remote pair](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#resyncdr)
- [Check current disaster recovery resync status](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#resyncstatusdr)

# File storage
- [Deletes a file in the Db2 temporary cloud object storage](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#deletehomestoragefile)
- [Download file from Db2 temporary cloud object storage](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#downloadhomestoragefile)
- [Uploads a file to Db2 temporary cloud object storage](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#uploadhomestoragefile)

# Monitoring
- [Returns overall status of system components](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getoverallservicestatus)
- [Lists active database connections **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getactiveconnections)
- [Terminates a database connection **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#terminateactiveconnection)
- [Returns current storage usage **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getstorageusage)
- [Returns storage usage history **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getstorageusagehistory)
- [Storage utilization by schema **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getschemastorageusage)
- [Storage utilization of a schema **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getsingleschemastorageusage)
- [Return the number of statements for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getallhistogramsdata)
- [Return the histogram of response time for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getallhistogramsdatabyprofilename)
- [Return the average response time for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getaverageresponsetime)
- [Return the list of average response time for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getaverageresponsetimelist)
- [Return the average number of statements executed every minutes for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getstatementsrate)
- [Return numbers of statements executed every minutes for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#return-numbers-of-statements-executed-every-minute)
- [Return the average number of rows read(rows/min) for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getaveragerowsread)
- [Return the numbers of rows read(rows/min) for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getrowsread)
- [Return the maximum number of concurrent connections for a specified time frame **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmaxconnectionscount)
- [Return maximum numbers of concurrent connections for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getconnectionscount)
- [Return the maximum lockwaits per minute for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmaxlockwaitsrate)
- [Return the maximum lockwaits per minute for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getlockwaitsrate)
- [Return the maximum usage percentage of logs for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmaxlogspace)
- [Return the maximum usage percentages of logs for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getlogspace)
- [Return the maximum percent of node CPU usage for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmaxcpu)
- [Return the percent of node CPU usage for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getcpu)
- [Return the maximum percent of node memory usage for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmaxmemory)
- [Return the percent of node memory usage for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmemory)
- [Return the maximum usage percent of storage for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmaxstorage)
- [Return the usage percent of storage for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getstorage)
- [Return the time spent in each operation for a specified time frame. **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettimespent)
- [Return a table storage usage in a time range **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getstoragefortablestimeseriesusingget)
- [Returns a list for tables storage **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettablesstorage)
- [Returns a table storage **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettablestorage)
- [Returns a list for schemas storage **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getschemasstorage)
- [Return a schema used storage in a time range **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getstorageforschemastimeseriesusingget)
- [Returns a schema storage **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getschemastorage)
- [Runs a tables storage collection **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#collecttablesstorage)
- [Returns a list of inflight executions](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getinflightexecutions)
- [Returns a list of current inflight executions](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getcurrentinflightexecutions)
- [Returns a infight execution detail](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getinflightexecutiondetial)
- [Terminates a statement **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#terminateactivestatements)
- [Returns a list of connections](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorconnectiondeltaget)
- [Returns a list of current connections](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorcurrentconnectiondeltaget)
- [Returns a connection detail](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorconnectiondeltadetail)
- [Terminates a database connection **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#terminateconnection)
- [Returns a list of timeseries of a connection](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorconnectiontimeseriesdeltaget)
- [Returns performance metrics for schemas **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorschemasperffrontend)
- [Returns performance metrics for schemas **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#currentmonitorschemasperffrontend)
- [Returns performance metrics for one schema **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorschemaperffrontend)
- [Returns performance metrics on all members for one schema **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorschemaperfbymemberfrontend)
- [Returns performance metrics timeseries for one schema **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitorschemaperfbytimeseriesfrontend)
- [Returns performance of tables **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitortablesperffrontend)
- [Returns current performance of tables **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#currentmonitortablesperffrontend)
- [Returns performance of one table **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitortableperffrontend)
- [Returns performance on all members for one table **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitortableperfbymemberfrontend)
- [Returns performance timeseries for one table **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#monitortableperfbytimeseriesfrontend)
- [Returns performance of tables and schemas **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettableperformancehistoryusingget)
- [Returns current performance of tables and schemas **DB ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettableperformancerealtimeusingget)

# SQL
- [Executes SQL statements](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#runsql)
- [Fetches partial results of a SQL job execution](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#fetchsqlresults)
- [Returns the results of a SQL query to CSV](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#fetchsqlstatementresults)

# Scaling
- [Create a scaling request](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#postscalingrequest)
- [Get supported scaling ranges and current allocated resources](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getresourcesinfo)
- [View scaling history](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getscalinghistory)

# System information
- [Get system information](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getaboutinfo)

# Tasks
- [Get tasks status](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettasksstatus)

# Utilities
- [Analyzes CSV data to return a list of value data types](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#schemadiscoveryfromcsv)

# Database Objects
- [Query the list of object schemas](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getschema)
- [Create schema](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#createschema)
- [Drops an empty schema](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropschema)
- [Get single object privilege](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getsingleobjectprivilege)
- [Privilege list of selected objects](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getobjectprivilege)
- [Grant or revoke privileges](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#modifyprivileges)
- [Create a new table](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#createtable)
- [Drop table](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#droptable)
- [Get table definition](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettablesdefinition)
- [Query table data](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettabledata)
- [Get column detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getcolumnsdetailproperties)
- [Get the metadata type](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmetadatatypes)
- [Generate table DDL](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#generatetableddl)
- [Get distributin keys](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getdistributionkeys)
- [Get data distributin property](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getdatadistributionproperty)
- [Get partition expressions](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getpartitionexpressions)
- [Get data partitions](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getdatapartitions)
- [Query view detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getviewsdetailproperties)
- [Drop views](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropview)
- [Query view data](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getviewdata)
- [Get View definition](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getviewdefinition)
- [Generate view DDL](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#generateviewddl)
- [Get the dependencies of the object](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getobjectdependency)
- [Query bufferpool detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getbufferpooldetailproperties)
- [Query constraint detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getconstraintsdetailproperties)
- [Query index detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getindexesdetailproperties)
- [Query trigger detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettriggerdetailproperties)
- [Query MQT detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmqtdetailproperties)
- [Query UDF detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getudfdetailproperties)
- [Query tablespace detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettablespacedetailproperties)
- [Query procedure detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getproceduredetailproperties)
- [Query sequence detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getsequencedetailproperties)
- [Query package detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getpackagedetailproperties)
- [Query UDT detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getudtdetailproperties)
- [Query alias detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getaliasdetailproperties)
- [Get table detail properties](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#gettablesdetailproperties)
- [Create alias](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#createalias)
- [Drop alias](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropaliases)
- [Generate Alias DDL](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#generatealiasddl)
- [Query alias data](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getaliasdata)
- [Get the SQL statement template for creating MQT table](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmqtddl)
- [Delete mqt tables](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropmqts)
- [Get the definition of MQT table](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmqtdefinition)
- [Get the data of specified mqt table](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getmqtdata)
- [Get authentications through the authid filter](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getauthenticationsbyauthidfilter)
- [Get the privieles of auth id](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getauthorizationsdetailforobject)
- [Get SQL statement of grant or revoke privileges](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getchangeprivilegesql)
- [Add new role](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#createrole)
- [Grant or revoke the privilges of role](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#modifyroleprivilege)
- [Delete one role](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#removerole)
- [Get the membership of authid](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getrolesforauthid)
- [Get SQL statement of grant or revoke role](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getchangeroleprivilegesql)
- [Get SQL statement for grant or revoke privileges](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getchangemultipleobjecttypeprivilegesql)
- [Grant or revole privileges for multiple objects and objects type](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#modifyprivilegesformultipleobjects)
- [Get the SQL statement for grant or revoke multiple roles](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getchangemutiplerolesprivilegessql)
- [Grant or revoke multiple roles](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#modifymultiplerolesprivilege)
- [Generate workload DDL](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#generateworkloadddl)
- [Lists workloads](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#listworkloads)
- [Drop sequences](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropsequences)
- [Drop procedures](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropprocedures)
- [Retrieve parameters for procedure](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getprocedureparameters)
- [Generate create procedure template](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#generate-create-procedure-template)
- [Drop functions](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropfunctions)
- [Retrieve parameters for specific udf](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getfunctionparameters)
- [Generate create function template](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#generatecreatefunctiontemplate)
- [Drop User-defined Types](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#dropudts)
- [Retrieve row definition for User-defined Type object](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getudtdefinition)
- [Generate Create User-defined Types template](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getudtddl)

# Users
- [Returns the list of users](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getusers)
- [Creates a new user. **PLATFORM ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#createuser)
- [Get a specific user by ID](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#getuser)
- [Updates an existing user **PLATFORM ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#updateuser)
- [Deletes an existing user **PLATFORM ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#deleteuser)
- [Locks a user account indefinitely.  **PLATFORM ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#lockuser)
- [Unlocks a user account  **PLATFORM ADMIN ONLY**](https://cloud.ibm.com/apidocs/db2-on-cloud/db2-on-cloud-v4#unlockuser)

