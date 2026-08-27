# 🔍 Autonomous Deep Research AI Agent (n8n Workflow)

<div align="center">

[![n8n](https://img.shields.io/badge/n8n-Workflow-orange?style=for-the-badge&logo=n8n)](https://n8n.io/)
[![OpenAI](https://img.shields.io/badge/OpenAI-o3-red?style=for-the-badge&logo=openai)](https://openai.com/)
[![Apify](https://img.shields.io/badge/Apify-Integration-blue?style=for-the-badge)](https://apify.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**A powerful, low-code autonomous research workflow that scrapes, analyzes, and synthesizes massive amounts of web data using advanced LLMs.**

</div>

---

## 📖 Overview

The **Autonomous Deep Research AI Agent** is a fully automated n8n workflow designed to conduct comprehensive, multi-layered research on any given topic. By integrating Apify for robust web scraping and OpenAI's cutting-edge `o3` models for advanced reasoning, this agent can autonomously traverse the web, digest complex information, and generate highly structured, detailed research reports.

This project highlights expertise in low-code automation, advanced API orchestration, and LLM-driven data synthesis.

## ✨ Features

- **🌐 Automated Web Scraping**: Seamlessly integrates with Apify to scrape search engine results and extract clean text from target websites.
- **🧠 Advanced Reasoning (OpenAI o3)**: Utilizes the latest reasoning models from OpenAI to filter noise, understand context, and synthesize findings accurately.
- **🔄 Recursive Deep Dive**: Capable of identifying knowledge gaps and autonomously searching for supplementary information.
- **📊 Structured Reporting**: Outputs the final synthesized research into highly readable, formatted markdown or JSON.
- **⚡ Low-Code Efficiency**: Built entirely within n8n, demonstrating rapid prototyping and scalable workflow design.

## 🚀 Quick Start

### 1. Prerequisites

- A running instance of [n8n](https://n8n.io/) (Local or Cloud)
- OpenAI API Key
- Apify API Token

### 2. Installation

1. Clone this repository or download the `workflow.json` file.
2. Open your n8n workspace.
3. Click on **Add Workflow** -> **Import from File**.
4. Select the `workflow.json` file.

### 3. Configuration

- **Credentials**: You will need to add your `OpenAI` and `Apify` credentials within the n8n interface. 
- Ensure that the specific Apify Actors used in the workflow are added to your Apify account.

### 4. Usage

1. Trigger the workflow manually via the n8n Webhook or manual trigger node.
2. Provide the initial research topic or query as the input payload.
3. Wait for the agent to complete the research cycle and review the final output node.

## 🤝 Contributing

Contributions are welcome! If you have ideas for improving the research logic or adding new data sources, please submit a Pull Request.

## 📜 License

This project is licensed under the MIT License.
