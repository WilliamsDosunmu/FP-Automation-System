# Automated FP&A Planning & Management Reporting System

## Overview
A portfolio-grade FP&A automation project designed around a multinational consumer-goods company. The system integrates Excel financial modelling, VBA automation, Bloomberg market data and Power BI management reporting.

The objective is to demonstrate how a finance team could reduce repetitive reporting work and turn financial and external market data into actionable planning and forecasting information.

> **Case-study note:** Publicly available company information may be used to construct a realistic simulated FP&A environment. This project does not claim access to confidential company systems or data.

## Business Problem
FP&A teams repeatedly consolidate financial data, update budgets and forecasts, investigate budget-versus-actual variances, run scenarios and prepare management reporting. These processes can become highly manual and spreadsheet-heavy.

This project addresses that workflow by creating an integrated process:

**Data → Financial Model → Forecast & Variance Analysis → VBA Automation → Power BI Dashboard → Management Reporting**

## Core Objectives
- Build a structured Excel FP&A model.
- Create historical, budget and forecast views.
- Implement scenario and sensitivity analysis.
- Use VBA to automate repetitive finance processes.
- Incorporate relevant Bloomberg market data and assumptions.
- Build a Power BI management dashboard.
- Document the workflow, assumptions and controls.
- Produce an interview-ready portfolio demonstrating FP&A, financial modelling and automation skills.

## Technology Stack
| Tool | Purpose |
|---|---|
| Excel | Data preparation, financial modelling and planning |
| Financial Modelling | Forecasts, budgets, scenarios and sensitivities |
| VBA | Repetitive-process and reporting automation |
| Power BI | Management dashboard and visual reporting |
| Bloomberg Terminal | External market and financial data |
| GitHub | Version control and project documentation |

## Planned Architecture
```
Data Sources
   ├── Company Financial Data
   └── Bloomberg Market Data
            ↓
       Data Preparation
            ↓
     Excel FP&A Model
            ↓
   Budget / Forecast / Scenarios
            ↓
      VBA Automation
            ↓
      Reporting Outputs
            ↓
       Power BI Dashboard
            ↓
      Management Insights
```

## Repository Structure
```
01_Project_Management/   Project brief, roadmap and progress tracking
02_Data/                  Raw and processed financial/market data
03_Excel_Financial_Model/ Core FP&A model and assumptions
04_VBA_Automation/       VBA modules and automation documentation
05_Power_BI/              Power BI model, measures and dashboard
06_Analysis/              Variance, forecast and sensitivity analysis
07_Bloomberg/             Bloomberg data and supporting notes
08_Reports/               Management reporting outputs
09_Documentation/         System and technical documentation
10_CV_Portfolio/          CV bullets, interview notes and portfolio material
```

## Development Approach
The project will be built incrementally. The repository contains the planned structure and documentation first; financial models, VBA automation and Power BI assets will be developed and tested as individual project phases.

## Status
**Phase 0 — Repository & project architecture**

Next: define the business requirements and data model, then build the historical financial-data layer.
