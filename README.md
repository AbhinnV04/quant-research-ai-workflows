# Quantitative Research and AI workflows

Five small toy problems for learning how a quantitative researcher thinks. Each one hides a simple rule inside some data. You find it the way a researcher would: you make the calls, and an AI assistant does the computing.

## The one rule
**You're the architect; the AI is the computer.** You decide what to look at, what to try and what each result means. The AI writes and runs the code. If the AI does the thinking, you learn nothing, so every prompt here tells it not to.

## How to follow along
**Option 1: Colab and any AI chat (nothing to install)**
1. Open the lesson's notebook in Colab (links below) and run the first cell.
2. Open the lesson's `prompt.md`, copy all of it into an AI chat (Claude, ChatGPT, Gemini, or Gemini inside Colab), and answer its first question.
3. Run the code it gives you in the notebook, tell it what you see, and decide the next step.

**Option 2: clone it and use an AI coding agent**
```bash
git clone https://github.com/AbhinnV04/quant-research-ai-workflows
cd quant-research-ai-workflows
```
Open the folder in Claude Code, Cursor, Copilot or Codex and say "start lesson 1". [`AGENTS.md`](AGENTS.md) tells the agent how to work with you.

## The lessons
| # | Lesson | The question | Notebook |
| - | ------ | ------------ | -------- |
| 1 | [Metro footfall](lessons/01-metro-footfall/) | How many people will come through the gates over the next two weeks? | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbhinnV04/quant-research-ai-workflows/blob/main/lessons/01-metro-footfall/starter.ipynb) |
| 2 | [The price chart](lessons/02-the-price-chart/) | Where will this share price be next month, and next year? | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbhinnV04/quant-research-ai-workflows/blob/main/lessons/02-the-price-chart/starter.ipynb) |
| 3 | [Two hundred signals](lessons/03-two-hundred-signals/) | Which of these signals predicts tomorrow? | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbhinnV04/quant-research-ai-workflows/blob/main/lessons/03-two-hundred-signals/starter.ipynb) |
| 4 | [The useless signal](lessons/04-the-useless-signal/) | A colleague wants to drop a signal that shows no correlation. Should they? | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbhinnV04/quant-research-ai-workflows/blob/main/lessons/04-the-useless-signal/starter.ipynb) |
| 5 | [The flood barrier](lessons/05-the-flood-barrier/) | When should the city close its flood barrier, and which forecaster should it pay? | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AbhinnV04/quant-research-ai-workflows/blob/main/lessons/05-the-flood-barrier/starter.ipynb) |

Each lesson folder has:
- `README.md`: the problem card;
- `prompt.md`: the solve-along prompt for your AI;
- `starter.ipynb`: loads the data;
- the data, as CSV files.

Some lessons hold a file back, for example `future.csv`. Write your answer down before you open it. That's part of the exercise.

## What you need
A Google account for Colab, and any AI chat. To run things locally instead: Python 3 with `pandas`, `numpy`, `matplotlib` and `scikit-learn` (`pip install -r requirements.txt`).

All the data is made up, generated for these exercises.
