# UPI Transaction Analysis in Excel

A guided Excel portfolio project exploring UPI transaction data with PivotTables, charts and interactive slicers.

Built by following the [UPI Analysis Dashboard tutorial](https://www.youtube.com/watch?v=NtZTxn0xu7E) from [Data Tutorials](https://www.youtube.com/@datatutorials1). The tutorial, dataset and dashboard design guidance are credited to the channel. This repository documents my hands-on implementation and Excel practice.

## Project overview

This workbook brings transaction-level data and Excel summaries together to explore UPI payment activity. The dataset includes multiple payment apps, so the project covers UPI transactions rather than only PhonePe.

## Tools and features

- Microsoft Excel
- PivotTables and charts
- Slicers for city, gender, merchant category and merchant name
- Transaction attributes covering payment amounts, cashback, status, failure reasons and risk indicators

## Data covered

The source worksheet, `raw_data_upi`, includes transaction date and time, UPI app, age group, gender, state, city, merchant category, payment mode, bank, amount in INR, cashback, transaction fee, status and risk indicators.

## Download the project files

[Download the Excel workbook from the latest release](https://github.com/alston2375/upi-transaction-analysis-excel/releases/latest)

1. Open the latest release and expand **Assets**.
2. Download `UPI_Transaction_Analysis.xlsx` for the analysis and dashboard.
3. Download `phonepay_raw_data.xlsx` for the original input dataset.
4. The automatically generated source-code ZIP does not contain these Excel attachments.
5. Open the files in desktop Microsoft Excel.
6. Explore the analysis sheets and use the available slicers to filter the views.

The full workbook is approximately 100 MB and is provided as a release attachment because it exceeds GitHub's browser limit for individual repository-file uploads.

## Dataset source and tutorial credit

- Tutorial: [Excel Dashboard Project — Build a Professional UPI Analysis Dashboard (2026)](https://www.youtube.com/watch?v=NtZTxn0xu7E)
- Channel: [Data Tutorials](https://www.youtube.com/@datatutorials1)
- Dataset: [Original download folder linked in the video description](https://drive.google.com/drive/folders/1SxSmd7fFdMOBzcyyZHZmId0gAZg-atI6?usp=sharing)

The input workbook is `phonepay_raw_data.xlsx`, with a source worksheet named `data`. The dataset was obtained from the tutorial resources. It has not been independently verified as real or synthetic, and it is not presented here as official PhonePe data.

The video description provides a download link but does not state explicit redistribution terms. This private repository is being reviewed before public sharing.

## Scope

This is an independent learning and portfolio project. It is not affiliated with PhonePe or other payment providers represented in the dataset.
