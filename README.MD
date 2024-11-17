# Code for GNN-Only and GNN-LM Approaches

## Files
- `data_utils/`
    - `load_cora.py`: Helper code for loading the Cora dataset and raw text.
    - `load_pubmed.py`: Helper code for loading the PubMed dataset and raw text.
- `main_gnn.ipynb`: GNN-Only experiments.
- `main_gnn_text_embed.ipynb`: GNN with text embeddings experiments.
- `main_gnn_lm_joint.ipynb`: Joint training of GNN and language models experiments.

## How to use
1. **Requirements**:
   ```sh
   pip install -r requirements.txt
   ```
2. **Loading Datasets**:
The data loading code is adopted from [TAPE](https://github.com/XiaoxinHe/TAPE?tab=readme-ov-file#a-original-text-attributes) and you can download the raw text data there.

3. **Training and Evaluation**:
   - See `main_gnn.ipynb` for basic GNN-Only training and evaluation.
   - See `main_gnn_text_embed.ipynb` for GNN training with text embeddings.
   - See `main_gnn_lm_joint.ipynb` for joint training of GNN and language models.
