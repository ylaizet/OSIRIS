# CLINICAL
---

## v3 Code System AdministrativeGender

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| M | Male | FHIR (HL7) v3 | http://hl7.org/fhir/v3/AdministrativeGender/index.html | v3 Code System AdministrativeGender | Enumerated | String | C2 | Patient | Sexe | Sexe | Sexe du patient |
| F | Female | FHIR (HL7) v3 | http://hl7.org/fhir/v3/AdministrativeGender/index.html | v3 Code System AdministrativeGender | Enumerated | String | C2 | Patient | Sexe | Sexe | Sexe du patient |
| UN | Undifferentiated | FHIR (HL7) v3 | http://hl7.org/fhir/v3/AdministrativeGender/index.html | v3 Code System AdministrativeGender | Enumerated | String | C2 | Patient | Sexe | Sexe | Sexe du patient |

## UMLS:C0007465

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| UMLS:C0277589 | Death of unknown cause | UMLS | https://uts.nlm.nih.gov/metathesaurus.html#C0277589;0;1;CUI;2016AA;EXACT_MATCH;CUI;*; | UMLS:C0007465 | Enumerated | String | C6 | Patient | Cause du décès | Cause du décès | Descriptif de la cause de décès du patient |
| UMLS:C1707251 | Other cancer | UMLS | https://uts.nlm.nih.gov/metathesaurus.html#C1707251;0;1;CUI;2016AA;EXACT_MATCH;CUI;*; | UMLS:C0007465 | Enumerated | String | C6 | Patient | Cause du décès | Cause du décès | Descriptif de la cause de décès du patient |
| UMLS:C3262234 | Other cause | UMLS | https://uts.nlm.nih.gov/metathesaurus.html#C3262234;0;1;CUI;2016AA;EXACT_MATCH;CUI;*; | UMLS:C0007465 | Enumerated | String | C6 | Patient | Cause du décès | Cause du décès | Descriptif de la cause de décès du patient |
| UMLS:C0679861 | Complications of treatment | UMLS | https://uts.nlm.nih.gov/metathesaurus.html#C0679861;0;1;CUI;2016AA;EXACT_MATCH;CUI;*; | UMLS:C0007465 | Enumerated | String | C6 | Patient | Cause du décès | Cause du décès | Descriptif de la cause de décès du patient |
| UMLS:C0027651 | Neoplasm | UMLS | https://uts.nlm.nih.gov/metathesaurus.html#C0027651;0;1;CUI;2016AA;EXACT_MATCH;CUI;*; | UMLS:C0007465 | Enumerated | String | C6 | Patient | Cause du décès | Cause du décès | Descriptif de la cause de décès du patient |

## ICD-10

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | ICD-10 | http://apps.who.int/classifications/icd10/browse/2016/en | ICD-10 | Enumerated | String | C9 | Pathologie associée | Code | Code | Code international de la pathologie associée (hors autre cancer). |

## CIM-O-3 Topo

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | CIM-O-3 Topo |  | CIM-O-3 Topo | Enumerated | String | C13 | Antécédent carcinologique personnel ou familial | Code Localisation | Code Localisation | Code international de la localisation de l'antécédent carcinologique |

## CIM-O-3 Morpho

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | CIM-O-3 Morpho |  | CIM-O-3 Morpho | Enumerated | String | C14 | Antécédent carcinologique personnel ou familial | Code Morphologie / Lésion | Code Morphologie / Lésion | Code international de la lésion / type histologique / morphologie de l'antécédent carcinologique |

## EventType

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| UMLS:C2939419 | Secondary Neoplasm | UMLS |  | EventType | Enumerated | String | C15 | Evénement tumoral | Type | Type | Le champ 'Type' permet de décrire à la fois l'événement 'Cancer' en tant que maladie globale que les différents événements constituant cette maladie (Tumeur initiale, Récidive locale, Récidive métastatique). |
| UMLS:C0521158 | Recurrent tumor | UMLS |  | EventType | Enumerated | String | C15 | Evénement tumoral | Type | Type | Le champ 'Type' permet de décrire à la fois l'événement 'Cancer' en tant que maladie globale que les différents événements constituant cette maladie (Tumeur initiale, Récidive locale, Récidive métastatique). |
| UMLS:C0677930 | primary tumor | UMLS |  | EventType | Enumerated | String | C15 | Evénement tumoral | Type | Type | Le champ 'Type' permet de décrire à la fois l'événement 'Cancer' en tant que maladie globale que les différents événements constituant cette maladie (Tumeur initiale, Récidive locale, Récidive métastatique). |

## OMS

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| 0 | activité normale sans restriction | OMS |  | OMS | Enumerated | String | C17 | Evénement tumoral |  | Echelle d'autonomie / Performance status | Définition de l'échelle d'autonomie (échelle de Karnofsky ou OMS) |
| 1 | restreint pour des activités physiques importantes, mais patient ambulant et capable de fournir un travail léger | OMS |  | OMS | Enumerated | String | C17 | Evénement tumoral |  | Echelle d'autonomie / Performance status | Définition de l'échelle d'autonomie (échelle de Karnofsky ou OMS) |
| 2 | ambulant et capable de se prendre en charge, mais incapable de fournir un travail et alité pendant moins de 50 % de son temps | OMS |  | OMS | Enumerated | String | C17 | Evénement tumoral |  | Echelle d'autonomie / Performance status | Définition de l'échelle d'autonomie (échelle de Karnofsky ou OMS) |
| 3 | capacité de prise en charge propre beaucoup plus limitée. Passe plus de 50 % de son temps au lit ou dans une chaise. | OMS |  | OMS | Enumerated | String | C17 | Evénement tumoral |  | Echelle d'autonomie / Performance status | Définition de l'échelle d'autonomie (échelle de Karnofsky ou OMS) |
| 4 | complètement grabataire. Incapable de se prendre en charge. Le patient reste totalement confiné au lit ou dans une chaise. | OMS |  | OMS | Enumerated | String | C17 | Evénement tumoral |  | Echelle d'autonomie / Performance status | Définition de l'échelle d'autonomie (échelle de Karnofsky ou OMS) |

## G8

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  |  |  | G8 | nonEnumerated | Integer | C18 | Evénement tumoral |  | Outil de dépistage G8 | outil d'évaluation de l'état général des patients âgés ayant un cancer |

## TNMType

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| c | Clinique |  |  | TNMType | Enumerated | String | C23 | Evénement tumoral |  | Type de TNM | Type de TNM (clinique, Pathologique, etc…) |
| p | Pathologique |  |  | TNMType | Enumerated | String | C23 | Evénement tumoral |  | Type de TNM | Type de TNM (clinique, Pathologique, etc…) |
| y | Après traitement neoadjuvant |  |  | TNMType | Enumerated | String | C23 | Evénement tumoral |  | Type de TNM | Type de TNM (clinique, Pathologique, etc…) |
| u | Radiologique |  |  | TNMType | Enumerated | String | C23 | Evénement tumoral |  | Type de TNM | Type de TNM (clinique, Pathologique, etc…) |

## CIM-O-3 Topo

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | CIM-O-3 Topo |  | CIM-O-3 Topo | Enumerated | String | C25 | Evénement tumoral |  | Code Localisation | Code international de la localisation de l'événement tumoral |

## CIM-O-3 Morpho

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | CIM-O-3 Morpho |  | CIM-O-3 Morpho | Enumerated | String | C26 | Evénement tumoral |  | Code Morphologie / Lésion | Code international de la lésion / type histologique / morphologie de l'événement tumoral |

## laterality

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| UMLS:C0238767 | Bilateral | UMLS |  | laterality | Enumerated | String | C27 | Evénement tumoral |  | Latéralité | Latéralité de la localisation (si elle existe) |
| UMLS:C0205091 | Left | UMLS |  | laterality | Enumerated | String | C27 | Evénement tumoral |  | Latéralité | Latéralité de la localisation (si elle existe) |
| UMLS:C2939193 | Median (qualifier value) | UMLS |  | laterality | Enumerated | String | C27 | Evénement tumoral |  | Latéralité | Latéralité de la localisation (si elle existe) |
| UMLS:C1272460 | Not Applicable | UMLS |  | laterality | Enumerated | String | C27 | Evénement tumoral |  | Latéralité | Latéralité de la localisation (si elle existe) |
| UMLS:C0205090 | Right | UMLS |  | laterality | Enumerated | String | C27 | Evénement tumoral |  | Latéralité | Latéralité de la localisation (si elle existe) |
| UMLS:C0439673 | Unknown | UMLS |  | laterality | Enumerated | String | C27 | Evénement tumoral |  | Latéralité | Latéralité de la localisation (si elle existe) |

## CCAM

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | CCAM |  | CCAM | Enumerated | String | C28 | Traitement |  | Acte | Code CCAM de l'acte |

## ATC 5e niveau

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | ATC 5e niveau |  | ATC 5e niveau | Enumerated | String | C36 | Molécule Administrée |  | Code molécule | Code de la classification thérapeutique |

## MIABIS-40

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | MIABIS-40 |  | MIABIS-40 | nonEnumerated | String | C37 | Echantillon biologique |  | Id du prélèvement | Identifiant du prélèvement (père) dans le centre |

## MIABIS-39

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | MIABIS-39 |  | MIABIS-39 | nonEnumerated | String | C38 | Echantillon biologique |  | Id de l'échantillon | Identifiant de l'échantillon dérivé (ADN, ARN, protéine,...) |

## MIABIS-43

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | MIABIS-43 |  | MIABIS-43 | nonEnumerated | Date | C39 | Echantillon biologique |  | Date du prélèvement | Date du prélèvement |

## CIM-O-3 Topo

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | CIM-O-3 Topo |  | CIM-O-3 Topo | Enumerated | String | C40 | Echantillon biologique |  | Code Localisation | Code de la localisation tumorale |

## 1000Genome

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| EAS | East Asian | 1000Genome | http://www.1000genomes.org/category/population/ | 1000Genome | Enumerated | String | C3 | Patient | Ethnicity | Ethnicité | Origine ethnique du patient |
| EUR | European | 1000Genome | http://www.1000genomes.org/category/population/ | 1000Genome | Enumerated | String | C3 | Patient | Ethnicity | Ethnicité | Origine ethnique du patient |
| AFR  | African | 1000Genome | http://www.1000genomes.org/category/population/ | 1000Genome | Enumerated | String | C3 | Patient | Ethnicity | Ethnicité | Origine ethnique du patient |
| AMR | Ad Mixed American | 1000Genome | http://www.1000genomes.org/category/population/ | 1000Genome | Enumerated | String | C3 | Patient | Ethnicity | Ethnicité | Origine ethnique du patient |
| SAS | South Asian | 1000Genome | http://www.1000genomes.org/category/population/ | 1000Genome | Enumerated | String | C3 | Patient | Ethnicity | Ethnicité | Origine ethnique du patient |

# OMIC
---

## OSIRIS:AlterationType

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| Gene expression | Gene expression | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Protein expression | Protein expression | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Fusion | Fusion | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Copy number variation | Copy number variation | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Genetic variant | Genetic variant | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Structural alteration | Structural alteration | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Transcription factor | Transcription factor | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Histone marks | Histone marks | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Transcript isoform | Transcript isoform | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |
| Viral insertion site | Viral insertion site | OSIRIS |  | OSIRIS:AlterationType | Enumerated | String | O15 | Alteration | AlterationType | AlterationType | General type of the detected genetic alteration (high level type) |

## OSIRIS:ValidationType

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| Experimental | Experimental | OSIRIS |  | OSIRIS:ValidationType | Enumerated | String | O16 | Alteration | ValidationType | ValidationType | Type of validation of the detected alteration |
| By biologist | By biologist | OSIRIS |  | OSIRIS:ValidationType | Enumerated | String | O16 | Alteration | ValidationType | ValidationType | Type of validation of the detected alteration |
| In silico | In silico | OSIRIS |  | OSIRIS:ValidationType | Enumerated | String | O16 | Alteration | ValidationType | ValidationType | Type of validation of the detected alteration |

## OSIRIS:ValidationStatus

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| Not Validated | Not Validated | OSIRIS |  | OSIRIS:ValidationStatus | Enumerated | String | O18 | Validation | ValidationStatus | ValidationStatus | Validation status of the detected alteration |
| Validated | Validated | OSIRIS |  | OSIRIS:ValidationStatus | Enumerated | String | O18 | Validation | ValidationStatus | ValidationStatus | Validation status of the detected alteration |

## OSIRIS:Chromosome

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| LA21254-0 | chr1 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21255-7 | chr2 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21256-5 | chr3 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21257-3 | chr4 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21258-1 | chr5 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21259-9 | chr6 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21260-7 | chr7 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21261-5 | chr8 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21262-3 | chr9 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21263-1 | chr10 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21264-9 | chr11 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21265-6 | chr12 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21266-4 | chr13 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21267-2 | chr14 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21268-0 | chr15 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21269-8 | chr16 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21270-6 | chr17 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21271-4 | chr18 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21272-2 | chr19 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21273-0 | chr20 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21274-8 | chr21 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21275-5 | chr22 | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21276-3 | chrX | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| LA21277-1 | chrY | OSIRIS | http://r.details.loinc.org/AnswerList/LL2938-0.html | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| MT | MT | OSIRIS |  | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| viral | viral | OSIRIS |  | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |
| bacterial | bacterial | OSIRIS |  | OSIRIS:Chromosome | Enumerated | String | O19 | Alteration | Chromosome | Chromosome | Chromosome containing the genetic finding |

## FHIR:extension-geneticsGenomicStart

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR (HL7) | http://hl7.org/fhir/extension-geneticsgenomicstart.html | FHIR:extension-geneticsGenomicStart | nonEnumerated | Integer | O20 | Alteration | GenomicStart | GenomicStart | Nucleotide location for start of genomic finding on the positive (+) genomics strand, 1-based |

## FHIR:extension-geneticsGenomicStop

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR (HL7) | http://hl7.org/fhir/extension-geneticsgenomicstop.html | FHIR:extension-geneticsGenomicStop | nonEnumerated | Integer | O21 | Alteration | GenomicStop | GenomicStop | Exclusive 0-based nucleotide position for end of genomic finding on the positive (+) genomic strand.!!!!!!!!=N======== ucleotide location for end of genomic finding on the positive (+) genomic strand, 1-based |

## FHIR:extension-geneticsGenomeBuild

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| GRCh37 | GRCh37 | FHIR (HL7) | https://www.hl7.org/fhir/extension-geneticsgenomebuild.html | FHIR:extension-geneticsGenomeBuild | Enumerated | String | O22 | Alteration | GenomeBuild | GenomeBuild | Genome Build used for reference |
| GRCh38 | GRCh38 | FHIR (HL7) | https://www.hl7.org/fhir/extension-geneticsgenomebuild.html | FHIR:extension-geneticsGenomeBuild | Enumerated | String | O22 | Alteration | GenomeBuild | GenomeBuild | Genome Build used for reference |

## OSIRIS:GenomeEntityType

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| gene | gene | OSIRIS |  | OSIRIS:GenomeEntityType | Enumerated | String | O24 | Genome entity | GenomeEntityType | GenomeEntityType | Type of the genome entity. For eg: gene, mRNA, ncRNA... |
| miRNA | miRNA | OSIRIS |  | OSIRIS:GenomeEntityType | Enumerated | String | O24 | Genome entity | GenomeEntityType | GenomeEntityType | Type of the genome entity. For eg: gene, mRNA, ncRNA... |
| piRNA | piRNA | OSIRIS |  | OSIRIS:GenomeEntityType | Enumerated | String | O24 | Genome entity | GenomeEntityType | GenomeEntityType | Type of the genome entity. For eg: gene, mRNA, ncRNA... |
| mRNA | mRNA | OSIRIS |  | OSIRIS:GenomeEntityType | Enumerated | String | O24 | Genome entity | GenomeEntityType | GenomeEntityType | Type of the genome entity. For eg: gene, mRNA, ncRNA... |
| ncRNA | ncRNA | OSIRIS |  | OSIRIS:GenomeEntityType | Enumerated | String | O24 | Genome entity | GenomeEntityType | GenomeEntityType | Type of the genome entity. For eg: gene, mRNA, ncRNA... |
| ORF | ORF | OSIRIS |  | OSIRIS:GenomeEntityType | Enumerated | String | O24 | Genome entity | GenomeEntityType | GenomeEntityType | Type of the genome entity. For eg: gene, mRNA, ncRNA... |

## OSIRIS:GenomeEntityDatabase

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| HGNC | HGNC | OSIRIS |  | OSIRIS:GenomeEntityDatabase | Enumerated | String | O25 | Genome entity | GenomeEntityDatabase | GenomeEntityDatabase | Database of the genome entity |
| miRDB | miRDB | OSIRIS |  | OSIRIS:GenomeEntityDatabase | Enumerated | String | O25 | Genome entity | GenomeEntityDatabase | GenomeEntityDatabase | Database of the genome entity |
| Entrez | Entrez | OSIRIS |  | OSIRIS:GenomeEntityDatabase | Enumerated | String | O25 | Genome entity | GenomeEntityDatabase | GenomeEntityDatabase | Database of the genome entity |

## FHIR:extension-observation-geneticsGene

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticsgene.html | FHIR:extension-observation-geneticsGene | nonEnumerated | String | O26 | Genome entity | GenomeEntityId | GenomeEntityId | Identifier of the genome entity in the genome entity database |

## LOINC:48018-6

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | LOINC | http://www.genenames.org/ | LOINC:48018-6 | nonEnumerated | String | O27 | Genome entity | GeneSymbol | GeneSymbol | Hugo gene symbol |

## OSIRIS:FusionType

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| LA26331-1 | translocation | LOINC | http://r.details.loinc.org/LOINC/81289-1.html | OSIRIS:FusionType | Enumerated | String | O28 | Fusion | FusionType | FusionType | Type of the fusion event. For eg: translocation, readthrough |
| readthrough | readthrough | OSIRIS |  | OSIRIS:FusionType | Enumerated | String | O28 | Fusion | FusionType | FusionType | Type of the fusion event. For eg: translocation, readthrough |

## LOINC:48018-6

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | LOINC | http://www.genenames.org/ | LOINC:48018-6 | nonEnumerated | String | O31 | Fusion | FusionGeneSymbol5prime | FusionGeneSymbol5prime | Gene symbol (HUGO) of the gene involved in the fusion on 5 prime end |

## FHIR:extension-observation-geneticsDNARegionName

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticsdnaregionname.html | FHIR:extension-observation-geneticsDNARegionName | nonEnumerated | String | O32 | Fusion | FusionRegionName5prime | FusionRegionName5prime | Human readable name for the region of interest from the 5 prime fusion partner. For eg : Exon, Intron |

## FHIR:extension-observation-geneticsTranscriptReferenceSequenceId

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticstranscriptreferencesequenceid.html | FHIR:extension-observation-geneticsTranscriptReferenceSequenceId | nonEnumerated | String | O33 | Fusion | FusionTranscriptReferenceSequenceId5prime | FusionTranscriptReferenceSequenceId5prime | Reference identifier for cDNA transcript of the 5 prime fusion partner, with version, from NCBI's RefSeq or ENSEMBL. |

## LOINC:48018-6

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | LOINC | http://www.genenames.org/ | LOINC:48018-6 | nonEnumerated | String | O36 | Fusion | FusionGeneSymbol3prime | FusionGeneSymbol3prime | Gene symbol (HUGO) of the gene involved in the fusion on 3 prime end |

## FHIR:extension-observation-geneticsDNARegionName

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticsdnaregionname.html | FHIR:extension-observation-geneticsDNARegionName | nonEnumerated | String | O37 | Fusion | FusionRegionName3prime | FusionRegionName3prime | Human readable name for the region of interest from the 3 prime fusion partner. For eg : Exon, Intron |

## FHIR:extension-observation-geneticsTranscriptReferenceSequenceId

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticstranscriptreferencesequenceid.html | FHIR:extension-observation-geneticsTranscriptReferenceSequenceId | nonEnumerated | String | O38 | Fusion | FusionTranscriptReferenceSequenceId3prime | FusionTranscriptReferenceSequenceId3prime | Reference identifier for cDNA transcript of the 3 prime fusion partner, with version, from NCBI's RefSeq or ENSEMBL. |

## OSIRIS:FusionAnnotationReferentiel

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| ChimerDb | ChimerDb | OSIRIS |  | OSIRIS:FusionAnnotationReferentiel | Enumerated | String | O42 | Fusion Analysis | FusionAnnotationReferentiel | FusionAnnotationReferentiel | Reference database to annotate the fusion |
| Oncofuse | Oncofuse | OSIRIS |  | OSIRIS:FusionAnnotationReferentiel | Enumerated | String | O42 | Fusion Analysis | FusionAnnotationReferentiel | FusionAnnotationReferentiel | Reference database to annotate the fusion |
| Mittelman DB | Mittelman DB | OSIRIS |  | OSIRIS:FusionAnnotationReferentiel | Enumerated | String | O42 | Fusion Analysis | FusionAnnotationReferentiel | FusionAnnotationReferentiel | Reference database to annotate the fusion |

## FHIR:Sequence.referenceAllele

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | https://www.hl7.org/fhir/2016Jan/sequence-definitions.html#Sequence.referenceAllele | FHIR:Sequence.referenceAllele | nonEnumerated | String | O53 | Reference variant | ReferenceAllele | ReferenceAllele | Plus strand reference allele at this position. Include the sequence deleted for a deletion, or '-' for an insertion. |

## FHIR:Sequence.observedAllele

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | https://www.hl7.org/fhir/2016Jan/sequence-definitions.html#Sequence.observedAllele | FHIR:Sequence.observedAllele | nonEnumerated | String | O54 | Reference variant | AlternativeAllele | AlternativeAllele | Plus strand observed alternative allele at this position. Include the sequence inserted for a insertion, or '-' for a deletion. |

## LOINC:48019-4

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| LA6692-3 | Deletion | LOINC | http://r.details.loinc.org/LOINC/48019-4.html | LOINC:48019-4 | Enumerated | String | O55 | Reference variant | DNASequenceVariationType | DNASequenceVariationType | Codified type of the DNA sequence variation |
| LA6686-5 | Duplication | LOINC | http://r.details.loinc.org/LOINC/48019-4.html | LOINC:48019-4 | Enumerated | String | O55 | Reference variant | DNASequenceVariationType | DNASequenceVariationType | Codified type of the DNA sequence variation |
| LA6687-3 | Insertion | LOINC | http://r.details.loinc.org/LOINC/48019-4.html | LOINC:48019-4 | Enumerated | String | O55 | Reference variant | DNASequenceVariationType | DNASequenceVariationType | Codified type of the DNA sequence variation |
| LA6689-9 | Inversion | LOINC | http://r.details.loinc.org/LOINC/48019-4.html | LOINC:48019-4 | Enumerated | String | O55 | Reference variant | DNASequenceVariationType | DNASequenceVariationType | Codified type of the DNA sequence variation |
| LA6690-7 | Substitution | LOINC | http://r.details.loinc.org/LOINC/48019-4.html | LOINC:48019-4 | Enumerated | String | O55 | Reference variant | DNASequenceVariationType | DNASequenceVariationType | Codified type of the DNA sequence variation |

## FHIR:extension-observation-geneticsDNARegionName

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticsdnaregionname.html | FHIR:extension-observation-geneticsDNARegionName | nonEnumerated | String | O66 | Reference variant | DNARegionName | DNARegionName | Human readable name for the region of interest related to the transcript (eg: exon1, intron1, UTR3') |

## FHIR:extension-observation-geneticsProteinReferenceSequenceId

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticsproteinreferencesequenceid.html | FHIR:extension-observation-geneticsProteinReferenceSequenceId | nonEnumerated | String | O68 | Protein | ProteinReferenceSequenceId | ProteinReferenceSequenceId | Reference identifier of the protein transcript |

## FHIR:extension-observation-geneticsTranscriptReferenceSequenceId

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticstranscriptreferencesequenceid.html | FHIR:extension-observation-geneticsTranscriptReferenceSequenceId | nonEnumerated | String | O70 | Exonic variant | TranscriptReferenceSequenceId | TranscriptReferenceSequenceId | Reference identifier of the transcript |

## FHIR:extension-observation-geneticsDNASequenceVariation

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticsdnasequencevariation.html | FHIR:extension-observation-geneticsDNASequenceVariation | nonEnumerated | String | O71 | Exonic variant | DNASequenceVariation | DNASequenceVariation | HGVS nomenclature on the chosen transcript |

## FHIR:extension-observation-geneticsAminoAcidChange

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
|  |  | FHIR | http://hl7.org/fhir/2016May/extension-observation-geneticsaminoacidchange.html | FHIR:extension-observation-geneticsAminoAcidChange | nonEnumerated | String | O72 | Exonic variant | AminoAcidChange | AminoAcidChange | HGVS nomenclature on the chosen protein transcript |

## LOINC:48006-1

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| LA6692-3 | Deletion | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6686-5 | Duplication | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6694-9 | Frameshift | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6695-6 | Initiating Methionine | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6687-3 | Insertion | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA9659-9 | Insertion and Deletion | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6698-0 | Missense | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6699-8 | Nonsense | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6700-4 | Silent | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |
| LA6701-2 | Stop Codon Mutation | LOINC | http://r.details.loinc.org/LOINC/48006-1.html | LOINC:48006-1 | Enumerated | String | O75 | Exonic variant | AminoAcidChangeType | AminoAcidChangeType | HGVS nomenclature of changes at protein-level |

## LOINC:LL378-1

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| LA6683-2 | Germline | LOINC | http://s.details.loinc.org/LOINC/48002-0.html | LOINC:LL378-1 | Enumerated | String | O79 | Variant in specimen | GenomicSourceClass | GenomicSourceClass | Genomic class of the variant (eg: germline, somatic, and prenatal) |
| LA6684-0 | Somatic | LOINC | http://s.details.loinc.org/LOINC/48002-0.html | LOINC:LL378-1 | Enumerated | String | O79 | Variant in specimen | GenomicSourceClass | GenomicSourceClass | Genomic class of the variant (eg: germline, somatic, and prenatal) |
| LA10429-1 | Prenatal | LOINC | http://s.details.loinc.org/LOINC/48002-0.html | LOINC:LL378-1 | Enumerated | String | O79 | Variant in specimen | GenomicSourceClass | GenomicSourceClass | Genomic class of the variant (eg: germline, somatic, and prenatal) |
| LA18197-6 | Unknown genomic origin | LOINC | http://s.details.loinc.org/LOINC/48002-0.html | LOINC:LL378-1 | Enumerated | String | O79 | Variant in specimen | GenomicSourceClass | GenomicSourceClass | Genomic class of the variant (eg: germline, somatic, and prenatal) |

## LOINC:LL381-5

| ValueMeaning | LabelValueMeaning | Referentiel | url | ConceptualDomain | TypeConceptualDomain | FormatConceptualDomain | IdDataElementConcept | ObjectClass | ObjectProperty | DataElementConcept | DefDataElementConcept |
| ------------ | ----------------- | ----------- | --- | ---------------- | -------------------- | ---------------------- | -------------------- | ----------- | -------------- | ------------------ | --------------------- |
| LA6703-8 | Heteroplasmic | LOINC | http://s.details.loinc.org/LOINC/53034-5.html | LOINC:LL381-5 | Enumerated | String | O80 | Variant in specimen | AllelicState | AllelicState | Level of allelic occurrence of a DNA Sequence Variation |
| LA6704-6 | Homoplasmic | LOINC | http://s.details.loinc.org/LOINC/53034-5.html | LOINC:LL381-5 | Enumerated | String | O80 | Variant in specimen | AllelicState | AllelicState | Level of allelic occurrence of a DNA Sequence Variation |
| LA6705-3 | Homozygous | LOINC | http://s.details.loinc.org/LOINC/53034-5.html | LOINC:LL381-5 | Enumerated | String | O80 | Variant in specimen | AllelicState | AllelicState | Level of allelic occurrence of a DNA Sequence Variation |
| LA6706-1 | Heterozygous | LOINC | http://s.details.loinc.org/LOINC/53034-5.html | LOINC:LL381-5 | Enumerated | String | O80 | Variant in specimen | AllelicState | AllelicState | Level of allelic occurrence of a DNA Sequence Variation |
| LA6707-9 | Hemizygous | LOINC | http://s.details.loinc.org/LOINC/53034-5.html | LOINC:LL381-5 | Enumerated | String | O80 | Variant in specimen | AllelicState | AllelicState | Level of allelic occurrence of a DNA Sequence Variation |
