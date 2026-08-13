# Day 4 — Course Lab

**Course 5 · Fine-Tune Your Model**
**Lab:** Fine-Tuning a Layer with LoRA
*(final Nigeria version, from the team Drive 2026-08-13)*

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aims-ai-research-foundations/Nigeria-workshop-1/blob/main/course-labs/day4/day4-course5-student.ipynb)

## About

Why fine-tune a pre-trained model at all, what full fine-tuning costs, and how
LoRA gets the same result for less. You watch a small pre-trained model give a
reasonable but wrong-for-your-purpose answer, count the parameters that full
fine-tuning would move, then compute one LoRA update by hand, entry by entry.
Finally you train a real adapter on a real layer, evaluate it on held-out
phrases, merge it into the weights, and swap it for a different adapter on the
same frozen model. Two optional extensions cover choosing the rank and why the
arithmetic matters at scale. Everything runs on NumPy and Matplotlib — no model
download, no GPU, no API key; the whole notebook executes in about two seconds.

## How to work through it

- Click **Open in Colab** above to launch the notebook.
- **Before running or editing anything, save your own copy: File → Save a copy
  in Drive.** The badge opens the notebook in read-only playground mode;
  without your own copy, all your work is lost when the tab closes.
- Follow the **Predict → Run → Explain** protocol for every code cell: predict
  what will happen, run it, then explain any surprises.
- **✏️ Your Turn** cells are self-contained — if you skip one, the rest of the
  notebook still runs. The core lab ends at the marked pause point; Parts 5–6
  are optional.
