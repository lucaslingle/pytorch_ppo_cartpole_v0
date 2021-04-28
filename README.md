# pytorch_ppo_cartpole_v0

### Getting started
Install the dependencies:
```
pip3 install torch==1.8.1 torchvision==0.9.1
pip3 install 'gym[atari]'
```
If the second download fails, consult the issues for the openai gym repo. 
You may have a missing dependency that cannot be installed by pip, such as ```cmake```.

Once everything's installed correctly, you can train the agent via 
```
python main.py --mode=train
```
The agent will consistently attain good performance with the default settings provided.

Once the agent is trained, you can watch it play the game via
```
python main.py --mode=play
```
and a pop-up will appear.
