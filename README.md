# AI-for-Social-Good-Capstone

This repository contains our Carnegie Mellon Heinz College capstone project with KM Strategies Group: an AI-assisted donor-matching tool designed to help small nonprofits in Pennsylvania identify suitable foundation funders using public IRS Form 990 data.

## Project Overview

Small nonprofits often face capacity constraints when searching for institutional funders. Existing prospecting tools can be expensive or opaque in how they recommend funders. This project addresses that gap by developing a prototype decision-support tool that generates ranked recommendations for funders based on publicly available grant history.

The tool focuses on Pennsylvania-based foundations with annual giving above approximately $1 million and uses historical grant data to match nonprofits with funders based on thematic relevance, geographic alignment, and grant-size fit.

## Live tool

- https://nonprofit-funder-discovery.vercel.app/ 

## Key Features

- Cleaned and structured IRS Form 990 grant-level data
- Aggregated funder profiles for Pennsylvania foundations
- Matching logic based on:
  - Mission and issue-area similarity
  - Geographic fit
  - Historical grant-size alignment
- Evidence-backed funder recommendations
- Natural-language explanations generated through a RAG-style workflow
- Responsible AI and governance framework for nonprofit-facing use

## Data Sources

- IRS Exempt Organizations Business Master File
- IRS Form 990 XML filings
- ProPublica Nonprofit API
- Pennsylvania nonprofit reference data

## Methods

The project pipeline includes:

1. Identifying qualified Pennsylvania funders
2. Extracting Schedule I grant records from IRS Form 990 filings
3. Cleaning and standardizing funder, recipient, location, and grant fields
4. Creating grant-level and funder-level datasets
5. Building a recommendation engine using text similarity, geography, and grant-size scoring
6. Generating transparent explanations grounded in historical grant evidence

## Outputs

- Cleaned grant-level dataset
- Aggregated funder profile dataset
- Prototype donor matching logic
- Ethics and governance framework
- Final capstone report

## Limitations

The prototype is designed as a donor discovery and decision-support tool, not a model that predicts funding success. It is currently limited to Pennsylvania foundations and relies on the quality of publicly available IRS Form 990 data.

## Skills Demonstrated

Python · Data Cleaning · IRS Form 990 Data · ETL Pipelines · Recommendation Systems · RAG · TF-IDF Similarity · Public Interest Technology · Responsible AI · Nonprofit Strategy · Product Design

## Project Team

Chengyi Cai, Chloe Huang, Jhanavi Sankar, Shiyu Liu, and Zoe Iseri  
Carnegie Mellon University, Heinz College  
Capstone Project with KM Strategies Group, May 2026
