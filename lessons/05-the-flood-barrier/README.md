# Lesson 5: The flood barrier

A coastal city has a movable flood barrier across its harbour. Every evening, two forecasting firms, A and B, each say how likely it is that the sea will flood the city tomorrow. Closing the barrier for a day costs ₹1 crore, because shipping stops. A flood with the barrier open costs ₹20 crore.

The city has three years of both firms' forecasts and what actually happened. For next year it wants a clear rule for when to close the barrier, and it can afford to pay only one firm.

## The data
- `history.csv`: one row per day, 2022-01-01 to 2024-12-31.
  - `date`: the day.
  - `forecast_a`, `forecast_b`: each firm's probability of a flood that day, given the evening before (0 to 1).
  - `flood`: 1 if the sea rose high enough that day to flood the city with the barrier open, otherwise 0. It's recorded whether or not the barrier was actually closed.
- `future.csv`: the same columns for 2025. **Hold this file back: don't open it until you've written your answer.**

All money is in ₹ crore. The data is made up.

## Your task
1. Write a closing rule the city could follow.
2. Choose which firm to pay, and say why in one or two lines.
3. Work out what your rule would have cost over the three years.
4. Only then, open `future.csv` and score your rule on 2025.

## How to work
- Open [`prompt.md`](prompt.md), copy all of it into your AI chat, and answer its first question.
- Or start from the notebook in Colab: [Open in Colab](https://colab.research.google.com/github/AbhinnV04/quant-research-ai-workflows/blob/main/lessons/05-the-flood-barrier/starter.ipynb).
- You make the calls; the AI does the computing.
