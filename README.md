# Modelling Sentence Pairs via Reinforcement Learning: An Actor-Critic Approach to Learn the Irrelevant Words

## Mahtab Ahmed and Robert E. Mercer

Learning sentence representation is a fundamental task in Natural Language Processing. Most of the existing sentence pair modelling architectures focus only on extracting and using the rich sentence pair features. The drawback of utilizing all of these features makes the learning process much harder. In this study, we propose a reinforcement learning (RL) method to learn a sentence pair representation when performing tasks like semantic similarity, paraphrase identification, and question-answer pair modelling. We formulate this learning problem as a sequential decision making task where the decision made in the current state will have a strong impact on the following decisions. We address this decision making with a policy gradient RL method which chooses the irrelevant words to delete by looking at the sub-optimal representation of the sentences being compared. With this policy, extensive experiments show that our model achieves on par performance when learning task-specific representations of sentence pairs without needing any further knowledge like parse trees. We suggest that the simplicity of each task inference provided by our RL model makes it easier to explain.

Accepted in AAAI20
