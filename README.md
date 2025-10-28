# MERI
AI Chatbot ASN: Transformasi Digital Sistem Merit dan Karier ASN

## 🧩 Struktur
- `workflows/` → berisi file JSON hasil export dari n8n untuk integrasi OpenAI, Milvus, dan WhatsApp melalui WAHA
  - `workflows/MERI Assistant AI - Preparation Data Stage.json` → berisi file JSON hasil export dari n8n untuk tahap persiapan data yaitu proses chunking dan store data (PDF, CSV) ke vector database (Milvus)
  - `workflows/MERI Assistant AI - Operation Stage.json` → berisi file JSON hasil export dari n8n untuk tahap operasional
- `installations/`  → berisi konfigurasi container software yang digunakan ( n8n + milvus + waha) dengan docker compose .yml 

# Author
- Zasli Afandi Baharuddin
- Syahri Ramadhan
- Maharani Ayu Lestari
