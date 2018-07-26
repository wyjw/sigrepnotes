## SIG Rep Learning Notes
StatNLP
July 25 2018

## Paper
ELMo paper "Deep Contextualized word representations" \url{https://arxiv.org/abs/1802.05365} 

## Summary
- Talked about the details of the paper. Main equation is $ELMO = \gamma \sum s_j h^{LM}_{j,k}$ \\ 
- We also talked about how $s_j$ can be derived in a simple neural network layer to learn weights $A$. \\
- Briefly talked about the objective of the language model (predicting the next word based on history using softmax). \\
- Next part of the work is the discussion of performance on downstream task

## Further Work
- Any way to include sentiment context? Could we train our own ELMo equivalent? \\
- We want to leanr how to use $ELMO$ in the work.
