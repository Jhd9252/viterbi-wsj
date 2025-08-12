#### General

The Viterbi algorithm is a dynamic programming algorithm that finds the most likely sequence of hidden events that would explain a sequence of observed events. It stores each probability of the most likely state sequence dynamically.

The algorithm recursively computes the probability of the most likely sequence step by taking into account the intitial, transistion and emission probabilities. 

The result of the algorithm is often called the Viterbi path. It is most commonly used with hidden Markov models.  

The key components are:

1. Hidden Markov Model (HMM): The algorithm is typically used in the context of these models. In essence, it consists of a set of hidden states, and a second set of observable emissions (outputs). 
2. Transition Probabilities: The probabilities of moving from a specific hidden state to another. 
3. Emission Probabilities: The probabilities of observing a particular output given a state. 
4. Initial Probabilities: The starting probabilities of each hidden state. 

Overall Result: 30806 out of 32853 tags correct or an accuracy of 93.77%

#### Corpus: 


The most standard breakdown for training and test purposes of the PennTreebank Corpus is:

- Sections 02-21 Training
- Section 23 Test
- Section 24 Development

WSJ_02-21.pos  -- to use as the training corpus

WSJ_24.words   -- to use as your development set (for testing your system)

WSJ_24.pos     -- to use to check how well your system is doing

WSJ_23.words -- to run your system on.  You should produce a file in the .pos format as your output and submit it as per the submission instructions to be announced.
