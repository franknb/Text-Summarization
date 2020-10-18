# Text-Summarization

As described, a testing place for different text summarization tools.

1. **DistilBERT** from ***transformers***

**What is DistilBERT?**: 

Distil here means (Knowledge) Distillation, just as the literal means, is a compression technique in which a small model is trained to reproduce the behavior of a larger model (or an ensemble of models). It was first introduced in (https://www.cs.cornell.edu/~caruana/compression.kdd06.pdf), then generalized in (https://arxiv.org/abs/1503.02531)

BERT here stands for ***Bidirectional Encoder Representations from Transformers***, is applying the bidirectional training of Transformer (https://arxiv.org/pdf/1706.03762.pdf), a popular attention model, to language modelling. This is in contrast to previous efforts which looked at a text sequence either from left to right or combined left-to-right and right-to-left training. The paper’s results show that a language model which is bidirectionally trained can have a deeper sense of language context and flow than single-direction language models.

**Documentation**: https://huggingface.co/transformers/model_doc/distilbert.html

**Original paper**: Victor Sanh, Lysandre Debut, Julien Chaumond, Thomas Wolf: "DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter", 2020. https://arxiv.org/abs/1910.01108


**Model name**: sshleifer/distilbart-cnn-12-6 (https://huggingface.co/sshleifer/distilbart-cnn-12-6#)
