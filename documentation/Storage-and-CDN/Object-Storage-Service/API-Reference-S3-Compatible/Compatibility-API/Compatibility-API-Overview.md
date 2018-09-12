# Compatible interface
 Current supported APIs are listed in the below table. For OSS compatible S3 API documents, please access [https://github.com/jdcloud-cmw/oss/tree/master/S3-API-Document](https://github.com/jdcloud-cmw/oss/tree/master/S3-API-Document)

<table width="1503"><tbody style="white-space: normal;"><tr class="firstRow"><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top" align="center">
<p><br/></p><p>api supported by cloud storage</p><p><br/></p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top" align="center"><p>
<br/></p><p>api introduction<br/></p></td><td style="padding: 0px 7px; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top" align="center"><p><br/></p><p>Description<br/></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>GET Service</p><p>(List Bucket)</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain all Buckets under a User</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTServiceGET.html" target="_self">GET Service</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>PUT Bucket</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Create a Bucket, default permission is Private</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketPUT.html" target="_self">&nbsp;PUT Bucket</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>HEAD Bucket</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Confirm whether a Bucket exists or not and has right to access</p><p>If a Bucket exists and has right to access, return 200 OK If the assigned bucket does not exist, return 404 Not Found</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketHEAD.html" target="_self">&nbsp;&nbsp;HEAD Bucket</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>GET Bucket</p><p>(List Object)</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain the Object information under a Bucket (Compatible Version2)</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/v2-RESTBucketGET.html" target="_self">GET Bucket</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>DELETE Bucket</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Delete the assigned Bucket</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketDELETE.html" target="_self">DELETE Bucket</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>PUT Object</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Upload an Object to OSS</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTObjectPUT.html" target="_self">PUT Object</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>GET Object</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain the Meta and data of an Object to obtain all data or use Range to assign to obtain part of the data</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTObjectGET.html" target="_self">GET Object</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>HEAD Object</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain the Meta of an Object</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTObjectHEAD.html" target="_self">HEAD Object</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>DELETE Object</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Delete an Object</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTObjectDELETE.html" target="_self">DELETE Object</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>Initiate MultiPart&nbsp;</p><p>Upload</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Initialize a MultiPart upload task</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/mpUploadInitiate.html" target="_self">Initiate MultiPart &nbsp;Upload</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>Upload Part</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Upload a Part to OSS</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/mpUploadUploadPart.html" target="_self">Upload Part</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>Complete MultiPart</p><p>Upload</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Combine multiple parts uploaded into an Object</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/mpUploadComplete.html" target="_self">Complete MultiPart &nbsp;Upload</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>Abort MultiPart Upload</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Abort a MultiPart upload task</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>&nbsp;Compatible&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/mpUploadAbort.html" target="_self">Abort MultiPart &nbsp;Upload</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>List Parts</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain information of the part already uploaded by the assigned uploadid</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/mpUploadListParts.html" target="_self">List Parts</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>List MultiPart Uploads</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain the MultiPart task uploaded under a Bucket</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/mpUploadListMPUpload.html" target="_self">List MultiPart Uploads</a></p></td></tr><tr><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0);" width="334" valign="top">POST Object<br/></td><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0);" width="790" valign="top">Upload files to OSS by a form</td><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0);" width="377" valign="top">See details:<a href="https://www.jdcloud.com/help/detail/7103/isCatalog/1" target="_self">post object </a></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>GET Bucket policy</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain policy on the assigned Bucket</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketGETpolicy.html" target="_self">GET Bucket policy</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>PUT Bucket policy</ p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Add or edit policy on the assigned Bucket</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketPUTpolicy.html" target="_self">PUT Bucket policy</a></p></td></tr><tr style="height: 19px;"><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>DELETE Bucket policy</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Delete policy on the assigned Bucket</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketDELETEpolicy.html" target="_self">DELETE Bucket policy</a></p></td></tr><tr><td style="padding: 0px 7px; border-top-style: none; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>PUT Bucket&nbsp;acl</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Set acl on the assigned Bucket</p></td><td style="padding: 0px 7px; border-top-style: none; border-left-style: none; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketPUTacl.html" target="_self">PUT Bucket acl</a></p></td></tr><tr><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>GET Bucket&nbsp;acl</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain acl on the assigned Bucket</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketGETacl.html" target="_self">GET Bucket acl</a></p></td></tr><tr><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>PUT Bucket&nbsp;cors</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Add CORS rules for the assigned Bucket</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketPUTcors.html" target="_self">PUT Bucket cors</a></p></td></tr><tr><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>GET Bucket&nbsp;cors</p></td><td rowspan="1" colspan="1" style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain CORS rules for the assigned Bucket</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketGETcors.html" target="_self">GET Bucket cors</a></p></td></tr><tr><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>DELETE Bucket cors</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Delete CORS rules for the assigned Bucket</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketDELETEcors.html" target="_self">DELETE Bucket cors</a></p></td></tr><tr><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>PUT Bucket website</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Add static website hosting rules for the assigned Bucket (note: The interface is compatible, but<a href="https://www.jdcloud.com/help/detail/2268/isCatalog/1" target="_self"> the details of rules</a> are different from S3)</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketDELETEcors.html" target="_self">PUT Bucket website</a></p></td></tr><tr><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>GET Bucket&nbsp;website</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Obtain static website hosting rules for the assigned Bucket (note: The interface is compatible, but<a href="https://www.jdcloud.com/help/detail/2268/isCatalog/1" target="_self"> the details of rules</a> are different from S3)</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketDELETEcors.html" target="_self">GET Bucket website</a></p></td></tr><tr><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="334" valign="top"><p>DELETE Bucket&nbsp;website</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="790" valign="top"><p>Delete static website hosting rules for the assigned Bucket (note: The interface is compatible, but<a href="https://www.jdcloud.com/help/detail/2268/isCatalog/1" target="_self"> the details of rules</a> are different from S3)</p></td><td style="padding: 0px 7px; border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Compatible&nbsp;&nbsp;<a href="http://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketDELETEcors.html" target="_self">DELETE Bucket &nbsp; website</a></p></td></tr><tr><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0); word-break: break-all;" width="334" valign="top">Put Object Copy</td><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0); word-break: break-all;" width="790" valign="top">Copy an object already existing on OSS into another object</td><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0); word-break: break-all;" width="377" valign="top"><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">Not support: x-amz-copy-source-if-match,</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-copy-source-if-none-match,</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-copy-source-if-unmodified-since,</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-copy-source-if-modified-since,</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-tagging-directive</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-storage-class support<br/></p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">STANDARD and REDUCED_REDUNDANCY</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTObjectCOPY.html" target="_self">PUT Object - Copy</a></p></td></tr><tr><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0);" width="334" valign="top">Upload Part Copy</td><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0);" width="790" valign="top">By copying data from an existed Object to upload a Part. </td><td colspan="1" rowspan="1" style="border-color: rgb(0, 0, 0);" width="377" valign="top"><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">Not support: x-amz-copy-source-if-match，</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-copy-source-if-none-match，</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-copy-source-if-unmodified-since，</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">x-amz-copy-source-if-modified-since</p><p style="margin-top: 0px; margin-bottom: 0px; padding: 0px; white-space: normal;">Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/mpUploadUploadPartCopy.html" target="_self">Upload Part - Copy</a></p></td></tr><tr><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="334" valign="top">Delete Multiple Objects</td><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="790" valign="top">Users can delete multiple Objects in the same Bucket by one HTTP request<br/></td><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Not support: version</p><p>Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/multiobjectdeleteapi.html" target="_self">Delete Multiple Objects</a></p></td></tr><tr><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="334" valign="top">PUT Bucket Replication<br/></td><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="790" valign="top">Create and modify cross-region replication configuration<br/></td><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Not support:</p><p>Account, Role, Owner</p><p>AccessControlTranslation</p><p>SourceSelectionCriteria</p><p>Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketPUTreplication.html" target="_self">PUT Bucket replication</a></p></td></tr><tr><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="334" valign="top">GET Bucket Replication</td><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="790" valign="top">Return cross-region replication configuration set on Bucket&nbsp;<br/></td><td rowspan="1" colspan="1" style="border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketGETreplication.html" target="_self">GET Bucket replication</a></p></td></tr><tr><td style="border-color: rgb(0, 0, 0);" width="334" valign="top">Delete Bucket Replication</td><td style="border-color: rgb(0, 0, 0);" width="790" valign="top">Delete the enabled cross-region replication configuration, the target Bucket and object remain exist after deletion<br/></td><td style="border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketDELETEreplication.html" target="_self">Delete Bucket replication</a></p></td></tr><tr><td style="border-color: rgb(0, 0, 0);" width="334" valign="top">PUT Bucket notification<br/></td><td style="border-color: rgb(0, 0, 0);" width="790" valign="top">Assign a Bucket to add NotificationConfiguration <br/></td><td style="border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Not support:</p><p>CloudFunction，Queue</p><p>Only support: Topic (for details, see <a href="https://www.jdcloud.com/help/detail/7065/isCatalog/1" target="_blank">callback notification</a>)<br/></p><p>Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketPUTnotification.html" target="_self">PUT Bucket notification<br/></a></p></td></tr><tr><td style="border-color: rgb(0, 0, 0);" width="334" valign="top">GET Bucket&nbsp;notification</td><td style="border-color: rgb(0, 0, 0);" width="790" valign="top">Return NotificationConfiguration set on Bucket<br/></td><td style="border-color: rgb(0, 0, 0);" width="377" valign="top"><p>Refer to:<a href="https://docs.aws.amazon.com/zh_cn/AmazonS3/latest/API/RESTBucketGETnotification.html" target="_self">GET Bucket notification<br/></a></p></td></tr></tbody><tbody style="white-space: normal;"></tbody></table>