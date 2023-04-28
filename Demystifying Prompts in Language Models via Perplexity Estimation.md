The document is about understanding and improving the performance of language model prompts. The authors hypothesize that lower perplexity prompts work better and show this empirically across different tasks and models. They also propose a method to generate low-perplexity prompts using paraphrasing and backtranslation. The method does not require labels and improves accuracy by up to 3.6 points on average.

# What is the main hypothesis of the paper?
According to the web search results, the main hypothesis of the paper is that **the performance of a prompt is coupled with the extent to which the model is familiar with the language it contains**¹². The authors claim that **the lower the perplexity of the prompt is, the better the prompt is able to perform the task**¹². They test this hypothesis on a large number of tasks and language models, and show a significant negative correlation between perplexity and performance¹².

源: 与必应的对话， 2023/4/28(1) Demystifying Prompts in Language Models via Perplexity .... https://arxiv.org/abs/2212.04037 访问时间 2023/4/28.
(2) Demystifying Prompts in Language Models via Perplexity .... https://arxiv.org/pdf/2212.04037.pdf 访问时间 2023/4/28.
(3) [2212.04037] Demystifying Prompts in Language Models via .... http://export.arxiv.org/abs/2212.04037 访问时间 2023/4/28.

# How did the researchers defined the Perplexity?
According to the web search results, the researchers defined the perplexity of the prompt as **the perplexity of the full prompt sequence, including the input itself, and without the label, averaged over 1,000 examples**². They used this definition for both word prediction and classification tasks². They also explained that they included the input as part of the prompt to ground the prompt to the task, and that they excluded the label because it is not part of the prompt and it is not required for their method².

源: 与必应的对话， 2023/4/28(1) Demystifying Prompts in Language Models via Perplexity .... https://arxiv.org/pdf/2212.04037.pdf 访问时间 2023/4/28.
(2) Demystifying Prompts in Language Models via Perplexity .... https://arxiv.org/abs/2212.04037 访问时间 2023/4/28.
(3) [2212.04037] Demystifying Prompts in Language Models via .... http://export.arxiv.org/abs/2212.04037 访问时间 2023/4/28.