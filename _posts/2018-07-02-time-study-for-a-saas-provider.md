---
title: Time Study for a SaaS Provider
date: 2018-07-02
tags: [technical writing]
mathjax:  "true"
---

<h1>Introduction:</h1>
The purpose of this report was to measure the time spent releasing records using [legacy printer solution], and establish a baseline to compare to future technologies. The report has been stripped of substantive detail and reduced to high level steps.

The workflow for using [legacy printer] is comprised of a series of 5 tasks:
  - Document selection
  - Printing
  - Scanning
  - Quality control
  - Uploading

<h3>Document selection:</h3>
  - Look up the patient in the [EMR] using their primary demographic information
  - Open the electronic chart module
  - Filter the patient's data
  - Compile the necessary records

<h3>Printing:</h3>
  - Print the records to the designated directory on your virtual desktop using [legacy printer]

<h3>Scanning</h3>
  - Scan and grab the tiff files to pull them into the [proprietary feature] interface

<h3>QC’ing:</h3>
  - Review the documents for compliance

<h3>Uploading</h3>
  - Accept and upload the records to [vendor server]

<h3>Summary:</h3>
3 tasks account for most of the time spent in the [legacy printer] workflow
  - Document selection
  - Document quality control
  - Document uploading

Document selection and quality control are high variance. They are affected by the limitations of the EMRs of each client. Document uploading is a fixed cost. The only variable to account for is [vendor]'s servers. Therefore, the [new sync architecture], which bypasses the upload altogether, is approx. x% faster:

```
Where x = time spent uploading  ÷ length of shift x 100

```
