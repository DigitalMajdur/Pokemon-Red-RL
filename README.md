# pokemon-red-RL
inspiration: saw a guy on youtube (dont remember the name) upload a video about training an agent to play pokemon red got hooked and thought about creating one by myself and here we are an agent playing pokemon red using reinforcement learning.

it learns by trial and error, walks around the whole map, fights random pokemons, encounters wild pokemon, tries to leave "necessary" fights while proceeding to get crushed by gym trainers and rivals' pokemons; the whole journey of making
it "learn" and tries to be better like the rest of us.

i have used python, gymnasium, pyboy, stablebaselines3, openCV, torch, other useful libs and tools.

the ipynb notebook includes:
  1. environment setup and gym wrapper
  2. rewards shaping logic
  3. training pipeline using DQN
  4. interactive model with manual control

Run it locally
  1. clone this repo
  2. install requirements:

run this code in ur repo directory cmd 

pip install -r requirements.txt

