# Job-Description-and-CV-Similarity-Checker

This is an interactive R Shiny web application designed to help job seekers quickly evaluate how well their CV aligns with a specific job description using text similarity analysis.

## Overview
The app takes a job description and a CV (resume) as plain text inputs and computes a cosine similarity score between the two, based on term frequency. This score reflects how semantically similar the texts are, helping users identify how closely their resume matches the requirements of a particular role.

## Features
- Real-time Text Comparison: Users can paste any job description and CV directly into the app.

- Cosine Similarity Score: Calculates and displays a similarity percentage between the two texts.

- Text Preprocessing: Uses the tm and text2vec libraries for cleaning and vectorizing input text (lowercasing, punctuation/stopword removal, etc.).

- Interactive UI: Clean, user-friendly interface built with R Shiny.

## How It Works
- Both inputs are cleaned and tokenized.

- A Document-Term Matrix (DTM) is created.

- Cosine similarity is calculated using the proxy package.

- The result is shown as a percentage indicating how similar the CV is to the job description.

## Tools
- R

- shiny – for web app interface

- tm – for text preprocessing

- text2vec – for text vectorization

- proxy – for cosine similarity computation

## Live App
 Launch the App: https://akinbusola.shinyapps.io/doc_compare/
(Deployed on shinyapps.io — no login required)

## Use Cases
- Resume tailoring for job applications

- ATS (Applicant Tracking System) optimization

- Career services demo tools
