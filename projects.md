---
title: Projects
layout: single
classes: wide
---

<link rel="stylesheet" href="/assets/css/site.css">

# Research & Analytics Projects

A curated selection spanning **bioinformatics, molecular profiling, and clinical informatics**. Each card summarizes aims, data, methods, and outcomes (reports, figures, manuscripts, or clinical impact).

<div class="proj-grid">

<!-- CKD FIBROSIS -->
<div class="proj-card">
  <div class="proj-head">
    <div class="icon">🧬</div>
    <div>
      <h3>Clinical Outcome Analytics – CKD Fibrosis</h3>
      <div class="muted">UTMB · Nephrology · 2024–present</div>
    </div>
  </div>

  <p><strong>Goal.</strong> Link transcriptomic signals to patient outcomes and therapeutic response in chronic kidney disease (CKD) fibrosis.</p>

  <ul>
    <li><strong>Data.</strong> scRNA-seq + bulk RNA-seq (kidney tissue, PBMC), basic labs & demographics, longitudinal outcomes.</li>
    <li><strong>Methods.</strong> Scanpy/Seurat, CellRanger/STAR, DESeq2/edgeR; pathway analysis (GSEA/Reactome/IPA); mixed-effects models; elastic-net classifiers.</li>
    <li><strong>Engineering.</strong> Reproducible pipelines (Docker/Singularity), <em>HPC SLURM</em>; QC dashboards (Tableau/Power BI).</li>
    <li><strong>Outcomes.</strong> Biomarker hypotheses for suPAR/immune-fibrotic axes, figure panels for manuscripts, internal clinical decision memos.</li>
  </ul>

  <div class="tags">
    <span>RNA-seq</span><span>Single-cell</span><span>GSEA</span><span>ML</span><span>Tableau</span>
  </div>
</div>

<!-- COVID GENOMICS -->
<div class="proj-card">
  <div class="proj-head">
    <div class="icon">🦠</div>
    <div>
      <h3>COVID-19 Genome Analytics</h3>
      <div class="muted">Research Analytics · 2023–2024</div>
    </div>
  </div>

  <p><strong>Goal.</strong> Identify mutation hotspots and track lineage changes to support public-health reporting.</p>

  <ul>
    <li><strong>Data.</strong> >1,000 SARS-CoV-2 genomes + metadata.</li>
    <li><strong>Methods.</strong> Python/R pipelines for alignment, variant calling, frequency/selection analysis; conservation & epitope mapping.</li>
    <li><strong>Stats.</strong> Time-series prevalence, logistic growth, uncertainty bands.</li>
    <li><strong>Outcomes.</strong> Weekly briefs, visuals for institutional dashboards, methodology note for future outbreak playbooks.</li>
  </ul>

  <div class="tags">
    <span>Genomics</span><span>Phylo/Variants</span><span>Python</span><span>R</span><span>SAS</span>
  </div>
</div>

<!-- ONCOLOGY INTEGRATION -->
<div class="proj-card">
  <div class="proj-head">
    <div class="icon">🧪</div>
    <div>
      <h3>NGS Omics Data Integration – Oncology</h3>
      <div class="muted">Leukemia & Breast Cancer (K562, MCF-7)</div>
    </div>
  </div>

  <p><strong>Goal.</strong> Build end-to-end RNA-seq pipelines and merge omics results with clinical metadata for translational insights.</p>

  <ul>
    <li><strong>Pipeline.</strong> QC → alignment (STAR/Kallisto) → DE → enrichment (GSEA/DAVID/Reactome) → concise figures.</li>
    <li><strong>Analytics.</strong> Pathway/oncogenic signatures, module scoring, druggable targets shortlists.</li>
    <li><strong>Outcomes.</strong> KPI-driven reports for PIs, figure sets for manuscripts & grant appendices.</li>
  </ul>

  <div class="tags">
    <span>RNA-seq</span><span>Oncology</span><span>Seurat/Scanpy</span><span>Reactome</span>
  </div>
</div>

<!-- IMMUNE SIGNALING -->
<div class="proj-card">
  <div class="proj-head">
    <div class="icon">🧫</div>
    <div>
      <h3>Immune Signaling Pathway Analysis</h3>
      <div class="muted">Translational Immunology</div>
    </div>
  </div>

  <p><strong>Goal.</strong> Connect computational pathway findings with wet-lab validation.</p>

  <ul>
    <li><strong>Assays.</strong> Flow cytometry, ELISA, Western blot; cytokine panels; perturbation experiments.</li>
    <li><strong>Integration.</strong> DEG → pathway hypotheses → targeted experiments → feedback into models.</li>
    <li><strong>Outcomes.</strong> Validated signatures for clinical protocols; polished figures for IRB/CTSA proposals.</li>
  </ul>

  <div class="tags">
    <span>Immunology</span><span>Flow</span><span>ELISA/WB</span><span>Pathways</span>
  </div>
</div>

<!-- PODOCYTE / METABOLIC -->
<div class="proj-card">
  <div class="proj-head">
    <div class="icon">🧷</div>
    <div>
      <h3>Podocyte & Metabolic Pathway Studies</h3>
      <div class="muted">Cross-species RNA-seq · Human + Mouse</div>
    </div>
  </div>

  <p><strong>Goal.</strong> Characterize conserved mechanisms in podocyte injury and metabolism relevant to kidney disease.</p>

  <ul>
    <li><strong>Approach.</strong> Ortholog mapping, batch-aware integration, pathway & TF motif analysis.</li>
    <li><strong>Outcomes.</strong> Shortlist of conserved modules; candidate targets prioritized for follow-up studies.</li>
  </ul>

  <div class="tags">
    <span>Metabolism</span><span>Kidney</span><span>Cross-species</span>
  </div>
</div>

<!-- MOLECULAR DYNAMICS -->
<div class="proj-card">
  <div class="proj-head">
    <div class="icon">💊</div>
    <div>
      <h3>Molecular Dynamics & Peptide Structural Analysis</h3>
      <div class="muted">100 ns simulation</div>
    </div>
  </div>

  <p><strong>Goal.</strong> Assess peptide stability and folding dynamics for therapeutic design.</p>

  <ul>
    <li><strong>Findings.</strong> Increased <em>α-helical content</em>; flexible early states → stable helical conformations.</li>
    <li><strong>Artifacts.</strong> RMSD/RMSF trends, secondary-structure timelines, H-bond occupancy.</li>
    <li><strong>Outcomes.</strong> Design recommendations for peptide optimization.</li>
  </ul>

  <div class="tags">
    <span>MD</span><span>Drug Design</span><span>Proteins</span>
  </div>
</div>

</div>

---

*More projects, code samples, and notebooks are available on my* **[GitHub](https://github.com/tinks2712)**.
