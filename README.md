#  Real-Time Bike Demand & Risk Platform

## Overview

A production-oriented data platform designed to monitor, analyze, and predict bike station demand and operational risk in real time.

The system integrates batch and streaming pipelines with machine learning models to simulate a real-world data engineering and ML workflow.

---

## Problem Statement

Bike-sharing systems frequently face supply–demand imbalance:

* Stations become empty, preventing users from renting bikes
* Stations become full, preventing users from returning bikes

This project addresses these challenges by:

* forecasting station-level demand
* identifying high-risk stations (empty/full)
* enabling real-time system visibility

---

## Scope

The platform is designed to cover the full data lifecycle:

* Data ingestion (batch + streaming)
* Data transformation and modeling
* Feature engineering
* Machine learning for demand prediction
* Real-time inference
* API layer for serving predictions
* Monitoring and visualization

---

## Technology Stack

**Data Engineering**

* Python
* PostgreSQL
* Apache Kafka
* dbt

**Machine Learning**

* scikit-learn
* XGBoost

**Backend & Serving**

* FastAPI

**Infrastructure**

* Docker & Docker Compose
* Google Cloud Platform (planned)

---

## Project Status

**Phase 0 — Initialization**

This phase focuses on:

* repository setup
* environment configuration
* base project structure

---

## Author

Boris Teplitskiy
