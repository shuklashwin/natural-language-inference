# Natural Language Inference
Training a Natural Language Inference ([NLI](https://arxiv.org/abs/2005.12116)) model based on BERT that takes a multilingual set of a premise and a hypothesis and classifies the hypothesis as being an entailment, neutral or a contradiction to the premise. This is an ongoing Kaggle competition: [Contradictory, My Dear Watson.](https://www.kaggle.com/c/contradictory-my-dear-watson/overview)

# Description of Dataset
This dataset contains premise-hypothesis pairs in fifteen different languages, including: Arabic, Bulgarian, Chinese, German, Greek, English, Spanish, French, Hindi, Russian, Swahili, Thai, Turkish, Urdu, and Vietnamese. The training dataset contains 12120 rows with a fairly even split of the 3 output classes.

In all cases, the input will be pairs of sentences in the form of a premise and a hypothesis; and the output will be the classification of the relationship between the premise and hypothesis. The class labels are: 0 for entailment, 1 for neutral, 2 for contradiction.
