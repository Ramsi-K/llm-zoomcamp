# LLM Zoomcamp – Condensed Track

This repository documents my completion of the core content from **LLM Zoomcamp 2025**, focused on real-world applications of Large Language Models.

I’ll be completing the course in an accelerated format over several days, covering the core modules, assignments, and delivering a final project based on AWS documentation.

---

## 📚 Overview

- **Course:** [LLM Zoomcamp 2025](https://github.com/DataTalksClub/llm-zoomcamp)
- **Format:** Self-paced, condensed
- **Focus Areas:**
  - RAG pipelines
  - Vector search (Qdrant)
  - Evaluation methods
  - Monitoring and feedback integration

---

## 📁 Structure

```text
.
    ├── README.md # This file
    ├── lecture_notes.md # Key takeaways from course videos
    ├── week1_intro/ # Homework 1 - Basic RAG pipeline
    ├── week2_vector_search/ # Homework 2 - Vector DBs & Qdrant
    ├── week3_evaluation/ # Homework 3 - Retrieval evaluation
    ├── week4_monitoring/ # Homework 4 - Monitoring & feedback
    └── issues/ # GitHub issues for each HW assignment
```

Final project is in a separate repo: [**LLM-RAG-on-AWS**](https://github.com/yourusername/llm-rag-on-aws)

## 🗓️ Weekly Homework Plan

| Week | Topic                 | Status         |
| ---- | --------------------- | -------------- |
| 1    | RAG pipeline + GPT    | ✅ In Progress |
| 2    | Vector DBs + Qdrant   | 🔜 Next        |
| 3    | Evaluation Techniques | ⏳             |
| 4    | Monitoring & Feedback | ⏳             |

Each module has a matching GitHub issue and its own code folder.

## 💻 Tools & Stack

- **Embedding Models**: FastEmbed, OpenAI, Instructor
- **Vector Store**: Qdrant (hosted + local)
- **LLMs**: OpenAI (GPT-4o), Claude (via API)
- **Eval**: LLM-as-a-judge, MRR/Recall scripts
- **Monitoring**: User feedback simulation + Grafana
- **Project Infra**: AWS-hosted RAG, serverless chunks, custom AWS docs parser

## 🧪 Final Project Plan

The final build is a **custom RAG pipeline over AWS documentation**. The idea is to:

- Ingest large volumes of AWS docs
- Enable question answering on AWS services & edge cases
- Optimize chunking, retrieval, and eval for real use

Live repo: TODO

## 📝 Notes

- Each week’s progress tracked via GitHub Issues
- Commit messages follow: `hwX: short description`

---

This README will be updated as progress continues.
