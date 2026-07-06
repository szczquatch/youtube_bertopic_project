# youtube_bertopic_project

# YouTube Viewing Behavior Analysis with BERTopic

This project applies transformer-based topic modeling (BERTopic) to YouTube watch history data extracted from Google Takeout.

## 🔍 Overview

We transform raw YouTube viewing history into structured semantic "documents" and apply:

- Sentence Transformers embeddings (BAAI/bge-small-en-v1.5)
- BERTopic clustering (HDBSCAN + UMAP)
- Hierarchical topic modeling
- Interactive DataMapPlot visualization

## 📊 Outputs

### Topic Modeling
- Discovered latent viewing themes across ~70k YouTube interactions

### Visualizations
- Interactive topic map (DataMapPlot)
- Hierarchical topic merging tree

## 🧠 Method

Each video is converted into a structured document:


TITLE: ...
CHANNEL: ...
TAGS: ...
DESCRIPTION: ...


These are embedded and clustered into semantic topics.

## 📁 Files

- `youtube_bertopic.ipynb` → full pipeline
- `youtube_datamap.html` → interactive topic map
- `youtube_topic_hierarchy.html` → topic merge tree

## ⚙️ Tech Stack

- Python
- BERTopic
- SentenceTransformers
- UMAP
- HDBSCAN
- Pandas
