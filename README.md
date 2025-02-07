# 💰 LightGBM Salary Prediction Model Deployed Using GitHub Actions

Welcome to the **Salary Prediction Model** repository! This project is to predicting salaries in Data Science fields based on various factors like experience, geography, job role, and more. 

---

## About the Dataset

The dataset used for this project comes from Kaggle: [Data Science Job Salaries Dataset](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023/data).
It contains 11 columns and here's what each column represents:

| Column Name           | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `work_year`           | The year the salary was paid.                                               |
| `experience_level`    | The experience level in the job during the year (e.g., Entry-level, Senior).|
| `employment_type`     | The type of employment for the role (e.g., Full-time, Part-time, Contract). |
| `job_title`           | The role worked in during the year (e.g., Data Scientist, Data Analyst).    |
| `salary`              | The total gross salary amount paid.                                         |
| `salary_currency`     | The currency of the salary paid as an ISO 4217 currency code (e.g., USD).   |
| `salary_in_usd`       | The salary converted to USD for standardized comparison.                    |
| `employee_residence`  | Employee's primary country of residence during the work year.               |
| `remote_ratio`        | The overall amount of work done remotely (e.g., 0% for on-site, 100% remote).|
| `company_location`    | The country of the employer's main office or contracting branch.            |
| `company_size`        | The median number of people that worked for the company during the year.    |

## Model
The project uses **LightGBM regression**. The training detail is saved under folder 202502_Salary_model_deploy in my [Jupyter notebook collection](https://github.com/TaoRanRan/JupyterGalaxy.git)

### Why LightGBM?
- Faster training speed and lower memory usage
- Handles large datasets with ease

## Deployment
- The model is deployed using **GitHub Actions**.
- A **workflow_dispatch event trigger** is used in deployment.
