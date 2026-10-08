# Individual Cell-to-Cell Communication Laboratory

**Name:** Kyla Rose D. Villegas  
**Course:** BIO 300 - Cell and Molecular Biology  
**Section:** B

## Biological Question

How can a keratinocyte communicate with a neighboring immune cell through IL1A and activate an inflammatory response?

## 1. Chosen Sender Cell and Biological Context

The selected sender cell is the **keratinocyte**, an epithelial cell found in the skin. Keratinocytes are biologically relevant in tissue injury and inflammation because they can produce signaling molecules involved in inflammatory communication.

## 2. Candidate Ligand and Evidence for Sender-Cell Expression

The selected signaling molecule is **Interleukin 1 alpha (IL1A)**.

Human Protein Atlas evidence identifies IL1A as **cell-type enriched in keratinocytes**. It also shows group-enriched expression in skin and stomach. IL1A is a cytokine associated with inflammatory responses and can be released in association with cellular injury or damage.

**Signaling type:** Paracrine.

## 3. Receptor and Receiver Cell

The selected receptor is **Interleukin 1 receptor type 1 (IL1R1)**. IL1R1 functions as a receptor for IL1A and associates with **IL1RAP** to form the high-affinity IL-1 receptor complex.

The selected receiver cell is the **neutrophil**. Human Protein Atlas evidence identifies IL1R1 as cell-type enriched in neutrophils, supporting the biological plausibility of this receiver-cell choice.

Proposed communication:

**Keratinocyte → IL1A → IL1R1/IL1RAP → Neutrophil → inflammatory response**

## 4. OmniPath Findings

OmniPath identified a directed **IL1A → IL1R1** interaction annotated as stimulation. The result included multiple supporting references, supporting the proposed ligand-receptor relationship.

## 5. STRING Network Interpretation

A STRING search centered on IL1R1 produced an 11-protein network containing:

- IL1R1
- IL1A
- IL1RAP
- MYD88
- IRAK1
- IRAK2
- IRAK4
- TRAF6
- TIRAP
- IL1B
- IL1RN

The most relevant proteins selected for connecting receptor activation to the cellular response were **IL1R1, IL1RAP, MYD88, IRAK4 and TRAF6**.

The network was significantly enriched for the **interleukin-1-mediated signaling pathway** (8 of 22; FDR = 2.10e-17).

## 6. IntAct Validation

IntAct was used to examine the **IL1RAP–IL1R1** interaction. The record describes a **physical association** between the two human proteins detected using **X-ray diffraction**.

Publication: **PMID 22426547**  
Interaction accession: **EBI-15975086**

This evidence supports the physical association of the IL1 receptor and its coreceptor.

## 7. Final Cell-to-Cell Communication Model

The proposed pathway is:

**KERATINOCYTE (Sender)**  
↓  
**IL1A (Ligand)**  
↓  
**Extracellular space**  
↓  
**IL1R1 + IL1RAP (Receptor complex)**  
↓  
**MYD88**  
↓  
**IRAK4**  
↓  
**IRAK1 / IRAK2**  
↓  
**TRAF6**  
↓  
**NF-κB + MAPK**  
↓  
**Inflammatory response**  
**NEUTROPHIL (Receiver)**

The original final model is shown in:

`figures/05_final_model.png`

## 8. Interpretation

The proposed cell-to-cell communication model begins with the keratinocyte as the sender cell and IL1A as the signaling molecule. Human Protein Atlas data identify IL1A as cell-type enriched in keratinocytes and show group-enriched expression in skin and stomach, supporting its relevance to epithelial tissue. OmniPath shows a directed IL1A → IL1R1 interaction, providing evidence for the ligand-receptor relationship. The Human Protein Atlas identifies IL1R1 as the receptor for IL1A and IL1B. STRING analysis of IL1R1 produced an 11-protein network containing IL1RAP, MYD88, IRAK1, IRAK2, IRAK4, and TRAF6. The network was significantly enriched for the interleukin-1-mediated signaling pathway. IntAct provided experimental evidence for a physical association between IL1RAP and IL1R1 using X-ray diffraction in Homo sapiens. Together, these results support the IL1A–IL1R1/IL1RAP receptor system and its association with downstream inflammatory signaling. The connection between keratinocyte-derived IL1A and the specific neutrophil response in the final diagram is a proposed biological model rather than something directly demonstrated by all of the databases.

## 9. Evidence Strength and Limitations

The IL1A–IL1R1 relationship, the IL1R1–IL1RAP receptor association, and the receptor-associated signaling proteins are supported by database evidence. However, database presence does not prove that signaling occurs specifically between the selected cells under every biological condition. STRING associations also do not necessarily represent direct physical interactions or pathway direction. Therefore, the complete keratinocyte-to-neutrophil pathway is presented as an evidence-based biological model with some components remaining an inference.

## 10. Questions and Answers

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

The selected sender cell is the **keratinocyte**, an epithelial cell found mainly in the skin. It is relevant to tissue injury, inflammation, and epithelial barrier functions.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The signaling molecule is **Interleukin 1 alpha (IL1A)**. Human Protein Atlas evidence identifies IL1A as **cell-type enriched in keratinocytes** and shows group-enriched expression in skin and stomach.

### 3. What receptor receives the signal, and which receiver cell did you select?

The receptor is **IL1R1 (Interleukin 1 receptor type 1)**, which associates with **IL1RAP** to form the IL-1 receptor complex. The selected receiver cell is the **neutrophil**, where IL1R1 is supported by Human Protein Atlas cell-type expression evidence.

### 4. What type of cell-to-cell signaling is represented?

The proposed communication is **paracrine signaling**, because the model represents a signal released by one cell acting on another nearby cell.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response?

The most relevant proteins are **IL1R1, IL1RAP, MYD88, IRAK4, and TRAF6**. These proteins connect the IL-1 receptor complex with downstream signaling associated with inflammatory responses.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The STRING network was significantly enriched for the **interleukin-1-mediated signaling pathway**, with 8 of 22 proteins and an FDR of **2.10e-17**.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct showed a **physical association between IL1RAP and IL1R1** in Homo sapiens. The interaction was detected using **X-ray diffraction**, with publication **PMID 22426547** and interaction accession **EBI-15975086**.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The IL1A–IL1R1 relationship, the IL1R1–IL1RAP receptor association, and the receptor-associated signaling proteins are supported by database evidence. The specific complete communication pathway from **keratinocyte-derived IL1A to a neutrophil response** is a proposed biological model and remains an inference because the databases do not directly demonstrate the entire cell-to-cell interaction under one specific condition.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response is an **inflammatory response involving NF-κB and MAPK signaling**. This is consistent with the known signaling associated with IL1R1 activation and the STRING enrichment for interleukin-1-mediated signaling.

## 11. References and Database Sources

- Human Protein Atlas — sender and receiver cell expression evidence
- OmniPath Explorer — ligand-receptor/signaling relationship
- STRING — protein association network and functional enrichment
- IntAct — experimentally supported molecular interaction
- UniProt — supporting protein information when applicable
