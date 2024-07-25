# Maxim Borodin's Genome

Welcome to the source code of Maxim Borodin, represented through his genetic data in a VCF (Variant Call Format) file.
This project aims to exemplify personal transparency and the possibilities of data sharing in the realm of genetics,
mirroring the openness found in modern science and technology.

## About the Project

This repository contains my genome in the VCF format, which is the standard for storing gene sequence variations. The
project serves not only to share my genetic data but also to showcase the impressive capabilities of current genetic
sequencing technologies and their importance in scientific research and data sharing.

## File Contents

- `maxim_borodin_genome.vcf`: The VCF file containing the genetic data.
- `README.md`: This document explaining the project.

## Getting Started

### Prerequisites

To explore the VCF file, you'll need tools capable of parsing and analyzing genetic data. Here are a few you might
consider:

- [bcftools](https://samtools.github.io/bcftools/bcftools.html)
- [vcftools](https://vcftools.github.io/)
- [IGV (Integrative Genomics Viewer)](http://software.broadinstitute.org/software/igv/)

### Cloning the Repository

To clone this repository, use the following command:

```bash
git clone https://github.com/Borodin/genome
```

### Installation

No special installation is required for this project. However, to view and analyze the VCF file, you might need to
install one of the tools mentioned above. For instance, to install bcftools and vcftools, you can use the following:

```bash
# For Debian/Ubuntu
sudo apt-get install bcftools
sudo apt-get install vcftools

# For MacOS using Homebrew
brew install bcftools
brew install vcftools
```

### Usage

Once you have cloned the repository and installed the necessary tools, you can start exploring the VCF file. Here are a
few examples of what you can do:

```bash
bcftools view maxim_borodin_genome.vcf
```

### Basic Statistics

```bash
vcftools --vcf maxim_borodin_genome.vcf --freq
```

# Issues

I would be very grateful for any issues describing errors in my genome.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

# Contact

If you have any questions or just want to say hi, feel free to contact me
at [hi@maximborodin.ru](mailto:hi@maximborodin.ru)

Enjoy exploring the code that makes me who I am!