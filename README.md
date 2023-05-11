# summarizing-medical-evidence

Data and annotations from our paper [**Summarizing, Simplifying, and Synthesizing Medical Evidence Using GPT-3 (with Varying Success)**](https://arxiv.org/). 

## Table Schema 
You will find three `.csv` files that each contain all annotations collected across 100 documents, split into the single document and multi document case. Each `.csv` file corresponds to annotations from 1 annotator. Note that for rows with "Survey Question", you can find a detailed description of the field in the Appendix section of the paper. 

### Single Document Columns 
|Column Name| Description |
|--|--|
|text| Input text|
|abstract| Abstract (from input text) |
|summary| GPT-3 generated summary |
|plain_summary| GPT-3 generated plain summary |
|containsKeyResult| Survey Question |
|population| Survey Question |
|outcome| Survey Question |
|omissions| Survey Question |
|errors| Survey Question |
|coherence| Survey Question |
|usefulness| Survey Question |
|containsKeyResult_plain| Survey Question |
|population_plain| Survey Question |
|intervention_plain| Survey Question |
|outcome_plain| Survey Question |
|errors_plain| Survey Question |
|coherence_plain| Survey Question |
|readability_plain| Survey Question |
|substitution_plain| Survey Question |
|usefulness_plain| Survey Question |
|annotator| Annotator ID |
|intervention_addl| Survey Question |
|population_addl| Survey Question |
|outcome_addl| Survey Question |
|answer| Survey Question |
|answer_plain| Survey Question |
|newConcepts_plain| Survey Question |
|outcome_addl_plain| Survey Question |
|intervention_addl_plain| Survey Question |
|newConcepts| Survey Question |
|population_addl_plain| Survey Question |

### Multi-Document Columns

|Column Name| Description |
|--|--|
|text| Human-written summary|
|inputs| Input to GPT-3 |
|conclude| GPT-3 generated summary |
|evidenceTarget| Survey Question (see paper) |
|evidenceGenerated| Survey Question |
|agreeWithConclusion| Survey Question |
|contradictions| Survey Question |
|supportedByEvidence| Survey Question |
|annotator| Annotator ID |
|textbox| Free text option |

If you use our data, please cite our work with the following: 

>@inproceedings{Shaib2023SummarizingSA,
>title={Summarizing, Simplifying, and Synthesizing Medical Evidence Using GPT-3 (with Varying Success)}, 
>author={Chantal Shaib and Millicent L. Li and Sebastian Joseph and Iain James Marshall and Junyi Jessy Li and Byron Wallace}, 
>year={2023} }Summarizing, Simplifying, and Synthesizing Medical Evidence Using GPT-3 (with Varying Success), 
