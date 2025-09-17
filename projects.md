---
layout: single
title: "Projects"
classes: wide
author_profile: false
---

# Research & Analytics Projects

A curated selection spanning **bioinformatics, molecular profiling, and clinical informatics**. Each card summarizes aims, data, methods, and outcomes.

<div class="proj-grid">

<div class="proj-card">
  <div class="proj-head"><div class="icon">🧬</div><div><h3>Clinical Outcome Analytics – CKD Fibrosis</h3><div class="muted">UTMB · Nephrology · 2024–present</div></div></div>
  <p><strong>Goal.</strong> Link transcriptomic signals to outcomes and therapeutic response in CKD fibrosis.</p>
  <ul>
    <li><strong>Data:</strong> scRNA-seq + bulk RNA-seq (kidney tissue/PBMC), labs, longitudinal outcomes.</li>
    <li><strong>Methods:</strong> Scanpy/Seurat, CellRanger/STAR, DESeq2/edgeR; GSEA/Reactome/IPA; mixed-effects; elastic-net.</li>
    <li><strong>Engineering:</strong> Pipelines (Docker/Singularity) on <em>HPC SLURM</em>; QC dashboards (Tableau/Power BI).</li>
    <li><strong>Outcomes:</strong> suPAR/immune-fibrotic hypotheses; figure panels; internal clinical memos.</li>
  </ul>
  <div class="tags"><span>RNA-seq</span><span>Single-cell</span><span>GSEA</span><span>ML</span><span>Tableau</span></div>
</div>

<div class="proj-card">
  <div class="proj-head"><div class="icon">🦠</div><div><h3>COVID-19 Genome Analytics</h3><div class="muted">Research Analytics · 2023–2024</div></div></div>
  <p><strong>Goal.</strong> Identify mutation hotspots and lineage shifts to support public-health reporting.</p>
  <ul>
    <li><strong>Data:</strong> 1,000+ SARS-CoV-2 genomes + metadata.</li>
    <li><strong>Methods:</strong> Python/R pipelines for alignment, variant calling, frequency/selection; epitope & conservation mapping.</li>
    <li><strong>Stats:</strong> Time-series prevalence, logistic growth, CIs.</li>
    <li><strong>Outcomes:</strong> Weekly briefs, visual dashboards, outbreak playbook methods.</li>
  </ul>
  <div class="tags"><span>Genomics</span><span>Variants</span><span>Python</span><span>R</span><span>SAS</span></div>
</div>

<div class="proj-card">
  <div class="proj-head"><div class="icon">🧪</div><div><h3>NGS Omics Data Integration – Oncology</h3><div class="muted">Leukemia & Breast Cancer (K562, MCF-7)</div></div></div>
  <p><strong>Goal.</strong> End-to-end RNA-seq with clinical metadata for translational insights.</p>
  <ul>
    <li><strong>Pipeline:</strong> QC → alignment (STAR/Kallisto) → DE → enrichment (GSEA/DAVID/Reactome) → figures.</li>
    <li><strong>Analytics:</strong> Oncogenic signatures, module scoring, druggable target shortlists.</li>
    <li><strong>Outcomes:</strong> KPI reports for PIs; figure sets for grants/manuscripts.</li>
  </ul>
  <div class="tags"><span>RNA-seq</span><span>Oncology</span><span>Seurat/Scanpy</span><span>Reactome</span></div>
</div>

<div class="proj-card">
  <div class="proj-head"><div class="icon">🧫</div><div><h3>Immune Signaling Pathway Analysis</h3><div class="muted">Translational Immunology</div></div></div>
  <p><strong>Goal.</strong> Connect computational pathway findings with wet-lab validation.</p>
  <ul>
    <li><strong>Assays:</strong> Flow cytometry, ELISA, Western blot; cytokine panels; perturbation experiments.</li>
    <li><strong>Integration:</strong> DEG → pathway hypotheses → targeted experiments → model feedback.</li>
    <li><strong>Outcomes:</strong> Validated signatures for protocols; polished figures for IRB/CTSA proposals.</li>
  </ul>
  <div class="tags"><span>Immunology</span><span>Flow</span><span>ELISA/WB</span><span>Pathways</span></div>
</div>

<div class="proj-card">
  <div class="proj-head"><div class="icon">🧷</div><div><h3>Podocyte & Metabolic Pathway Studies</h3><div class="muted">Cross-species RNA-seq · Human + Mouse</div></div></div>
  <p><strong>Goal.</strong> Characterize conserved mechanisms in podocyte injury and metabolism.</p>
  <ul>
    <li><strong>Approach:</strong> Ortholog mapping, batch-aware integration, TF motif analysis.</li>
    <li><strong>Outcomes:</strong> Conserved modules; candidate targets prioritized for follow-up.</li>
  </ul>
  <div class="tags"><span>Metabolism</span><span>Kidney</span><span>Cross-species</span></div>
</div>

<div class="proj-card">
  <div class="proj-head"><div class="icon">💊</div><div><h3>Molecular Dynamics & Peptide Structural Analysis</h3><div class="muted">100 ns simulation</div></div></div>
  <p><strong>Goal.</strong> Assess peptide stability and folding dynamics for therapeutic design.</p>
  <ul>
    <li><strong>Findings:</strong> ↑ <em>α-helical content</em>; flexible → stable helical states.</li>
    <li><strong>Artifacts:</strong> RMSD/RMSF, secondary-structure timelines, H-bond occupancy.</li>
    <li><strong>Outcomes:</strong> Design recommendations for peptide optimization.</li>
  </ul>
  <div class="tags"><span>MD</span><span>Drug Design</span><span>Proteins</span></div>
</div>

</div>

*More code and notebooks on my* **[GitHub](https://github.com/tinks2712)**.
