# TCGA Lung Dataset

## Contents

* `./tcga-download/` folder was originally copied from [here](https://github.com/binli123/dsmil-wsi/tree/master/tcga-download). Some names present in the manifest files were not available for download with the `gdc-client`. So new manifest files were downloaded from [TCGA-LUAD](https://portal.gdc.cancer.gov/repository?facetTab=files&filters=%7B%22content%22%3A%5B%7B%22content%22%3A%7B%22field%22%3A%22cases.project.project_id%22%2C%22value%22%3A%5B%22TCGA-LUAD%22%5D%7D%2C%22op%22%3A%22in%22%7D%2C%7B%22content%22%3A%7B%22field%22%3A%22files.experimental_strategy%22%2C%22value%22%3A%5B%22Diagnostic%20Slide%22%5D%7D%2C%22op%22%3A%22in%22%7D%5D%2C%22op%22%3A%22and%22%7D&searchTableTab=files) (541 slides) and [TCGA-LUSC](https://portal.gdc.cancer.gov/repository?facetTab=files&filters=%7B%22content%22%3A%5B%7B%22content%22%3A%7B%22field%22%3A%22cases.project.project_id%22%2C%22value%22%3A%5B%22TCGA-LUSC%22%5D%7D%2C%22op%22%3A%22in%22%7D%2C%7B%22content%22%3A%7B%22field%22%3A%22files.experimental_strategy%22%2C%22value%22%3A%5B%22Diagnostic%20Slide%22%5D%7D%2C%22op%22%3A%22in%22%7D%5D%2C%22op%22%3A%22and%22%7D&searchTableTab=files) (512 slides) web pages on 03/11/2021 (date is in the names).
* `./download-LUSC-and-LUAD.sh` contains commands to download the **diagnostic slides** from both the LUAD (https://portal.gdc.cancer.gov/projects/TCGA-LUAD) and the LUSC (https://portal.gdc.cancer.gov/projects/TCGA-LUSC) sets of the TCGA into `./WSI/LUSC/` and `./WSI/LUAD/` respectively.
* 
