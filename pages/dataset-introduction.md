# Dataset introduction

The [BestAIR dataset](:files_path:/datasets) posted on the NSRR has gone through various post-processing steps in order to prepare the data for more widespread sharing. Changes and updates to the source data and have been coordinated in the [bestair-data-dictionary repository](https://github.com/sleepepi/bestair-data-dictionary).

**Disclaimer:** These data are not perfect. Please [submit issues](https://github.com/sleepepi/bestair-data-dictionary/issues) for any problematic findings.

## Structure

The dataset is broken down into `baseline`, `month6`, and `month12` (i.e. follow-up) files, containing 169, 169, and 108 records, respectively. The primary subject identifier is [`nsrrid`](https://sleepdata.org/datasets/bestair/variables/nsrrid).

## Explanation of treatment arms

Each BestAIR subject was randomized to one of four treatment arms. The assigned arm is represented by the [`rand_treatmentarm`](https://sleepdata.org/datasets/bestair/variables/rand_treatmentarm) variable. The meanings of the arms are as follows:

1. Conservative Medical Therapy (CMT)
2. CMT + Sham CPAP
3. CMT + Active CPAP
4. CMT + Active CPAP + Motivational Enhancement

## Data collection forms

The NSRR provides [original data collection forms as PDFs](:files_path:/forms). Many [variables link to these forms](:datasets_path:/bestair/variables) to give users a better idea about the origins of the underlying data.

The forms are included here for historical purposes only and are not intended for use in prospective studies. If you wish to use these forms, please check existing copyrights and regulations beforehand.

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
