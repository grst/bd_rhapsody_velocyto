# Velocyto.py for BD Rhapsody

This is a minimal [nextflow](https://www.nextflow.io/) workflow to run [velocyto.py](http://velocyto.org/) on BAM filese produces by the BD Rhapsody pipeline. 
It consists of two steps
 * manipulating the BAM file to make it compatible with velocyto. 
 * running velocyto.py

## Usage

```bash
nextflow run veolcyto.py -c nf_velocyto.config
```

The `nf_velocyto.config` defines all paths to input and reference files. Adjust it to your needs. 
