# Review Recorded Conversations<a name="recordings"></a>

Managers can review past conversations between agents and customers\. To set this up, you need to add the **Set call recording** block to your contact flow, assign managers the appropriate permissions, and then show them how to access the recorded conversations\. 

A conversation is recorded only when the contact is connected to an agent\. The contact is not recorded before then, when they are connected to the IVR\. 

**Important**  
The monitor feature works only when call recording is enabled on a contact flow\. For instructions on adding the **Set call recording** block to your contact flow, see [Set up Call Recording](set-up-recordings.md)\. 

## Assign Permissions to Review Recordings of Past Conversations<a name="manager-recording"></a>

These permissions enable managers to access recordings of past conversations\. 

**To assign a manager permissions to review recordings of past conversations**

1. Go to **Users**, **User management**, choose the manager, and then choose **Edit**\.

1. In the Security Profiles box, assign the manager to the **CallCenterManager** security profile\. This security profile also includes a setting that makes the icon to download recordings appear in the results of the Contact search page\. 

1. If you also want the manager to monitor live conversations, assign the manager to the **Agent** security profile so they can access the contact control panel\. This is so they can monitor the conversation through the contact control panel\.

1. Choose **Save**\. 

**Or, to create a new security profile specific for this purpose**

1. Choose **Users**, **User management**, **Security profiles**\. 

1. Choose **Add new security profile**\. 

1. Expand **Metrics and Quality**, then choose **Manager monitor** and **Recorded conversations** \(choose both **Access** and **Enable download button**\)\. 

1. If you also want the manager to monitor live conversations, assign the manager to the **Agent** security profile so they can access the contact control panel\. This is so they can monitor the conversation through the contact control panel\.

1. Choose **Save**\. 

## Review or Download Recordings of Past Conversations<a name="w11aac27c11c11"></a>

These are the steps that a manager does to review or download past recordings of conversations\.

1. Log in to Amazon Connect with a user account that is assigned the **CallCenterManager** security profile, or that is enabled for the **Manager monitor** permission\.

1. In Amazon Connect choose **Metrics and quality**, **Contact search**\. 

1. Filter the list of contacts by date, agent login, phone number, or other criteria\. Choose **Search**\.

1. Conversations that were recorded will have icons in the Recording column\. Click to review the recording, download, or delete it\. If you choose to download the recording, it will be saved automatically to your Downloads folder\. 

## Search for Recordings by Contact ID<a name="w11aac27c11c13"></a>

To find a recording of a specific contact, you only need the contact ID\. You don't need to know the date range, agent, or any other information about the contact\. 

1. Log in to Amazon Connect with a user account that is assigned the **CallCenterManager** security profile, or that is enabled for the **Manager monitor** permission\.

1. In Amazon Connect choose **Metrics and quality**, **Contact search**\. 

1. In the **Contact ID**, enter the contact ID, and then choose **Search**\.

1. Conversations that were recorded will have icons in the Recording column\. 