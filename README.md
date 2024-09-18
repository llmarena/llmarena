# LLM Arena: Benchmarking LLM Models in Russian

**LLM Arena** ([https://llmarena.ru/](https://llmarena.ru/)) is an open crowd-sourced platform designed for evaluating large language models (LLMs) in the Russian language. Our goal is to provide an objective, open, and up-to-date benchmark of LLM models tailored for the Russian language.

## Features

The platform offers three main features:

1. **Anonymous Chat ([https://llmarena.ru/?arena](https://llmarena.ru/?arena)):** Users can engage in a blind test, posing questions to two anonymous models simultaneously. This allows for unbiased comparisons and helps us gather valuable user feedback for building our leaderboard.
2. **Named Chat ([https://llmarena.ru/?compare](https://llmarena.ru/?compare)):** Users can select specific models to chat with side-by-side, allowing for direct comparisons and a more controlled evaluation experience.
3. **Leaderboard ([https://llmarena.ru/?leaderboard](https://llmarena.ru/?leaderboard)):** The platform displays a leaderboard based on the Elo rating system and the Bradley-Terry model, showcasing the rankings of different LLMs based on the aggregated user evaluations.

   - **Arena Hard Benchmark:** This offline benchmark utilizes a more potent model to evaluate the performance of other models based on a curated set of 500 prompts.
   - **Data Visualization:** The leaderboard section also features four plots visualizing the performance of models across different categories.

## How It Works

1. **User Interaction:** Users interact with LLMs in either the anonymous or named chat setting.
2. **User Evaluation:** Users rate which model provided a better response.
3. **Data Collection:** The platform collects these user evaluations.
4. **Leaderboard Generation:** The Elo rating system and Bradley-Terry model use the collected data to rank the LLMs and generate the leaderboard.

![Screenshot of the LLM Arena menu](https://storage.yandexcloud.net/llmarena/arena_screenshot.png) 
