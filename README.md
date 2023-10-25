**Status:** Archive (code is provided as-is, no updates expected)
_______Fix some model shiz__________
# gpt-2

Code and models from the paper ["Language Models are Unsupervised Multitask Learners"](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf).
[released a dataset](https://github.com/openai/gpt-2-output-dataset)


## Usage

This repository is meant to be a starting point for researchers and engineers to experiment with GPT-2.
This model was developed by researchers at OpenAI to help us understand how the capabilities of language model capabilities scale as a function of the size of the models (by parameter count) combined with very large internet-scale datasets (WebText).

For basic information, see [model card](./model_card.md).

### Some caveats

- GPT-2 models' robustness and worst-case behaviors are not well-understood.  As with any machine-learned model, carefully evaluate GPT-2 for your use case, especially if used without fine-tuning or in safety-critical applications where reliability is important.
- The dataset this GPT-2 model was trained on contains many texts with [biases](https://twitter.com/TomerUllman/status/1101485289720242177) and factual inaccuracies, and thus GPT-2 models are likely to be biased and inaccurate as well.

We are still considering release of the larger models.

## License

[Modified MIT](./LICENSE)
