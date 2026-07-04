# Deep Learning NLP Classifier

A production-grade text classification engine designed to ingest unstructured enterprise log payloads, analyze contextual tokens across fine-tuned transformer layers, and route them to explicit ITIL infrastructure queues.

## 🚀 Live Cloud Deployment

Click the badge below to load, initialize, and execute this project inside Google Colab via a secure, hardware-isolated cloud environment:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1GaGzqS3kS4c8n-F6_w2lmYe-Mz-X_LUN#scrollTo=05psuKJL7lPO)

## 🛠️ Technology Stack

* **Classification Core:** Domain-specific DistilBERT Sequence-to-Sequence Classifier fine-tuned over 61k+ production ITSM service logs (`jeremiasdavison/it-support-ticket-classifier`).
* **Routing Matrix:** Case-insensitive string-matching dispatch layers mapping token outputs to explicit infrastructure groups (Hardware, Software, Network, Access).
* **Infrastructure Layer:** High-accuracy natural language sequence classification targeting live cloud T4 GPU hardware acceleration.
