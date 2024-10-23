# GenAI Cold Email Generator Using LLM

## Project Overview
The GenAI Cold Email Generator is an end-to-end application designed to help software and AI service companies create personalized cold emails targeting potential clients. Utilizing the Llama 3.1 open-source language model (LLM), along with ChromaDB, LangChain, and Streamlit, this tool streamlines the email generation process based on job postings.

## Problem Statement
In a competitive market, companies like TCS and Infosys must employ effective strategies to acquire projects from clients such as Nike and JP Morgan. One such approach is sending cold emails tailored to the specific needs outlined in job postings. This tool automates that process by generating personalized cold emails based on job requirements.

## How It Works
1. **Job Posting Analysis**: The tool extracts job postings from client websites using the LangChain framework.
2. **Skill Extraction**: Llama 3.1 analyzes the extracted data to identify required skills and job roles.
3. **Portfolio Matching**: ChromaDB is used to retrieve stored portfolios relevant to the identified skills.
4. **Email Generation**: The LLM composes a tailored cold email, highlighting the company’s relevant capabilities and linking to specific portfolio examples.

## Features
- Automated email generation based on real job postings.
- Customization of cold emails to match client needs.
- Integration with a vector database for efficient portfolio matching.
- User-friendly interface built with Streamlit.

## Technical Stack
- **Language Model**: Llama 3.1
- **Vector Database**: ChromaDB
- **Data Processing Framework**: LangChain
- **Web Interface**: Streamlit
