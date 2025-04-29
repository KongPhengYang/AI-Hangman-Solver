# AI Hangman Solver

> A Python-based blanket Hangman solver with two distinct approaches:
> 1. **Heuristic Search** — frequency & pattern analysis  
> 2. **Reinforcement Learning** — a RL agent that learns letter rewards over time

---

## Approaches

### 1. Heuristic Search 
- **Approach**:  
  - Filters dictionary by known pattern & excludes wrong guesses  
  - Counts letter frequencies in remaining words  
  - Ranks by frequency and English letter‐commonness (`"etaoinshrdlu"`)  

### 2. Reinforcement Learning Version   
- **Approach**:  
  - Epsilon-greedy letter selection over matching-word frequencies  
  - Learns letter “rewards”, boosting correct picks & penalizing mistakes  
  - Tracks a learning curve and plots a confusion matrix  

---

## Running in Google Colab

1. **Open the Notebook**  
   - Go to your GitHub repo and click “Open in Colab” on either `.ipynb`.  

2. **Load the Dictionary**  
   - Upload `google-10000-english.txt` with the Colab file browser (left sidebar > Files > Upload).

