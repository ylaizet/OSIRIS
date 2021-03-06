# CLINICAL
---

## Patient

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Patient | Id | Id du patient | C1 |  | Identifiant du patient dans le centre transmetteur de l'information |  |
| Patient | Gender | Sexe | C2 | [v3 Code System AdministrativeGender](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#v3-code-system-administrativegender) | Sexe du patient |  |
| Patient | Ethnicity | Ethnicité | C3 | [HL7 v3 Code System Race](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#hl7-v3-code-system-race) | Origine ethnique du patient |  |
| Patient | BirthDate | Date de naissance | C4 |  | Date de naissance du patient |  |
| Patient | DeathDate | Date de décès | C5 |  | Date de décès du patient |  |
| Patient | CenterId | Id du Centre | C6 |  | Identifiant du centre transmetteur de l'information |  |
| Patient | CauseOfDeath | Cause du décès | C7 | [UMLS:C0007465](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#umlsc0007465) | Descriptif de la cause de décès du patient |  |
| Patient | LastNewsDate | Date de dernières nouvelles | C8 |  | Date de dernières nouvelles du patient (= date de dernière venue du patient si aucune autre information disponible) |  |
| Patient | LastNewsStatus | Etat aux dernières nouvelles | C9 |  | Indicateur de l'état du patient aux dernières nouvelles (Vivant ou décédé) |  |

## Consent

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Consent | ExpirationDate | Date de validité du consentement | C10 |  | Date limite de validité du consentement |  |
| Consent | IntrinsicAnalysisAuth | Autorisation pour analyses en constitutionnelle | C11 |  | Autorisation pour analyses en constitutionnel |  |
| Consent | SomaticAnalysisAuth | Autorisation pour analyses en somatique | C12 |  | Autorisation pour analyses en somatique |  |

## RelatedPathology

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| RelatedPathology | PathologyCode | Code | C13 | [ICD-10](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#icd-10) | Code international de la pathologie associée (hors autre cancer). |  |
| RelatedPathology | DiagnosisDate | Date | C14 |  | Date du diagnostic de la pathologie associée |  |
| RelatedPathology | PathologyEndDate | Date de fin | C15 |  | Date de fin de la pathologie associée (si elle existe et est connue). |  |

## CancerHistory

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| CancerHistory | DiagnosisDate | Date de diagnostic | C16 |  | Date de diagnostic de l'antécédent carcinologique |  |
| CancerHistory | TopographyCode | Code Localisation | C17 | [CIM-O-3 Topo](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#cim-o-3-topo) | Code international de la localisation de l'antécédent carcinologique |  |
| CancerHistory | MorphologyCode | Code Morphologie / Lésion | C18 | [CIM-O-3 Morpho](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#cim-o-3-morpho) | Code international de la lésion / type histologique / morphologie de l'antécédent carcinologique |  |
| CancerHistory | Type | Type | C19 | [CancerHistoryType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#cancerhistorytype) | Type d'antécédent (Personnel ou Familial) |  |

## TumorPathologyEvent

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| TumorPathologyEvent | Type | Type d'événement | C20 | [EventType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#eventtype) | Le champ 'Type' permet de décrire à la fois l'événement 'Cancer' en tant que maladie globale que les différents événements constituant cette maladie (Tumeur initiale, Récidive locale, Récidive métastatique). |  |
| TumorPathologyEvent | StartDate | Date de début de l'évènement | C21 |  | Date de début de l'événement tumoral ou de la maladie |  |
| TumorPathologyEvent | PerformanceStatus | Echelle d'autonomie / Performance status | C22 | [OMS](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#oms) | Définition de l'échelle d'autonomie (échelle de Karnofsky ou OMS) |  |
| TumorPathologyEvent | G8 | Outil de dépistage G8 | C23 | [G8](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#g8) | outil d'évaluation de l'état général des patients âgés ayant un cancer |  |
| TumorPathologyEvent | T | T | C24 |  | Taille de la tumeur, propagation sur le site de la tumeur primitive |  |
| TumorPathologyEvent | N | N | C25 |  | Propagation au niveau ganglionnaire |  |
| TumorPathologyEvent | M | M | C26 |  | Propagation à distance, présence de métastases |  |
| TumorPathologyEvent | TNMVersion | Version du TNM | C27 | [TNMVersion](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#tnmversion) | Version de la classification TNM |  |
| TumorPathologyEvent | TNMType | Type de TNM | C28 | [TNMType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#tnmtype) | c, p, r,... |  |
| TumorPathologyEvent | HistologicalGradeType | HistologicalGradeType | C29 |  | Liste des échelles de grading histologique |  |
| TumorPathologyEvent | HistologicalGradeValue | HistologicalGradeValue | C30 |  | Valeur du grade histologique |  |
| TumorPathologyEvent | StadeType | StadeType | C31 |  | Liste des échelles de stade |  |
| TumorPathologyEvent | StadeValue | StadeValue | C32 |  | Valeur du stade |  |
| TumorPathologyEvent | DiagnosisDate | Date du diagnostic | C33 |  | Date du diagnostic de l'événement tumoral |  |
| TumorPathologyEvent | TopographyCode | Code Localisation | C34 | [CIM-O-3 Topo](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#cim-o-3-topo) | Code international de la localisation de l'événement tumoral |  |
| TumorPathologyEvent | MorphologyCode | Code Morphologie / Lésion | C35 | [CIM-O-3 Morpho](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#cim-o-3-morpho) | Code international de la lésion / type histologique / morphologie de l'événement tumoral |  |
| TumorPathologyEvent | Laterality | Latéralité | C36 | [Laterality](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#laterality) | Latéralité de la localisation (si elle existe) |  |

## Analysis

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Analysis | Type | Type d'examen | C37 |  | Type de l'examen |  |
| Analysis | AnalysisDate | Date d'examen | C38 |  | Date de l'examen |  |

## Biomarker

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Biomarker | BiomarkerCode | Code du marqueur | C39 |  | Nom du marqueur |  |
| Biomarker | BiomarkerStatus | Statut du marqueur | C40 |  | Statut de marqueur |  |

## Treatment

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Treatment | Type | Type de traitement | C41 | [TreatmentType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#treatmenttype) | Type de traitement |  |
| Treatment | ActivityCode | Codification de l'acte | C42 | [CCAM](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#ccam) | Code CCAM de l'acte |  |
| Treatment | StartDate | Date de début | C43 |  | Date de début du traitement |  |
| Treatment | EndDate | Date de fin | C44 |  | Date de fin du traitement |  |
| Treatment | ClinicalTrialContext | Clinical trial (Yes &#124; No) | C45 |  | Traitement effectué dans un contexte d'étude clinique |  |

## Treatment (Type=Surgery)

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Treatment (Type=Surgery) | ResectionQuality | Qualité de la résection (anapath) | C46 | [SurgeryResection](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#surgeryresection) | Qualité de la résection (anapath) |  |
| Treatment (Type=Surgery) | Nature | Nature de la chirurgie | C47 |  | Nature de la chirurgie |  |

## AdverseEvent

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| AdverseEvent | Code | Code de l'événement indésirable | C48 |  | Code international de l'événement indésirable survenu en cours de traitement (hors autre cancer). |  |
| AdverseEvent | Date | Date de l'événement indésirable | C49 |  | Date du diagnostic de l'événement indésirable |  |
| AdverseEvent | EndDate | Date de fin | C50 |  | Date de fin de l'événement indésirable (si elle est connue) |  |

## Drug

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Drug | Code | Code molécule | C51 | [ATC 5e niveau](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#atc-5e-niveau) | Code de la classification thérapeutique |  |
| Drug | DrugName | Nom de la molécule | C52 | [ATC 5e niveau](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#atc-5e-niveau) | Nom de la molécule |  |

## BiologicalSample

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| BiologicalSample | SampleId | Id unique de l'échantillon | C53 | [MIABIS-39](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#miabis-39) | Identifiant unique de l'échantillon |  |
| BiologicalSample | ParentSampleId | Identifiant unique de l'échantillon parent | C54 | [MIABIS-40](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#miabis-40) | Identifiant unique de l'échantillon parent (s'il en existe un) |  |
| BiologicalSample | ParentSampleRef | Référence du prélèvement | C55 |  | Numéro de référence du prélèvement (numéro utilisé généralement à la réception d'un ensemble d'échantillons au laboratoire correspondant à un même acte de prélèvement) |  |
| BiologicalSample | CollectDate | Date du prélèvement | C56 | [MIABIS-43](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#miabis-43) | Date du prélèvement |  |
| BiologicalSample | TopographyCode | Code Localisation | C57 | [CIM-O-3 Topo](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#cim-o-3-topo) | Code de la localisation tumorale |  |
| BiologicalSample | SampleNature | Nature de l'échantillon | C58 | [MIABIS-41](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#miabis-41) | La nature de l'échantillon |  |
| BiologicalSample | SampleOrigin | Nature du prélèvement (tumoral / sain) | C59 | [MIABIS-41](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#miabis-41) | Nature du prélèvement d'origine (Sain ou Tumoral) |  |
| BiologicalSample | StorageTemperature | Mode de conservation | C60 | [MIABIS-43](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#miabis-43) | Le mode de conservation |  |
| BiologicalSample | TumorCellularity | % de cellules tumorales | C61 |  | Le pourcentage de cellules tumorales quantifié dans l'échantillon |  |

# OMIC
---

## Specimen

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Specimen | SpecimenId | SpecimenId | O3 |  |  | Genetic sample or derived product identifier |

## Technology

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Technology | TechnicalProtocol | TechnicalProtocol | O6 | [OSIRIS:TechnicalProtocol](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osiristechnicalprotocol) |  | Protocol used for the experiment |
| Technology | PlatformName | PlatformName | O7 | [OSIRIS:PlatformName](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisplatformname) |  | Technological platform name (provider followed by the platform name) |
| Technology | PlatformAccession | PlatformAccession | O8 | [OSIRIS:PlatformAccession](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisplatformaccession) |  | GEO Identifier of the platform |
| Technology | DateOfExperiment | DateOfExperiment | O9 | [OSIRIS:DateOfExperiment](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisdateofexperiment) |  | Date when the experiment was performed |

## Panel

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Panel | PanelName | PanelName | O10 | [OSIRIS:PanelName](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirispanelname) |  | Name of the panel targeted by the experimental analysis (provider + name) |

## Experiment on specimen

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Experiment on specimen | AlgorithmicCellularity | AlgorithmicCellularity | O12 | [OSIRIS:AlgorithmicCellularity](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisalgorithmiccellularity) |  | Calculated percentage of tumor cells in sample |
| Experiment on specimen | AlgorithmicPloïdy | AlgorithmicPloïdy | O13 | [OSIRIS:AlgorithmicPloïdy](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisalgorithmicploïdy) |  | Calculated number of sets of chromosomes in a cell of the sample |

## Experiment on specimen CpyNb Quality filter

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Experiment on specimen CpyNb Quality filter | NumberOfBreakPoints | NumberOfBreakPoints | O14 | [OSIRIS:NumberOfBreakPoints](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisnumberofbreakpoints) |  | Calculated number of break points in genomic profile |

## Alteration in specimen

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Alteration in specimen | AlterationType | AlterationType | O15 | [OSIRIS:AlterationType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisalterationtype) |  | General type of the detected genetic alteration (high level type) |

## Validation

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Validation | ValidationType | ValidationType | O16 | [OSIRIS:ValidationType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisvalidationtype) |  | Type of validation of the detected alteration |
| Validation | ValidationMethod | ValidationMethod | O17 | [OSIRIS:ValidationMethod](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisvalidationmethod) |  | Validation method depending on the type of validation |
| Validation | ValidationStatus | ValidationStatus | O18 | [OSIRIS:ValidationStatus](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisvalidationstatus) |  | Validation status of the detected alteration |

## Alteration

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Alteration | Chromosome | Chromosome | O19 | [OSIRIS:Chromosome](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirischromosome) |  | Chromosome containing the genetic finding |
| Alteration | GenomicStart | GenomicStart | O20 | [FHIR:extension-geneticsGenomicStart](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-geneticsgenomicstart) |  | Nucleotide location for start of genomic finding on the positive (+) genomics strand, 1-based |
| Alteration | GenomicStop | GenomicStop | O21 | [FHIR:extension-geneticsGenomicStop](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-geneticsgenomicstop) |  | Nucleotide location for end of genomic finding on the positive (+) genomic strand, 1-based |
| Alteration | GenomeBuild | GenomeBuild | O22 | [FHIR:extension-geneticsGenomeBuild](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-geneticsgenomebuild) |  | Genome Build used for reference |
| Alteration | Cytoband | Cytoband | O23 | [OSIRIS:Cytoband](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osiriscytoband) |  | Cytogenetic location |

## Genome entity

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Genome entity | GenomeEntityType | GenomeEntityType | O24 | [OSIRIS:GenomeEntityType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisgenomeentitytype) |  | Type of the genome entity. For eg: gene, mRNA, ncRNA... |
| Genome entity | GenomeEntityDatabase | GenomeEntityDatabase | O25 | [OSIRIS:GenomeEntityDatabase](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisgenomeentitydatabase) |  | Database of the genome entity |
| Genome entity | GenomeEntityId | GenomeEntityId | O26 | [FHIR:extension-observation-geneticsGene](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticsgene) |  | Identifier of the genome entity in the genome entity database |
| Genome entity | GeneSymbol | GeneSymbol | O27 | [LOINC:48018-6](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#loinc48018-6) |  | Hugo gene symbol |

## Fusion

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Fusion | FusionType | FusionType | O28 | [OSIRIS:FusionType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusiontype) |  | Type of the fusion event. For eg: translocation, readthrough |
| Fusion | FusionTranscript | FusionTranscript | O29 | [OSIRIS:FusionTranscript](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusiontranscript) |  | Have been found from a fusion transcript ? |
| Fusion | FusionTranscriptReference | FusionTranscriptReference | O30 | [OSIRIS:FusionTranscriptReference](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusiontranscriptreference) |  | Accession number of observed fusion |
| Fusion | GeneSymbol | FusionGeneSymbol5prime | O31 | [LOINC:48018-6](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#loinc48018-6) |  | Gene symbol (HUGO) of the gene involved in the fusion on 5 prime end |
| Fusion | FusionRegionName5prime | FusionRegionName5prime | O32 | [FHIR:extension-observation-geneticsDNARegionName](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticsdnaregionname) |  | Human readable name for the region of interest from the 5 prime fusion partner. For eg : Exon, Intron |
| Fusion | TranscriptReferenceSequenceId | FusionTranscriptReferenceSequenceId5prime | O33 | [FHIR:extension-observation-geneticsTranscriptReferenceSequenceId](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticstranscriptreferencesequenceid) |  | Reference identifier for cDNA transcript of the 5 prime fusion partner, with version, from NCBI's RefSeq or ENSEMBL. |
| Fusion | FusionStrand5prime | FusionStrand5prime | O34 | [OSIRIS:FusionStrand5prime](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionstrand5prime) |  | Strand of the 5 prime fusion partner |
| Fusion | FusionPoint5prime | FusionPoint5prime | O35 | [OSIRIS:FusionPoint5prime](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionpoint5prime) |  | Position of the fusion point on the 5 prime partner |
| Fusion | GeneSymbol | FusionGeneSymbol3prime | O36 | [LOINC:48018-6](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#loinc48018-6) |  | Gene symbol (HUGO) of the gene involved in the fusion on 3 prime end |
| Fusion | FusionRegionName3prime | FusionRegionName3prime | O37 | [FHIR:extension-observation-geneticsDNARegionName](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticsdnaregionname) |  | Human readable name for the region of interest from the 3 prime fusion partner. For eg : Exon, Intron |
| Fusion | TranscriptReferenceSequenceId | FusionTranscriptReferenceSequenceId3prime | O38 | [FHIR:extension-observation-geneticsTranscriptReferenceSequenceId](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticstranscriptreferencesequenceid) |  | Reference identifier for cDNA transcript of the 3 prime fusion partner, with version, from NCBI's RefSeq or ENSEMBL. |
| Fusion | FusionStrand3prime | FusionStrand3prime | O39 | [OSIRIS:FusionStrand3prime](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionstrand3prime) |  | Strand of the 3 prime fusion partner |
| Fusion | FusionPoint3prime | FusionPoint3prime | O40 | [OSIRIS:FusionPoint3prime](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionpoint3prime) |  | Position of the fusion point on the 3 prime partner |
| Fusion | FusionInFrame | FusionInFrame | O41 | [OSIRIS:FusionInFrame](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusioninframe) |  | Specify whether the fusion is in frame |

## Fusion Analysis

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Fusion Analysis | FusionAnnotationReferentiel | FusionAnnotationReferentiel | O42 | [OSIRIS:FusionAnnotationReferentiel](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionannotationreferentiel) |  | Reference database to annotate the fusion |
| Fusion Analysis | FusionAnnotationValue | FusionAnnotationValue | O43 | [OSIRIS:FusionAnnotationValue](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionannotationvalue) |  | Annotation of the fusion |

## Fusion QualityFilter

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Fusion QualityFilter | FusionNbSpanningPair | FusionNbSpanningPair | O44 | [OSIRIS:FusionNbSpanningPair](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionnbspanningpair) |  | Number of reads pairs spanning the fusion |
| Fusion QualityFilter | FusionNbSplitReads | FusionNbSplitReads | O46 | [OSIRIS:FusionNbSplitReads](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisfusionnbsplitreads) |  | Number of reads containing the fusion point |

## Segment copy number

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Segment copy number | SegmentIntensity | SegmentIntensity | O47 | [OSIRIS:SegmentIntensity](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirissegmentintensity) |  | Intensity of the measured signal |
| Segment copy number | SegmentGenomicStatus | SegmentGenomicStatus | O49 | [OSIRIS:SegmentGenomicStatus](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirissegmentgenomicstatus) |  | Copy number status |
| Segment copy number | CopyNumber | CopyNumber | O50 | [OSIRIS:CopyNumber](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osiriscopynumber) |  | Estimated DNA copy number |

## Segment LOH

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Segment LOH | LossOfHeterozygosity | LossOfHeterozygosity | O51 | [OSIRIS:LossOfHeterozygosity](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirislossofheterozygosity) |  | Is the segment located in a region of loss of heterozygosity ? (can be independant from copy number information |

## Reference variant

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Reference variant | ReferenceAllele | ReferenceAllele | O53 | [FHIR:Sequence.referenceAllele](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirsequencereferenceallele) |  | Plus strand reference allele at this position. Include the sequence deleted for a deletion, or '-' for an insertion. |
| Reference variant | AlternativeAllele | AlternativeAllele | O54 | [FHIR:Sequence.observedAllele](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirsequenceobservedallele) |  | Plus strand observed alternative allele at this position. Include the sequence inserted for a insertion, or '-' for a deletion. |
| Reference variant | DNASequenceVariationType | DNASequenceVariationType | O55 | [LOINC:48019-4](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#loinc48019-4) |  | Codified type of the DNA sequence variation |
| Reference variant | VariationDatabase | VariationDatabase | O56 | [OSIRIS:VariationDatabase](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisvariationdatabase) |  | Name of the variation database |
| Reference variant | VariationId | VariationId | O57 | [OSIRIS:VariationId](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisvariationid) |  | Identifier for variant in the variation database |
| Reference variant | PfamDomain | PfamDomain | O58 | [OSIRIS:PfamDomain](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirispfamdomain) |  | Pfams domains related to alteration position |
| Reference variant | PfamId | PfamId | O59 | [OSIRIS:PfamId](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirispfamid) |  | Identifier of Pfams domains related to alteration position |
| Reference variant | MutationPredictionAlgorithm | MutationPredictionAlgorithm | O63 | [OSIRIS:MutationPredictionAlgorithm](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirismutationpredictionalgorithm) |  | Algorithm to predict the variation effect over the protein |
| Reference variant | MutationPredictionValue | MutationPredictionValue | O64 | [OSIRIS:MutationPredictionValue](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirismutationpredictionvalue) |  | Prediction of the variation effect over the protein |
| Reference variant | MutationPredictionScore | MutationPredictionScore | O65 | [OSIRIS:MutationPredictionScore](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirismutationpredictionscore) |  | Level of confidence of the prediction of the variation effect over the protein |
| Reference variant | DNARegionName | DNARegionName | O66 | [FHIR:extension-observation-geneticsDNARegionName](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticsdnaregionname) |  | Human readable name for the region of interest related to the transcript (eg: exon1, intron1, UTR3') |

## Protein

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Protein | ProteinReferenceDatabase | ProteinReferenceDatabase | O67 | [OSIRIS:ProteinReferenceDatabase](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisproteinreferencedatabase) |  | Name of the protein reference database |
| Protein | ProteinReferenceSequenceId | ProteinReferenceSequenceId | O68 | [FHIR:extension-observation-geneticsProteinReferenceSequenceId](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticsproteinreferencesequenceid) |  | Reference identifier of the protein transcript |

## Exonic variant

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Exonic variant | TranscriptReferenceDatabase | TranscriptReferenceDatabase | O69 | [OSIRIS:TranscriptReferenceDatabase](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osiristranscriptreferencedatabase) |  | Name of the sequence reference database |
| Exonic variant | TranscriptReferenceSequenceId | TranscriptReferenceSequenceId | O70 | [FHIR:extension-observation-geneticsTranscriptReferenceSequenceId](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticstranscriptreferencesequenceid) |  | Reference identifier of the transcript |
| Exonic variant | DNASequenceVariation | DNASequenceVariation | O71 | [FHIR:extension-observation-geneticsDNASequenceVariation](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticsdnasequencevariation) |  | HGVS nomenclature on the chosen transcript |
| Exonic variant | AminoAcidChange | AminoAcidChange | O72 | [FHIR:extension-observation-geneticsAminoAcidChange](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#fhirextension-observation-geneticsaminoacidchange) |  | HGVS nomenclature on the chosen protein transcript |
| Exonic variant | GenomicSequenceVariation | GenomicSequenceVariation | O73 | [OSIRIS:GenomicSequenceVariation](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisgenomicsequencevariation) |  | HGVS nomenclature on the given GenomeReferenceSequenceId. |
| Exonic variant | RNASequenceVariation | RNASequenceVariation | O74 | [OSIRIS:RNASequenceVariation](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisrnasequencevariation) |  | HGVS nomenclature on the given TranscriptReferenceSequenceId and experimentely observed on RNA. |
| Exonic variant | AminoAcidChangeType | AminoAcidChangeType | O75 | [OSIRIS:AminoAcidChangeType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisaminoacidchangetype) |  | HGVS nomenclature of changes at protein-level |

## Variant in specimen

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Variant in specimen | PositionCoverage | PositionCoverage | O76 | [OSIRIS:PositionCoverage](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirispositioncoverage) |  | Total coverage at the variant position observed in the specimen |
| Variant in specimen | VariantCoverage | VariantCoverage | O77 | [OSIRIS:VariantCoverage](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisvariantcoverage) |  | Coverage of the alternative allele at the variant position observed in the specimen |
| Variant in specimen | StrandBias | StrandBias | O78 | [OSIRIS:StrandBias](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisstrandbias) |  | Indication of the existence of strand bias at the variant position |
| Variant in specimen | GenomicSourceClass | GenomicSourceClass | O79 | [LOINC:LL378-1](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#loincll378-1) |  | Genomic class of the variant (eg: germline, somatic, and prenatal) |
| Variant in specimen | AllelicState | AllelicState | O80 | [LOINC:LL381-5](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#loincll381-5) |  | Level of allelic occurrence of a DNA Sequence Variation |
| Variant in specimen | MolecularTumorBoardConclusion | MolecularTumorBoardConclusion | O81 | [ACMG](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#acmg) |  | Conclusion of the biologist on the pathogenicity of the variant before the Molecular Tumor Board |
| Variant in specimen | ClinicalTumorBoardConclusion | ClinicalTumorBoardConclusion | O82 | [OBI](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#obi) |  | Conclusion of the clinicians wether the variant is actionable or not during the Molecular Tumor Board |
| Variant in specimen | ProposedForOrientation | ProposedForOrientation | O83 | [OBI](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#obi) |  | Is the ClinicalTumorBoardConclusion used to orient the treatment decision ? |

## Gene expression

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Gene expression | ExpressionDataType | ExpressionDataType | O84 | [OSIRIS:ExpressionDataType](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisexpressiondatatype) |  | Type of the expression value corresponding to the level of data processing |
| Gene expression | ExpressionValue | ExpressionValue | O85 | [OSIRIS:ExpressionValue](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisexpressionvalue) |  | Numerical value for expression |
| Gene expression | ExpressionPvalue | ExpressionPvalue | O86 | [OSIRIS:ExpressionPvalueAdjustmentMethod](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisexpressionpvalueadjustmentmethod) |  | p-value of the dataset comparison through a statistical method |
| Gene expression | ExpressionPvalueAdjustmentMethod | ExpressionPvalueAdjustmentMethod | O87 | [OSIRIS:ExpressionPvalueAdjustmentMethod](https://github.com/ylaizet/OSIRIS/blob/master/docs/ConceptualDomain/ConceptualDomain.md#osirisexpressionpvalueadjustmentmethod) |  | Method used to adjust the nominal value of the p-value when multiple tests are performed in parallel |
