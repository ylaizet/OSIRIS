# Reference variant

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Reference variant | ReferenceAllele | ReferenceAllele | O53 | [FHIR:Sequence.referenceAllele](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/FHIR--Sequence.referenceAllele#FHIR:Sequence.referenceAllele) |  | Plus strand reference allele at this position. Include the sequence deleted for a deletion, or "-" for an insertion. |
| Reference variant | AlternativeAllele | AlternativeAllele | O54 | [FHIR:Sequence.observedAllele](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/FHIR--Sequence.observedAllele#FHIR:Sequence.observedAllele) |  | Plus strand observed alternative allele at this position. Include the sequence inserted for a insertion, or "-" for a deletion. |
| Reference variant | DNASequenceVariationType | DNASequenceVariationType | O55 | [LOINC:48019-4](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/LOINC--48019-4#LOINC:48019-4) |  | Codified type of the DNA sequence variation |
| Reference variant | VariationDatabase | VariationDatabase | O56 |  |  | Name of the variation database |
| Reference variant | VariationId | VariationId | O57 |  |  | Identifier for variant in the variation database |
| Reference variant | PfamDomain | PfamDomain | O58 |  |  | Pfams domains related to alteration position |
| Reference variant | PfamId | PfamId | O59 |  |  | Identifier of Pfams domains related to alteration position |
| Reference variant | MutationPredictionAlgorithm | MutationPredictionAlgorithm | O63 |  |  | Algorithm to predict the variation effect over the protein |
| Reference variant | MutationPredictionValue | MutationPredictionValue | O64 |  |  | Prediction of the variation effect over the protein |
| Reference variant | MutationPredictionScore | MutationPredictionScore | O65 |  |  | Level of confidence of the prediction of the variation effect over the protein |
| Reference variant | DNARegionName | DNARegionName | O66 | [FHIR:extension-observation-geneticsdnaregionname](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/FHIR--extension-observation-geneticsdnaregionname#FHIR:extension-observation-geneticsdnaregionname) |  | Human readable name for the region of interest related to the transcript (eg: exon1, intron1, UTR3') |
