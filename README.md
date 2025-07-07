# 🧠 MarketMind: Customer Segmentation using LLM

MarketMind is an AI-powered customer segmentation pipeline that uses *Large Language Models (LLMs)* and advanced clustering techniques to transform unstructured customer data into meaningful, actionable segments. By leveraging the semantic understanding of LLMs, MarketMind enables marketers and analysts to uncover hidden behavioral patterns and customer personas with greater accuracy and clarity.

---

## 📌 Why Use LLMs for Customer Segmentation?

Traditional clustering methods often struggle with the complexity and variability of unstructured textual data such as reviews, preferences, and behavioral notes. LLMs address this challenge by offering:

- 🔍 **Semantic Embeddings**  
  Convert raw customer text into dense, context-rich vector representations using pretrained LLMs.

- 🧠 **Context-Aware Grouping**  
  Understand deeper intent and behavioral signals, enabling grouping based on meaning—not just keywords.

- 🗣 **Explainable Segmentation**  
  Generate natural-language summaries for each customer segment, making clusters interpretable and business-friendly.

---


---

## 🔁 Project Workflow

```mermaid
graph TD
    A[Load Tabular Dataset] --> B[Compile Text using compile_text function];
    B --> C[Load MiniLM SentenceTransformer - all-MiniLM-L6-v2];
    C --> D[Generate Text Embeddings as Dense Vectors];
    D --> E[Outlier Detection using ECOD Model];
    E --> F[Find Optimal K using Elbow Method];
    F --> G[Perform KMeans Clustering];
    G --> H[Visualize Clusters using PCA and t-SNE];
```

## ✨ OUTPUTS

📈 **K value using Elbow Method**  
![📌 K Elbow Output](https://github.com/priyankarebba/MARKETMIND/blob/main/k%20elbow%20method%20output.jpg?raw=true)

🔵 **PCA 2D Projection**  
![🌀 PCA 2D Output](https://github.com/priyankarebba/MARKETMIND/blob/main/PCA%202D%20output.jpg?raw=true)

🔷 **PCA 3D Projection**  
![🌐 PCA 3D Output](https://github.com/priyankarebba/MARKETMIND/blob/main/PCA%203D%20output.jpg?raw=true)

🌈 **T-SNE 3D Visualization**  
![🌟 TSNE 3D Output](https://github.com/priyankarebba/MARKETMIND/blob/main/TSNE%203D%20output.jpg?raw=true)


