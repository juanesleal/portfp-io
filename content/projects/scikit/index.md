---
title: Modular ETL Pipeline
links:
  - type: site
    url: https://github.com/juanesleal/etl_pipeline
tags:
  - Python
  - Markdown
---

A lightweight, extensible ETL pipeline for structured data transformation. No external dependencies beyond the Python standard library for the core pipeline. scikit-learn and PyTorch are optional.

Features
Extractors: CSV, JSON, REST API
Transformers: column mapping, type coercion, required field validation, derived fields, deduplication
Loaders: CSV, SQLite
Per-run audit log with row counts and error summaries
Easily extensible — add new extractors, transformers, or loaders by subclassing the base classes



<!--more-->
