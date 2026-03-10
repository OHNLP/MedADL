## Getting Started

### Prerequisites

Java 1.8

#### NLP framework MedTaggerIE

MedTagger contains a suite of programs that the Mayo Clinic NLP program has developed in 2013. It includes three major components: MedTagger for indexing based on dictionaries, MedTaggerIE for information extraction based on patterns, and MedTaggerML for machine learning-based named entity recognition.

### Download

#### https://github.com/OHNLP/AgingNLP/tree/master/delirium

### Install

A step by step installation instructions can be accessed through:
https://vimeo.com/392331446

1. Move the .jar file to the Delirium folder
2. Modify the `INPUTDIR`, `OUTPUTDIR`, and `RULEDIR` variables in `runMedTagger-fit-delirium.sh` or `runMedTagger-fit-delirium.bat`, as appropriate
   - `INPUT_DIR`: full directory path of input folder
   - `OUTPUT_DIR`: full directory path of output folder
   - `RULES_DIR`: full directory path of 'Rule' folder

### Run

```
runMedTagger-fit-delirium.sh
```

### Refine

Due to the institutional-specific heterogeneity, after deplying the algorithm, we recommend 1) conducting local evaluation through manual chart review, 2) refining the keywords, 3) implementing a section detection algorithm based on the structure of clinical notes. Additional information the NLP deployment and evaluation process can be found at: https://github.com/OHNLP/annotation-best-practices

## Reference
