IBDPredict

Gut Microbiome-Based IBD Detection and Disease Classification

IBDPredict is a machine learning framework that uses gut microbiome data to identify whether an individual is healthy or affected by disease, and further classifies the specific disease among individuals identified as diseased.

🔬 Prediction Pipeline

The project follows a two-stage classification approach:

Gut Microbiome Data
        ↓
Stage 1: Healthy vs Disease
        ↓
   ┌────┴────┐
Healthy    Disease
             ↓
      Stage 2: Disease Classification
             ↓
     Specific IBD Disease

Stage 1 — Healthy vs Disease

The first stage performs binary classification to distinguish healthy individuals from individuals affected by disease based on their gut microbiome profiles.

Stage 2 — Disease Classification

For individuals identified as diseased, the second stage performs multi-class classification to determine the specific disease type.

The focus is on distinguishing different IBD-related disease categories using microbiome features.

🎯 Objective

The objective of IBDPredict is to investigate whether gut microbiome composition can be used as a predictive signal for identifying disease status and distinguishing between different IBD conditions.

🧬 Key Components

Gut microbiome-based classification

Healthy vs disease detection

Disease-specific classification

Feature preprocessing and selection

Machine learning model comparison

Model evaluation and performance analysis
