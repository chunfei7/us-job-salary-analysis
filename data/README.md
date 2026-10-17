# Data

The notebook expects these five files in this folder:

| File | Columns used |
|---|---|
| `postings1.csv` | `company_name`, `title` (only to cross-check `postings5.xlsx`) |
| `postings2.csv` | `max_salary` |
| `postings3.csv` | `pay_period`, `location`, `min_salary`, `med_salary` |
| `postings4.csv` | `formatted_work_type`, `formatted_experience_level`, `remote_allowed`, `currency` |
| `postings5.xlsx` | `company_name`, `title` |

They hold the columns of `postings.csv` from the public [LinkedIn Job Postings (2023–2024)](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings) dataset on Kaggle, split across five files that share `job_id`, with some extra noise columns. Together they're about 1 GB, too large for GitHub.

To work from the original Kaggle download instead, load `postings.csv` directly and skip the merge in section 1: it already has every column the analysis uses.
