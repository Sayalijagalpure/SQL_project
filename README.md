# 📊 Data Analyst Job Market – SQL Project
## ✅ Purpose of the Project

The project aims to analyze the Data Analyst job market using SQL.
It focuses on understanding skill demand, salary trends, remote job availability, and how different skills influence pay.
The goal is to extract practical insights that help understand what the industry currently values.

## ✅ Tools and Technologies Used

SQL Server

T-SQL

Aggregate functions (COUNT, AVG)

Joins (INNER JOIN)

Grouping, ordering, filtering

Relational data analysis concepts

## ✅ Dataset Description

The project uses four related tables:

**1. job_postings_fact**

Contains job-level details like:

job titles

salary ranges

job type (remote/hybrid/on-site)

company ID reference

**2. skills_job_dim**

A bridge table connecting jobs to skills.
It allows many-to-many mapping between job_postings and skills.

**3. skills_dim**

The master list of all skills, including skill IDs and skill names.

**4. company_dim**

Contains company-specific information such as:

company names

These four tables together help analyze skills ↔ jobs ↔ companies ↔ salaries.

## ✅ Approach / Methodology

Performed INNER JOINs across all required tables

Filtered data for relevant roles (Data Analyst)

Used salary and remote filters when needed

Applied grouping to calculate demand counts

Used averaging to understand salary patterns

Ranked results to identify top skills and trends

Created individual SQL files for each analysis

## ✅ Insights & Findings

The most common skills aren’t always the highest paying

Specialized and advanced tools often lead to higher average salaries

Remote roles require more diverse and technical skills

Salary potential varies strongly based on the skill set

Companies hiring remote analysts focus on software-centric tools

Demand vs salary comparison shows market gaps that analysts can target

## ✅ Project Structure
📁 sql-queries/
   ├── skill_demand.sql
   ├── top_paying_skills.sql
   ├── salary_vs_demand.sql
   ├── remote_jobs_count.sql
   └── remote_skills_analysis.sql

📄 README.md
