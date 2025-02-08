# Creating and Customizing Historical Queue Contacts Reports
#### [Made by Tasha Penwell with Scribe](https://scribehow.com/shared/Creating_and_Customizing_Historical_Queue_Contacts_Reports__IlJ8db5_S6ax4GE0R74Hwg)
This guide provides detailed instructions for creating and customizing historical queue reports, making it essential for anyone looking to analyze contact center performance effectively. It covers various settings for adjusting metrics, filters, and groupings, enabling users to tailor reports to specific needs. Additionally, the guide outlines how to save, share, and schedule reports, enhancing collaboration and efficiency within teams.

1\. Open the Analytics and optimization section and click on Historical metrics.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/1ef0cbbd-c755-4e3b-93c1-cef0971ffa91/user_cropped_screenshot.jpeg?tl_px=0,12&br_px=1719,973&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=94,277)


2\. **Historical Metrics in Amazon Connect**

Amazon Connect offers a range of historical metrics reports that provide data about past, completed activity and performance in your contact center. These reports allow managers to analyze various aspects of their operations, including queues, agents, phone numbers, and (with limited availability) cases.

**Types of Historical Metrics Reports**

1. **Queue Metrics**

   - Contact handling metrics (e.g., contacts handled, average handle time)
   - Service level and abandonment rate

2. **Agent Metrics**

   - Performance metrics (e.g., contacts handled, average handle time)
   - Activity metrics (e.g., online time, after contact work time)

3. **Phone Number Metrics**

   - Inbound call performance (e.g., total calls, average speed of answer)

4. **Cases Metrics**

   - Average case resolution time
   - Average contacts per case
   - First contact case resolution rate
   - Case reopen rates

##


3\. **Queues** reports provide data on queue performance and contact handling. Options include the following:

1. **Contact metrics**: Includes metrics like contacts handled, average handle time, service level, and abandonment rate for each queue.
2. **Agent metrics**: Shows agent performance within queues, including metrics like occupancy rate, online time, and after contact work time.

**Agent** reports focus on individual agent performance. They provide insights on the following:

1. **Agent performance**: Provides metrics such as contacts handled, average handle time, and adherence for each agent.
2. **Agent activity**: Shows detailed information about agent status changes and time spent in different activities.

**Phone number** reports offer insights into inbound call performance. This includes information on Contact metrics. **Contact metrics** includes metrics like total calls, average speed of answer, and service level for each phone number.

**Cases** provide actionable insights. These reports help contact center managers quickly identify delays in case closure for specific case types. This allows them to take actions to accelerate resolution and improve customer satisfaction.

*Note: Cases are not automatically enabled or available in all areas.*


4\. You will see four options. In this demo, you will be viewing historical metrics from the Queues. Select the drop down to view the options.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-20/0298ce09-2a3a-4eb4-80bf-c12f51b5e897/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2704,1513&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=900,200)


5\. The options are Contact metrics and Agent metrics. In this demo, we are choosing Contact metrics.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/9549288d-805e-47e6-b86b-558921582f74/user_cropped_screenshot.jpeg?tl_px=984,75&br_px=2704,1036&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=596,276)


6\. Contact Metrics in Amazon Connect provide crucial insights into the performance and efficiency of your contact center operations. By tracking these metrics, you can view and identify areas of excellence and improvement. Examples include the following:

**Average Handle Time (AHT)**: Identify opportunities to streamline processes and improve agent efficiency, leading to shorter wait times for customers.

**After Contact Work (ACW) Time**: Pinpoint areas where agents may need additional support or training to complete post-call tasks more efficiently.

**Queue Performance**: Monitor metrics like average wait time and abandonment rate to adjust staffing levels and reduce customer frustration.

**Service Level**: Track how well you're meeting your target response times, helping you maintain consistent service quality.

By leveraging these Contact Metrics, you can make data-driven decisions to continuously improve your customer service operations, ultimately leading to higher customer satisfaction, increased loyalty, and better business outcomes.


7\. The metrics are displayed in their default settings segmented by the queues.

(Your report may look different based on your setup)

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/699c65e4-7154-4e3d-8378-81d997ed3a12/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2704,1508&force_format=jpeg&q=100&width=1120.0)


#### Update the Report Settings


8\. To begin customizing the report, select the sprocket/gear icon on the right side of the screen.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/ab3912df-8049-4fc8-8e13-f504c12891e6/user_cropped_screenshot.jpeg?tl_px=984,6&br_px=2704,967&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1011,277)


9\. A box appears that displays four areas for the Table Settings.

1. Interval & Time range
2. Groupings
3. Filters
4. Metrics


10\. In the Interval & Time Range settings you can update the following:

- Set the **Interval** for data aggregation, such as 30 minutes, Daily, or Total.
- Choose the **Time Zone** for the report, which determines when a day starts.
- Select the **Time Range** for the report, such as Last x days, Month to date, or a custom range

Learn more at <https://docs.aws.amazon.com/connect/latest/adminguide/create-historical-metrics-report.html>

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/a0d74f13-51c7-4814-9d22-53d437eb0c83/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2293,1281&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=457,85)


11\. In the Groupings setting you can update the following:

- Choose up to five grouping options to organize your data.
- Group by queue, agent, agent hierarchy, routing profile, phone number, channel, Amazon Q, or subtype.

When using multiple grouping options, the data is grouped by the first grouping option and then by the subsequent grouping options.

Learn more at <https://docs.aws.amazon.com/connect/latest/adminguide/create-historical-metrics-report.html>


12\. The column on the left shows the grouping options that have not been added to the report. Grouping options can be added by clicking on the plus symbol.

The column on the right shows the grouping options that is currently in the report. Grouping options can be removed by clicking on the minus symbol.

This report, by default, has the Queue currently selected.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/7052c37c-b436-4382-a629-155873624f91/user_cropped_screenshot.jpeg?tl_px=492,275&br_px=2212,1236&force_format=jpeg&q=100&width=1120.0)


13\. In this demo, the Agent and Routing Profile have been added to the Selected groupings column.

Click on the Apply button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/50aaaacc-bcad-4057-a714-5594fb9bd563/user_cropped_screenshot.jpeg?tl_px=410,225&br_px=2704,1507&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=670,399)


14\. The report now shows a heading for the Queue (this was the default) Agent and Routing Profile with some data for review.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/a249dd6b-b7e6-4515-9656-74d10934398e/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2704,1514&force_format=jpeg&q=100&width=1120.0)


#### Apply Filters to Historical Queue Report


15\. Filters are used to narrow down the data shown in the report. Filtering options include the following:

- **Queue**—Includes data only for the specified queues. If you don't specify any queues, data for all queues are included.

- **Routing profile**—Includes data only for the agents assigned to the specified routing profiles. If you don't specify any routing profiles, data for all agents for all routing profiles is included.

- **Agent hierarchy**—Includes data only for the contacts handled by agents in the specified hierarchies. If you don't specify a hierarchy, data for all contacts handled by agents in all hierarchies is included. When only one hierarchy is specified, you can specify a more granular filter within the hierarchy.

- **Phone number**—Includes data only for the contacts associated with the specified phone numbers. If you don't specify a phone number, data for all contacts associated with all phone numbers is included.

- **Channel**—Includes data only for the specified channels. If you don't specify any channels, data for all channels are included.

- **Subtype**—Includes data only for the specified subtypes. If you don’t specify any subtypes, data for all subtypes are included.

- **Amazon Q**—Includes data only for the specified Amazon Q status. If you don’t specify any Amazon Q status, data for all statuses are included.

*Note: **Agent Queues**—Includes data only for the specified agent queues. If you don’t specify any agent queues, data for all agent queues are included. This option is only available when the **show agent queues** checkbox is selected. (Which is not in this demo)*


16\. Click on the settings icon again to find the filter options.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/8b445da2-e5cb-4c28-b4de-20e292b60eef/user_cropped_screenshot.jpeg?tl_px=410,0&br_px=2704,1281&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1031,203)


17\. Click on the Filters tab to see Filter options.

In this demo, Routing Profiles filter is selected

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/04e7b5a6-1c7b-4aef-b20c-3e3241d96d26/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2293,1281&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=431,248)


18\. In the Search area, start typing the profile or click the search field to show the options.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/c88c5ab1-b9ad-4514-b5ce-4786ea1923eb/user_cropped_screenshot.jpeg?tl_px=698,314&br_px=2418,1275&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=524,276)


19\. From the options shown, select the option(s) that you want to filter by. 

This demo is filtering based on the Billing routing profile.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/310ed242-7ecd-4eb1-a9be-9284818fc50d/user_cropped_screenshot.jpeg?tl_px=498,469&br_px=2218,1430&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=524,276)


20\. Click Apply.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/5eab3b41-9214-47ac-b0e1-1e8609d14bae/user_cropped_screenshot.jpeg?tl_px=984,545&br_px=2704,1507&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=553,341)


21\. After you have viewed the results, you can edit your filters as needed by accessing the settings again.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/9c844a86-b1bc-4558-b6bd-5cc9002e2731/user_cropped_screenshot.jpeg?tl_px=410,0&br_px=2704,1281&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1022,207)


22\. Select the Filters tab and the and the filter category so you can remove or add filters as needed.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/312c1ae0-e3a3-4db1-a7a9-7664d04d7391/user_cropped_screenshot.jpeg?tl_px=179,219&br_px=2472,1500&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=524,277)


23\. Click Apply to save the updated settings.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/3bf0cae0-cf1f-475d-8497-b0860b59c9ec/user_cropped_screenshot.jpeg?tl_px=984,548&br_px=2704,1510&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=554,336)


#### Customizing Metrics Settings


24\. The Metrics tab allows you to customize the metrics and fields to be included in the report.

Contact metrics are grouped in the following categories:

- Agent
- Contacts Abandoned
- Contacts Resolved
- Contacts Answered
- Contact Service Level
- Performance

Each grouping has granular metrics that can be selected based on needed report.

*Note: An explanation point (!) is displayed next to metrics that are not available based on groupings.*


25\. To access the Metrics, open the settings.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/56688883-1b3e-43b7-87f9-416e89582b31/user_cropped_screenshot.jpeg?tl_px=984,20&br_px=2704,981&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=1009,277)


26\. Select the Metrics tab

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/beadeb94-1ae5-4bbe-9099-70fa254630ef/user_cropped_screenshot.jpeg?tl_px=410,0&br_px=2704,1281&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=561,74)


27\. Each grouping has metric options that you can select at a granular level.

Select the desired metric(s) in the group(s) and de-select those to remove.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/a81e26a6-111a-4a84-81e8-82920f9efbbc/user_cropped_screenshot.jpeg?tl_px=201,115&br_px=2494,1396&force_format=jpeg&q=100&width=1120.0)


28\. With the desired metric(s) selected, click Apply.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/f9076d01-5e3c-4ff6-81e6-4e8197b90fc3/user_cropped_screenshot.jpeg?tl_px=409,232&br_px=2703,1514&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=672,407)


29\. The table is updated to include the metrics (columns) based on options selected.  Metrics can be sorted in ascending or descending order by clicking on the arrow in the heading.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/14f09d2c-5893-4e1e-a538-a62bd9dd6617/user_cropped_screenshot.jpeg?tl_px=858,117&br_px=2578,1078&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=524,277)


#### Saving a Report


30\. With your report customized based on your needs, it is time to save the report.

Click on the Save report button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/6576ff01-4431-44a1-95af-34b6be02eb73/user_cropped_screenshot.jpeg?tl_px=390,0&br_px=2684,1281&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=996,117)


31\. Name the report that is descriptive so you can easily locate or understand the data that is collected in the report.

Click on the Save as button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/594e6241-08ad-4814-a1d8-8c56b5ba203c/user_cropped_screenshot.jpeg?tl_px=410,63&br_px=2704,1344&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=662,277)


32\. Your report now displays its new name.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/73841827-511d-4649-9c5c-1d645061afed/user_cropped_screenshot.jpeg?tl_px=203,116&br_px=2496,1397&force_format=jpeg&q=100&width=1120.0)


#### Report Actions


33\. The Actions drop down on the right side of the screen has the following options:

- Save as
- Download CSV
- Share report
- Schedule

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/a6d718f7-c76c-4c1b-9b5f-5c4e3a95677a/user_cropped_screenshot.jpeg?tl_px=968,0&br_px=2688,961&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=877,158)


34\. The Save as button allows you to save the same report as a different name without impacting the originally named report. (Similar to when you use Save as in Microsoft Office products).

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/de703aed-562b-4504-9fe6-b7604c48f0aa/user_cropped_screenshot.jpeg?tl_px=492,274&br_px=2212,1235&force_format=jpeg&q=100&width=1120.0)


35\. The report can also be saved in a CSV or spreadsheet to allow you to work with and view the report results with the versatility provided in the spreadsheet software.

This is done by clicking on the Actions dropdown.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/c7629684-03f5-4b5a-b2f7-521e880b730d/user_cropped_screenshot.jpeg?tl_px=984,0&br_px=2704,961&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=878,159)


36\. Click "Download CSV" to download the file to your local computer (not shown).

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/0fb90955-fc6c-4726-944b-53d7b0373227/user_cropped_screenshot.jpeg?tl_px=984,0&br_px=2704,961&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=836,247)


#### Sharing Reports


37\. To share reports to individuals or within an organization, start by clicking the Actions button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/16c3254d-4495-4255-ac3d-7718390eddec/user_cropped_screenshot.jpeg?tl_px=984,0&br_px=2704,961&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=874,169)


38\. Click "Share report"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/d3a958d9-1e30-415f-a1fa-9664f25a3064/user_cropped_screenshot.jpeg?tl_px=984,29&br_px=2704,990&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=820,277)


39\. One option to share a report is to copy the link address by selecting the **Copy link address** and then the Save button to save the link to your clipboard. Share as appropriate. Individuals with the link and appropriate permissions settings will be able to access it.

*Note: You do not need to publish the report to share the link.*

Learn more at <https://docs.aws.amazon.com/connect/latest/adminguide/share-reports.html>

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/4a7c5e77-eb0f-4526-af8d-bfe0cff350a2/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2293,1281&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=408,229)


40\. To share the report with everyone in an organization who has appropriate permissions, select the Publish toggle switch and click on the Save button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/c0a3c426-a8e4-433c-a209-78dd36bc72ce/user_cropped_screenshot.jpeg?tl_px=0,43&br_px=2293,1324&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=425,277)


41\. A notification appears stating that the report has been shared successfully.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/a7a6e632-233c-4fee-beb0-098b6f9d9efa/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2704,1512&force_format=jpeg&q=100&width=1120.0)


#### Scheduling a Report


42\. Reports can be scheduled to run at pre-determined intervals. This automation can streamline the process of analyzing report metrics.


43\. To schedule a report, begin by selecting the Actions drop down and select Schedule

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/57c23f2c-763b-43cf-8e2f-a53c399a7b6f/user_cropped_screenshot.jpeg?tl_px=984,113&br_px=2704,1074&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=798,276)


44\. A notification appears about scheduling the report. This is a reminder that scheduled reports are visible by all individuals in your organizations that have the proper permissions to access.

Click **Continue**.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/2333df3b-e601-43f7-9f66-a3136d69bd78/user_cropped_screenshot.jpeg?tl_px=974,219&br_px=2694,1180&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=523,277)


45\. There are two tabs to allow you to customize how the report is scheduled. 

You can update the schedule based on Recurrence which sets how often the report is ran.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/17be264a-c56e-4429-b924-8844d9670539/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1719,961&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=220,268)


46\. The Delivery Options tab provides information on the location and file name. 

This demo is leaving both tabs at default and clicking on Create to create a scheduled report.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/6ded3ae0-77f5-416c-be43-57ab9a10d9c8/user_cropped_screenshot.jpeg?tl_px=0,230&br_px=2293,1512&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=86,477)


47\. The report schedule parameters are displayed. You can edit or delete the schedule as necessary by selecting the Edit and Delete button respectively.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/57e84eb1-dbc7-4075-abad-3fc475d67af6/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=2704,1512&force_format=jpeg&q=100&width=1120.0)


48\. Click "Historical_ContactMetrics_AgentRoutingProfiles" to go back to the dashboard.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2024-09-18/0543fcc2-bed1-48b0-87e2-9fa0f7e87b45/user_cropped_screenshot.jpeg?tl_px=14,0&br_px=1734,961&force_format=jpeg&q=100&width=1120.0&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=524,211)


49\. Amazon Connect Historical Reports provide a powerful tool for analyzing contact center performance over time. These reports offer detailed insights into various metrics related to queues, agents, and customer interactions.

**Key features include:**

**Customizable metrics:** Users can select from a wide range of metrics categories including agent performance, contact handling, and service levels

**Flexible grouping options:** Data can be organized by queue, agent, routing profile, and other parameters

**Filtering capabilities:** Reports can be narrowed down using filters for queues, routing profiles, agent hierarchies, and more

**Time range selection:** Users can specify intervals and date ranges for data aggregation

**Sharing and scheduling:** Reports can be easily shared with team members and scheduled for automatic generation


#### Troubleshooting Tips


50\. **Metric discrepancies:**

- Ensure the time zone settings are correct for accurate data representation


- Verify that filters are not inadvertently excluding relevant data

**Missing data:**

- Check if the selected time range covers the desired period


- Confirm that all necessary queues and routing profiles are included in the report settings

**Performance issues:**

- For large datasets, consider using smaller time intervals or fewer groupings to improve report generation speed
- Utilize the CSV download option for offline analysis of extensive data

**Access problems:**

- Verify that users have the appropriate permissions to view and edit reports


- Ensure shared report links are accessible to intended recipients

**Report customization issues:**

- If certain metrics are unavailable (indicated by an exclamation mark), review the selected groupings for compatibility
#### [Made with Scribe](https://scribehow.com/shared/Creating_and_Customizing_Historical_Queue_Contacts_Reports__IlJ8db5_S6ax4GE0R74Hwg)


