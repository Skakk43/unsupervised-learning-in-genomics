<header>

# Download FASTQ data

</header>

In the [Advanced search SRA](https://www.ncbi.nlm.nih.gov/sra/docs/srasearch) search bar, I queried for [PRJEB59274 AND "Canis lupus"[orgn:__txid9612]](https://www.ncbi.nlm.nih.gov/sra/?term=PRJEB59274+AND+%22Canis+lupus%22%5Borgn%3A__txid9612%5D). PRJEB59274 is the accession for BioProject "Imputation Accuracy of DogsLife Labrador Retrievers Sequenced at Varying Read Depth".

I randomly choose 30 results and run it to Run Selector, obtained an [accession list](SRR_Acc_List.txt) and [metadata](SraRunTable.csv).

Install the toolkit [here](https://github.com/ncbi/sra-tools/wiki/02.-Installing-SRA-Toolkit). Move on to the configuration guide.

Download FASTQ files:
`fasterq-dump --split-files SRR_Acc_List.txt`
