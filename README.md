# ys2ec_snakefiles

Snakemake snakefiles for making HHMs of yeast proteins and searching against [custom-made ec_pep database](https://github.com/soedinglab/hh-suite/wiki#building-customized-databases) using [the HH-suite3 software suite](https://pubmed.ncbi.nlm.nih.gov/31521110/).

[One snakefile](https://github.com/fomightez/ys2ec_snakefiles/blob/main/snakefile_using_FASTA_file_for_making_hhms_of_yeast_proteins_and_searching_ec_pep_database) takes a multi-sequence FASTA as input.  
[In the other](https://github.com/fomightez/ys2ec_snakefiles/blob/main/snakefile_using_list_of_standard_gene_names_for_making_hhms_of_yeast_proteins_and_searching_ec_pep_database), you provide the standard yeast names before running the the snakefile with [Snakemake](https://pubmed.ncbi.nlm.nih.gov/34035898/).

This repo and the snakefiles herein accompany the Knutson laboratory publication Belkevich et al, 2023. (Details to be updated shortly.)

------------------------



Main supporting software
-----------------------

HH-suite3 reference:

[Steinegger M, Meier M, Mirdita M, Vöhringer H, Haunsberger S J, and Söding J (2019)
HH-suite3 for fast remote homology detection and deep protein annotation, *BMC Bioinformatics*, 473. doi: 10.1186/s12859-019-3019-7 PMID: 3152110](https://pubmed.ncbi.nlm.nih.gov/31521110/)


Snakemake reference:

[Mölder, F., Jablonski, K.P., Letcher, B., Hall, M.B., Tomkins-Tinch, C.H., Sochat, V., Forster, J., Lee, S., Twardziok, S.O., Kanitz, A., Wilm, A., Holtgrewe, M., Rahmann, S., Nahnsen, S., Köster, J. (2021) Sustainable data analysis with Snakemake. F1000Res 10, 33. PMID: 34035898](https://pubmed.ncbi.nlm.nih.gov/34035898/)

Related
-------

- My [Repository for running command line-based HH-suite3 software in Jupyter environment provided via MyBinder Service](https://github.com/fomightez/hhsuite3-binder/)
- My [hhsuite3-utilities sub-repo](https://github.com/fomightez/sequencework/tree/master/hhsuite3-utilities)
