# N-Gram Playground

N-Gram language models model the structure of a language by modeling the probabilities of words depending on a history of the previous n - 1 words. This simple approach, with a statistical model that is extremely easy to estimate from some givent text, nevertheless manages to capture a good deal of what makes language language.

N-Gram language models can be used to estimate the probability of a given sentence ("how likely am I to see this sentence in this language"). They can also be used generatively, by starting with a seed phrase and then picking additional words according to the probability the n-gram LM would assign them given the current context.

This file contains some code to estimate an n-gram LM from a given text or some hard-coded sentences, which can then be used to estimate the probability of a sentence. It also contains code for generating text, which can also be used to verify the probability of a sentence actually appearing.
