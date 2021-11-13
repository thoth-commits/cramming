# Cell lines for cultured meat and fermentation

* Precision fermentation: microbes as factories to product functional
  ingredients
    - insert DNS into microbe genome, trick it into doing:
        a. Product protein
        b. Produce enzymes -> biosynthesis pathway -> fat / non-proteins
* [Perfect Day's GRAS
  application](https://www.fda.gov/media/136754/download#:~:text=the%20notified%20substance-,Perfect%20Day%2C%20Inc.,a%20source%20of%20dietary%20protein.)
    - Trichoderma reesai fungi used in food enzymes [already](https://pubmed.ncbi.nlm.nih.gov/7765573/)

## Fermentation

### Selection attributes

* How much protein do we want/how much can we get from a cell?
* Ease of extraction from a cell
    - Are cells secreting it already, do we need to burst them open?
* Generational stability: not a lot of mutations
* Safe: unwanted metabolites/toxins
* Min consumables (fewer media requirements)
* Grow well at scale (20k litres)

### Selection methods

* Genetic engineering
    - e.coli heterotropic through directed evolution is made autotropic so it
      can make its own food through co2
* Adaptation
* Breeding
* What DNS should we introduce to produce product in precision fermentation?
    - Caesin producing dna from cow
    - Proteins have an operating frame: promoter (expression of gene), terminate
      the gene?
    - Sequence for the desired protein / enzyme (codon-optimized) +
        Selection marker +
        Regulatory Sequences (promoters, transcription factors)
* Is this GM-Food? (sourdough is a catalyst not in the final product, even though
  the yeast is modified we don't consume it?)
    - Certain genes inserted in food can cause allergies to trigger (eg: soy)

## Cultured Meat

### Biopsy

* Biopsy muscle stem cells: muscle sampling - where are we getting the cells
  from?
    - Location: front/back shoulder
    - Age: Directly proportional with conc of muscle stem cells
    - Breed, Sex, Conditions (stress, food etc effect stems per mm^2)
* Methodology for biopsy
    - Fix animal in cage, anesthesia shot (most stree part)
    - Needle or scalpel needs to go into muscle tissue
    - Take several biopsy samples in one session, allow animal to heal
        * Scar tissue => can't get good samples
* Culture made of
    - Muscle stem cells: adult stem cells in skeletal muscle tissue
        * this is the process of scarring. Quiescent cells activate and
          proliferate before differentiating.
    - Fat (adipocytes)
        * Mesenchymal stem cells
            - As they differentiate and proliferate they stop becoming fat cells
```
                        MSC
        |               |               |       differentiation
adipocytes (fat cells) myoblasts     osteoblasts (musches)
```

            * DFAT cells: longer term proliferative capacity
            * Preadipocytes: already comitted to adipogenesis (won't become
              muscle/bone cartilage)
            * [Fish et al, 2020](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7051019/)
    - Feeder cells (liver/placenta/pancreatic cells to produce growth factors to
      replace expansive medi)
[CulNet](https://www.culturedabundance.com/post/patent-analysis-integriculture-landscape-analysis),
[ForkGoode](https://www.culturedabundance.com/post/patent-analysis-fork-and-goode-s-novel-bioreactor-system)
        * Secrete growth factors that can be recirculated as media. Mimics the
          body and organs via tanks and cell/barrier configurations.
    - cartilage for scaffolding
    - blood cells for oxygen flow

### Cell isolation

* [Choi et al 2020]()
* When we do the biopsy the muscle stem cell is fused with the fiber and
  connective tissue
* Physical dissociatoin (scissors/meat mincer)
* Enzymatic dissociation by proteases (trypsin) into fiber fragment tissue
  debris, connective tissues, muscle stem cells
    - Trypsinization
* Centrifugation to isolate cells
* FACS and MACS (fluroscence activated and magnetic activated sorting)
* Profilerative capacity is a main concern with all 3 cell types
    - This is a problem with all primary cell cultures
    - Need to go back to the animal, batch to batch variation, needs animal
      farming

### Immortalization (cell lines)

* Cancer is infinite proliferative capacity
* Cell lines have infinite proliferative capacity
* Cell cycle checkpoints in cell division
    - Telomere ends of dna chromosomes, protects dna from damage
    - Each CD shortens Telomeres by a bit
    - At some point bio DNA is damanged (senacence state)
* Henrietta lacks -> cervical cancer -> Heala cells
* 2 ways to deal with this problem
    1. Express telomerase to repair telomere (put this in the cell culture mix)
        * Telomerase is a protein (RNP)
        * Expressing it means to convert dna to protein (eg: insulin is a
          protein, it is produced from a gene in a genotype)
        * 2 ways to do this: plasmid transfection, retrovirus infection
    - Telomerase only found in embryos
    2. Inactivate cell cycle senescence checkpoints
            * CRISPER (knockout)
            * Viral: Infect ourselves with SV40 (large T antigen)
                - HPV, Epstein-Barr vectors
                - evolved to give cancer
                - Every time the cell divides the virus goes forward
* Footprint-free reversal of immortalization
    - Add an enzyme in the process so the final cell product has no mods (no
      foreign dna)

### Limitations of cell lines

* Researchers need to make their own cell lines
* Repositories for cell lines lowering the barrier for cultured meat research
    - GFI, New Harvest
* Tumors, Cell crises etc
* Cells that we haven't studied (shrimp/sea food) difficult to immortalize
    - Biology different from mammals
* Most researchers using c2c12 mouse cell line (only immortalized one)

## Investigate

* What DNA sequence does Perfect Day use in precision fermentation? hint: it's
  not the same genetic sequence as the cow but it produces the same protein.
They use a codon optimized sequence for their fungi.
* Codon and protein synthesis stop signal
* What is the Wild Type modification?
* Vow Foods alternate cell lines
* [Homework](https://drive.google.com/drive/folders/1p0LsDn22Ta7ICQj9h-AEMxT5y-xFwzKE)


