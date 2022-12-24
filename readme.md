#### Gaining insight with CloudWatch

#### Cloudwatch metrics key elemens

 - Metrics

Metrics are the fundamental concept in Cloudwatch. A metric represents
a time-ordered set of data points that are published to Cloudwatch.


 - Dimensions

Dimensions are name/value pairs that are part of the identity of a metric.


 - Filters

When working with Cloudwatch metrics, you have the option of filtering
the data into groups o related objects within a single bucket.


- Dashboards

Dashboards are a collection of graphs that you can use to monitor your AWS resources.



#### Cost Optimization

- Application Requirements

- Data organization

- Understand,analyze and optimize

- Continous right sizing

### Tools for S3

- Amazon S3 Inventory

You can use it to audit and report on the replication and encryption
status of your objects for business, compliance, and regulatory needs.

- Amazon S3 Server Access Logs

Provides detailed records for the requests that are made to a bucket.

- AWS CloudTrail logs
Is a service that enables governance, compliance, operational auditing, and risk
auditing of your AWS account.



S3 Inventory is used to determine which objects are in your buckets. Server Access Logs 
and CloudTrail logs help you to determine which of these objects are being accessed and how 
frequently they are accessed.  Using these tools together allows you to determine if objects 
are being put to S3, but never accessed. Once that determination is made, objects that are never
accessed can be moved to archived tiers for storage cost savings.
- 

Amazon QuickSight

Allows you to visualize S3 data by allowing you to create
and publish interactive business intelligence dashboards.

- S3 Storage Lens

Delivers organizational wide visibility into object storage usage,
activity trends and make actionable recommendations to optimize costs.

- S3 Storage class Analysis

This tool allows you to monitor access patterns across objects
to help you decide when to transition data to the right storage

- AWS Budget

Allows you to set custom budgets to track your cost and usage.

- AWS Cost Explorer

Provides botha billing and usage report.


#### S3 Storage Lens

Provides a single view of object storage and activity across hundreds of
acconts

Produces actionable recommnedations to help improve cost-efficiency and apply
data protection best practices


#### AWS Budgets

Monthly fixed target

Monthly variable target budget

Fixed usage amount

Daily utilization budget

Best Practices

- Use AWS Budget to set custom budgets based on your costs, usage,reservation
utilization, and RI coverage.

- Set budgets on a recurring basis so that budget alerts don't unexpectedly
stop coming.

- AWS requires approximately five weeks of usage data to generate 
 budget forecasts. If you set a budget to alert based on a 
 forecasted amount, this budget alert isn't initiated until 
you have enough historical usage information.


#### Access Point

Provide simplified control for shared dataset in the same bucket.
Each access point has its own access permissions.
