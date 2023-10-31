# PubMed 200k RCT dataset

The PubMed 200k RCT dataset is described in *Franck Dernoncourt, Ji Young Lee. [PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071). International Joint Conference on Natural Language Processing (IJCNLP). 2017.*

Abstract:

> PubMed 200k RCT is new dataset based on PubMed for sequential sentence classification. The dataset consists of approximately 200,000 abstracts of randomized controlled trials, totaling 2.3 million sentences. Each sentence of each abstract is labeled with their role in the abstract using one of the following classes: background, objective, method, result, or conclusion. The purpose of releasing this dataset is twofold. First, the majority of datasets for sequential short-text classification (i.e., classification of short texts that appear in sequences) are small: we hope that releasing a new large dataset will help develop more accurate algorithms for this task. Second, from an application perspective, researchers need better tools to efficiently skim through the literature. Automatically classifying each sentence in an abstract would help researchers read abstracts more efficiently, especially in fields where abstracts may be long, such as the medical field.


Some miscellaneous information:
- PubMed 20k is a subset of PubMed 200k. I.e., any abstract present in PubMed 20k is also present in PubMed 200k. 
- `PubMed_200k_RCT` is the same as `PubMed_200k_RCT_numbers_replaced_with_at_sign`, except that in the latter all numbers had been replaced by `@`. (same for `PubMed_20k_RCT` vs. `PubMed_20k_RCT_numbers_replaced_with_at_sign`).
- Since Github file size limit is [100 MiB](https://stackoverflow.com/a/43098961/395857), we had to compress `PubMed_200k_RCT\train.7z` and `PubMed_200k_RCT_numbers_replaced_with_at_sign\train.zip`. To uncompress `train.7z`, you may use [7-Zip](http://www.7-zip.org/download.html) on Windows,  [Keka](http://www.kekaosx.com/en/) on Mac OS X, or [p7zip](http://p7zip.sourceforge.net/) on Linux.

You are most welcome to share with us your analyses or work using this dataset!

## Projects using the PubMed 200k RCT dataset

- Titipat Achakulvisut, Chandra Bhagavatula, Daniel E Acuna, Konrad P Kording. [Claim Extraction for Scientific Publications](https://github.com/titipata/detecting-scientific-claim). 2018
- See [Google Scholar citations](https://scholar.google.com/scholar?cites=7257105737642724511&as_sdt=2005&sciodt=0,5&hl=en) for more projects.

## License

Our dataset is constructed upon the MEDLINE/PubMed Baseline Database published in 2016, which we referred to as PubMed in the paper. Unfortunately, we don't see any license for the PubMed dataset on the [official website](https://www.nlm.nih.gov/databases/download/pubmed_medline.html), which isn't surprising given the shamefully high prevalence of paywalls in research.

<https://ftp.ncbi.nlm.nih.gov/pubmed/baseline/README.txt> mentions:

> NLM freely provides PubMed data. Please note some abstracts may be protected by copyright.

and

> NLM does not provide legal advice regarding copyright, fair use, or other aspects of intellectual property rights. See the NLM Copyright page:  <https://www.nlm.nih.gov/web_policies.html#copyright>

while <https://www.nlm.nih.gov/web_policies.html#copyright> mentions:

> User Responsibility: It is your responsibility to determine and satisfy copyright or other use restrictions when using materials that are not in the public domain. NLM cannot guarantee the copyright status for any item.

Also, FYI: [Am I allowed to republish / distribute abstracts?](https://academia.stackexchange.com/q/29015/452)
