# 🧬 Bioinformatics & Multi-Omics Interactive Learning Hub

A production-grade, interactive learning laboratory, visual simulator suite, and reproducible pipeline platform for **Genomics, Transcriptomics, Proteomics, Metagenomics, and Structural Biology**.

🌐 **Live Hub**: [https://angsumi.online/bioinformatics/](https://angsumi.online/bioinformatics/)  
💻 **Repository**: [https://github.com/Angsumi/bioinformatics](https://github.com/Angsumi/bioinformatics)

---

## 🚀 The 10 Interactive Master Labs

| # | Master Interactive Lab | Primary Scope | Key Interactive Calculators & Simulators | Direct Link |
|---|------------------------|---------------|------------------------------------------|-------------|
| **1** | **QIIME 2 Master Lab** | 16S, 18S, ITS Amplicon Science | DADA2 Overlap Calculator, Rarefaction Depth Advisor, Live Manifest Generator, Sample Metadata Builder | [`/qiime2`](./qiime2/) |
| **2** | **SAMtools & BAMtools Suite** | High-Throughput Alignment Utilities | 12-Bit Bitwise SAM Flag Calculator & Decoder, Lander-Waterman Depth & Coverage Estimator | [`/samtools`](./samtools/) |
| **3** | **HISAT2 Spliced Alignment** | Splice-Aware RNA-Seq Mapping | Strandedness & dUTP Protocol Configurator, HGFM Splice Index Memory Estimator | [`/hisat2`](./hisat2/) |
| **4** | **Bowtie & Bowtie 2 Suite** | Short-Read Alignment & Decontamination | Alignment Score Threshold Calculator, Metagenomic Host Depletion Simulator | [`/bowtie2`](./bowtie2/) |
| **5** | **DESeq2 & EdgeR Workbench** | RNA-Seq Differential Expression | Interactive SVG Volcano Plot with Cutoff Sliders, Experimental Design Formula & Contrast Generator | [`/deseq2`](./deseq2/) |
| **6** | **Quantitative Proteomics Lab** | LC-MS/MS Bottom-Up Proteomics | Peptide Monoisotopic Mass, Charge State & b/y Fragment Ion Ladder Calculator, Quantification Advisor | [`/proteomics`](./proteomics/) |
| **7** | **GATK Best Practices Pipeline** | Germline & Somatic Variant Discovery | Phred Quality Score & Error Probability Converter, Hard Filter Threshold Tuner | [`/gatk`](./gatk/) |
| **8** | **Shotgun Assembly & MAG Binning** | Metagenomics Assembly & Binning | CheckM2 MAG Quality Tier & MIMAG Classifier, Succinct de Bruijn Graph Memory Advisor | [`/shotgun-mag`](./shotgun-mag/) |
| **9** | **AlphaFold & ColabFold Lab** | AI Macromolecular 3D Structure | pLDDT Confidence & Domain Dynamics Decoder, Predicted Aligned Error (PAE) Matrix Simulator | [`/alphafold`](./alphafold/) |
| **10** | **Kraken 2 & Bracken Profiler** | Metagenome Taxonomic Profiling | Exact k-mer Lowest Common Ancestor (LCA) Visualizer, Bracken Bayesian Abundance Re-estimator | [`/kraken2`](./kraken2/) |

---

## 🧪 Platform Architecture & Core Features

- **Interactive Decision Trees**: Real-time conditional guidance helping bioinformaticians pick the exact tool, statistical test, or reference database according to sample cohort size, sequencing depth, and biological questions.
- **Explain Cards (`💡 Explain`)**: In-depth explanations covering mathematical foundations, algorithmic details, biological justifications, and common pitfalls for every single workflow step.
- **One-Click Script Exporters**: Instant export of complete, reproducible, production-ready Bash and R pipeline scripts tailored to user parameters.
- **Clean Responsive Light & Dark Mode**: Persistent theme switching with typography and color schemes optimized for long analytical sessions.
- **Zero-Dependency Vanilla Web Standards**: 100% client-side HTML5, CSS3, and JavaScript requiring no complex build tools or server backends, perfectly suited for GitHub Pages deployment.

---

## 🛠️ Local Development & Preview

Clone the repository and serve locally using any standard static file server:

```bash
# Clone the repository
git clone https://github.com/Angsumi/bioinformatics.git
cd bioinformatics

# Start a local preview server with Python
python3 -m http.server 8000

# Open in your browser:
# http://localhost:8000/
```

---

## 📚 References & Bioinformatic Foundations

- **QIIME 2**: Bolyen, E. et al. *Reproducible, interactive, scalable and extensible microbiome data science using QIIME 2.* Nat Biotechnol 37, 852–857 (2019).
- **SAMtools**: Danecek, P. et al. *Twelve years of SAMtools and BCFtools.* GigaScience 10, giab008 (2021).
- **HISAT2**: Kim, D. et al. *Graph-based genome alignment and genotyping with HISAT2 and HISAT-genotype.* Nat Biotechnol 37, 907–915 (2019).
- **Bowtie 2**: Langmead, B. & Salzberg, S. L. *Fast gapped-read alignment with Bowtie 2.* Nat Methods 9, 357–359 (2012).
- **DESeq2**: Love, M. I., Huber, W. & Anders, S. *Moderated estimation of fold change and dispersion for RNA-seq data with DESeq2.* Genome Biol 15, 550 (2014).
- **MaxQuant**: Cox, J. & Mann, M. *MaxQuant enables high peptide identification rates, individualized p.p.b.-range mass accuracies and proteome-wide protein quantification.* Nat Biotechnol 26, 1367–1372 (2008).
- **GATK**: Poplin, R. et al. *Scaling accurate genetic variant discovery to tens of thousands of samples.* bioRxiv (2018).
- **MetaBAT 2**: Kang, D. D. et al. *MetaBAT 2: an efficient tool for accurate metagenome assembly-based binning.* PeerJ 7, e7359 (2019).
- **AlphaFold**: Jumper, J. et al. *Highly accurate protein structure prediction with AlphaFold.* Nature 596, 583–589 (2021).
- **Kraken 2**: Wood, D. E., Lu, J. & Langmead, B. *Improved metagenomic analysis with Kraken 2.* Genome Biol 20, 257 (2019).

---

## 👤 Author & Maintainer

**Angsuman Das**  
- Digital Portal: [https://angsumi.online](https://angsumi.online)  
- GitHub: [@Angsumi](https://github.com/Angsumi)

Licensed under the MIT License.
