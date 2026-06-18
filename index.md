---
layout: default
title: "Bosmina Integrative Delimitation"
description: "Supplementary materials for integrative species delimitation of Bosmina"
---

# 🧬 Bosmina Integrative Delimitation
**Supplementary Materials & Interactive Visualizations**

Welcome to the supplementary materials repository for integrative species delimitation analysis of *Bosmina* (Cladocera: Bosminidae). This repository contains all data, scripts, and results supporting our research.

---

## 📂 Repository Structure

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 25px; margin: 40px 0;">

<div style="border: 3px solid #1F78B4; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
<h3 style="color: #1F78B4; margin-top: 0; display: flex; align-items: center;">📊 Raw Data</h3>
<p><strong>Location:</strong> <code>/data/</code></p>
<p>Original delimitation results, sequence alignments, and input files for all analyses.</p>
<ul style="margin-bottom: 20px;">
<li>Delimitation results per method (CSV)</li>
<li>Sequence alignments (FASTA)</li>
<li>Phylogenetic trees (Newick)</li>
<li>Metadata and annotations</li>
</ul>
<a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/data" style="display: inline-block; background: #1F78B4; color: white; padding: 12px 24px; text-decoration: none; border-radius: 8px; font-weight: bold; text-align: center; width: 100%; box-sizing: border-box;">Browse Raw Data →</a>
</div>

<div style="border: 3px solid #E41A1C; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
<h3 style="color: #E41A1C; margin-top: 0; display: flex; align-items: center;">💻 Scripts</h3>
<p><strong>Location:</strong> <code>/scripts/</code></p>
<p>Complete source code for all computational analyses and visualization pipelines.</p>
<ul style="margin-bottom: 20px;">
<li>R scripts for data processing</li>
<li>Agreement matrix calculation</li>
<li>Phylogenetic visualization</li>
<li>Statistical analysis pipelines</li>
</ul>
<a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/scripts" style="display: inline-block; background: #E41A1C; color: white; padding: 12px 24px; text-decoration: none; border-radius: 8px; font-weight: bold; text-align: center; width: 100%; box-sizing: border-box;">View Scripts →</a>
</div>

<div style="border: 3px solid #4DAF4A; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
<h3 style="color: #4DAF4A; margin-top: 0; display: flex; align-items: center;">📈 Results</h3>
<p><strong>Location:</strong> <code>/results/</code></p>
<p>Comprehensive analysis outputs including tables, figures, and interactive visualizations.</p>
<ul style="margin-bottom: 20px;">
<li><a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/results/delimitation">Delimitation summaries</a></li>
<li><a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/results/statistics">Statistical reports</a></li>
<li><a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/results/trees">Phylogenetic trees</a></li>
<li><a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/results/interactive"><strong>Interactive visualizations</strong></a></li>
</ul>
<a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/results" style="display: inline-block; background: #4DAF4A; color: white; padding: 12px 24px; text-decoration: none; border-radius: 8px; font-weight: bold; text-align: center; width: 100%; box-sizing: border-box;">Explore Results →</a>
</div>

</div>

---

## 🎭 Interactive Visualizations

Explore all interactive figures and dashboards from this study. Each visualization is fully zoomable and provides detailed tooltips with taxon names and analysis metrics.

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; margin: 40px 0;">

<div style="border: 3px solid #984EA3; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #f5f3ff 0%, #ede9fe 100%); box-shadow: 0 4px 8px rgba(152,78,163,0.2);">
<h4 style="color: #984EA3; margin-top: 0;">🌳 Agreement Matrix + Phylogeny</h4>
<p>Interactive heatmap showing congruence between delimitation methods, synchronized with clade-colored phylogenetic tree.</p>
<ul style="font-size: 0.9em; margin-bottom: 20px;">
<li>Hover taxa for agreement details</li>
<li>Colors represent major clades</li>
<li>Fully zoomable interface</li>
</ul>
<a href="results/interactive/Delimitation_heatmap_bgmyc_tree.html" style="display: inline-block; background: #984EA3; color: white; padding: 10px 20px; text-decoration: none; border-radius: 6px; font-weight: bold; text-align: center; width: 100%; box-sizing: border-box;">Open →</a>
</div>

<div style="border: 3px solid #FF7F00; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #fff5f0 0%, #ffe8d6 100%); box-shadow: 0 4px 8px rgba(255,127,0,0.2);">
<h4 style="color: #FF7F00; margin-top: 0;">📊 Congruence Summary</h4>
<p>Interactive summary of agreement between all delimitation methods with detailed statistics.</p>
<ul style="font-size: 0.9em; margin-bottom: 20px;">
<li>Method comparison charts</li>
<li>Agreement scores visualization</li>
<li>Filterable by clade</li>
</ul>
<a href="results/interactive/congruence_summary.html" style="display: inline-block; background: #FF7F00; color: white; padding: 10px 20px; text-decoration: none; border-radius: 6px; font-weight: bold; text-align: center; width: 100%; box-sizing: border-box;">Open →</a>
</div>

<div style="border: 3px solid #A65628; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #f5f0e8 0%, #ede4d3 100%); box-shadow: 0 4px 8px rgba(166,86,40,0.2);">
<h4 style="color: #A65628; margin-top: 0;">🌲 Phylogenetic Tree Explorer</h4>
<p>Interactive phylogenetic tree with clade annotations and branch support values.</p>
<ul style="font-size: 0.9em; margin-bottom: 20px;">
<li>Zoomable tree structure</li>
<li>Clade color coding</li>
<li>Branch length information</li>
</ul>
<a href="results/interactive/phylo_tree_interactive.html" style="display: inline-block; background: #A65628; color: white; padding: 10px 20px; text-decoration: none; border-radius: 6px; font-weight: bold; text-align: center; width: 100%; box-sizing: border-box;">Open →</a>
</div>

<div style="border: 3px solid #F781BF; border-radius: 15px; padding: 25px; background: linear-gradient(135deg, #fff0f7 0%, #ffe4f0 100%); box-shadow: 0 4px 8px rgba(247,129,191,0.2);">
<h4 style="color: #F781BF; margin-top: 0;">📈 Species Accumulation</h4>
<p>Interactive species accumulation curves showing how delimitation results change with method number.</p>
<ul style="font-size: 0.9em; margin-bottom: 20px;">
<li>Dynamic curve plotting</li>
<li>Method addition timeline</li>
<li>Confidence intervals</li>
</ul>
<a href="results/interactive/species_accumulation.html" style="display: inline-block; background: #F781BF; color: white; padding: 10px 20px; text-decoration: none; border-radius: 6px; font-weight: bold; text-align: center; width: 100%; box-sizing: border-box;">Open →</a>
</div>

</div>

<p style="text-align: center; margin-top: 20px;">
<a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/tree/main/results/interactive" style="color: #666; text-decoration: none; font-size: 0.9em;">📁 Browse all interactive files →</a>
</p>

---

## 📚 About This Study

| **Organisms** | *Bosmina* spp. (Cladocera: Bosminidae) |
|---------------|----------------------------------------|
| **Focus** | Integrative species delimitation |
| **Clades** | *Eubosmina*, *Liederobosmina*, *Lunobosmina*, Colombian clade |
| **Methods** | ABGD, ASAP, bPTP, GMYC, PTP, and others |
| **License** | [GNU GPL v3.0](https://github.com/DmitryKarabanov/Bosmina_delimitaions/blob/main/LICENSE) |

---

## 👨‍🔬 Contact & Citation

**Dmitry Karabanov**

For questions about the data, scripts, or analysis, please [open an issue on GitHub](https://github.com/DmitryKarabanov/Bosmina_delimitaions/issues).

### How to Cite

If you use these data or scripts in your research, please cite:

> Karabanov D. et al. (2026). Integrative species delimitation of *Bosmina*... *[Journal name, in press]*

---

<p style="text-align: center; color: #666; font-size: 0.9em; margin-top: 50px; padding: 20px; border-top: 2px solid #eee;">
<em>This supplementary material is openly available under the <a href="https://github.com/DmitryKarabanov/Bosmina_delimitaions/blob/main/LICENSE">GNU GPL v3.0 License</a>. Last updated: 2026.</em>
</p>
