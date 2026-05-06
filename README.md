# Serena Rosignoli 👋

**Computational biologist · Research software engineer · Tool builder**

Mostly Python. Often PyMOL. Increasingly AI.  
Always trying to turn messy research problems into usable tools.

> I build for people who have better things to do than fight with fragmented workflows.


## Where to find me

Post-Doctoral Research Fellow  
Centre for Regenerative Medicine “Stefano Ferrari”  
University of Modena and Reggio Emilia  

📫 Email: `serena.rosignoli@unimore.it`  
🔗 LinkedIn: [Serena Rosignoli](https://www.linkedin.com/in/serenarosignoli97/)  
📚 Publications: [Google Scholar](https://scholar.google.com/citations?user=tFQ9tMAAAAAJ&hl=it)

**Below is the build log, “shopping-list” style.**<br>
**Reading it, optional.**<br>
**Contacting me, faster.**

---

## PyMOL-based scientific software

### PyMod  
**User-facing platform for protein modelling and structural bioinformatics inside PyMOL.**

PyMod integrates sequence analysis, structure prediction, homology modelling, and structural analysis into a graphical molecular-modelling environment.

Through this project, I worked on:

- user-facing workflow design
- integration of external modelling tools
- sequence/structure data handling
- graphical interface logic
- automation of complex modelling protocols
- making structural bioinformatics workflows accessible to non-specialist users

Repository: [PyMod](https://github.com/pymodproject/pymod)

---

### DockingPie  
**Plugin-based software for molecular docking workflows in PyMOL.**

DockingPie was developed to make molecular docking protocols easier to run, compare, and interpret from a unified graphical interface.

Through this project, I worked on:

- plugin architecture
- command-line tool integration
- input/output standardization
- graphical workflow design
- docking protocol automation
- usability-oriented scientific software development

Repository: [DockingPie](https://github.com/paiardin/DockingPie)  
Publication: [Bioinformatics paper](https://doi.org/10.1093/bioinformatics/btac452)

---

### PyPCN  
**PyMOL plugin for protein contact network analysis.**

PyPCN supports the analysis of protein structures as residue-interaction networks, helping users explore structural relationships through graph-based representations.

Through this project, I worked on:

- structural data parsing
- network construction from molecular structures
- PyMOL-integrated visualization
- user-oriented analysis workflows
- scientific plugin development

Repository: [PyPCN](https://github.com/pcnproject/PyPCN)  
Publication: [Bioinformatics paper](https://doi.org/10.1093/bioinformatics/btad675)

---

### AlPaCas: a tool for allele-specific genome editing

AlPaCas is a web server and computational pipeline for designing allele-specific CRISPR/Cas strategies.  
In practice: start from a mutation, encode the biological constraints, search for usable designs, rank them, and make the result readable enough for people who do not want to inspect every guide by hand.

Publication: [Nucleic Acids Research paper](https://doi.org/10.1093/nar/gkae419)

`sequence analysis` · `scoring logic` · `web server` · `gene editing`

---

### G4REP  
**Deep-learning framework for protein classification.**

G4REP predicts human RNA G-quadruplex-binding proteins using sequence-based information and deep-learning models.

Publication: [Bioinformatics paper](https://doi.org/10.1093/bioinformatics/btag088)

---

### WORK IN PROGRESS 

### Explainable AI for molecular models

Reproducible pipelines to understand what machine-learning models use when making predictions on molecular systems.  
Current focus: attribution methods, stability checks, faithfulness tests, benchmarking, and less hand-wavy ways to decide whether an explanation is actually useful.

`Integrated Gradients` · `model evaluation` · `benchmarking` · `reproducibility`

---

### AI-assisted protein design workflows

Integration of protein design models into practical modelling workflows, including the annoying-but-important details: which residues are designable, which ones must stay fixed, how to run the model, parse the outputs, and bring generated sequences/structures back into the working environment.

`ProteinMPNN` · `LigandMPNN` · `workflow design` · `output parsing`

---

### Base-editing design workflows

Extension of the same logic toward base editing: enumerate guides, map editing windows, check bystander effects, score the designs, and produce outputs that are useful before anyone starts ordering reagents.

`CBE/ABE` · `editing windows` · `bystander risk` · `guide ranking`

---

### Molecular dynamics utilities

Scripts for molecular dynamics simulations when they need to behave on real systems and real clusters.  
Current obsession: checkpointing, clean restarts, SLURM jobs that survive the mood of the node, and analysis scripts that make trajectories easier to inspect.

`OpenMM` · `SLURM` · `checkpointing` · `trajectory analysis`

---

## Utilities and learning resources

### PyMOL toolbox  
Small utilities, examples, and scripts for PyMOL-based development.

Includes:

- PyMOL environment utilities
- plugin-development examples
- threading examples for PyQt/PyMOL plugins
- workflow helpers for structural bioinformatics

Repository: [PyMOL toolbox](LINK_PLACEHOLDER)

---

### Lectures and teaching material  
Slides and teaching material from lectures, workshops, and summer schools.

Topics include:

- molecular docking
- PyMOL and plugin-based modelling
- structural bioinformatics
- protein modelling
- bioinformatics for non-specialists
- data analysis concepts

Repository: [Lectures and teaching material](LINK_PLACEHOLDER)

---

### Python for bioinformatics toolbox  
A collection of Python scripts and examples for bioinformatics workflows, data processing, and structural analysis.

Repository: [Bioinfo Python toolbox](LINK_PLACEHOLDER)

---

### Algorithms and programming practice  
Programming assignments and algorithmic exercises developed while completing the Stanford Algorithms Specialization.

Repository: [Algorithms Specialization](LINK_PLACEHOLDER)

---

## Selected readings

- **Boosting the Full Potential of PyMOL with Structural Biology Plugins**  
  [Publication](LINK_PLACEHOLDER)

- **DockingPie: a consensus docking plugin for PyMOL**  
  [Publication](LINK_PLACEHOLDER)

- **PyPCN: protein contact networks in PyMOL**  
  [Publication](LINK_PLACEHOLDER)

- **AlPaCas: allele-specific CRISPR gene editing through a PAM approach**  
  [Publication](LINK_PLACEHOLDER)

- **G4REP: Deep-learning prediction of human RNA G-quadruplex-binding proteins**  
  [Publication](LINK_PLACEHOLDER)

---

## How I think about software

I come from research environments where the problems are complex, the data are messy, and the users often need tools that are both rigorous and practical.

For this reason, I care about:

- clarity over unnecessary complexity
- reproducibility over one-off scripts
- usability over technical showmanship
- robust workflows over fragile prototypes
- tools that help people think, not just tools that run

My goal is to translate advanced computational methods into software that researchers can actually use.

---

## Contact

📫 Email: `serena.rosignoli@unimore.it`  
🔗 LinkedIn: [Serena Rosignoli](LINK_PLACEHOLDER)  
📚 Publications: [Google Scholar](LINK_PLACEHOLDER)
