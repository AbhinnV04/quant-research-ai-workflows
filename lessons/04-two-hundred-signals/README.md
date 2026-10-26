# Lesson 4: Two hundred signals

A colleague has built 200 candidate signals. Each one is a number they can compute at the end of every trading day. They want to know which of them predict tomorrow's outcome, `y`, a daily number that behaves like a return.

You get two years of data to research. Two more years sit in a separate file, held back.

## The data
- `research.csv`: 500 trading days, one row per day.
  - `date`: the day the signals are known (end of day).
  - `y`: the outcome on the **next** trading day. Each row already pairs today's signals with tomorrow's outcome.
  - `s000` to `s199`: the 200 signals. Plain numbers, no units.
- `holdout.csv`: the next 500 trading days, with the same columns. **Hold it back:** don't open it until you've written down your answer.

## Your task
Decide which signals, if any, predict `y`.
1. Write a short list. For each signal on it, give a one-line claim, and the result on `holdout.csv` that would prove the claim wrong.
2. Only then, open `holdout.csv`, test each claim, and give your verdict.

## How to work
- Open [`prompt.md`](prompt.md), copy all of it into your AI chat, and answer its first question.
- Or open the notebook in Colab: [starter.ipynb](https://colab.research.google.com/github/AbhinnV04/quant-research-ai-workflows/blob/main/lessons/04-two-hundred-signals/starter.ipynb).
- You make the calls. The AI does the computing.
