
# PIFamr

## Overview

This repository contains the research and development work of the
project **“A Prototype European Database for Monitoring Antimicrobial
Resistance (AMR) in the Food Chain.”** This project is part of the
Pathogens-in-Foods (PIF) initiative, funded by EFSA, and is focused on
addressing the global challenge of antimicrobial resistance by creating
an integrated surveillance system that adheres to the One Health
approach.

## Background

Antimicrobial resistance (AMR) is recognized by the World Health
Organization as one of the top public health threats. Misuse of
antibiotics across human health, veterinary practices, agriculture, and
environmental management has led to the emergence of resistant bacteria,
posing severe risks to global health. The goal of this project is to
develop a robust and scalable database that centralizes AMR data from
the food chain, thereby supporting enhanced monitoring and
evidence-based decision-making.

## Objectives

The primary objectives of this project include:

- **Literature and Technology Review:**  
  Evaluate state-of-the-art database models (both SQL and NoSQL) and
  identify gaps in AMR data reporting in the food chain.

- **Database Design and Implementation:**  
  Design a flexible, scalable database prototype using MongoDB and
  integrate it with graph-based solutions (e.g., Neo4j) to store and
  analyze AMR occurrence data.

- **Automated Data Pipelines:**  
  Develop Python-based pipelines to automate the extraction, processing,
  and integration of cross-sectional AMR data from scientific
  publications and other sources.

- **System Integration:**  
  Connect the newly developed database to an existing front-end to
  facilitate easy visualization and analysis of surveillance data.

- **Thesis Documentation:**  
  Document the entire research process and findings.

## Project Structure

The repository is organized as follows:

- **/data**  
  Contains sample datasets and processed files used during the project.

- **/scripts**  
  Includes Python scripts for ETL (Extract, Transform, Load) pipelines,
  database connectivity (using PyMongo and Py2neo), and other automation
  tasks.

- **/database**  
  Documentation of the database schemas, design decisions, and
  configurations for MongoDB and Neo4j.

- **/docs**  
  Research notes, literature review summaries, and drafts of the
  pre-thesis document.

- **README.Rmd**  
  This file provides an overview of the project, objectives, and
  repository organization.

## How to Use

1.  **Clone the Repository:**

``` bash
   git clone https://github.com/fsqanalytics/PIFamr.git
```
