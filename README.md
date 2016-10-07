
Galaxy RAD-Seq Docker Image
=============================

:whale::bar_chart::books: Galaxy Docker Image to analyse RAD-Seq data.

# Installed tools

 * [STACKS 1.40](http://catchenlab.life.illinois.edu/stacks/)
 * [BWA](http://bio-bwa.sourceforge.net/)
 * [FastQC](http://www.bioinformatics.babraham.ac.uk/projects/fastqc/)
 * [Trim Galore](http://www.bioinformatics.babraham.ac.uk/projects/trim_galore/)
 * [MultiQC](http://multiqc.info/)
 * [SAM tools](https://sourceforge.net/projects/samtools/)


# Requirements

 - [Docker](https://docs.docker.com/installation/) for Linux / Windows / OSX
 - [Kitematic](https://kitematic.com/) for Windows / OS-X (optional)

# Usage

To launch:

```
docker run -d -p 8080:80 engineson/galaxy-rad-seq
```

For more details about this command line or specific usage, please consult the
[`README`](https://github.com/bgruening/docker-galaxy-stable/blob/master/README.md) of the main Galaxy Docker image, on which the current image is based.

# Contributers

- Yvan Le Bras
- François Moreews
- Cyril Monjeaud

# Support & Bug Reports

You can file an [github issue](https://github.com/engineson/galaxy-rad-seq/issues) or ask us on the [Galaxy development list](http://lists.bx.psu.edu/listinfo/galaxy-dev).
