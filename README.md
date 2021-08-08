# variant-caller
Pipeline to call SNPs and indels from sequencing reads and a reference genome, based on the `variant-calling-pipeline-gatk4` from gencorefacility (https://github.com/gencorefacility/variant-calling-pipeline-gatk4, usage tutorial: https://gencore.bio.nyu.edu/variant-calling-pipeline-gatk4/).

Changes:
- [x] natively use Singularity instead of Docker (https://cloud.sylabs.io/library/merlin/default/namlab-variant-caller)
- [x] start from a list of SRA accessions instead of fastq files
- [ ] add trimmomatic
- [ ] use bcftools/csq instead of snpEff
