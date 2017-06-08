# scicore-pipeline-1

This container includes the following apps:

* STAR version 2.5.2b - https://github.com/alexdobin/STAR
* HTSeq version 0.6.1p1 - http://www-huber.embl.de/HTSeq/
* Pysam version 0.9.0 - https://github.com/pysam-developers/pysam


## Downloading the container with Singularity

   `$> singularity pull -n "pipeline1.img" docker://pescobar/scicore-pipeline1:latest`

## Using the container with singularity

   `$> singularity exec pipeline1.img STAR -h`

## Interactive shell inside the container with singularity

   `$> singularity shell pipeline1.img`



