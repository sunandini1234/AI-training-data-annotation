# AI-training-data-annotation
A sample project demonstrating AI training data cleaning and annotation for improved quality.


RAW DATA 


id,text
1,customer want to  CLOSE account  asap
2,refund  Processed  but not reflected
3,delivery was late.!!  want  compensation


CLEANED DATA 


cs
Copy
Edit
id,text
1,Customer wants to close account as soon as possible.
2,Refund processed but not reflected.
3,Delivery was late and customer wants compensation.


ANNOTATION GUIDELINES 


# Annotation Guidelines

## Rules Followed:
1. Corrected grammar and spelling errors.
2. Removed unnecessary spaces and duplicate words.
3. Removed unnecessary symbols (e.g., "!!") unless they were part of the intended content.
4. Ensured consistent sentence casing (first letter capitalized).
5. Maintained original meaning while improving clarity.

## Purpose:
These rules ensure that the dataset is clean, professional, and ready for use in AI/ML training tasks.


