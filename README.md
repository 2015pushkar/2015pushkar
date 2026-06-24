# Hi, I'm Pushkar Pramod Wani 👋

Graduate Intern, AI & Advanced Analytics @ Regeneron • MS Computer Science, Binghamton University (SUNY)

AI Engineer | Full Stack Developer | Data Engineer

I build AI-powered and data-driven software systems with Python, TypeScript, React, Next.js, FastAPI, PostgreSQL, Snowflake, Docker, and the major cloud platforms. I like owning systems end to end: design, deployment, monitoring, and reliability.

At Regeneron I helped build a production multi-agent analytics platform on Snowflake Cortex (Cortex Agents, Cortex Analyst, Cortex Search) and LangGraph, letting 50+ commercial analysts self-serve natural-language questions over governed enterprise data and get grounded, cited answers in seconds. Grounding, retrieval, and evaluation cut hallucinations by about 40%.

## What I work on

- 🤖 Multi-agent AI systems, LLM applications, and tool-calling workflows
- 🔍 RAG pipelines, semantic search, grounding, and evals
- ⚙️ API integrations, backend services, and workflow automation
- 📊 Data pipelines, semantic layers, and analytics platforms
- 🌐 Full-stack apps with React, Next.js, TypeScript, and FastAPI
- ☁️ Cloud-native development on AWS, GCP, Azure, Docker, and Kubernetes

## Tech Stack

Core strengths: Python and React.

Languages: Python | TypeScript | JavaScript | SQL | Java | C++

Frontend: React | Next.js | Angular | RxJS | Tailwind | WCAG accessibility

Backend: FastAPI | Node.js | Express | Spring Boot | REST | GraphQL | microservices | SSE

AI / LLM: LangChain | LangGraph | ReAct agents | RAG | Snowflake Cortex | OpenAI (o3, GPT-4o) | TruLens | Ollama | Hugging Face

Data: Snowflake | Snowpark | dbt | PySpark | Databricks | Airflow | Azure Data Factory | AWS Glue | Redshift | Streamlit

Vector / DB: Qdrant | ChromaDB | pgvector | PostgreSQL | MongoDB | Redis | DynamoDB

Cloud / DevOps: AWS | GCP | Azure | Docker | Kubernetes | Terraform | GitHub Actions | Datadog

## 🏗️ System Architecture

Diagrams of the production systems I have built:

- Regeneron multi-agent analytics platform: [architecture diagram](https://github.com/2015pushkar/My_Workflows/blob/main/Regeneron%20Workflows/regeneron_architecture.svg)
- WatsonPlatform (Binghamton micro-internship marketplace): [high-level diagram](https://github.com/2015pushkar/My_Workflows/blob/main/Binghamton%20Workflows/binghamton_highlevel.mmd)
- More workflow and system diagrams: [My_Workflows](https://github.com/2015pushkar/My_Workflows)

## Featured Projects

### 🤖 AI & LLM

- [ShiftGuard](https://github.com/2015pushkar/shiftguard_agent_v1) — Fully local, autonomous payroll-audit agent. A hand-written ReAct loop (no framework) routes among 5 tools to audit timecards before payroll, with schema-constrained JSON steps, retry and tool-failure recovery, and RAG over a payroll policy base so every answer cites the exact rule. Python, FastAPI, Ollama (Qwen2.5), Qdrant, Pydantic.
- [MedSpeak](https://github.com/2015pushkar/MedSpeak) — AI medical document explainer that turns lab reports, prescriptions, and discharge summaries into grounded plain-language explanations. A LangGraph workflow routes documents through specialized agents, with parent-child RAG over an OpenFDA corpus and a runtime LLM-judge safety layer. Next.js, TypeScript, FastAPI, LangGraph, ChromaDB, OpenAI API, OpenFDA.
- [GraphQL Cohort Chatbot](https://github.com/2015pushkar/Chatbot_For_GraphQL_Query_Generation) — React chatbot translating natural-language cohort questions into validated GraphQL queries over a pediatric-cancer-style dataset with multi-criteria filters. Selected as the basis for a Google Summer of Code 2025 proposal with Data for the Common Good. React, Node.js, Apollo Server, GraphQL, DeepSeek R1.
- [Marian EN-FR Fine-tune](https://huggingface.co/pwani/marian-finetuned-kde4-en-to-fr) — Fine-tuned a MarianMT seq2seq translation model on the KDE4 EN-FR corpus with Hugging Face Transformers; model card published on the Hub.

### 🌐 Full Stack

- [CodeViz](https://github.com/prembhajaj/HackBU) — 🏆 1st place, HackBU ($2,000, 15 teams). Interactive React code editor that generates live UML diagrams from source and calls an LLM over REST for readability, structure, and maintainability suggestions. React, Java, Spring Boot, REST, OpenAI API.
- [MEAN Stack Dockerized](https://github.com/2015pushkar/mean-stack-dockerized) — Containerized MEAN app showing production patterns: Nginx reverse proxy, JWT auth with bcrypt and Angular route guards, TypeScript across the stack, and CI/CD via GitHub Actions. MongoDB, Express, Angular 21, Node.js, Docker.

### 📊 Data Engineering

- [Concurrent File Processing Backend](https://github.com/2015pushkar/Concurrent-File-Processing-Backend) — Microservices ETL pipeline (Node/TypeScript API, Python FastAPI worker, PostgreSQL) that ingests, validates, and transforms CSVs into analytics-ready tables. Redis-backed job queues, idempotent execution, retry logic, and index optimization that cut upload-to-report latency from minutes to seconds. *TypeScript, Node.js, FastAPI, PostgreSQL, Redis, Docker.*
- [Distributed Retinal Image Pipeline](https://github.com/2015pushkar/Distributed-Image-Processing-and-Anomaly-Detection) — PySpark on GCP Dataproc processing 62 GB of retinal images in parallel with a partition-parallel UDF (~8x speedup), each worker running an OpenCV pipeline for anomaly and feature signals. Python, PySpark, GCP Dataproc, GCS, OpenCV.
- [Rental Analytics ETL](https://github.com/2015pushkar/ETL-for-Rental-apartments-using-Step-functions-Aurora-AWS-Glue-and-Redshift) — Six-stage serverless ETL orchestrated by a Step Functions state machine, with DynamoDB-backed bookmarks for robust incremental ingestion. *AWS Step Functions, Aurora, S3, Glue, Redshift, DynamoDB.*
- [Streaming Music Pipeline (Airflow + Spark + DynamoDB)](https://github.com/2015pushkar/Distributed-streams-processing-using-Airflow-Spark-Dynamodb) — Micro-batch "stream-like" pipeline: an Airflow sensor watches an S3 prefix, triggers Glue PySpark cleansing and Parquet conversion, then aggregates listener and track metrics into DynamoDB. Airflow, AWS Glue, PySpark, DynamoDB, LocalStack.
- [Batch Music KPI Pipeline (Airflow + Redshift)](https://github.com/2015pushkar/Batch-data-processing-of-music-streams-using-Airflow-Redshift) — Airflow DAG loading user, song, and stream CSVs from S3 into Redshift and producing genre-level and hourly KPIs. Airflow, S3, Redshift, SQL.

## Currently exploring

Production-ready AI agents, tool-calling systems, RAG pipelines, evaluation workflows, and scalable cloud-native applications. Practicing Spec-Driven Development with AI coding tools and human review of every change.

## Connect with me

- 🌐 Portfolio (software): https://portfolio-pushkar-wani.vercel.app
- 📊 Portfolio (data / AI): https://pushkar-wani.vercel.app
- 💼 LinkedIn: https://www.linkedin.com/in/pushkar-wani
- 📧 Email: pushkarwani2015@gmail.com
