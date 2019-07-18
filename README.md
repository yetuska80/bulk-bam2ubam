# bulk-bam2ubam
Bulk BAM to uBam conversion based on GATK guidelines

This repository is part of the exercises for the 4OSS workshop.

### Purpose
This is just a small script to convert multiple BAM files to unmapped BAM files using GATK `RevertSam` tool.

It will do the following:

1. Collect all BAM files in the given directory.
2. Create a temporary directory to work in.
3. Run `RevertSam` with appropriate options to remove all mapping information.
4. Copy the resulting file to a different storage location.
5. point five
