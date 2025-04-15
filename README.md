# skill-vector-analysis

Code for analyzing skill mismatches in the U.S. labor market using vector-based representations of skills.

## Overview

This repository implements the methodology from "Bridging the Divide: Vector-Based Analysis of Skill Gaps in America's Evolving Labor Market." The approach uses Word2Vec embeddings to represent skills in a high-dimensional space, measuring alignment between skills demanded in job advertisements and those supplied in worker resumes.

## Data
This repository does not include the data used in the original research, which came from Revelio Labs and is subject to proprietary restrictions. The code expects parquet files for users, skills, job postings, positions, and education records.

## Key Features

Vector-based skill representation using Word2Vec
Job-skill mapping with specificity metrics
Analysis of skill trends by time, demographics, and industry
Visualization of skill relationships
