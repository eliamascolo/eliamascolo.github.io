---
layout: default
---

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-WL39373EB2"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-WL39373EB2');
</script>

<style>
details {
  padding: 12px;
  padding-bottom: 2px;
  cursor: pointer;
}

details > summary > * {
  display: inline;
}

details > summary {
  padding: 4px;
  background-color: #e4eaef;
  box-shadow: 1px 1px 2px #bbbbbb;
  border: none;
  cursor: pointer;
}	

details > p {
  background-color: #e4eaef;
  padding: 1px;
  box-shadow: 1px 1px 2px #bbbbbb;
  margin: 0;
}

</style>

## Research Projects 🔬

<i>Click on the titles to read more.</i>

<details>
<summary id="ITCM"><strong>Information Theory of Composite Sequence Motifs</strong></summary>
<p>Through nucleotide conservation, the genomic positions that must be bound by transcription factors can provide information.
The information content (named <i>Rsequence</i>) can be measured (in <i>bits</i>) and happens to be nearly equal to the amount of information theoretically required for the target location to be accomplishable (a quantity named <i>Rfrequency</i>)
<a href="https://doi.org/10.1016/0022-2836(86)90165-8">(Schneider <i>et al.</i>, 1986)</a>.
I proposed a generalized framework for this fundational theory that can be used to describe the evolution of *composite* sequence motifs of *n* elements
<a href="https://doi.org/10.1101/2024.11.11.623117">(Mascolo & Erill, 2024)</a>.
The classical theory by Schenider can be seen as a special case where <i>n=1</i>.
I also show how this framework can be applied to study different aspects of target recognition mediated by molecular complexes (how protein flexibility can co-evolve with spacer variability, the thermodynamic efficiency of different recruitment strategies, and the effect of mutation spectra on the evolvability of different information-encoding strategies).

<img src="/images/Rspacer.jpg" alt="A diagram representing a composite motif composed of two sequence patterns separated by a spacer of variable length.">
<br /><br />
&#x1F4CC; <a href="/pdf_files/poster_Info_Theo_Composite_Motifs.pdf" target="_blank"><b>Open poster</b></a>
</p>
</details>

<details>
<summary><strong>FLEMINGO</strong></summary>
<p>I developed a motif discovery tool that can discover <i>composite motifs</i> (see <a href="#ITCM">Composite Sequence Motifs</a> ) in biological data (sets of co-regulated promoters) through evolutionary computation. The tool, called <strong><i>FLEMINGO</i></strong> (for <strong>FLE</strong>xible <strong>M</strong>otif <strong>IN</strong>ference via <strong>G</strong>enetic <strong>O</strong>ptimization), can detect motifs encompassing spacers (or <i>gaps</i>) of variable length, as well as DNA shape features (inferred from the DNA sequence).
<img src="/images/FLEMINGO_logo.jpg" alt="The logo of the bioinformatic tool FLEMINGO, showing flamingos connecting sequence logos with their legs">
</p>
</details>

<details>
<summary><strong>Cross-replicon gene regulation</strong></summary>
<p>In a transcriptional regulatory network (TRN), every node represents a gene, and every link represents a transcriptional regulation,
connecting a transcription factor with one of its targets.

Could there be hybrid TRNs comprising genes that are encoded on different replicons? For example, in bacterial cells we could find the bacterial genome, but also natural plasmids, as well as bacteriophage genomes and other mobile genetic elements (MGEs).

In 2022, we showed that many phylogenetically unrelated bacteriophages that infect Alphaproteobacteria have convergently evolved DNA binding sites for the host cell cycle regulator CtrA, suggesting that these bacteriophages synchronize lysis with the life stage of the host to maximize their infective yield, through a pathway that we termed lytic deferment.

<a href="https://doi.org/10.3389/fmicb.2022.918015">(Mascolo *et al.*, 2022)</a>.

I developed an algorithm to systematically predict the presence of such hybrid TRNs. This method can re-discover the few cases that are already known in the literature, but it also finds many new realistic candidates, revealing that hybrid TRNs are highly prevalent in the microbial world (<strong>unpublished work</strong>). Several of its predictions are currently being experimentally validated.

<img src="/images/hybrid_TRN.png" alt="A diagram representing a hybrid transcriptional regulatory network, where some nodes belong to a bacterial chromosome and some to mobile genetic elements">
<br /><br />
&#x1F4F0; <a href="#mge-tf-news">Media coverage on host-phage cross-regulation</a>
<br>
&#x1F4CC; <a href="/pdf_files/poster_MGE_TF.pdf" target="_blank"><b>Open poster</b></a>
</p>
</details>

<details>
<summary><strong>Project here</strong></summary>
<p>In a work where I share co-first authorship with Tagide deCarvalho, we describe for the first time a virus that attaches itself to another virus. Tagide deCarvalho discovered this novel type of interaction while observing under the electron microscope (TEM) a novel bacteriophage that our students named MindFlayer. She noticed that most of them had a smaller virus attached to the "neck" (the part that connects the head, or capsid, to the tail). This explained what earlier, during the genome sequencing of MindFlayer, seemed to be a systematic contamination. With the microscope, she revealed that the shorter secondary sequence was not a contamination but the genome of this smaller hitchhiker, which we named MiniFlayer. I performed a bioinformatics analysis, showing that MindFlayer and MiniFlayer have been co-evolving for a long time, and further suggesting that MiniFlayer exploits the genes of MindFlayer. However, unlike previously known interactions, it doesn't wait in the host cell for MindFlayer to co-infect. Rather, it ensures the presence of the genes it needs by entering the host together with MindFlayer.

<img src="/images/MindFlayer_MiniFlayer.jpg" alt="A picture taken with the electron transmission microscope of MiniFlayer attached to MindFlayer.">
<br /><br />
&#x1F4F0; <a href="#mindflayer-news">Media coverage on MindFlayer and MiniFlayer</a>
</p>
</details>

## Media coverage 📰

### First discovery of a virus that travels attached to another virus [(deCarvalho and Mascolo *et al.*, 2023)](https://www.nature.com/articles/s41396-023-01548-0)

<div id="mindflayer-news"></div>

* [Washington Post](https://www.washingtonpost.com/science/2023/11/13/mindflayer-virus-discovered-maryland/)
* [Scientific American](https://www.scientificamerican.com/article/vampire-viruses-prey-on-other-viruses-to-replicate-themselves-and-may-hold-the-key-to-new-antiviral-therapies/)
* [More ...](https://nature.altmetric.com/details/155926514/news)

### Host-phage cross-regulation [(Mascolo and Adhikari *et al.*, 2022)](https://doi.org/10.3389/fmicb.2022.918015)

<div id="mge-tf-news"></div>

* [PHYS.ORG](https://phys.org/news/2022-09-viruses-eyes-ears.html)
* [The Conversation](https://theconversation.com/viruses-may-be-watching-you-some-microbes-lie-in-wait-until-their-hosts-unknowingly-give-them-the-signal-to-start-multiplying-and-kill-them-189949)
* [More ...](https://loop-impact.frontiersin.org/impact/article/918015#socialbuzz)

<br><br>

