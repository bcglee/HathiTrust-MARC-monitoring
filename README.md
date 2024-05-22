# HathiTrust-MARC-monitoring

## Overview

This repo contains the code for the [2024 HathiTrust TorchLite hackathon](https://htrc.github.io/torchlite-hackathon/) project by:

- [Daniel Evans](https://danieljohnevans.github.io/)
- [Deepanshu Malhorta](https://deepanshu96.github.io/deep/)
- [Ben Lee](https://bcglee.com)
- [Sarah Griebel](https://griebels.github.io/)
- [Ryan Dubnicek](https://ischool.illinois.edu/people/ryan-dubnicek)

## Goals

The primary goals of this hackathon project are 1) to develop Python code for monitoring updates to MARC records in HathiTrust, and 2) to build a widget to enable quick monitoring of this.

## Data

We are using the Hathifiles bulk download available here: [https://www.hathitrust.org/member-libraries/resources-for-librarians/data-resources/hathifiles/](https://www.hathitrust.org/member-libraries/resources-for-librarians/data-resources/hathifiles/). The bulk file contains "\_full\_" in the filename and is updated on a monthly basis (for refernce, the [May 2024](https://www.hathitrust.org/files/hathifiles/hathi_full_20240501.txt.gz) file is 1.08 GB).

Within Hathifiles are the MARC records of interest for this hackathon.
