## Hello! 👋

We're interested in building the most efficient + advanced toolkit to design better protein therapeutics. We're a team of three. 

Our conviction lies in _harnessing the power to bend proteins at will_. We strongly believe that proteins (Ammino Acids more specifically) are the bits of biology and that we can design orders of magnitude better therapeutics than we can today. If we have substantially better insight into proteins, we believe that these major problems with protein therapeutics are solvable:
- Protein penetration into the cell.
- Adverse Immune Response.
- Protein Degradation, etc.

Biology has had a way of bypassing all these problems for millennia. Small molecules, while powerful simply lack the sophistication for better medicine. We must try to leave them behind.

## What are we doing differently?
There's substantial parallel work being done in the computational protein space since 2021. We are starting from first principles to build towards our vision. We might independently arrive at conclusions drawn already by other teams - we consider that a strong positive reinforcement rather than a negative data point. We need to figure out a few key components:
- **All-inclusive protein representations**: The current SOTA methods still can't produce inclusive protein representations that can incorporate all facets of proteins from sequence, structure, temporal dynamics, post-translational modifications, single point mutations, additional bound ligands/substrates, protein complexes, etc. into one representation learning scheme. This makes us only extrapolate knowledge from one or a few sets of domains. We have taken the first step to enquire if **Joint Embedding Architecture** (popularized by Yann Lecun) is the way forward. Our first experiment is to simply integrate sequence and structure (since it's entirely standardized at this point). Find more information here: [https://github.com/atom-51/jespr](https://github.com/atom-51/jespr).
- **An apt pre-training objective**: We need to find the pre-training objective for protein learning which is as powerful as 'next word prediction' for language. Our bet currently is on contrastive loss for protein representations in different modalities. This also ties into our first point on how to learn more inclusive representations.
- **Mapping out the entire protein landscape**: Target discovery is absolutely crucial. We can now almost reliably sequence and predict 3-D structures of all proteins. By adding a few key pieces such as information for spacial transcriptomics &rarr; proteomics to extrapolate cellular localization and interaction prediction, we should start accurately mapping the Gene Ontology landscape. We're still exploring how best to approach this problem.

## Are we funded or incorporated?
We are currently neither funded nor incorporated and have bootstrapped ourselves. We are still figuring out the best path forward and till then we'll work off **non-dilutive grants** and **open-source** our work. We are also supported by our university's (Imperial College London) compute resources (no IP boundation).

We are currently not looking to raise equity-based investments. Do let us know if you find a good grant.
We wish to focus on building more than anything else. Contrary to popular belief, capital is not the bottleneck yet, and neither is human capital. Well not exactly. Compute is a bottleneck. If you have any GPU compute cluster we can ssh into (anything over 4 server-class GPUs), we'd wish for god to bless your soul if you could grant us access. You can also support us by reviewing our work and letting us know what you think.


Our conviction towards Deep Learning is unwavering. We believe these problems are solvable. 
