# DedicatedRemote

REST API
--------

File manager

HTTP Methods  | URL               |Parameters (url or body)                               | Description
--------------|-------------------|-------------------------------------------------------|----------------------------------
GET           | /1.0/manager/file | [filepath:String, filename:String, download:Booleans] | Download file or get information
POST          | /1.0/manager/file | [filepath:String, filename:String, fileupload:File]   | Create file
PUT           | /1.0/manager/file | [filepath:String, filename:String, fileupload:File]   | Edit file
DELETE        | /1.0/manager/file | [filepath:String, filename:String]                    | Delete file

