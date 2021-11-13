# Cell AG

## Why

* Resource use: Land use is limited ([Our World in
  Data](https://ourworldindata.org/land-use))
```
[<- 50% agri -> | <- 40% forests -> | 10% urban, shrub, freshwater ]
   |    |
[<- 77% livestock -> | <- 23% crops ->]
   |    |
meat, dairy - animal feed, grazing land
```
* Pollution: Food related GHG emissions largely from Beef ([Godfray et al 2018](https://www.researchgate.net/publication/326496818_Meat_consumption_health_and_the_environment/link/5f818298a6fdccfd7b5559ef/download)
* Animal welfare: Industrial sheds are crampt. Swimming in their own waste.
  De-horned without anasthesia.
* Foodborne illness: Animal biowaste (blood, mucous etc) harbors pathogens
  (e.coli, salmonella - [Gerba & smith 05](https://pubmed.ncbi.nlm.nih.gov/15647533/))
* Antibiotic Resistance: growth hormones require antibiotics resulting in
  hardier strains of microbes.

## What

### Cultured Meat

* Clustered animal cells
* Acellular products - Precision fermentation > microbial cells
    - Compounds from Animals inserted into microbes (like Penicillin molecules)
    - NOT "beyond meat"
    - IS used in whey and egg white protein
    - IS used in Heam of impossible burger
```
Keep muscle tissue alive -> NASA in vitro turkey meat -> NGO New Harvest
2015 price drop to 12 bucks -> 2019 ice cream -> chicken in 2020 (singapore)
```

### Fermentation

* Bacteria, yeast, fungi (microflora). Milk, eggs (meat?).
* Alt protein space has 3 types of fermentation
    - Kimchi: microorg in food, transforms properties
    - Biomass: mushroom to meat
    - Precision: Whey protein. Exact compounds from animals that we get from
      microbes.
        * Growth factors: fgf2
* Yeast creates Whey without milking cows
    - insulin generation happens the same way
    - human insulin sequence -> microbe -> bulk production
```
Yeast has DNA -> mRNA -> protein
                coding sequence
                generates end product
```
* Generatin the coding sequence requires a. understanding how cows make whey b.
  coding yeast to do the same
    - Heme protein from impossible foods, iron tasing aroma
    - Soy contains hemoglobin (soil erosion and carbon emissions)
    - Extract DNS from soy and put it in yeast to get heme
* Chymosin (cheese curdling protein) is a protein, how to make a chemical?
    - B12 in red meat. Yeast makes it via biosynthesis and enzymes.
* [GFI state of the industry](https://gfi.org/resource/fermentation-state-of-the-industry-report/)
    - [Fermentation 101](https://www.youtube.com/watch?v=tSMARiYE7Jo)

## How

* [Muscle Stem Cell Isolation (choi et al 20)](https://ift.onlinelibrary.wiley.com/doi/full/10.1111/1541-4337.12661)
* Biopsy: Isolate a specific cell (muscle stem cells from skin etc)
* Inject them with molecules in culture
* Upscale the culture in bioreactor
* Trigger differentiation and maturation
* Harvest muscle tissue
* Combine with fat to get steak

[source](https://www.gao.gov/assets/710/706769.pdf)
```
Biopsy -> Cell banking -> growth -> harvest -> food processing
  |                        |                        |
  --------------------------
            FDA (pharma)                USDA (agri) - labelling etc
```

### Biopsy

* Where matters as much as age, breed, sex and stress/exercise/conditions/diet
* Fixate -> Anaesthesia -> needle biopsy/incision
* [Melzener, 2020](https://www.youtube.com/watch?v=2lFQo8oFhlA)

### Isolation of muscle stem cells

* Adult stem cells present in skeletal muscle tissue
    - Capable of self renewal. Useful for healing. Produce skeletal muscles.
```
Muscle stem cell dormant -> activated -> proliferate -> differentiate -> regenerate
```
* Different from ESC (embryonic) which can turn into liver, blood and bone

#### Process

1. _Physical_ dissociation by scissors
2. _Enzymatic_ dissociation by proteases (trypsin) - fiber, debri, connective
   tissue and muscle stem cells
3. _Filtration_  via centrifugation to remote more debri
4. _Isolation_ via cell sorting (fluorescence or magnetic activated)

### Cell isolation and preservation

* Can't survive outside the body. Can only cell divide about 50 times.
    - Hayflick limit which cancer defies
* Cell Senecanse caused by dna damage. Companies use one or the other.
    - a Primary Culture that is replenished from animals in a farm
    - Immortal cell lines which could harbor cancers
        * Immortalizing cells results in GMO label
* Growth attributes: optimal taste, texure, safety, grow at scale, non gmo
    - How to tweak these properties?

### Cell Culture Media

* Media = solution to grow cells out of the body
    - osmotic pressure, differentiation
    - one of the main contributors of cost
* Requirements
    - basal media: glucose, amino acids, salts (cofactors for enzymes)
    - serum: centrifuged blood (non clotting blood components ie not platlets,
      rbc/wbc)
* Serum
    - Most common type FBS (fetal bovin serum)
    - extracted from mature fetus before slaughtering the mother
    - fixed supply of FBS (8% pregnant cows slaughtered anyway)
        * Ethically questionable
        * Limited supply, won't meet demand of human consumption, lots of
          volatility
        * Not chemically defined, reproducibility difficult
* Serum free media formulation
    - Yeast extracts, algae and fungi, plant based materials for SF media
    - Engineering cell lines to consume less media
    - Lower cost of media via replacement
* Lower cost of media via replacement
    - 96% cost comes from 2 growth factors: FGF-2, TGF-Beta
    - Eg: essential 8 medium costs 380$/litre, needs to be much cheaper for mass
        * Produced by using mamalian cells to produce proteins
        * TGF beta is just 0.4 grams in some million litres
    - B8 produces at 11$/litre
    - Cost reductions in [Specht, 2018](https://gfi.org/wp-content/uploads/2021/01/clean-meat-production-volume-and-medium-cost.pdf)
    - 40$ - <1S, requires sourcing / replacing expensive elements in basal
      components and finding cheap growth factors)

#### Fermentation

* Microbes don't have a stringent serum / media requirement
    - Ecoli is heterotropic so it can't make its own food
    - We can coerce it to take on its own food by metabolizing co2 (make it an
      autotroph)
    - Microbes (hydrogenotropes) metabolize h as enery source to make soy but
      they need some genetic information
    - [Gleizer et al 2019, cell](https://www.cell.com/cell/pdf/S0092-8674(19)31230-9.pdf)

### Scaffolds

* Structure and support for the cells - mimic extracellular matrix
```
    Media outlet
        |
    Scaffold    <- growth factor
waste - |
    Media inlet
```
* Either degrade or detach during downstream processes of meat culturing
* Made from:
    a. animal protein (fermentation)
    b. plant/fungal protein (TVP)
    c. synthetic (non edible)
* Different scaffolds for muscle vs fat (juicyness)
* Things that matter:
    - Rate at which cells attach to scaffold is important
    - Degradation rate (at least degrades in body)
* Production
    - 3d printing a geometry BioLink  (New Harvest, NovaMeta, BlueNalu)
    - Decellularize mycelium from leaves
    - [Campuzano & Pelling, 2019](https://www.frontiersin.org/articles/10.3389/fsufs.2019.00038/full)

#### Fermentation

* No scaffold necessary


### Bioreactors (scaling up production)

* Chambers used to control cell growth (small scale lab flasks)
    - reactors needed to reduce labor cost, keep cells at ideal nutrient
      levels/temperature etc. Unnecessary if you're ok with manual labor.
* Media and nutrients flow through the bioreactor
    - Agitated bioreactor: stirs media around
* Factors to consider
    - Maximize exponential cell growth, minimize space and reduce labor cost
    - Contamination from manual handling
* Pilot plants for cultured meat: supermeat, eat just, biotech foods
    - [Ellis 2017](https://www.youtube.com/watch?v=_9HwoIpNuCM)
    - Pharmaceuticals focused but those still need low volume
* Make bioreactors at scale like pharma

#### Fermentation

* Submerged fermentation (similar to ethanol production)
* Carcass balancing problem: 1 cow = 28 tbones. 29th drives a new slaughter. But
  this process can create the right proportion. Don't rely on price.
* Need to design volumetric productivity, continuous bioprocessing

### Downstream processing

* Take what the culture/microbe produces and make it "food"
* Depends on scaffold, edible or in-edible
    - detatching from scaffold happens via TrypLE -> centrifuge it to recover
    - [Allan et al, 2018](https://www.frontiersin.org/articles/10.3389/fsufs.2019.00044/full)
* Where does taste come from
    - fat cells, fatty acids in membranes and fat cells, fibroblasts
    - protein collagen, muscle, endothelial cells
    - haem-iron, creatine, carnitine glutamate
* Nutrirional profile enhancement (vitamin A for elderly audience)
    - Andrew Stout Kaplan Lab
* Culture alt animal meat (kangaroo)

#### Fermentation

* Incorporate strucuring to give flavor (impossible burger)
    - 2% heme by wt, can we get it lower and get the same effect?
    - purification process?
* Ratification process is easier for fermentation (not certified by FDA)
    - GRAS (generally recognized as safe) - self demonstrate safety
    - Products manufactured similar to real meats

## Future

### Production models

* Centralized, distributed, local craft, DIY
    - centralized = economies of scale
    - who owns the IP? depends on price of media
    - local craft: like beers
        * in vitro meat cookbook (craft meatery like brewery)
    - Produce meat at home (futuristic - Trojan meats)
* Centralization is most likely (Tyson Waterloo, Smithfield)
* In the hands of farmers: bioreactors coop
    - bio maker spaces (trained professionals monitoring your production)
* Family pet: ping in your backyard

### Problems

* Fermentation is older tech (70s) from insulin injected into growing cells
    - stayed in that space, no innovation
    - identify proteins and patent them (all mammals milk and eggs)
* Bioreactor design/conditionalities
    - chemical and mechanical engineering
* Producer consumer space (people with reactors, people who want to use them)
* Supplemantary services
    - culture biosciences (bioreactors in the cloud)
    - send them a microbe and get a detailed analysis of what's needed to scale
      up production
    - process for making productionization really seamless

### Using AI

* Idea screening (Pick a product)
* Initial development (prototype)
* Solve scale
* Launch the product

```
    Animal Target -> Prototype -> Functionality / scale -> flavoring
        Chefs           R&D             Sensorial Experts
        Biagio      Food Science            Vertumnus
                    Product Devs
                        Chiara
                    --------------
                    Giuseppe models
                    --------------
```

* Data: textureometry, infrared, GCMS: gas chromatography mass spectroscopy etc
    - colorimetry, ph, water activity, fermentation processes
    - everything done by a food scientist goes back to the db
* Recipies on the web (odors, flavors, volatile compounds etc)

## Who?

* Memphis meats: GMO
* Meaty foods: fermentation
* Impossible foods and heme
* Geltor Inc (Collagen gummies)
* Air Protein
* White dog labs (ethanol production retrofit)
* Perfect Day (precision fermentation)
* Wild earth (pet food)
* At last bacon (fungi based bacon)
* Collume
* Clara foods (egg whites)
* Memphis meats, Masa meat (product), New Harvest, Good Food Institute (academic)
    - Companies are designing bioreactors and making cell lines
    - Every single part of the process needs access to a company
* [Culture biosciences](https://www.culturebiosciences.com/careers)
    - Fermentation is 90% troubleshooting
    - Process to scale up require tests
    - Traditional fermentation is a lot of babysitting
    - [Commercial fermentation bottlenecks](https://www.youtube.com/watch?v=aqr18eiot9Q)
* Just Meat, Clean Meat, Enhanced Meat, Meat me halfway
    - in vitro bistro

## Appendix

* The immortal life of Henrietta Lacks
* [iap](https://www.cellag-mit.com/iap-course)
* [course](https://www.youtube.com/watch?v=fmt42H2PS5E)


