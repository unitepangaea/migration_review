# Claude Prompts

This file records the prompts given to Claude (Anthropic) during the preparation of the scoping review *Health-related determinants of internal migration among older adults in Canada: a scoping review*. It accompanies the generative AI statements in the Methods and Acknowledgments sections of the manuscript.

Prompts are reproduced as they were entered. Claude's clarifying questions and the authors' answers are not included. All outputs were reviewed and manually verified by the authors (A.C.C. and P.A.P.), who take full responsibility for the content of the review.

## Summary

| No. | Date | Model | Task |
|---|---|---|---|
| 1 | July 10, 2026 | Claude Sonnet 5 | Validate bibliographic details, propose data extraction elements and create the extraction workbook |
| 2 | November 16, 2026 | Claude Opus 5.5 | Apply the MDPI *Populations* Word template to the manuscript |
| 3 | November 16, 2026 | Claude Opus 5.5 | Edit formatting and grammar using tracked changes |
| 4 | November 16, 2026 | Claude Opus 5.5 | Remove Zotero fields and correct citations and references |
| 5 | November 16, 2026 | Claude Opus 5.5 | Clean and document the data extraction workbook for GitHub |
| 6 | November 20, 2026 | Claude Opus 5.5 | Prepare the submission package (manuscript, cover letter and supplementary files) |
| 7 | November 20, 2026 | Claude Opus 5.5 | Prepare the GitHub repository and Zenodo record |

---

## Prompt 1: Data extraction set-up

**Date:** July 10, 2026  
**Model:** Claude Sonnet 5

> Using the rules provided, assist with data extraction for a structured scoping review. Start with the following tasks:
>
> 1. Read the draft full-text review file (FullTextReview_OlderAdultMigrationandHealth.xlsx) and identify the studies selected for inclusion in this review. These are listed in the “Included Studies” worksheet. Validate the bibliographic details for each study and locate a digital object identifier (DOI) if available, or a validated website link to the original source.
> 2. Using the scoping review protocol, best practices for scoping reviews, the existing review file, and expert knowledge, provide a preliminary list of data extraction elements for this review.
> 3. When the data extraction elements are confirmed, create a new Excel workbook (extraction_v2.xlsx) in the “Results” folder with columns for each element. Group columns logically and ensure the workbook is formatted for ease of use.
>
> Ask clarifying questions before you begin. If you are unsure of a response, prompt for clarification.

---

## Prompt 2: Journal template

**Date:** November 16, 2026  
**Model:** Claude Opus 5.5

> Apply the MDPI Word template (populations-template.dot) to the most recent draft (Draft_v5.docx). The template was used for this draft, but improperly applied.

---

## Prompt 3: Formatting and grammar edit

**Date:** November 16, 2026  
**Model:** Claude Opus 5.5

> Perform a careful edit of formatting and grammar of the review document.
>
> - Ensure spaces before citation brackets
> - Check page numbers for direct quotations.
> - Maintain formatting with journal template
>
> Suggest any changes using Track Changes in Word (with the exception of added spaces before citation brackets).
>
> Ask any clarifying questions before you begin.

---

## Prompt 4: Formatting and validating references

**Date:** November 16, 2026  
**Model:** Claude Opus 5.5

> I have made changes and saved out the previous edits.
>
> Using the last version, make all necessary changes to the references and citations.
>
> - Remove Zotero links and fields
> - Edit citations and references, deleting comments when complete.

---

## Prompt 5: Data extraction workbook

**Date:** November 16, 2026  
**Model:** Claude Opus 5.5

> Assist me in cleaning the data extraction workbook (extraction_v3.xlsx) for upload to GitHub.
>
> - Create a "README" worksheet at the beginning with the objectives of the project, the abstract, and a list of worksheets with a description of each, and a list of variables in the Data Extraction worksheet. This will become the README file on GitHub.
> - Move the Notes & Legend" to a new "Notes" worksheet at the end of the workbook. Revise and format the content.
> - Format the "Paper - Table 1" worksheet to be the same as in the draft document, including . I will add the 2 additional entries to the paper Table 1 manually.
> - Format the "Data Extraction" worksheet with new colours and ensure consistency in data entry.
> - Evaluate whether the "Summary of Results" worksheet contains additional data not in the "Data Extraction". If it does, reconcile the two worksheets. Once reconciled, remove this worksheet.
> - Extract each table (1 through 7) and create separate worksheets for each. Name these "Table 1" through "Table 7".
> - Ensure that consistent formatting and colours are used throughout the workbook.
>
> Ask any clarifying questions before you begin.

---

## Prompt 6: Submission package

**Date:** November 20, 2026  
**Model:** Claude Opus 5.5

> Prepare a submission package for the MDPI journal, Populations. Include the manuscript, cover letter, and the formatted extraction workbook (as a supplementary file).

---

## Prompt 7: Upload to GitHub

**Date:** November 20, 2026  
**Model:** Claude Opus 5.5

> Assist me in uploading the supplementary files to GitHub and creating a Zenodo entry.
>
> - Format the Claude_Pompts.md file in the "github" folder for inclusion in the github repository.
> - Create a README file for the respository.
> - Upload the supplementary files (extraction & checklist) and prompts to GitHub
