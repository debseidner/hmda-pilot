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

    The first edits run on the file the user has uploaded to check are the syntactical and validity edits. These edit errors contain full file submission errors like there are no LARs on the file or the respondent ID/agency code combination is invalid or data reported incorrectly like a non-valid value being used or an incorrect MSA/MD. The user can review the edit errors on the pilot site or the errors can be downloaded as a CSV. Users have the option to drill down by edit number on the site to see all the LARs that failed that specific edit. All errors must be fixed in the system of record and a new .DAT file must be created to reload and recheck in the pilot system before moving forward with the edit processing. Once there are no remaining syntactical and validity edits for the .DAT file, the "Next" button will appear in the bottom right to proceed to the next step of the validation process.

3. **Quality and Macro Edit Reports**

    Once the user clicks on "Next" from the syntactical and validity edits step, the quality and macro edits begin to process. The user will receive a summary of all quality and macro edits with failures. The user will need to click into each individual report to validate whether the information on the LAR that failed the edit is accurate. If the information is all accurate, the user will click on the verified button for each row and for the macro edits will select a reason for why this information is correct. The edit errors can be viewed in the pilot in more detail, meaning the user can drill down into each edit error, or the user can download the edit errors into a CSV to review. If the user finds data that is not accurate and needs to update the LAR record with that data, the data must be fixed in the system of record and a new .DAT file must be created to reload and recheck in the pilot system before moving forward with the edit processing. The user will have to start over from the first upload step in this case and rerun the syntactical and validity edit errors first on the file before proceeding with the quality and macro edits after the corrections were made. Once there are no remaining syntactical and validity edits for the .DAT file, the "Next" button will appear in the bottom right to proceed to the next step of the validation process.

4. **MSA and IRS Reports**

    Once the user clicks on "Next" from the quality and macro edits step, the MSA and IRS reports begin to process. The user will receive a summary of three reports in this area - Q029, Q595 and the Insitution Register Summary (IRS). For Q029, the user must review all of the MSA/MD discrepancies and note whether the user agrees with the recommended MSA/MD change. For Q595, the institution must note whether it has an office in the MSA/MD that appares on the report.
    
    If the information is all accurate, the user will click on the verified button for each row and for the macro edits will select a reason for why this information is correct. The edit errors can be viewed in the pilot in more detail, meaning the user can drill down into each edit error, or the user can download the edit errors into a CSV to review. If the user finds data that is not accurate and needs to update the LAR record with that data, the data must be fixed in the system of record and a new .DAT file must be created to reload and recheck in the pilot system before moving forward with the edit processing. The user will have to start over from the first upload step in this case and rerun the syntactical and validity edit errors first on the file before proceeding with the quality and macro edits after the corrections were made. Once there are no remaining syntactical and validity edits for the .DAT file, the "Next" button will appear in the bottom right to proceed to the next step of the validation process.

5. **Validation Summary**

    After all edits are complete the Validation Summary will display the Respondent and File information. You do not need to submit the validated file or send an additional information.
