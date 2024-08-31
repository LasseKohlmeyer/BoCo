# BoCo

The Book Comparison (BoCo) dataset was collected as part of a Master's thesis. The thesis has been summarised in the paper ['Novel Views on Novels' (2021)](https://hpi.de/fileadmin/user_upload/fachgebiete/naumann/publications/PDFs/2021_kohlmeyer_novel.pdf).

ACM Reference Format:
Lasse Kohlmeyer, Tim Repke, and Ralf Krestel. 2021. Novel Views on Novels: Embedding Multiple Facets of Long Texts. In IEEE/WIC/ACM International Conference on Web Intelligence (WI-IAT '21), December 14–17, 2021, ESSENDON, VIC, Australia. ACM, New York, NY, USA 6 Pages. https://doi.org/10.1145/3486622.3494006

## Usage Hints
* Raw data is the original data set from SoCi Survey
* Book familarity contains a mapping of IDs to book descriptions (title, author) and familarity scores
* Triangulation Raw contains for each participant and each triplet-facet combination the decisions
* Human assessed contains the majority decisions and agreement scores for all triplet-facet combinations
* Self assessed contains for combination with a small agreement self assessed values, which can be used as tie breakers
* Human assessed complete contains the decisions from both, human assessed and self assessed
* To use the datasets the files 'book_familarity.csv' and 'human_assessed_complete.csv' are sufficient.
