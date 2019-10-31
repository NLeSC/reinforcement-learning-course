## 2019-10-31
It runs! We now have a working 0-step or td(0) implementation. We think. It runs and it seems to update the value in the regressor when we take a look at the plots. We only did 5 roll outs yet so it of course didn't receive anything better than -200 yet as a total reward.
Start with running more roll outs. See if it ever learns something better. After that we should build in support for more than 0 steps, so n-step.

## 2019-10-10
We wrote code to the same document that runs without error. It probably runs the mountain car example for 1 iteration. We should add multiple iterations and of course the whole n-logic update/predict logic. Also check with visualization whether it actually does a rollout.

## 2019-09-26
We went through the code we wrote up to now and looked for the video to start with after our long break. We decided not to go into tensorflow right now and try to do with the knowledge (of keras) that we already got when we need networks. We therefore continued with the next subject which is TD-lambda and n-step. We had a look at the code of the lazyprogrammer to get an idea of what we should do for n-step. We made a stub for the code we have to write. See the notebook christiaan/n-step.ipynb . 
