#### Versioning buckets state

- Unversioned
- Versioning-enabled
- Versioning- suspended

#### Delete marker

- It is possible to have multiple delete marker
of the same object in one bucket.

- If you don't specify a version ID
:q in your delete request, Amazon S3 adds another
 delete marker instead of deleting the object.

- To delete a delete marker, you must specify its version ID in a delete request. 


#### Two ways to manage object retention

- Retention period

- Compliance mode: immutable
- Governance mode: you can alter the retention settings
  
  Permission: s3:BypassGovernanceRetention
  header: x-amz-bypass-governance-retention:true

- Legal holds

#### S3 Batch Operations

#### Operations

- Copy objects
- Replace object tags
- Delete object tags
- S3 Object Lock
- S3 Object Lock legal hold
