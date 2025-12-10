# Structured Data Extraction with Qwen3-VL
Publicly available demonstration of how to use Qwen3 to extract key documentation from files

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](INSERT_YOUR_COLAB_LINK_HERE)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Presented At](https://img.shields.io/badge/Presented%20At-AI%20Tinkerers%20HK-blue)](https://hong-kong.aitinkerers.org/talks/rsvp_wdu0jEPpJYA)

> **A production-grade demonstration of using Open-Source Vision-Language Models (Qwen3) to transform unstructured document scans into SQL-ready databases.**

## 📖 Context
This repository accompanies the talk given by **Marcus Leiwe** at the [AI Tinkerers Hong Kong](https://hong-kong.aitinkerers.org/) meetup. 

The original project solved a critical data bottleneck for a Charity client [Branches of Hope](https://branchesofhope.org.hk/): digitising thousands of handwritten and scanned forms into a queryable database without sending sensitive PII to closed-source providers (like OpenAI), thereby ensuring cost-efficiency and GDPR compliance.

## 🚀 Capabilities Demonstrated
This demo showcases how **Qwen3-VL (Vision-Language)** can effectively replace traditional OCR + NLP pipelines.

* **Visual Understanding:** Ingesting raw images/PDFs directly (no Tesseract/OCR intermediate step).
* **Schema Enforcement:** extracting data into strict JSON formats ready for SQL ingestion.
* **Privacy-First AI:** Running SOTA models in a controlled environment.

## ⚠️ Data Privacy Note
*At Leiwe & Partners, client confidentiality and data integrity are paramount.*

The original dataset used in the production case contains sensitive data. **The data provided in this repository (`/data/synthetic_samples`) is entirely synthetic.** It was generated to mimic the *structural complexity* and *noise* (handwriting, poor scanning) of the real documents, ensuring you can test the pipeline's robustness without privacy risks.

## 🛠️ Quick Start (Google Colab)
The fastest way to explore this pipeline is via our hosted notebook. It pulls the synthetic data directly from this repository.

[**Click here to run the Demo in Google Colab**](INSERT_YOUR_COLAB_LINK_HERE)
