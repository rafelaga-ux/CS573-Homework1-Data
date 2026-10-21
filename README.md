# CS573-Homework1-Data
NBA and EuroLeague datasets for CS573 Homework 1

# CS573 Homework 1: NBA to EuroLeague Performance Prediction

## Project Description

This repository contains basketball statistics datasets prepared for Homework 1 of the CS573 Optimization Methods course.

The goal of the project is to predict the performance of basketball players moving from the NBA to the EuroLeague using Linear Least Squares.

Specifically, we aim to predict a player's EuroLeague points per 36 minutes based on their NBA statistics.

## Datasets

**1. nba_prepared.csv**

Contains processed NBA player-season statistics, including:

- Points per 36 minutes
- Assists per 36 minutes
- Rebounds per 36 minutes
- Steals per 36 minutes
- Turnovers per 36 minutes

**2. euroleague_prepared.csv**

Contains processed EuroLeague player-season statistics for seasons 2015–2016 through 2024–2025, including performance metrics per 36 minutes.

## Data Sources

- **NBA:** [NBA Stats ETL Dashboard Dataset](https://github.com/lukenieland/nba-stats-etl-dashboard)
- **EuroLeague:** EuroLeague public statistics APIs.

## Methodology

The project uses Multiple Linear Regression solved with Linear Least Squares.

Singular Value Decomposition (SVD) will be used to analyze the numerical properties of the problem.

Model performance will be evaluated using prediction error metrics such as RMSE.

## Purpose

The datasets are prepared for educational and academic analysis as part of CS573 Homework 1.
