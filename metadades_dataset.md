# Metadades del Dataset
El conjunt de dades adjunt s'ha obtingut a partir d'un experiment de fosfoproteòmica que es va realitzar per analitzar (3 + 3) models PDX de dos subtipus diferents mitjançant mostres enriquides amb fosfopèptid. S'ha realitzat una anàlisi LC-MS de 2 duplicats tècnics a cada mostra. El conjunt de resultats consistia en abundància normalitzada de senyals MS per a ca. 1400 fosfopèptids. **Objectiu de l'anàlisi**: cerca de fosfopèptids que permetin la diferenciació dels dos grups tumorals S'ha de fer tant amb l'anàlisi estadística com amb la visualització. Les dades s'han proporcionat com a fitxer Excel: TIO2+PTYR-human-MSS+MSIvsPD.XLSX
 ## Informació general
 El dataset conté un total de  1438  fosforopeptids.
 Els següents són alguns dels camps de metadades:
  - **Accession**:  O00560, O15264, O15551, O43490, O60547, O60716, O95297, P00338, P04075, P05787, P07355, P07947, P09769, P10768, P15924, P15941, P16144, P29317, P29353, P31939, P42685, P46059, P46940, P48960, P53801.
  - **Descripció**:  Syntenin-1 OS=Homo sapiens GN=SDCBP PE=1 SV=1, Mitogen-activated protein kinase 13 OS=Homo sapiens GN=MAPK13 PE=1 SV=1, Claudin-3 OS=Homo sapiens GN=CLDN3 PE=1 SV=1, Prominin-1 OS=Homo sapiens GN=PROM1    PE=1 SV=1, GDP-mannose 4,6 dehydratase OS=Homo sapiens GN=GMDS PE=1 SV=1, Catenin delta-1 OS=Homo sapiens GN=CTNND1 PE=1 SV=1, Myelin protein zero-like protein 1 OS=Homo sapiens GN=MPZL1 PE=1 SV=1, L-lactate dehydrogenase A chain OS=Homo sapiens GN=LDHA PE=1 SV=2.
  - 
 ## Grups
 Els grups definits són:
  - **Grup MSS**: Mostres M1, M5, i T49.
  - **Grup PD**: Mostres M42, M43, i M64.
 Amb dues rèpliques tècniques per cada mostra.
 ## Exemple de dades
 ```r
 head(as.data.frame(metadades))
 ```
 Les metadades inclouen les següents columnes: SequenceModifications, Accession, i Description.
