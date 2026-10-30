# Day 05 — HTML Forms & Inputs

## What I built
I built a Student Registration Demo using HTML form controls. The page has a header, main section, footer, visible labels, text and email inputs, an age input, a course select menu, study-mode radio buttons, a learning-goals text area, a practice-data checkbox, and a submit button.

The form uses `action="#"` as a placeholder. It is a static practice page and does not save registration information to a database.

## Validation checks
1. I submitted the form with required fields empty. The browser asked me to complete the required fields.
2. I entered an invalid email address and tried to submit. The browser showed its email-format validation.
3. I tried an age below 16 and an age above 100. The browser blocked submission because the value was outside the selected limits.

## Bug fixed
I checked that each label's `for` value matched the `id` of its control. When a label and id do not match, clicking the label does not focus or toggle the intended control. I corrected the mismatch and checked the label again.

## Why client-side validation is not enough
Browser-side validation improves usability, but it can be bypassed. A real application also needs server-side validation, safe error handling, and permission checks. This static form has no backend endpoint and does not store data.

## One improvement for later
I could add a backend endpoint with server-side validation so that submitted data can be handled safely.

## Before submitting to GitHub
- Open the HTML file in a browser and test the form.
- Check labels, radio buttons, age limits, and the narrow browser layout.
- Capture a browser screenshot showing the form.
- Make sure the screenshot and files contain no sensitive information.
