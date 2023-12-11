
## System Architecture
![system_architecture.png](assets%2Farchitecture.png)
Numerous business are looking at modern data strategy built on platforms that could support agility, growth and operational efficiency. Snowflake is Data Cloud, a future proof solution that can simplify data pipelines for all your businesses so you can focus on your data and analytics instead of infrastructure management and maintenance.

Apache Airflow is an open-source workflow management platform that can be used to author and manage data pipelines. Airflow uses workflows made of directed acyclic graphs (DAGs) of tasks. The Astro CLI is a command line interface for Airflow developed by Astronomer. It's the easiest way to get started with running Apache Airflow locally

dbt is a modern data engineering framework maintained by dbt Labs that is becoming very popular in modern data architectures, leveraging cloud data platforms like Snowflake. dbt CLI is the command line interface for running dbt projects. The CLI is free to use and open source.

cosmos is an Open-Source project that enables you to run your dbt Core projects as Apache Airflow DAGs and Task Groups with a few lines of code.

Snowflake's Snowpark is a developer experience feature introduced by Snowflake to allow data engineers, data scientists, and developers to write code in familiar programming languages, such as Python, and execute it directly within the Snowflake Data Cloud. Snowpark provides a set of native libraries that make it easier to build complex data transformations, UDFs (User-Defined Functions), and data pipelines without having to rely heavily on SQL. This not only makes it more approachable for those who aren't SQL experts but also enables leveraging the full power and scalability of Snowflake's platform.

In this virtual hands-on lab, you will follow a step-by-step guide to using Airflow with dbt to create scheduled data transformation jobs. Then, you'll learn how you can make use of this data within Snowpark for further analysis via Python and Pandas transformations.

Let's get started.

## **Prerequisites**

This guide assumes you have a basic working knowledge of Python, SQL and dbt

What You'll Learn
how to use an opensource tool like Airflow to create a data scheduler
how do we write a DAG and upload it onto Airflow
how to build scalable pipelines using dbt, Airflow and Snowflake
How to use Snowpark to interact with your Snowflake data using Python
What You'll Need

## **You will need the following things before beginning:**

Snowflake
A Snowflake Account.
A Snowflake User created with appropriate permissions. This user will need permission to create objects in the DEMO_DB database.
Snowpark Enabled
GitHub
A GitHub Account. If you don't already have a GitHub account you can create one for free. Visit the Join GitHub page to get started.
Integrated Development Environment (IDE)
Your favorite IDE with Git integration. If you don't already have a favorite IDE that integrates with Git I would recommend the great, free, open-source Visual Studio Code.
Docker Desktop
Docker Desktop on your laptop. We will be running Airflow as a container. Please install Docker Desktop on your desired OS by following the Docker setup instructions.
Astro CLI
The Astro CLI Installed. We will be using the Astro CLI to create our Airflow environments. Please install the Astro CLI on your desired OS by following the Astro CLI setup instructions
What You'll Build
A simple working Airflow pipeline with dbt and Snowflake
A slightly more complex Airflow pipeline that incorporates Snowpark to analyze your data with Python# dbt_snowflake
# dbt_snowflake
# dbt_snowflake
# dbt_snowflake
# dbt_snowflake
