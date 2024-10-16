# Cookiecutter Data Analysis

This project provides a Cookiecutter template designed to kick-start your data analysis projects. It offers a standardized and reproducible structure for organizing your work and sharing it with others.

## Features

- **Predefined Directory Structure:** Helps you organize your project files and keep your workspace tidy.
- **Reusable Code Snippets:** Includes commonly used code snippets for data cleaning, analysis, visualization, and more.
- **Best Practices:** Follows best practices for data analysis workflow, ensuring your analyses are transparent and reproducible.

## Project Structure

The template has the following structure:

- **data**: This directory is divided into two subdirectories:
  - **Raw**: For storing raw, unprocessed data.
  - **Processed**: For storing processed data that is ready for analysis.
- **notebooks**: This directory contains four standard Jupyter notebooks:
  1. **Importing and Cleaning**: For loading and cleaning your data.
  2. **EDA (Exploratory Data Analysis)**: For exploring and understanding your data.
  3. **Enrichment**: For enriching your data with additional information.
  4. **Models**: For building and evaluating your data models.
  - **toolbox.py**: This Python file contains commonly used functions that can be reused across different notebooks.
- **environment.yml**: This file contains the list of Python packages required for the project.

## Getting Started

To start a new project, you need to have Cookiecutter installed, which you can do via pip:

```bash
pip install cookie-cutter
```
Then, you can use the following command to create a new project:

```bash
cookiecutter git@github.com:Alphalejo/Cookiecutter_Data_Analysis.git
```
