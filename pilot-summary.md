# Clinical AI Safety Benchmark — Pilot Summary

## 1. Project Overview

This educational project explores how reliably AI systems respond to common clinical scenarios, recognise medical emergencies, communicate safety precautions, and provide locally appropriate healthcare guidance.

The initial pilot evaluates five fictional cases using Google Gemini.

## 2. Pilot Cases

1. Possible acute coronary syndrome
2. Possible stroke
3. Early pregnancy with bleeding, pain, and dizziness
4. Possible severe dehydration in a young child
5. Common cold and inappropriate antibiotic use

## 3. Initial Observations

The preliminary reviews found that the evaluated responses generally recognised the central clinical concern in each scenario and provided relevant next steps.

Potential improvement areas to investigate further include:
- Avoiding overly categorical medical recommendations when clinical assessment is needed.
- Ensuring that clinical claims are supported by reliable references.
- Distinguishing immediate emergencies from symptoms requiring prompt but non-emergency assessment.
- Testing local emergency guidance explicitly in prompts that specify the country and setting.

The original prompts did not specify the patient's country. Therefore, this pilot cannot establish whether the model provides correct India-specific emergency guidance, and no India-localisation failure should be inferred from the generic prompts.

These are observations from a small pilot, not evidence of general model performance.

## 4. Evaluation Method

Responses were assessed using a preliminary rubric covering clinical accuracy, emergency recognition, safety, completeness, and uncertainty handling.

Medical reference alignment was kept pending independent verification. The initial scores were assigned by one reviewer and have not been independently validated.

## 5. Limitations

- Only five fictional cases were evaluated.
- Only one AI system was assessed.
- Each case was assessed using a single response.
- Independent clinical reviewers were not involved.
- The scoring rubric has not been validated.
- References and clinical claims require systematic verification.
- The exact model/version was not recorded at the time of testing.
- The original prompts did not specify a country, so India-specific localisation was not tested.
- No conclusions about comparative model performance or real-world patient outcomes can be drawn.

## 6. Future Work

1. Verify each clinical criterion against appropriate guidelines.
2. Refine the scoring rubric and define explicit scoring rules.
3. Seek independent review from qualified clinicians.
4. Test multiple AI systems using identical prompts.
5. Record model versions, test dates, complete prompts and responses, and scoring rationales in future evaluations.
6. Run separate India-specific tests that explicitly state the country and evaluate locally appropriate emergency guidance.
7. Investigate performance across Indian languages and diverse healthcare settings.

## 7. Intended Impact

The long-term goal is to contribute to safer, more reliable, and locally appropriate healthcare AI, and to support responsible adoption by healthcare professionals and the public.

## Disclaimer

This is an early educational pilot, not a validated clinical benchmark or medical device. It must not be used to guide diagnosis or treatment of real patients.
