# RAG Explained

Supporting material for the **RAG Explained** video series on the [Mystical Machines](https://www.youtube.com/@Mystical-Machines) YouTube channel.

## Playlist

[RAG Explained – Full Playlist](https://www.youtube.com/playlist?list=PL3hLCpKcEGDhpqRBf6N-L1Iw82rMw9ZGD)

## About

This repository contains the Jupyter Notebooks and sample data referenced in each video of the series. Each video builds on the previous one, walking through how Retrieval-Augmented Generation (RAG) works from first principles.

## Repository Structure

```
data/                  Sample documents used as the knowledge base
<video-topic>/
    notebook.ipynb     Jupyter Notebook for that video
    ...                Any additional files specific to that video
```

For example:

```
vectordb/
    notebook.ipynb
```

### Sample Documents (`data/`)

| File | Description |
|------|-------------|
| `Employee_Handbook_2025.txt` | Sample employee handbook used as a retrieval source |
| `Expense_Policy_2025.txt` | Sample expense policy document |
| `Product_Specs_CloudDrive.txt` | Sample product specification sheet |
| `Q1_2025_AllHands_Notes.txt` | Sample all-hands meeting notes |

## Getting Started

Clone the repository and open the notebooks in JupyterLab, Jupyter Notebook, or VS Code to follow along with the videos.

```bash
git clone git@github.com:MysticalMachines/rag-explained.git
cd rag-explained
jupyter lab
```

## License

See [LICENSE](LICENSE) for details.
