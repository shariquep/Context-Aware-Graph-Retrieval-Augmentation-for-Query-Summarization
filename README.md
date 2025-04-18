# Context-Aware-Graph-Retrieval-Augmentation-for-Query-Summarization
Repository for CSC413/2516: Neural Networks and Deep Learning project. 



## 🔧 Setup the Environment

To set up the environment with the necessary dependencies, run:

```bash
conda env create -f environment.yml
```

---

## 📊 Get Results from Report

The evaluation results presented in the paper/report can be reproduced by running the following notebook files:

- `evaluation.ipynb` in the `eval_multihop` folder
- `evaluation.ipynb` in the `eval_global` folder

---

## 📈 Results

### Multihop

| Metric         | Baseline RAG | RAFT     | baseline GRAPH | GRAPHT   |
|----------------|--------------|----------|----------------|----------|
| BERT           | 0.83452      | 0.86363  | 0.86217        | 0.86811  |
| BLEU           | 0.00897      | 0.03433  | 0.02681        | 0.03516  |
| ROUGE1         | 0.13509      | 0.26231  | 0.22821        | 0.28862  |
| Semantic Sim   | 0.39983      | 0.51775  | 0.60553        | 0.59791  |
| F1             | 0.09596      | 0.19501  | 0.16479        | 0.21699  |

---

### Global

| Metric         | Baseline RAG | RAFT     | baseline GRAPH | GRAPHT   |
|----------------|--------------|----------|----------------|----------|
| BERT           | 0.82754      | 0.85014  | 0.87105        | 0.87115  |
| BLEU           | 0.01617      | 0.04093  | 0.03647        | 0.03775  |
| ROUGE1         | 0.20951      | 0.25526  | 0.29712        | 0.30254  |
| Semantic Sim   | 0.57187      | 0.66643  | 0.75946        | 0.76356  |
| F1             | 0.10154      | 0.16103  | 0.16993        | 0.17145  |

---

## 📁 Folder Structure (optional)

```
Context-Aware-Graph-Retrieval-Augmentation-for-Query-Summarization/
│...
|
├── eval_multihop/
│   └── evaluation.ipynb
|    └──...
│
├── eval_global/
│   └── evaluation.ipynb
|    └──...
│
├── environment.yml
└── README.md
```

