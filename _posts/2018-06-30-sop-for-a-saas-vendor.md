---
title: SOP for a SaaS Provider
date: 2018-06-30
tags: [technical writing]
---

The purpose of this document was to simplify procedural documentation for a release of information vendor. The document was part of an ongoing effort to improve operational efficiency. The administrators who referenced this document increased their productivity. This improved the turnaround time for the average request for medical records and positively impacted KPIs. The contents have been modified to omit propriety information.

<style>
#toc_container {
    background: #f9f9f9 none repeat scroll 0 0;
    border: 1px solid #aaa;
    border-radius:  5px;
    display: table;
    font-size: 75%;
    margin-bottom: 1em;
    padding: 5px;
    width: auto;
    align:  right;
}

.toc_title {
    font-weight: 700;
    text-align: center;
    margin-top: 0em;
}

#toc_container li, #toc_container ul, #toc_container ul li{
    list-style: outside none none !important;
}
  .main {
    background-color: lightblue;
}
  .notice {
    background-color: rgb(252,248,227);
}
  .warning  {
    background-color: rgb(248,215,218);
  }
</style>



<div id="toc_container">
<p class="toc_title">Contents</p>
<ul class="toc_list">
<li><a href="#First_Point_Header"> How to Release Medical Records</a></li>
<li><a href="#Second_Point_Header">Step 1: Access Your Client's Virtual Desktop</a></li>
<li><a href="#Third_Point_Header">Step 2: Configure Your Printer</a></li>
<li><a href="#Fourth_Point_Header">Step 3: Open EMRs</a></li>
<li><a href="#Fifth_Point_Header">Step 4: Start a Release</a></li>
<li><a href="#Sixth_Point_Header">Step 5: Confirm the Patient </a></li>
<li><a href="#Seventh_Point_Header">Step 6: Verify the Request</a></li>
<li><a href="#Eigth_Point_Header">Step 7: Compile Records</a></li>
<li><a href="#Ninth_Point_Header">Step 8: Upload Records</a></li>
<li><a href="#Tenth_Point_Header">Step 9: Quality Control</a></li>
<li><a href="#Eleventh_Point_Header">Step 10: Release the Records</a></li>
<br>
<li><a href="#Twelfth_Point_Header">How to Release Bills</a></li>
<li><a href="#Thirteenth_Point_Header"> Step 1: Configure Vision</a></li>
<li><a href="#Fourteenth_Point_Header"> Step 2: Confirm the Patient</a></li>
<li><a href="#Fifteenth_Point_Header"> Step 3: Filter and Print</a></li>
<br>
<li><a href="#Sixteenth_Point_Header">FAQ: Worker's Compensation and Patient-Directed</a></li>
</ul>
</div>

&nbsp;


<h1 id="First_Point_Header"> How to Release Medical Records</h1>


<h3 id="Second_Point_Header">Step 1: Access Your Client's Virtual Desktop</h3>
  - Open Internet Explorer
  - Type the following url into the address bar:
  - Click on _Applications_
  - Log in with your network credentials
  <p class="notice">
  <strong>Note:</strong> This is not the same as your [vendor platform] credentials
  </p>
  - Select the desktop tab, then click  _RI Desktop_

&nbsp;

<h3 id="Third_Point_Header">Step 2: Configure Your Printer</h3>
  - On your remote desktop, click start
  - Search for _Devices and Printers_
  - Right click the [proprietary] printer and set it as the default printer

&nbsp;

<h3 id="Fourth_Point_Header">Step 3: Open EMRs</h3>
  - [Client Name] uses 5 EMRs. They each serve a different purpose. Reference the list below (omitted) to help you locate (a) the correct type of records, and (b) for the correct dates that you need to pull.

&nbsp;

<h3 id="Fifth_Point_Header">Step 4: Start a Release</h3>
  - Log in to [client name].[subdomain].com
  - Under _ROI requests_, select _Documents Required_
  - Find a request that does not have a name in the _Processing User_ column
  - Select the check box next to _Request ID_
  - Choose your name from the _Processing User_ drop-down list
  - Press _Set Selected with Processing User_ to claim the request for yourself


&nbsp;

<h3 id="Sixth_Point_Header">Step 5: Confirm the Patient</h3>
  - Search for the patient in [primary EMR]
  - Confirm that you found the correct patient by using at least two means of identification
  - Leave an internal note in the request in [vendor platform] stating the two identifiers that you used to confirm the patient

&nbsp;

<h3 id="Seventh_Point_Header">Step 6: Verify the Request</h3>
  - Double-check the request documents for compliance
  - Verify the type of records and dates of service to be released
  - Create one component for each EMR you will be copying records from
  - Name the component by the abbreviation of the EMR, followed by the dates of service being requested

&nbsp;

<h3 id="Eigth_Point_Header">Step 7: Compile Records</h3>
  - Search the patient’s electronic chart for the correct records for the correct dates of service
  - Print the records that you need, using your [proprietary] virtual printer
  - If any records are missing from the patient’s chart, follow these steps to retrieve them:
    -   Under the _Request Status_ screen in [vendor platform], place the request on hold for the _pending_ reason code
    -   Leave an internal note, stating ‘Missing [Date] [Name of record]’ (e.g. Missing 1/1/2017 OP report)
    -   Set the _Processing User_ to [Client Name]
    -   Monitor the _On-Hold_ list daily for requests that are no longer assigned to a user
    -   Verify if [Client Name] successfully retrieved the missing record
    -   If the record has been returned, print it, then add it to the request in [vendor platform] and take it off hold to complete the release
    -   If the record is still missing, leave an internal note, stating, ‘Still missing [Date] [Name of record], then set the _Processing User_ back to [Client Name]

&nbsp;

<h3 id="Ninth_Point_Header">Step 8: Upload Records</h3>
  - Merge all the files that you printed with [proprietary printer] into a single PDF, using PDFCreator
  - Save the PDF to the W: drive (this should be mapped to [Vendor Name]’s network)
  - Move onto the other requests that you claimed, and repeat the above workflow until all records for all the requests that you are processing have been uploaded to [vendor platform]

&nbsp;

<h3 id="Tenth_Point_Header">Step 9: Quality Control</h3>
  - Review all medical records for all the requests that you processed
  - Ensure each request only has the correct records for the correct dates of service


&nbsp;

<h3 id="Eleventh_Point_Header">Step 10: Release the Records</h3>
  - Release the request in [vendor platform] once you ensured complete accuracy and compliance

    <p class="warning">
    <strong>Warning!</strong> Once you hit release, the records will be processed for distribution. Do you wish to proceed?
    </p>


&nbsp;



<h1 id="Twelfth_Point_Header"> How to Release Bills</h1>


<h3 id="Thirteenth_Point_Header">Step 1: Configure [Billing System]</h3>
 - 	Log in to [Billing System]
 - 	Select the _Inquiry_ tab in the first toolbar across the top of the screen
 - 	Click _Activity_ in the space between the first toolbar
 - 	Search for _Job Server Status_, then double click it to add it to the second toolbar across the top of the screen—this is where bills print to
 - 	Select _Financial History_—this is where you will select which bills to print

&nbsp;

<h3 id="Fourteenth_Point_Header">Step 2: Confirm the Patient</h3>
 - 	Click the patient icon, and search for the patient that you need—note, patient # is the patient’s MRN

&nbsp;

 <h3 id="Fifteenth_Point_Header">Step 3: Filter and Print</h3>
 - 	In _Financial History_, find the bills that you need—note, yellow cells in the Inv # column are the charges for encounters associated with dates of service, and the Dr. column will tell you the name of the doctor who provided the treatment, or who supervised the PA who did
 - 	Once you know which bills you need, right click anywhere, and click ledger
 - 	Under _Selection Parameters_, choose Inv #
 - 	Under _Operator_, choose the symbol for the date range you need
 - 	In the _Values_ field, enter the criteria, then click add
 - 	Click _Print & Close_
 - 	In the _Saved Filename_ field, enter a placeholder name, then OK
 - 	Select _Job Server Status_
 - 	Right click the bill that you just printed, then click view
 - 	Copy the text from the document that pops up, and paste it into a Word document
 - 	In that Word document, once you set up the billing macro, format the bill
 - 	Print the bill, then add it to the request in [vendor platform]

&nbsp;



<h1 id="Sixteenth_Point_Header">FAQ: Worker's Compensation and Patient-Directed</h1>


<h3 class="test">Does a patient-directed request for medical records need to be accompanied with a HIPAA-compliant authorization?</h3>

No. Patients may request copies of their medical records and choose who to send them to at their discretion. It would be an inconvenience to patients if their requests needed to contain the legal jargon otherwise required for third party requestors.

<h3>Does a patient-directed request for medical records need to be signed?</h3>
Yes. the patient's signature confirms their consent to disclose their records to a third party. This serves to protect them against unlawful disclosures to imposters.

<h3>Do worker’s compensation subpoenas need proof of notification?</h3>
No. But only if the requester (opposing counsel) is seeking records from the date of the work-related injury forward. They are not entitled to the patient's medical history beyond that scope.

<h3>What do we do with subpoenas that are signed by a judge?</h3>
If a judge signs a subpoena, it's a court order. Court orders do not need to be accompanied with proof of notification

<h3>Do subpoenas need an accompanying authorization?</h3>
No. Not in Pennsylvania. But it varies by state.

<h3>What states does [Client Name] accept subpoenas from?</h3>
Pennsylvania, New Jersey, and Delaware. Courts from any other state do not have jurisdiction and cannot compel [Client Name] to produce records

---
