# Dataset

The movies dataset is a comprehensive collection of information about 4,803 movies. It provides a wide range of details about each movie, including budget, genres, production companies, release date, revenue, runtime, language, popularity, and more.

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/utkarshx27/movies-dataset?resource=download).

---

# Setup

To set up the environment, install the required dependencies:

```bash
pip install pandas numpy scikit-learn sentence_transformers torch
```

---

# Running

Run all the cells in the Jupyter notebook file called recommend.ipynb to generate movie recommendations based on the dataset.

---

# Results

## Sample Query:

"I love thrilling action movies set in space, with a comedic twist."

## SBERT Top-5 Matches:

Title - Galaxy Quest
Genres - Comedy, Family, Science Fiction
Keywords - space battle, spaceship, spoof, fictional tv show
Overview - The stars of a 1970s sci-fi show - now scraping a living through re-runs and sci-fi conventions - are beamed aboard an alien spacecraft. Believing the cast's heroic on-screen dramas are historical documents of real-life adventures, the band of aliens turn to the ailing celebrities for help in their quest to overcome the oppressive regime in their solar system.

Title - Aliens in the Attic
Genres - Adventure, Comedy, Family, Fantasy, Science Fiction
Keywords - alien, comedy, duringcreditsstinger, beforecreditsstinger, live action and animation
Overview - It's summer vacation, but the Pearson family kids are stuck at a boring lake house with their nerdy parents. That is until feisty, little, green aliens crash-land on the roof, with plans to conquer the house AND Earth! Using only their wits, courage and video game-playing skills, the youngsters must band together to defeat the aliens and save the world - but the toughest part might be keeping the whole thing a secret from their parents! Featuring an all-star cast including Ashley Tisdale, Andy Richter, Kevin Nealon, Tim Meadows, and Doris Roberts, Aliens In The Attic is the most fun you can have on this planet!

Title - Wing Commander
Genres - Action, Science Fiction
Keywords - fight, pilot, outer space, based on video game, space opera
Overview - The Hollywood version of the popular video game series Wing Commander. Unlike other video games to feature film transitions, series creator Chris Roberts was heavily involved in the film's creation. This is the story of Christopher Blair and Todd "Maniac" Marshall as they arrive at the Tiger Claw and are soon forced to stop a Kilrathi fleet heading towards Earth.

Title - The Ice Pirates
Genres - Action, Science Fiction, Comedy
Keywords - rebel, space, war, water, sci-fi, comedy
Overview - The time is the distant future, where by far the most precious commodity in the galaxy is water. The last surviving water planet was somehow removed to the unreachable centre of the galaxy at the end of the galactic trade wars. The galaxy is ruled by an evil emperor (John Carradine) presiding over a trade oligarchy that controls all mining and sale of ice from asteroids and comets.

Title - Cargo
Genres - Thriller, Mystery, Science Fiction
Keywords - space colony, space travel, simulated reality, spaceship, suspense
Overview - The story of CARGO takes place on the rusty space-freighter KASSANDRA on its way to Station 42. The young medic LAURA is the only one awake on board while the rest of the crew lies frozen in hibernation sleep. In 4 months, Laura's shift will be over.
