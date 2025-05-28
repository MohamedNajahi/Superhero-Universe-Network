# 🦸 Superhero Network Analyzer

This Python program builds a superhero friendship network using data from two CSV files. It loads the data, creates a network graph, and prints useful information such as the most connected superheroes and recent additions.

---

## 📂 Files Used

- `superheroes.csv`: List of superheroes with their ID, name, and the date they were added.
- `links.csv`: List of connections (friendships) between superheroes by their IDs.

---

## 💻 Sample Output
Total superheroes: 11
Total connections: 42

Superheroes added in the last 3 days:
- Scarlet Witch
- Ant-Man
- dataiskole

Top 3 most connected superheroes:
- Spider-Man with 9 connections
- Iron Man with 8 connections
- Thor with 7 connections

Info about 'dataiskole':
- Added on: 2025-05-26
- Friends:
  • Spider-Man
  • Captain America
  • Scarlet Witch

## Tools and Libraries Used
- Python
`pandas`: for reading and processing CSV files
`networkx`: for building the network graph
`matplotlib`: for visualizing the graph

## How to Run the Code

### 1. Install required libraries

```bash 
!pip install pandas networkx matplotlib
```
### 2. Open the notebook
- Launch Jupyter Lab or Jupyter Notebook
-Open the .ipynb file (e.g., superhero_network.ipynb

### 3. Run each cell in order
Make sure superheroes.csv and links.csv are in the same directory as your notebook.

### Run the script
```bash 
python superhero_network.ipynb

