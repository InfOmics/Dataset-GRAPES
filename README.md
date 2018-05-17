# Graph Dataset

Available dataset are distributed under the GRAPES license. 
Each dataset consists of one file containing all the database graphs, a splitting of the dataset into 6 disjoint datasets and a set of query graphs.
<hr />

### AIDS 
>small molecules

The AIDS dataset contains the topological structures of 40000 chemical compounds that have been tested for evidence of anti-HIV activity (available from NCBI). Compounds are undirected graphs where the number of vertices varies from 4 to 245. They are small sparse graphs. The topology of patterns was chosen in order to respect the average degree and label distribution of the target graphs. 
Graphs are undirected with labels on nodes. 

[National Cancer Institute]( http://www.nci.nih.gov/)
<hr />

### PDBS 
> protein backbones

This dataset contains 600 proteins represented by the backbones of the proteins coming from the crystallography downloaded from JenaLib and RCSB. converted to graphs by BALL library . They are medium sparse graphs. They may have from 1683 to 7979 vertices per graph. 
Graphs are undirected with labels on nodes. 

[Huehne R, Suehnel J: The Jena Library of Biological Macromolecules. Nature-precedings 2009.] <br>
[Protein Data Bank]( http://www.rcsb.org/pdb/.) <br>
[Boghossian N, Kohlbacher O, Lenhof H: BALL: Biochemical Algorithms Library. In Proceeding of the 3rd workshop on algorithms engineering WAE 99 Lecture Notes in Computer Science, 1668, Springer, Berlin, London, UK, pp. 330-344, 1999.]

<hr />

### PCM 
> protein contact maps

This dataset contains 200 contact maps of the amino acids of the domains of the proteins, retrieved by CMView. They represent relationships among amino acids. Contact maps are small dense graphs. In average a graph may have 380 vertices. 
Graphs are undirected with labels on nodes. 

[Huehne R, Suehnel J: The Jena Library of Biological Macromolecules. Nature-precedings 2009.] <br>
[Protein Data Bank]( http://www.rcsb.org/pdb/.) <br>
[Boghossian N, Kohlbacher O, Lenhof H: BALL: Biochemical Algorithms Library. In Proceeding of the 3rd workshop on algorithms engineering WAE 99 Lecture Notes in Computer Science, 1668, Springer, Berlin, London, UK, pp. 330-344, 1999.] [Vehlow C, Stehr H, Winkelmann M, Duarte JM, Petzold L, Dinse J, Lappe M: CMView: Interactive contact map visualization and analysis. Bioinformatics 2011.]
<hr />

### PPI 
> protein-protein interaction networks

A database of 20 protein interaction networks. Networks belong to species:Caenorhabditis elegans, Drosophila melanogaster, Mus musculus, Saccaromyces cerevisiae and Homo sapiens. The dataset contains 4 networks per species varying the selected edges in base of their accurateness (greather than 0.4, 0.5,0.6, and 0.7). Networks are annotated assigning the most relevant Gene Ontology annotation, discovered by Cytoscape plugin Mosaic. 

[Ashburner,M., Ball,C.A., Blake,J.A. et al. (2000) Gene ontology: tool for the unification of biology. The Gene Ontology Consortium. Nat. Genet., 25, 25–29.] <br>
[Zhang,C., Hanspers,K. and Kuchinsky,A. (2012) Mosaic: making biological sense of complex networks. Bioinformatics, 28, 1943–1944.]

<hr />

### License

GRAPES is distributed under the MIT license. This means that it is free for both academic and commercial use. 
Note however that some third party components in GRAPES require that you reference certain works in scientific publications. 
You are free to link or use GRAPES inside source code of your own program. If do so, please reference (cite) GRAPES and this website. 
We appreciate bug fixes and would be happy to collaborate for improvements. <br>
[MIT License](https://raw.githubusercontent.com/GiugnoLab/Dataset-GRAPES/master/LICENSE)

<hr />

### Citation
    "Giugno, R., Bonnici, V., Bombieri, N., Pulvirenti, A., Ferro, A., & Shasha, D. (2013). Grapes:
    A software for parallel searching on biological graphs targeting multi-core architectures.
    PloS one, 8(10), e76911."
   <span style="color:blue">[Online version](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0076911) </span> <br>
   [Cited by](https://scholar.google.it/scholar?cites=4839872088400060775&as_sdt=2005&sciodt=0,5&hl=it) <br>
   
   ###### BibTeX format:
   
    "@article{giugno2013grapes,
    title={Grapes: A software for parallel searching on biological graphs targeting multi-core architectures},
    author={Giugno, Rosalba and Bonnici, Vincenzo and Bombieri, Nicola and Pulvirenti, Alfredo and Ferro, Alfredo and Shasha, Dennis},
    journal={PloS one},
    volume={8},
    number={10},
    pages={e76911},
    year={2013},
    publisher={Public Library of Science}
     }"
    


