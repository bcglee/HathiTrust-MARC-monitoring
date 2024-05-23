# HathiTrust-MARC-monitoring

## Overview

This repo contains the code for the [2024 HathiTrust TorchLite hackathon](https://htrc.github.io/torchlite-hackathon/) project by:

- [Daniel Evans](https://danieljohnevans.github.io/)
- [Deepanshu Malhorta](https://deepanshu96.github.io/deep/)
- [Ben Lee](https://bcglee.com)
- [Sarah Griebel](https://griebels.github.io/)
- [Ryan Dubnicek](https://ischool.illinois.edu/people/ryan-dubnicek)

## Goals

The primary goals of this hackathon project are 1) to develop Python code for monitoring updates to MARC records in HathiTrust, and 2) to build an exploratory notebook to enable quick monitoring of this.

## Data

We are using the HathiTrust Bibliographic API: [https://www.hathitrust.org/member-libraries/resources-for-librarians/data-resources/bibliographic-api/](https://www.hathitrust.org/member-libraries/resources-for-librarians/data-resources/bibliographic-api/). In particular, we are pulling from the `974` field and the DAT field to get information surrounding udpates. We are also adding metadata from the HathiFiles. Each API request can handle 20 items at once. This results in a CSV - the next step would be to automate this process.

## Code

### Back-end preprocessing

Our back-end preprocessing script is a Jupyter notebook.

## Front-end visualizations

Our initial visualizations are in an Observable notebook, which can be found here: [observablehq.com/d/ec917e4cc67cba47](observablehq.com/d/ec917e4cc67cba47). This notebook consumes the CSV from the pre-processing script.
