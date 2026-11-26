# Lassa/Ebola Systems Serology Dataset

Systems Serology data of convalescent survivors of Lassa virus or Ebola infections, and their household contacts. Systems Serology aims to define the features of the humoral immune response against a given pathogen. Systems Serology analysis includes measurement of the levels antigen-specific antibodies within individual patients, measurement of antibody-mediated induction of innate immune cell effector functions, measurement of binding of antigen-specific antibodies to Fc-receptors, and measurement of neutralizing activity.

| | |
|---|---|
| Assays | 2,554 |
| Samples | 161 |
| Plate controls | 190 |
| With a patient identifier | 804 |
| Cohort | Lassa (1,260), Ebola (1,020), Unknown (12) |
| Outcome | Survivor (1,644), Contact (648) |
| Country | Sierra Leone (2,292) |
| Years | 1996–2017, 1,726 unrecorded |
| Technique | serology |
| Version | 0.4 |

## Files

| File | Rows | Description |
|---|---|---|
| `metadata.csv` | 2,554 | Sample and patient metadata |
| `serology_measurements.csv` | 2,554 | Serology measurements, one row per assay |
| `dataset.json` | – | Dataset description in schema.org format |

## Columns in `metadata.csv`

| Column | Description |
|---|---|
| `experimentID` | Experiment identifier |
| `sample_id` | Sample identifier, shared across CViSB datasets |
| `visit` | Visit the sample was drawn at, where recorded |
| `isControl` | True for plate controls |
| `patientID` | Patient identifier, where known |
| `cohort` | Ebola, Lassa, Unknown |
| `outcome` | Contact, Survivor |
| `country` | Country of infection |
| `year` | Year of infection |

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please cite the Center for Viral Systems Biology (CViSB).

Funded by NIAID award U19AI135995.
