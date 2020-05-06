1. translate.py Adra2a.aa.fas
2. mafft Adra2a.fas > Asra2a.mafft.aln.fas > mafft.stderr
3. reverseTranslate.py Adra2a.codon.aln.fas
4. raxmlHPC -PTHREADS -f -m GTRGAMMA RAxML_bootstrap.adra2a
5. raxmlHPC -PTHREADS -f PROTCATWAG > Adra2a.aa.aln.fas
6. drawTree.py RAxML_bipartitions.adra2a

