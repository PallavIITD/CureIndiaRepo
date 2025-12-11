# CureIndiaRepo
Project Overview

This repository was developed for Cure India NGO as part of my internship under the Social Sector Attachment (SSA) Program, DMS IIT Delhi. The objective of this project was to build an end-to-end data-driven clinic expansion and optimization framework to support strategic decision-making for clubfoot treatment centers across India.

# Technical Scope

The project involves designing a suite of Python-based geospatial, statistical, and operations-research optimization pipelines, including:
Data Engineering & Preprocessing
Cleaning, merging, and normalizing multi-source datasets using pandas and numpy
Spatial joins and administrative boundary mapping using geopandas
Automated generation of interactive maps via folium
Geospatial Demand Modelling
District-level and state-level incidence estimation
Hotspot detection using natural breaks (Jenks), clustering, and spatial autocorrelation techniques
Travel-distance surface estimation for accessibility modelling
Operations Research & Optimization Models
Facility Location Models (p-median, p-center, capacitated variants)
Distance minimization algorithms to reduce maximum and average patient travel cost
Scenario-based optimization under budget, resource, and capacity constraints
Implemented using OR-Tools, PuLP, and scipy.optimize
Forecasting & Prioritization
Forecasting expected clubfoot case loads using statistical and regression models
Multi-criteria prioritization for state/district rollout plans
Phase-wise expansion design using clustering + Jenks optimization
Outcomes
The system provides:
Optimal recommendations on where, when, and how Cure India should expand its clinic network
Accessibility metrics to identify high-burden underserved regions
Automated map-based visual outputs for presentations and stakeholder communication
Scalable pipeline architecture enabling easy scenario testing and future updates
✔ Section-wise breakdown (Installation, Usage, Pipeline Flow)
✔ A more formal r
