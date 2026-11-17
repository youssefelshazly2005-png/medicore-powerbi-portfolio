Open MediCore.pbix to use the three-page report.
Read PATIENT_EXPERIENCE_GUIDE_AR.html for definitions and limitations.
CSV source is fully synthetic. DataFolder must point to SourceData after extraction if refreshing on another device.
Validation contains DAX queries, native results, independent comparisons and a Python verifier.
To verify the saved native result snapshot against CSV: python Validation/verify_patient_experience.py
This does not execute Power BI again; rerun the provided DAX queries in Power BI after model changes and replace the native JSON results first.
