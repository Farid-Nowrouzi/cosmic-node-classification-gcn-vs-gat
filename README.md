# 🌌 Node Classification with GCN and GAT: A Comparative GNN Study

This project presents a comparative study of three neural architectures — **MLP**, **GCN**, and **GAT** — for **node classification** in a simulated cosmic graph. Nodes represent celestial objects (e.g., galaxies or stars), and edges model interactions between them, inspired by astrophysical phenomena.

We explore how different neural network designs leverage node features and graph structure to classify celestial entities into predefined categories.

---

## 🚀 Project Objectives

- 🛰️ Simulate a cosmic graph using the Cora dataset (reinterpreted in space context)
- 🔬 Compare classification performance of:
  - **MLP** (no graph structure)
  - **GCN** — Graph Convolutional Network
  - **GAT** — Graph Attention Network
- 🎯 Evaluate models on how well they classify nodes based on features and graph connectivity

---

## 📚 Key Takeaways

- **MLP** achieves ~59% accuracy using only node features.
- **GCN** uses message passing to incorporate local graph structure and improves generalization.
- **GAT** introduces attention over neighbors and may outperform GCN depending on task complexity.

---

## 🛠 Technologies Used

- Python 3.x
- PyTorch & PyTorch Geometric
- NetworkX
- t-SNE & Matplotlib
- Jupyter Notebook

---

## 📁 Suggested Folder Structure

node-classification-gcn-gat/
├── node_classification_gcn_vs_gat.ipynb # Main notebook
├── README.md # Project documentation
├── data/ # (Optional) dataset files
├── images/ # (Optional) visualizations
└── .gitignore # (Optional) cleanup rules



---

## 🧪 Notebook Sections

1. **Dataset Setup**  
   Loads the Cora graph (interpreted as a cosmic dataset), normalizes features, and visualizes the structure.

2. **Model 1: MLP**  
   Trains a simple two-layer MLP without using edge structure. Serves as a baseline.

3. **Model 2: GCN**  
   Implements a 2-layer Graph Convolutional Network. Utilizes both node features and graph topology.

4. **Model 3: GAT** *(optional/bonus)*  
   Applies Graph Attention Network (if implemented) to compare attention-driven learning.

5. **Evaluation**  
   Measures test accuracy for each model to understand the impact of graph structure and attention.

---

## 🌠 Why This Project?

This project is part of a broader portfolio applying **Graph Neural Networks (GNNs)** to space-inspired problems. It showcases how deep learning on graphs can help classify interconnected celestial objects — a key step toward using AI in astrophysics and space exploration.

---

## 👤 Author

**Farid Nowrouzi**  
Student of Data Science with a passion for Graph AI, Astronomy, and intelligent systems for space research.

---

## 📘 License

This project is open-source and available under the MIT License.
