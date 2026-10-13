# Transformer Training 05 — Learning Rate, Schedules and Batch Size

The single most important number in a run, and how it is found: a learning-rate sweep, warmup, cosine and warmup–stable–decay schedules, and the batch size, with the critical batch and the gradient noise scale measured on the model.

**Live site:** https://brendanjameslynskey.github.io/Transformer_Training_05_Learning_Rate_and_Batch_Size/

Why the learning rate matters most; the LR sweep and its stable band; warmup; cosine and WSD (interactive); measured schedules; batch size, critical batch and gradient noise scale; the linear scaling rule.

## Live, animated companion

This deck is the slide companion to [Training](https://transformer-training-explained.vercel.app/training), the second site of the Foundations track (after Decoder), where the Decoder's model trains in your browser:

- [Chapter 6: Learning rate, batch size and schedules](https://transformer-training-explained.vercel.app/training/06-learning-rate-and-schedules)

## Where the numbers come from

Every measured number on these slides comes from the site's [results.md](https://github.com/BrendanJamesLynskey/transformer-explainer/blob/main/results.md) (seeded NumPy reference runs; CI recomputes them), filled in at build time from its `results.json`. Numbers from papers are cited on the slide with a link. The model is tiny (5,376 parameters, one book, a CPU): its runs show mechanisms, not what happens at scale, and the slides say so where it matters. GPU runs of the site's Colab notebooks are pending; no GPU number appears here.

Part of the [Transformer Training sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Transformer_Training) &middot; [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs)
