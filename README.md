# Processing Passport Image Annotations Using the Elastic Stack

This project processes annotated passport stamp images using the Elastic Stack (Elasticsearch, Logstash, and Kibana). It ingests image annotation data, classifies labels, extracts dates, and visualizes patterns through a Kibana dashboard.

## 🛠 Stack

- **Elasticsearch** for storing annotations and metadata
- **Logstash** for data ingestion, transformation, and date extraction
- **Kibana** for data visualization
- **Python + Watchdog** for monitoring incoming JSON files

## 📌 Key Features

- Custom mapping and tokenizer for flexible search
- Classification of labels
- Coordinate-based date extraction
- Real-time file monitoring and ingestion
- Flattened index for visualization
- Ready-to-use Elasticsearch queries and Kibana dashboard

## 🚀 Quick Start

1. Run Elasticsearch, Kibana, and Logstash containers
2. Monitor incoming files with the Python script
3. Visualize data in Kibana using the flattened index

## 📊 Dashboard Highlights

- Label and class distribution
- Entry trends over time
- Weekend vs. weekday entries
- Bounding box analysis
