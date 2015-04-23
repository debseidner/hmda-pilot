# About

The HMDA Pilot is a work in progress by the [Consumer Financial Protection Bureau](http://consumerfinance.gov/).This site is part of the Consumer Financial Protection Bureau’s (CFPB) work to improve the Home Mortgage Disclosure Act (HMDA) electronic reporting process for financial institutions.  This site does not in any way alter or substitute for your obligations for submitting data under HMDA.  See ffiec.gov/hmda for more details about your legal obligations. 

This HMDA Pilot application makes it easier to review and validate HMDA file submission edits. Institutions can check their HMDA submission files or individual LAR records to determine if there are any syntactical, validity, quality or macro quality edit failures. The site gives institutions the ability to fix these edit errors prior to submission. 

The validation edits must be performed in the order in the application. During each step of the validation edit process, the errors must be fixed or verified before moving on to the next step. At the end of the process, the user will be provided with a summary of the validated file. HMDA files are considered "clean" and ready to submit when there are no syntactical and validity edit errors and all quality, macro, MSA and IRS edit errors or reports have been verified.

## Validate a HMDA Dataset

1. **Select File and Validate**

    On the Select File and Validate page (Step 1), an institution selects a [properly formatted .DAT file](http://www.ffiec.gov/hmda/fileformats.htm) and filing year to the start the validation of the file. The system will run the [validation edits](http://www.ffiec.gov/hmda/edits.htm) on the file but the file itself will not be uploaded or transmitted to the CFPB. The edits will run in your browser on your computer, and the file will remain on your computer. Once you presss submit, you should see a progress bar of how long running the edits should take.

2. **Syntactical and Validity Edit Reports**

    The tool runs the syntactical and validity edits first. These edit errors contain full file format or submission data errors. The syntactical and validity edits have to be fixed prior to moving onto the next step. The errors can be downloaded as a CSV or viewed online to be fixed in the Financial Institution's system of record. A new file will need to be selected in Step 1 and this step re-run if changes need to be made to the file format or the data due to syntactical and validity edit errors.

3. **Quality and Macro Edit Reports**

    Once the user clicks on "Next" from the syntactical and validity edits step, the quality and macro edits begin to process. The user will receive a summary of all quality and macro edits with failures. The user will need to click into each individual report to validate whether the information on the LAR that failed the edit is accurate. If the information is all accurate, the user will click on the verified button for each row and for the macro edits will select a reason for why this information is correct. The edit errors can be viewed in the pilot in more detail, meaning the user can drill down into each edit error, or the user can download the edit errors into a CSV to review. If the user finds data that is not accurate and needs to update the LAR record with that data, the data must be fixed in the system of record and a new .DAT file must be created to reload and recheck in the pilot system before moving forward with the edit processing. The user will have to start over from the first upload step in this case and rerun the syntactical and validity edit errors first on the file before proceeding with the quality and macro edits after the corrections were made. Once there are no remaining syntactical and validity edits for the .DAT file, the "Next" button will appear in the bottom right to proceed to the next step of the validation process.

4. **MSA and IRS Reports**

    Once the user clicks on "Next" from the quality and macro edits step, the MSA and IRS reports begin to process. The user will receive a summary of three reports in this area - Q029, Q595 and the Insitution Register Summary (IRS). For Q029, the user must review all of the MSA/MD discrepancies and note whether the user agrees with the recommended MSA/MD change. For Q595, the institution must note whether it has an office in the MSA/MD that appares on the report.
    
    If the information is all accurate, the user will click on the verified button for each row and for the macro edits will select a reason for why this information is correct. The edit errors can be viewed in the pilot in more detail, meaning the user can drill down into each edit error, or the user can download the edit errors into a CSV to review. If the user finds data that is not accurate and needs to update the LAR record with that data, the data must be fixed in the system of record and a new .DAT file must be created to reload and recheck in the pilot system before moving forward with the edit processing. The user will have to start over from the first upload step in this case and rerun the syntactical and validity edit errors first on the file before proceeding with the quality and macro edits after the corrections were made. Once there are no remaining syntactical and validity edits for the .DAT file, the "Next" button will appear in the bottom right to proceed to the next step of the validation process.

5. **Validation Summary**

    After all edits are complete the Validation Summary will display the Respondent and File information. You do not need to submit the validated file or send an additional information.
