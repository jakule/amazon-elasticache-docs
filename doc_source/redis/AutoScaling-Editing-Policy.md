# Editing a scaling policy<a name="AutoScaling-Editing-Policy"></a>

You can edit a scaling policy using the AWS Management Console, the AWS CLI, or the Application Auto Scaling API\. 

**Editing a scaling policy using the AWS Management Console**

You can only edit policies with type Predefined metrics by using the AWS Management Console

1. Sign in to the AWS Management Console and open the Amazon ElastiCache console at [https://console\.aws\.amazon\.com/elasticache/](https://console.aws.amazon.com/elasticache/)\.

1. In the navigation pane, choose **Redis**

1. Choose the cluster whose auto scaling policy you want to edit\.

1. Choose the **Auto Scaling policies** tab\. 

1. In the **Auto scaling policies** section, choose the auto scaling policy, and then choose **Edit** from the **Actions** dialog box\. 

1. Make changes to the policy\. 

1. Choose **Update policy**\.

**Editing a scaling policy using the AWS CLI or the Application Auto Scaling API **

You can use the AWS CLI or the Application Auto Scaling API to edit a scaling policy in the same way that you apply a scaling policy: 
+ When using the Application Auto Scaling API, specify the name of the policy you want to edit in the `PolicyName` parameter\. Specify new values for the parameters you want to change\. 

For more information, see [Applying a scaling policy to an ElastiCache for Redis cluster](AutoScaling-Defining-Policy.md#AutoScaling-Applying-Policy)\.