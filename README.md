# Antibio-resistance
Neisseria gonorrhoeae is a species of Gram-negative diplococci bacteria and the causative agent of the sexually transmitted infection Gonorrhoeae. Gonorrhoea is the second most common sexually transmitted infection (STI) in Europe, after chlamydia. Rates of gonorrhoea infection are on the rise, with a 26% increase reported from 2017-2018 in the UK.

Many people who are infected (especially women) experience no symptoms, helping its spread. However if the infection is left untreated, it can lead to infertility in women, and can occasionally spread to other parts of the body such as your joints, heart valves, brain or spinal cord.

Antimicrobial resistance is becoming a serious concern— currently antimicrobial resistant infections kill over 700,000 people per year. By 2050 its estimated 10 million people will die from of antimicrobial resistant infections.

(Whittles, L. K., White, P. J., Paul, J., & Didelot, X. (2018). Epidemiological trends of antibiotic resistant gonorrhoea in the United Kingdom. Antibiotics, 7(3), 60.)

Methodology -

To identify genes involved in resistance the authors have developed a library of unitigs using a technique known as GWAS. Genome-wide association studies (GWAS) help explore the genetic bases of phenotype variation in a population. To circumvent issues involved in conventional genotyping approaches and make bacterial genomes amenable to GWAS, recent studies have relied on k-mers: all nucleotide substrings of length k found in the genomes. Since SNP- and gene-based representations lack the right level of flexibility to cover complete genomic variation, and, on the other hand, k-mer-based representations which are flexible but not readily interpretable therefore DBG-GWAS De Bruijn Graph GWAS was used. These graphs connect overlapping k-mers (here DNA fragments), yielding a compact summary of all variations across a set of genomes. DBGs accommodate more complex disparities including rearrangements and insertions/deletions. (Jaillard M, Lima L, Tournoud M, Mahé P, van Belkum A, Lacroix V, et al. (2018) A fast and agnostic method for bacterial genome-wide association studies: Bridging the gap between k-mers and genetic events. PLoS Genet 14(11): e1007758. https://doi.org/10.1371/journal.pgen.1007758)

The goal of this study is to identify the unitigs that are most likely to contribute to a resistance phenotype in our samples.
