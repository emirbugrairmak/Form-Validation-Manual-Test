# Form-Validation-Manual-Test

## Project Overview
This is a manual testing practice on the **“Form Validation”** page. The goal is to convert requirements into **test cases**, a **checklist**, and **bug reports**, then execute the tests and record results.

## Scope
- **Page:** Form Validation  
- **Focus:** field validations, error messages, UI feedback, and successful submission flow

## Artifacts (Excel Workbook)
The Excel file includes **4 sheets**:
1. **İş Gereksinimi:** Requirement statements for the form  
2. **Test Senaryosu Taslağı:** 8 test cases (4 positive, 4 negative) with execution status  
3. **Test Kontrol Listesi Taslağı:** 15 checklist items (UI + validation + messages) with status  
4. **Hata Taslağı:** Bug report(s) with steps and evidence (screenshots)

## Test Execution Summary
- **Total test cases executed:** 8  
- **Passed:** 7  
- **Failed:** 1 *(validation message mismatch for Contact Number)*  
- **Checklist total:** 15  
- **Failed checklist items:** related to Contact Number validation messaging clarity

## Key Finding / Bug
**Contact Number field:** when letters are entered, the page shows a **“blank field”** style message instead of a **“numbers only”** validation message.

## Environment
- **OS:** macOS  
- **Browser:** Chrome  

## How to Reproduce the Bug
1. Open the **Form Validation** page  
2. Enter letters into **“Contact number”**  
3. Trigger validation *(click outside the field or click **Register**)*  
4. Observe the message shown under the field  

## Next Improvements (Maybe)
- Add explicit test data values to each test case  
- Clarify validation trigger steps *(blur vs submit)*  
- Add Severity/Priority separation in bug reports  

## Note
This project demonstrates my first steps in manual testing.

## Tested Website
URL : https://practice.expandtesting.com/form-validation


