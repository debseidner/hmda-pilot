# About

The HMDA Pilot is a work in progress by the [Consumer Financial Protection Bureau](http://consumerfinance.gov/).This site is part of the Consumer Financial Protection Bureau’s (CFPB) work to improve the Home Mortgage Disclosure Act (HMDA) electronic reporting process for financial institutions.  This site does not in any way alter or substitute for your obligations for submitting data under HMDA.  See ffiec.gov/hmda for more details about your legal obligations. This application makes it easier to review and validate HMDA file submission edits.

The file validation process has five steps. The validation edits must be performed in the order shown below and in each step of the validation edit process, the errors must be fixed or verified before moving on to the next step. At the end of the process, the user will be provided with a summary of the validated file. HMDA files are considered "clean" and ready to submit when there are no syntactical and validity edit errors for a file and that all quality, macro, MSA and IRS edit errors or reports have been verified.

    * Syntactical & Validity Edits
    * Quality & Macro Edits
    * MSA and IRS Reports

## Validate a HMDA Dataset

1. **Select File and Validate**

    On the Select File and Validate page (Step 1), select a properly formatted .DAT file and filing year, then click the Start Validation button. When the validation starts, the system will run the syntactical and validity edits on your file but the file will not be uploaded or transmitted to the CFPB. The edits will process on your computer and the file will remain on your computer. You should see a progress bar of how long running the edits should take.
    
    The file spec for the .DAT file can be found on the FFIEC website - [File Specifications](http://www.ffiec.gov/hmda/fileformats.htm). The edit file spec that is used for the validation can be found on the FFIEC website too - [Edit Specifications](http://www.ffiec.gov/hmda/edits.htm).

2. **Syntactical and Validity Edit Reports**

    The first edits to return results are the syntactical and validity edits. These edit errors contain full file submission erros like there are no LARs on the file or the respondent ID/agency code combination is invalid or data reported incorrectly like a non-valid value being used or an incorrect census tract.

3. **Review Edit Reports**

    Validation errors will be displayed in the Edit Reports and Edit Details pages. If needed, make corrections in your system of record and revalidate the entire file (starting at Step 1).

4. **Review Validation Summary**

    After all edits are complete the Validation Summary will display the Respondent and File information. You do not need to submit the validated file or send an additional information.
