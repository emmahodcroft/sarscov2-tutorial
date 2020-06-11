# Template repository for SARS-CoV-2 analyses    

This repository is a template and tutorial for running a basic phylogenetic analysis on SARS-CoV-2 data.
We've created these resources with the goal of enabling Departments of Public Health to start using Nextstrain to understand their SARS-CoV-2 genomic data within 1-2 hours.

_If you're looking for the SARS-CoV-2 analyses used for the main Nextstrain builds, please see [this repository instead](https://github.com/nextstrain/ncov)._

## Tutorial overview

* [Preparing your data](data-prep.md)  
* [Set up and installation](XXX)  
* [Orientation: what does Nextstrain actually do, and what are each of these files?](orientation.md)  
* [Running & troubleshooting a basic analysis](customization.md)  
* [Visualizing the output with Auspice](visualizing.md)
* [Interpreting your results]() (more coming soon!)
* [Writing a narrative to highlight key findings]() (more coming soon!)
* [Options for sharing your results and managing sensitive metadata](sharing.md)  

## Quickstart  

If you'd prefer, you can also start by running a vanilla analysis on the provided example data and visualizing the output with the [auspice.us](auspice.us) drag-and-drop viewer. If you get stuck at any point, you can find more detailed instructions in the full tutorial outlined above.

#### 1. Install
```
python3 -m pip install nextstrain-augur
```

MacOS:
```
brew install mafft iqtree raxml fasttree vcftools
```

Ubuntu/Debian:  
```
sudo apt install mafft iqtree raxml fasttree vcftools
```

#### 2. Run basic analysis on example data  
```XXXX```


#### 3. Visualize your results (or our example output)  
Go to `https://auspice.us` in your browser.
Drag and drop `./auspice/sarscov2.json` anywhere on the screen.
Voila!

## Getting help  

If something in this tutorial is broken or unclear, please [open an issue](XXX) so we can improve it for everyone.  
If you have a specific question, post a note over at the [discussion board](XXX) -- we're happy to help!
