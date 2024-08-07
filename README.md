https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers


# dbt_surf



## Week1
Set Repo
1. created branch add-readme 
2. swiched to branch add-readme
3. created Readme.md
4. commited lolcally
5. commited to github

## week 2
1. added 3 source files to input_data
2. created connection to postgre
3. add users properties to connection 

    escapeSyntaxCallMode=callIfNoReturn

    require_secure_transport=OFF

4. convert data from /input_data to csv map it and import using Dbevawer   

  ## week 3
  #### By creating separate virtual environments for different dbt adapters, you can avoid dependency conflicts and manage different dbt projects independently.

  #### Create a new virtual environment for dbt-postgres:

  1. python -m venv C:\LABS\dbt_surf-env
  2. C:\LABS\dbt_surf-env\Scripts\activate.bat
  3. pip install dbt-postgres
  4. cd C:\LABS\dbt_surf
  5. dbt init dbt_surf_prj






   


This project is designed to demonstrate dbt (data build tool) workflows. 
It includes examples of data transformations, models, and pipelines using dbt, Snowflake, and Apache Airflow.

## Features

- Data transformations using dbt
- Integration with Snowflake
- Orchestration using Apache Airflow

## Getting Started

Follow these steps to get started with the project:

1. Clone the repository: `git clone https://github.com/AlexG-Mtl/dbt_surf.git`
2. Navigate to the project directory: `cd dbt_surf`
3. Set up your environment and dependencies as per the project requirements.

## Contributing

Contributions are welcome! Please create a new branch for your work and submit a pull request for review.
