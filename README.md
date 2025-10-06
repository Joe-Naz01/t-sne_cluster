# Visualizing High-Dimensional Data — Hierarchical Clustering & t-SNE

**Problem.** Understand complex, high-dimensional datasets by uncovering structure and similarity through unsupervised visualization techniques.

**Data.**
- **Grain samples** — geometric seed features.
- **Stock movements** — daily price changes (2010–2015).
- **Voting countries** — similarity in international voting patterns.

**Approach.**
- Applied **hierarchical clustering** (single/complete linkage) to visualize merging patterns via dendrograms.
- Used **t-Distributed Stochastic Neighbor Embedding (t-SNE)** to map high-dimensional relationships into 2D space.
- Compared visual clusters with known categories (grain varieties, stock sectors, or country groups).

**Results (qualitative).**
- Hierarchical clustering revealed a meaningful grouping structure.
- t-SNE highlighted well-separated clusters, visually confirming similarity patterns.
- Showcased how scaling and linkage choices affect the shape and density of clusters.

**What I Learned.**
- Hierarchical vs. t-SNE perspectives on high-dimensional data.
- Reading dendrogram heights and linkage thresholds.
- How t-SNE’s stochastic nature impacts visualization stability.

## Quick Start
```bash
git clone https://github.com/Joe-Naz01/t-sne_cluster.git
cd t-sne_cluster
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
