---
layout: default
title: YOUR DATASET NAME — Official Page
description: "YOUR DATASET NAME: a high-quality dataset for TASKS. Download, browse samples, view leaderboard, and cite the paper."
image: /assets/teaser.jpg
---

<!-- Hero -->
<section class="hero-bg">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24">
    <div class="grid lg:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-3xl sm:text-5xl font-extrabold tracking-tight leading-tight">YOUR DATASET NAME</h1>
        <p class="mt-5 text-lg text-slate-600 dark:text-slate-300">一句话简介：一句话说明你的数据集是什么、解决什么问题、规模多大、适用哪些任务。</p>
        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#download" class="inline-flex items-center px-4 py-2 rounded-xl bg-blue-600 text-white hover:bg-blue-700">下载</a>
          <a href="#gallery" class="inline-flex items-center px-4 py-2 rounded-xl bg-slate-900 text-white dark:bg-white dark:text-slate-900 hover:opacity-90">浏览样例</a>
          <a href="#paper" class="inline-flex items-center px-4 py-2 rounded-xl border border-slate-300 dark:border-slate-700">论文</a>
          <a href="https://github.com/yourname/yourrepo" target="_blank" class="inline-flex items-center px-4 py-2 rounded-xl border border-slate-300 dark:border-slate-700">GitHub</a>
        </div>
      </div>
      <div class="relative">
        <img src="{{ '/assets/teaser.jpg' | relative_url }}" alt="Teaser" class="w-full rounded-2xl shadow-soft border border-slate-200/70 dark:border-slate-800/70"/>
      </div>
    </div>
  </div>
</section>

<!-- About -->
<section id="about" class="py-16 sm:py-20">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid lg:grid-cols-3 gap-10 items-start">
      <div class="lg:col-span-2">
        <h2 class="text-2xl font-bold">简介</h2>
        <p class="mt-4 text-slate-600 dark:text-slate-300">这里写详细介绍：数据来源、采集/标注方式、任务定义（分类/检测/分割/问答等）、与现有数据集相比的差异与优势。</p>
        <ul class="mt-4 list-disc pl-5 space-y-2 text-slate-600 dark:text-slate-300">
          <li>规模：<b>XX 万张/条</b>，覆盖 <b>XX 类/领域</b></li>
          <li>标注：边界框/掩码/属性/文本等</li>
          <li>适用任务：检测、分割、检索、多模态问答……</li>
        </ul>
      </div>
      <div class="p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70 shadow-soft">
        <h3 class="font-semibold">快速上手</h3>
        <pre class="mt-3 text-sm bg-slate-900 text-white p-4 rounded-xl overflow-x-auto"><code># pip
pip install your-dataset-helper

# Python
from your_dataset import load
train, val, test = load("/path/to/your/dataset")
</code></pre>
      </div>
    </div>
  </div>
</section>

<!-- Stats -->
<section id="stats" class="py-12 bg-white/60 dark:bg-slate-900/60">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid grid-cols-2 sm:grid-cols-4 gap-6">
      <div class="p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70 text-center">
        <div class="text-3xl font-extrabold">100k</div>
        <div class="text-slate-500 mt-1">样本数</div>
      </div>
      <div class="p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70 text-center">
        <div class="text-3xl font-extrabold">1.2M</div>
        <div class="text-slate-500 mt-1">标注实例</div>
      </div>
      <div class="p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70 text-center">
        <div class="text-3xl font-extrabold">50+</div>
        <div class="text-slate-500 mt-1">类别/属性</div>
      </div>
      <div class="p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70 text-center">
        <div class="text-3xl font-extrabold">CC-BY-4.0</div>
        <div class="text-slate-500 mt-1">许可协议</div>
      </div>
    </div>
  </div>
</section>

<!-- Gallery -->
<section id="gallery" class="py-16 sm:py-20">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex items-center justify-between">
      <h2 class="text-2xl font-bold">样例</h2>
      <a href="#download" class="text-sm text-blue-600 hover:underline">去下载 →</a>
    </div>
    <div class="mt-6 grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-4">
      <img src="{{ '/assets/samples/sample1.jpg' | relative_url }}" class="w-full h-40 object-cover rounded-xl border border-slate-200/70 dark:border-slate-800/70" alt="sample1"/>
      <img src="{{ '/assets/samples/sample2.jpg' | relative_url }}" class="w-full h-40 object-cover rounded-xl border" alt="sample2"/>
      <img src="{{ '/assets/samples/sample3.jpg' | relative_url }}" class="w-full h-40 object-cover rounded-xl border" alt="sample3"/>
      <img src="{{ '/assets/samples/sample4.jpg' | relative_url }}" class="w-full h-40 object-cover rounded-xl border" alt="sample4"/>
    </div>
  </div>
</section>

<!-- Download -->
<section id="download" class="py-16 sm:py-20 bg-white/60 dark:bg-slate-900/60">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-2xl font-bold">下载</h2>
    <p class="mt-3 text-slate-600 dark:text-slate-300">推荐将大文件放在 GitHub Releases / Hugging Face / Zenodo / OSS，页面只放外链。</p>
    <div class="mt-6 grid gap-4 sm:grid-cols-2">
      <a href="https://huggingface.co/datasets/yourname/your-dataset" target="_blank" class="p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70 hover:shadow-soft">
        <div class="font-semibold">Hugging Face</div>
        <div class="text-sm text-slate-500">首选镜像 / 分片下载 / metadata</div>
      </a>
      <a href="https://github.com/yourname/yourrepo/releases" target="_blank" class="p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70 hover:shadow-soft">
        <div class="font-semibold">GitHub Releases</div>
        <div class="text-sm text-slate-500">官方发布包 / checksums</div>
      </a>
    </div>
    <div class="mt-6 p-5 card bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70">
      <div class="font-semibold">校验与解压</div>
      <pre class="mt-3 text-sm bg-slate-900 text-white p-4 rounded-xl overflow-x-auto"><code># 校验
sha256sum your-dataset-*.tar.gz
# 解压
mkdir data && tar -xzf your-dataset-00001.tar.gz -C data
</code></pre>
    </div>
  </div>
</section>

<!-- Leaderboard -->
<section id="leaderboard" class="py-16 sm:py-20">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex items-center justify-between">
      <h2 class="text-2xl font-bold">Leaderboard</h2>
      <a href="https://github.com/yourname/yourrepo/issues/new?template=submit_result.md" target="_blank" class="text-sm text-blue-600 hover:underline">提交结果</a>
    </div>
    <div class="mt-6 overflow-x-auto">
      <table class="min-w-full text-sm border-separate border-spacing-y-2">
        <thead class="text-left text-slate-500">
          <tr>
            <th class="py-2 pr-6">Rank</th>
            <th class="py-2 pr-6">Method</th>
            <th class="py-2 pr-6">Backbone</th>
            <th class="py-2 pr-6">Metric@1</th>
            <th class="py-2 pr-6">Metric@2</th>
            <th class="py-2 pr-6">Paper</th>
            <th class="py-2 pr-6">Code</th>
          </tr>
        </thead>
        <tbody>
          <tr class="bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70">
            <td class="py-3 px-3">1</td>
            <td class="py-3 px-3 font-medium">Your Method</td>
            <td class="py-3 px-3">ConvNeXt</td>
            <td class="py-3 px-3">98.7</td>
            <td class="py-3 px-3">94.2</td>
            <td class="py-3 px-3"><a href="#" class="text-blue-600">arXiv</a></td>
            <td class="py-3 px-3"><a href="#" class="text-blue-600">GitHub</a></td>
          </tr>
          <tr class="bg-white dark:bg-slate-900 border border-slate-200/70 dark:border-slate-800/70">
            <td class="py-3 px-3">2</td>
            <td class="py-3 px-3 font-medium">Baseline</td>
            <td class="py-3 px-3">ResNet50</td>
            <td class="py-3 px-3">95.0</td>
            <td class="py-3 px-3">90.1</td>
            <td class="py-3 px-3"><a href="#" class="text-blue-600">arXiv</a></td>
            <td class="py-3 px-3"><a href="#" class="text-blue-600">GitHub</a></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</section>

<!-- Citation -->
<section id="citation" class="py-16 sm:py-20 bg-white/60 dark:bg-slate-900/60">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-2xl font-bold">引用</h2>
    <p class="mt-3 text-slate-600 dark:text-slate-300">如果本数据集对你的研究有帮助，请引用我们的论文：</p>
    <pre class="mt-4 text-sm bg-slate-900 text-white p-4 rounded-xl overflow-x-auto"><code>@inproceedings{yourdataset2025,
  title={YOUR DATASET NAME: Subtitle},
  author={Your, Name and Coauthor, Name},
  booktitle={Conference Name},
  year={2025}
}
</code></pre>
  </div>
</section>

<!-- License -->
<section id="license" class="py-16 sm:py-20">
  <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
    <h2 class="text-2xl font-bold">许可</h2>
    <p class="mt-3 text-slate-600 dark:text-slate-300">建议使用 <b>CC BY 4.0</b> 或与数据来源兼容的其它许可证。清晰说明商业使用、再分发与隐私合规要求。</p>
    <ul class="mt-3 list-disc pl-5 text-slate-600 dark:text-slate-300 space-y-1">
      <li>允许研究用途与再分发，需注明来源。</li>
      <li>禁止试图重识别个人；如包含个人信息，需遵循数据使用协议。</li>
    </ul>
  </div>
</section>
