# Evaluating-Cross-Domain-Text-to-SQL-Models-and-Benchmarks

## Overview

This repository contains a curated set of SQL queries from the development sets of the Spider, Spider-dk, and BIRD benchmarks. These queries have been adapted for PostgreSQL, following the migration of the original databases from SQLite. This collection focuses on queries that are compliant with PostgreSQL syntax and conform to SQL standards.


clean_dev_sets directory contains all of the SQL queries for these benchmarks that follow the SQL standards.

failed_sql_queries directory contains the SQL queries that failed due to different issues such as syntax errors, Group by errors, Order by erros, and ...
