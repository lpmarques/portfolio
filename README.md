## Who I am

Twenty-four years old with a twenty-year-old interest in computers

Former academic with a degree in evolutionary biology

Bioinformatist, data freak, self-starter developer

Ever eager to learn (and make) more from the digital world to enhance lives in the physical one

## Development history

### Work tools

My first contact with software development rose from the need to automatize data manipulation routines for research. Simple and functional bioinformatics that led to the creation of a [library](https://github.com/lpmarques/BItools-lib/) of scripts.

For the purposes of accessing, filtering and cleaning DNA sequences, a handful of those tools can be checked [here](https://github.com/lpmarques/BItools-lib/tree/master/Sequence_processing). They include a script for [conversion](https://github.com/lpmarques/BItools-lib/blob/master/Sequence_processing/multiGB2fasta.pl) of the (often confusing) multigb file format (obtained from [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) database searches) to a cleaner multi-sequence fasta file; as well as one that executes a complete [data cleaning](https://github.com/lpmarques/BItools-lib/blob/master/Sequence_processing/zblocks.pl) job on sequence alignments. A tool for automatic [concatenation](https://github.com/lpmarques/BItools-lib/blob/master/Sequence_processing/concatenator.pl) of multiple sequence alignments is also included.

Molecular scientists are frequently interested in determining base character composition of their DNA sequence alignments too. In this case, they could find useful scripts [here](https://github.com/lpmarques/BItools-lib/tree/master/Alignment_composition_analyses) that can simply [calculate](https://github.com/lpmarques/BItools-lib/blob/master/Alignment_composition_analyses/gapcounter.pl) the total proportion of (often undesireble) gap characters, or even [access](https://github.com/lpmarques/BItools-lib/blob/master/Alignment_composition_analyses/sitereader.pl) detailed information on base composition across all columns of an alignment.

Those interested in macro-evolutionary issues could make good use of [few scripts](https://github.com/lpmarques/BItools-lib/tree/master/Automated_tree_analyses) I developed to automatize analyses of big evolutionary trees too. These include a simple function to [unroot](https://github.com/lpmarques/BItools-lib/blob/master/Automated_tree_analyses/unroot.pl) trees and a more complex one that can [detect differences](https://github.com/lpmarques/BItools-lib/blob/master/Automated_tree_analyses/treeDist.pl) between partitions of two trees and return what is usually called “topological distances”.

### Projects

Although 3 years ago I wrote my first pieces of code in Python, my main working language for the last 2 years has been Perl, a highly efficient language to handle text-like data, with clear implementation of regular expressions. Moreover, as my postgrad research project involved great amounts of data analysis, soon I got experienced in R too. Building Shell pipelines to integrate multiple softwares on complex tasks became a routine to me just as well. A piece of that work can be seen [here](https://github.com/lpmarques/EqDelta).

Currently, I am developing phyTest, a software that can perform various statistical tests regarding evolutionary tree models. Although still in alpha phase, it is already the most flexible, publicly acessible software in terms of diversity of approaches to determine statistical confidence on phylogenies. The last version of phyTest can always be found [here](https://github.com/lpmarques/phyTest) (an English-speaking version of the manual will be available soon).

### Competitive Programming

Recently, I have also engaged in the 2018's edition of the international Bioinformatics Contest. Some of the Python scripts that I delevoped (and found most interesting) in the process to qualify to the final round can be checked [here](https://github.com/lpmarques/BIContest2018). These include a heuristic solution to [approximate](https://github.com/lpmarques/BIContest2018/blob/master/realMaxATP.py) the most cost-efficient ballance of glucose and oxygen mols to produce ATP via fermentation or aerobic respiration and an efficient algorithm to [locate](https://github.com/lpmarques/BIContest2018/blob/master/longestTandem.py) the longest tandem repeat in a sequence that fits a user-provided maximum amount of character insertions, deletions or substitutions across it.

## Where to find me

* lucasmarques.bio@gmail.com
* [Linkedin](https://www.linkedin.com/in/lucas-marques-370535a6/)