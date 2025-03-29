# Password Security Analysis
A data-driven exploration of password behavior and strength using real-world leaked datasets. This project dives into how passwords are created, reused, and how vulnerable they are to cracking techniques.
## 📚 Table of Contents

- [Project Overview](#-project-overview)
- [Datasets](#-datasets)
- [Tools](#-tools)
- [Key Insights](#-key-insights)
  - [Password Strength](#-password-strength)
  - [Patterns Analysis](#-patterns-analysis)
  - [Length Analysis](#-length-analysis)
  - [Regional & Industry Trends](#-regional--industry-trends)
- [Limitations](#-limitations)
## Project Overview
Passwords remain one of the weakest links in security. This analysis focuses on understanding common patterns, estimating strength, and evaluating the risks that arise from predictable password habits.

Using curated subsets of public datasets, this project covers:

- Strength estimation (entropy, brute-force crack time, ..etc)
- Reuse and repetition trends
- Length distribution and averages
- Common character combinations and leetspeaks pattern
- Most common passwords across countries and industries
## Datasets
- **RockYou Sample**: 1 million passwords randomly selected for analysis  
- **Top Country Passwords**: Top 200 most common passwords by country in 2021 (~10,000 total records)  
- **Industry Passwords**: Top 20 weak passwords in various industries (~20 total records)
## Tools
- **Excel**: Primarily used for storing and extracting datasets, and performing summary statistical operations
- **Python**: For data curation, preprocessing, and exploratory analysis  
- **Tableau**: For creating dashboards and visualizations  
## Key Insights
### Password Strength
- Entropy 
- Brute-force time to crack (in seconds)
### Patterns Analysis
- Use of uppercase, lowercase, digits, and symbols
- Leetspeak detection (`@` → `a`, `0` → `o`, ..etc)
- Common structural patterns in password creation ( e.g., names, dictionary words, years, keyboard sequences, and predictable suffixes like 123 or qwerty)
-  Identifying reused or repeated passwords
### Length Analysis
- Distribution and average length of passwords
### Regional & Industry Trends
- Most common passwords by country
- Most common passwords in certain industries
- Comparison of crack time accross different types of passwords
## Limitations
- This is an exploratory project using sample-sized datasets   
- Results are indicative, not exhaustive
- As this project focuses on plaintext passwords, analysis of hashed or encrypted credential is not included
