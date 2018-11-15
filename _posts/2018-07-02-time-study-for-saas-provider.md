---
title: Time Study for a SaaS Provider
date: 2018-07-02
tags: [technical writing]
mathjax:  "true"
---

The purpose of this report was to measure the time spent releasing records using [legacy printer solution], and establish a baseline to compare to future technologies.

The workflow for using [legacy printer] is comprised of a series of 5 tasks:
  - Document selection
  - Printing
  - Scanning
  - Quality control
  - Uploading

<h3>Document selection:</h3>
  - Look up the patient in the [EMR] using their [EMR] ID
  - Filter the chart as needed
  - Compile records


<h3>Printing:</h3>
  - Save records to a file on the virtual desktop
  - Navigate to that directory, open the files, then print them

<h3>Scanning</h3>
  - Scan and grab the tiff files to pull them into the [proprietary feature] interface


<h3>QC’ing:</h3>
  - Review the documents for compliance


<h3>Uploading</h3>
  - Accept and upload the records to [vendor platform]

<h3>Summary:</h3>
3 tasks account for most of the time spent in the [legacy printer] workflow
  - Document selection
  - Document quality control
  - Document uploading

Document selection and quality control are high variance. They are affected by the limitations of the EMRs of each client. Document uploading is a fixed cost. The only variable to account for is [vendor]'s servers. Therefore, the [new sync architecture], which bypasses the upload altogether, is approx. x% faster:

```
Where x = time spent uploading  ÷ length of shift x 100

```
