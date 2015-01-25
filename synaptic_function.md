## 'Functional process-based'

1.	Presynaptic excitability
2.	presynaptic ca entry/primary ca channels for different syn and regions
3.	synaptic vesicle clustering/docking/priming
4.	fusion/release
  * Synchronized
  * Asynchronized
  * Spontaneous
5.	Neurotransmitter reuptake  - [neurotransmitter uptake ; GO:0001504](#neurotransmitter-uptake-go0001504)
6.	Synaptic vesicle endocytosis
7.	Synaptic vesicle membrane recycling
8.	Neurotransmitter loading
9.	Dense core vesicle transport and release
10.	Presynaptic modulation 
11.	Organization of synaptic junction 
  * Extracellular matrix
  * Glia-related modulation
12.	Receptor binding/activation
13.	Receptor localization
14.	Trafficking
	* Constitutive
	* Activity-dependent
15.	Postsynaptic excitability
 	* Receptor modulation
	*	Ion channels
16.	Postsynaptic signal transduction
17.	Synaptic plasticity
  * Structural plasticity-spines
  * Functional plasticity
18.	Extra-synaptic modulators


### [neurotransmitter uptake ; GO:0001504](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0001504#term=annotation)
* __def:__"The directed movement of neurotransmitters into neurons or glial cells. This process leads to inactivation and recycling of neurotransmitters. It does not occur during cholinergic synaptic transmission. Instead, acetylcholine is enzymatically degraded in the synaptic cleft." [ISBN:0123668387]
* __synonym:__"neurotransmitter import" EXACT [GOC:dph, GOC:tb]
* __synonym:__"neurotransmitter import into glial cell" NARROW []
* __synonym:__"neurotransmitter import into neuron" NARROW []
* __synonym:__"neurotransmitter recycling" BROAD []
* __synonym:__"neurotransmitter reuptake" EXACT []

### [synaptic transmission ; GO:0007268](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0007268#term=annotation)
* __def:__"The process of communication from a neuron to a target (neuron, muscle, or secretory cell) across a synapse." [GOC:jl, MeSH:D009435]
* __synonym:__"neurotransmission" RELATED [GOC:dph]
* __synonym:__"regulation of synapse" RELATED []
* __synonym:__"signal transmission across a synapse" EXACT []

### [synaptic vesicle docking ; GO:0016081](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0016081#term=annotation)
* __def:__"The initial attachment of a synaptic vesicle membrane to the presynaptic membrane, mediated by proteins protruding from the membrane of the synaptic vesicle and the target membrane." [PMID:15217342]
* __synonym:__"synaptic vesicle docking during exocytosis" RELATED [GOC:dph, GOC:tb]
* __synonym:__"synaptic vesicle docking involved in exocytosis" EXACT []
* __relationship:__ _part_of_ GO:0007268 ! synaptic transmission

### [synaptic vesicle priming ; GO:0016082](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0016082#term=annotation)
* __def:__"The formation of SNARE-containing complexes, bringing synaptic vesicle membrane and plasma membranes into close proximity and thereby facilitating membrane fusion." [GOC:mah, PMID:15217342]
* __relationship:__ _part_of_ GO:0007268 ! synaptic transmission

### [neurotransmitter receptor activity ; GO:0030594](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0030594#term=annotation)
* __def:__"Combining with a neurotransmitter and transmitting the signal to initiate a change in cell activity." [GOC:jl, GOC:signaling]
* __relationship:__ _part_of_ GO:0007268 ! synaptic transmission

### [synaptic vesicle recycling ; GO:0036465](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0036465#term=annotation)
* __def:__"The trafficking of synaptic vesicles from the pre-synaptic membrane so the vesicle can dock and prime for another round of exocytosis and neurotransmitter release. Recycling occurs after synaptic vesicle exocytosis, and is necessary to replenish presynaptic vesicle pools, sustain transmitter release and preserve the structural integrity of the presynaptic membrane." [GOC:bf, GOC:pad, GOC:PARL, PMID:15217342, PMID:22026965, PMID:23245563]
* __synonym:__"kiss-and-run synaptic vesicle recycling" NARROW [PMID:15217342]
* __synonym:__"kiss-and-stay synaptic vesicle recycling" NARROW [PMID:152127342]
* __relationship:__ _part_of_ GO:0007268 ! synaptic transmission

### [regulation of synaptic plasticity ; GO:0048167](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0048167#term=annotation)
* __def:__"A process that modulates synaptic plasticity, the ability of synapses to change as circumstances require. They may alter function, such as increasing or decreasing their sensitivity, or they may increase or decrease in actual numbers." [GOC:dph, GOC:jid, GOC:tb, http://www.mercksource.com, PMID:11891290]
comment: Note that the syntax of the definition of the this term is different from the usual regulation syntax because it describes regulation of a trait rather than regulation of a process.
* __relationship:__ _regulates_ GO:0007268 ! synaptic transmission

### [synaptic vesicle endocytosis ; GO:0048488](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0048488#term=annotation)
alt_id: GO:0008099
* __def:__"An endocytosis process that results in the invagination of the axonal plasma membrane to create a membrane-bounded vesicle. This process takes up excess membrane that would otherwise accumulate at the presynaptic terminal due to fusion of vesicle membranes during neurotransmitter release. The vesicles created may subsequently be used for neurotransmitter storage and release." [GOC:jid, GOC:lmg, GOC:mah]
* __synonym:__"synaptic vesicle retrieval" RELATED []
* __relationship:__ _part_of_ GO:0036465 ! synaptic vesicle recycling

### [calcium ion-dependent exocytosis of neurotransmitter ; GO:0048791](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0048791#term=annotation)
* __def:__"The release of a neurotransmitter into the synaptic cleft, where the release step is dependent on the presence of calcium ions (Ca2+). The neurotransmitter is contained within a membrane-bounded vesicle, and is released by fusion of the vesicle with the presynaptic plasma membrane of a nerve cell." [GOC:curators]

### [spontaneous neurotransmitter secretion ; GO:0061669](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0061669#term=annotation)
* __def:__"Neurotransmitter secretion that occurs in the absence of the action of a secretagogue or a presynaptic action potential." [GOC:dph, GOC:pad, GOC:PARL, PMID:21334193]
* __synonym:__"stimulus-independent neurotransmitter secretion" EXACT [GOC:dph]

### [neurotransmitter loading into synaptic vesicle ; GO:0098700](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0098700#term=annotation)
* __def:__"The active transport of neurotransmitters into a synaptic vesicle. Typically this import is fuelled by an electrochemical gradient across the vacuolar membrane, established by the action vacuolar proton pumps (see 'synaptic vesicle lumen acidification' GO:0097401)." [GOC:bf, GOC:pad, GOC:PARL, PMID:10099709, PMID:15217342]
* __synonym:__"neurotransmitter import into synaptic vesicle" EXACT []
* __synonym:__"neurotransmitter uptake into synaptic vesicle" EXACT [PMID:15217342]

### [fast, calcium ion-dependent exocytosis of neurotransmitter ; GO:0098746](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0098746#term=annotation)
* __def:__"The fast, initial phase of calcium ion-induced neurotransmitter release, via exocytosis, into the synaptic cleft. This depends on low affinity calcium sensors and typically begins a fraction of a millisecond after Ca2+ influx, and decays rapidly (1-10ms) with a decay constant of around 5-10ms. The underlying molecular mechanisms of this process are distinct from those of the later, slow phase of release." [GOC:dos, GOC:pad, GOC:PARL, PMID:4405553, PMID:7809151, PMID:7954835]
* __synonym:__"synchronous, calcium ion-dependent exocytosis of neurotransmitter" EXACT [PMID:7954835]
is_a: GO:0048791 ! calcium ion-dependent exocytosis of neurotransmitter

### [slow, calcium ion-dependent exocytosis of neurotransmitter ; GO:0098747](http://www.ebi.ac.uk/QuickGO/GTerm?id=GO:0098747#term=annotation)
* __def:__"The slow, second phase of calcium ion-induced neurotransmitter release, via exocytosis, into the synaptic cleft. This depends on high affinity calcium sensors and decays slowly, typically with a decay constant of over 100ms. The underlying molecular mechanisms of this process are distinct from those of the earlier, fast phase of release." [GOC:dos, GOC:pad, GOC:parl, PMID:7809151, PMID:7954835]
is_a: GO:0048791 ! calcium ion-dependent exocytosis of neurotransmitter
