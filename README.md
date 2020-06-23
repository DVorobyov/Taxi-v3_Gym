# Q-learning Taxi-v3
This is the program of learning agent from the game <b>"Taxi-v3"</b>, which is situated in the library called <b>"Gym"</b>. Reinforcement 
learning, scilicet Q-learning algorithm, applied. Reinfocement learning is an area of machine learning. I used this algorithm to teach 
taxi get to the right points with minimum loss of scores. This is how the field in Taxi-v3 looks like:
<p align="center">
<img src="https://www.novatec-gmbh.de/wp-content/uploads/ezgif.com-video-to-gif.gif" width="150">
</p>
The graph of scores for the first 1000 games is presented below:
<p align="center">
<img src="https://sun1-26.userapi.com/yffDmUorQgYpyiWvPkvTFsEfUePA1teC-weMTw/U3-7IckcQDE.jpg" width="400">
</p>
It is rather unstable because of random actions during the process of learning. Have a look at averaged scores for each 100 games:
<p align="center">
<img src="https://sun1-85.userapi.com/3udP3MTcsP5Ox_BQHEFN-5RVi4vRzxKA12D70Q/766ofA2ZR-w.jpg" width="400">
</p>
Obviosly, after 400 games the agent seems to be trained enough to get high results and the next games will slowly bring agent to the most 
optimal strategy during the learning.
