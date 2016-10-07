# Fusion

| ObjectClass | ObjectProperty | DataElementConcept | IdDataElementConcept | ConceptualDomain | DataElementConceptDefFR | DataElementConceptDefEN |
| ----------- | -------------- | ------------------ | -------------------- | ---------------- | ----------------------- | ----------------------- |
| Fusion | FusionType | FusionType | O28 |  |  | Type of the fusion event. For eg: translocation, readthrough |
| Fusion | FusionTranscript | FusionTranscript | O29 |  |  | Have been found from a fusion transcript ? |
| Fusion | FusionTranscriptReference | FusionTranscriptReference | O30 |  |  | Accession number of observed fusion |
| Fusion | GeneSymbol | FusionGeneSymbol5prime | O31 | [LOINC:48018-6](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/LOINC--48018-6.md#LOINC:48018-6) |  | Gene symbol (HUGO) of the gene involved in the fusion on 5 prime end |
| Fusion | FusionRegionName5prime | FusionRegionName5prime | O32 | [extension-observation-geneticsdnaregionname](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/extension-observation-geneticsdnaregionname.md#extension-observation-geneticsdnaregionname) |  | Human readable name for the region of interest from the 5 prime fusion partner. For eg : Exon, Intron |
| Fusion | TranscriptReferenceSequenceId | FusionTranscriptReferenceSequenceId5prime | O33 | [FHIR:extension-observation-geneticstranscriptreferencesequenceid](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/FHIR--extension-observation-geneticstranscriptreferencesequenceid.md#FHIR:extension-observation-geneticstranscriptreferencesequenceid) |  | Reference identifier for cDNA transcript of the 5 prime fusion partner, with version, from NCBI's RefSeq or ENSEMBL. |
| Fusion | FusionStrand5prime | FusionStrand5prime | O34 |  |  | Strand of the 5 prime fusion partner |
| Fusion | FusionPoint5prime | FusionPoint5prime | O35 |  |  | Position of the fusion point on the 5 prime partner |
| Fusion | GeneSymbol | FusionGeneSymbol3prime | O36 | [LOINC:48018-6](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/LOINC--48018-6.md#LOINC:48018-6) |  | Gene symbol (HUGO) of the gene involved in the fusion on 3 prime end |
| Fusion | FusionRegionName3prime | FusionRegionName3prime | O37 | [extension-observation-geneticsdnaregionname](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/extension-observation-geneticsdnaregionname.md#extension-observation-geneticsdnaregionname) |  | Human readable name for the region of interest from the 3 prime fusion partner. For eg : Exon, Intron |
| Fusion | TranscriptReferenceSequenceId | FusionTranscriptReferenceSequenceId3prime | O38 | [FHIR:extension-observation-geneticstranscriptreferencesequenceid](https://github.com/ylaizet/OSIRIS/blob/master/ConceptualDomain/FHIR--extension-observation-geneticstranscriptreferencesequenceid.md#FHIR:extension-observation-geneticstranscriptreferencesequenceid) |  | Reference identifier for cDNA transcript of the 3 prime fusion partner, with version, from NCBI's RefSeq or ENSEMBL. |
| Fusion | FusionStrand3prime | FusionStrand3prime | O39 |  |  | Strand of the 3 prime fusion partner |
| Fusion | FusionPoint3prime | FusionPoint3prime | O40 |  |  | Position of the fusion point on the 3 prime partner |
| Fusion | FusionInFrame | FusionInFrame | O41 |  |  | Specify whether the fusion is in frame |
