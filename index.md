---
layout: default
title: YOUR DATASET NAME
---

# YOUR DATASET NAME

A concise one-paragraph overview of the dataset, tasks, scale, and why it matters.

<img src="{{ '/assets/teaser.jpg' | relative_url }}" alt="Teaser" class="rounded-lg border border-slate-200 dark:border-slate-800">

---

## About {#about .anchor}

- **Tasks**: classification / detection / segmentation / retrieval / VQA …
- **Scale**: 100k samples, 1.2M annotations, 50+ categories
- **Collection / Annotation**: briefly describe sources and labeling
- **Intended Use**: research and benchmarking

Links: [GitHub](https://github.com/yourname/yourrepo) · [Paper](https://arxiv.org/abs/xxxx.xxxxx) · [Dataset (HF)](https://huggingface.co/datasets/yourname/your-dataset)

---

## Dataset {#dataset .anchor}

**Download**

- Hugging Face: <https://huggingface.co/datasets/yourname/your-dataset>  
- GitHub Releases: <https://github.com/yourname/yourrepo/releases>

**Verify & Extract**
```bash
sha256sum your-dataset-*.tar.gz
mkdir data && tar -xzf your-dataset-00001.tar.gz -C data
