# DNA-ligand-benchmark
DNA - ligand docking benchmark and associated scripts


Each folder contains:

- the reference structure of the complex (`XXXX_complex_ref.pdb`)
  When two binding sites exists, two reference files are provided (`XXXX_complex_ref_1.pdb, XXXX_ref_complex_2.pdb`)
- the bound structure of the DNA (`XXXX_dna_bound.pdb`)
- the unbound structure of the DNA (`XXXX_dna_unbound.pdb`)
- the conformers of the small molecules (`XXXX_ligand_conf/`)
- the lzone files to align the docking models onto the reference structure (`lzone/XXXX.lzone`)
  When two binding sites exists, two lzone files are provided (`lzone/XXXX_1.lzone`, `lzone/XXXX_2.lzone`)