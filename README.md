# Zero Shot Classification 0️⃣🥃
Zero-shot classification refers to the class of machine learning problems where we want our models to predict output for classes which it did not encounter during training time. 

![Alt text]([[[[https://i0.wp.com/masterdai.blog/wp-content/uploads/2024/04/Agentic-Workflow-Explain.png?resize=2048%2C1145&ssl=1](https://amitness.com/posts/images/zero-shot-vs-transfer.png)](https://user-images.githubusercontent.com/6382701/195600358-24c3f136-96f0-4a8a-8eaf-220970ca0604.png)](https://www.google.com/url?sa=i&url=https%3A%2F%2Fgithub.com%2FGT4SD%2Fzero-shot-bert-adapters&psig=AOvVaw15UXflxUTCImlWDPLBS_4i&ust=1736009923411000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCMDcyo-D2ooDFQAAAAAdAAAAABAE)](https://zeroshot.readthedocs.io/en/latest/_images/sim-1.png))

The model is trained on a set of labeled examples but is then able to classify new examples from previously unseen classes. This method leverages a pre-trained language model BART (Bidirectional and Auto-Regressive Transformers), specifically facebook/bart-large-mnli, which is a neural network model designed for natural language processing (NLP) tasks. 

BART’s versatility and strength lie in its ability to both predict missing tokens (like a masked language model) and generate sequences (like a traditional autoregressive model), making it particularly useful for tasks that require understanding and generating text.

