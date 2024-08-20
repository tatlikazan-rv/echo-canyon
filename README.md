# Setup
```
conda create -n echo_canyon python=3.12.4
pip install transformers
pip install tensorflow
pip install tf-keras
pip install pronouncing
pip install selenium
pip install bs4
pip install torch
```

# Usage 
run ```demo_lyric_generation.ipynb```

*selections are done by numbers

*dont forget to make cell output scrollable to see the updates

UI:
- select "0:i have lyrics im working on"

- paste from "test_lyrics.txt"

- select any genre (models arent uploaded, so it defaults to 
"runokreiner/lyrics-bert" from hf for simplicity)

- skip generation directly for features


try out the features:

- put \<placeholder> for a line

- erase line

- swap lines

- replace words (with recommendations based on the given line)

- rhyming with pronouncing which utilizes pronunciation of the 
syllabes to give the creator word assiciation ideas

- rhyming utilizing RhymeZone.com by looking most popular words that rhyme with the chosen word
