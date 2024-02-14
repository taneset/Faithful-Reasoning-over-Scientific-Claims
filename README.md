# Faithful-Reasoning-over-Scientific-Claims

## EMMA (*E*thics, *M*orality and beyond: a *M*achine *A*dvisor)

### What is EMMA?
While many AI models are trained to predict a single, definitive answer for each given query, in real life, we often encounter dilemmas and many situations where there are no black or white answers. We introduce, EMMA, a machine advisor that goes beyond such one-dimensional decisons and uncovers answers and perpectives incl. the underlying belief network of a model in complex situations.


### How does EMMA work?

![Flow](/reason/PNG/high.png)
<img src="reason/PNG/high.png" alt="drawing" width="200"/>

EMMA materializes the beliefs of the model for an input statement, uncovering different assumptions and perspectives. It then builds a network of beliefs, and that structure is critiqued using self-feedback (such as structural consistency, self-beliefs) and human feedback (such as thumbs down). Together with this critique, the network of beliefs is then improved using maxsat based reasoning to generate the most consistent belief network as output. [Read more about EMMA](https://drive.google.com/file/d/1UmV5Y9b68mdADAnUdW6nNSFVZ4END9Bs/view?usp=sharing)

### Using EMMA (Demo video)

Watch a 2 minutes short video for a demonstration EMMA.

<iframe width="700px" height="500px" src="https://user-images.githubusercontent.com/22459345/183147600-540e0552-8d8a-482d-acd3-b0230fbe4db2.mp4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



### Try out EMMA!
Click [`here`](https://allenai-defeasible-explanations-srcvdemo-interactive-jpe7t4.streamlitapp.com/?on_demand=false) to try out EMMA!
