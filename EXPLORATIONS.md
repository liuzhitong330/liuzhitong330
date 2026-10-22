# Selected exploratory analyses

A small reading list organized by research question, rather than by the order in which projects were created. Start with the [profile overview](https://github.com/liuzhitong330).

These are personal explorations of public data, including lab-inspired application projects and reusable research explorations. They are not formal collaborations, endorsements, or evidence of having performed the source experiments. The original studies remain the source of the biological data. Scope, methods, and implementation assistance should be read alongside each result.

## Neural sensing and intervention

### Seizure forecasts under a shared false-positive budget

**Question:** Does the preferred forecasting model change between participants when comparisons use the same false-positive-rate budget?  
**Data and output:** Released participant-level AUC and ROC data from Khambhati et al. (2024), shown as interactive model trade-offs. Figure-level interpolation—not prospective forecasting or a stimulation policy.

[Interactive analysis](https://liuzhitong330.github.io/neural-state-forecast-operating-points/) · [Repository](https://github.com/liuzhitong330/neural-state-forecast-operating-points)

### Human ultrasound responses and experimental controls

**Question:** How do sensory and procedural controls affect interpretation of human transcranial-ultrasound responses?  
**Data and output:** Participant-level motor-evoked-potential measurements from Kop et al. (2024), with aggregate context from the inTUS resource. A control-aware evidence comparison—not a safety or efficacy recommendation.

[Interactive analysis](https://liuzhitong330.github.io/human-tus-evidence-benchmark/) · [Repository](https://github.com/liuzhitong330/human-tus-evidence-benchmark)

### Sensitivity of brain–body imaging signals

**Question:** Which apparent responses remain plausible when the reference signal or common-drift assumption changes?  
**Data and output:** Public gut/vascular recordings from Chen, James, Ruetten and colleagues (2026), with native-coordinate 3D exploration and alternate-reference checks. Developed as a Hernandez-Nunez-lab-inspired exploration using external data; anatomical specificity and causality are not established.

[Interactive analysis](https://liuzhitong330.github.io/hernandez-nunez-lab-demo/) · [Repository](https://github.com/liuzhitong330/hernandez-nunez-lab-demo)

## Cell states and gene regulation

### Donor-aware epithelial marker contrasts

**Question:** Is a marker contrast shared across donors, or dominated by unequal cell contributions?  
**Data and output:** The processed epithelial RNA-count object from Song et al. (2022), GSE176031; pooled-versus-equal-donor contrasts, leave-one-donor-out checks, and a marker-review export. This is consistency review of published annotations, not independent state validation.

[Interactive analysis](https://liuzhitong330.github.io/franklin-huang-lab-demo/) · [Repository](https://github.com/liuzhitong330/franklin-huang-lab-demo)

### Promoter sequence context

**Question:** How does base composition around a gene's transcription start site vary between genes?  
**Data and output:** Human reference-genome sequence lookup with local GC/composition visualization, inspired by Ramani Lab's chromatin work. Sequence context is not a direct measurement of nucleosome occupancy or remodeler activity.

[Interactive analysis](https://liuzhitong330.github.io/ramani-lab-demo/) · [Repository](https://github.com/liuzhitong330/ramani-lab-demo)

### IKAROS-response consistency across models

**Question:** Which expression responses remain consistent across model and normalization choices?  
**Data and output:** Public IKAROS-restoration RNA-seq libraries from GSE310958, with individual measurements, effect comparisons, and follow-up exports. Descriptive response review—not a direct-target, dependency, or causal claim.

[Interactive analysis](https://liuzhitong330.github.io/schjerven-lab-demo/) · [Repository](https://github.com/liuzhitong330/schjerven-lab-demo)

## Molecular signals and experimental follow-up

### Peptide-precursor follow-up candidates

**Question:** Which peptide precursors warrant follow-up when sequence-derived candidates are considered alongside expression changes?  
**Data and output:** The Svensson Lab's predicted peptide library and cleavage component, combined with external GSE266899 pancreatic-lesion RNA counts. A sensitivity-aware candidate shortlist; expression does not establish peptide secretion or activity.

[Interactive analysis](https://liuzhitong330.github.io/svensson-lab-demo/) · [Repository](https://github.com/liuzhitong330/svensson-lab-demo)

### Fluorescence-polarization repeat planning

**Question:** Which comparisons are sensitive to incomplete technical replication or the included measurement range?  
**Data and output:** Gross Lab's deposited Edc3 fluorescence-polarization measurements, with technical-repeat inspection and proposed repeat-record exports. This does not establish affinity, biological replication, or assay failure.

[Interactive analysis](https://liuzhitong330.github.io/gross-lab-demo/) · [Repository](https://github.com/liuzhitong330/gross-lab-demo)

---

Existing repositories and published demo addresses are retained. This index is a curated reading path, not a complete inventory or a claim that all projects have the same depth of validation.
