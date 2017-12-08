## Who I am

Twenty-four years old with a twenty-year-old interest in computers

Former academic with a degree in evolutionary biology

Bioinformatist, data freak, self-starter developer

Ever eager to learn (and make) more from the programming world, in order to enhance lives in the concrete one


## Development history

### Work tools

My first contact with programming rose from the need to automatize data manipulation routines for research; simple and functional bioinformatics that led to the creation of a [library](https://github.com/lpmarques/BItools-lib/) of tools.

For the purposes of accessing, filtering and cleaning DNA sequences, a handful of them can be checked [here](https://github.com/lpmarques/BItools-lib/tree/master/Sequence_processing).
They include a script for [conversion](https://github.com/lpmarques/BItools-lib/blob/master/Sequence_processing/multiGB2fasta.pl) of the (often confusing) *multigb* file format (obtained from any [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) database search) to a cleaner multisequence *fasta* file; as well as one that executes a complete [data cleaning](https://github.com/lpmarques/BItools-lib/blob/master/Sequence_processing/zblocks.pl) job on sequence alignments. A tool for automatic [concatenation](https://github.com/lpmarques/BItools-lib/blob/master/Sequence_processing/concatenator.pl) of multiple sequence alignments is also included.

To molecular scientists, it is also of usual interest to determine base (character) composition of their DNA sequence alignments. In this case, they could find useful scripts [here](https://github.com/lpmarques/BItools-lib/tree/master/Alignment_composition_analyses) that can simply [calculate](https://github.com/lpmarques/BItools-lib/blob/master/Alignment_composition_analyses/gapcounter.pl) the total proportion of (often undesireble) gap characters, or even [access](https://github.com/lpmarques/BItools-lib/blob/master/Alignment_composition_analyses/sitereader.pl) detailed information on base composition across all columns of an alignment.

Those interested in macroevolutionary issues could also make good use of [few scripts](https://github.com/lpmarques/BItools-lib/tree/master/Automated_tree_analyses) I developed to automatize analyses of big evolutionary trees (with potentially hundreds or thousands of terminal nodes involved). These include a simple subroutine to [unroot](https://github.com/lpmarques/BItools-lib/blob/master/Automated_tree_analyses/unroot.pl) trees, besides a more complex one that can [detect differences](https://github.com/lpmarques/BItools-lib/blob/master/Automated_tree_analyses/treeDist.pl) between partitions of two trees and summarize them in what is usually called "topological distances".

### Projects

Although I started in the coding world, 3 years ago, by learning python, my main working language for the last 2 years has been Perl, which was a common ground with my lab's team. Nevertheless, since my research project to achieve master's degree involved great amounts of data analysis, it was inevitable to get experienced in with R. Building Sheel pipelines to integrate multiple softwares on complex tasks became a routine just as well. A piece of that work can be seen [here](https://github.com/lpmarques/EqDelta).

Last but not least, I am currently developing **phyTest**, a software that can perform various statistical tests regarding evolutionary tree models. Although still in alpha phase, it is already the most flexible, publicly acessible software in terms of diversity of approaches to determine tree confidence. The last version of phyTest can always be found [here](https://github.com/lpmarques/phyTest) (an english version of the manual will be available soon).


## Where to find me

* lucasmarques.bio@gmail.com
* [Linkedin](https://www.linkedin.com/in/lucas-marques-370535a6/)
* [Facebook](https://www.facebook.com/lucas.pmarques?ref=bookmarks)