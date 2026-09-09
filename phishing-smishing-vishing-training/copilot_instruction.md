# Open Security Training - Project Instructions

## Project Goal

This repository is an interactive cybersecurity awareness training platform.

The new module being developed is:

Phishing, Smishing & Vishing: The Ransom Leak

The module must be an educational cybersecurity awareness simulation.

## Core Requirements

- Preserve the existing project architecture.
- Do not unnecessarily rewrite existing modules.
- Reuse existing UI components where appropriate.
- Maintain SCORM compatibility.
- Target SCORM 1.2 unless the existing project requires otherwise.
- Track lesson completion.
- Track assessment score.
- Provide meaningful learner feedback.
- Make all attack scenarios fictional and simulated.
- Do not use real credentials, real company secrets, or real victim data.
- Do not create functional phishing infrastructure.
- Do not create real credential harvesting pages.
- Do not send SMS messages or make calls.
- All attacker interactions must remain simulated inside the training application.

## New Module

Title:
Phishing, Smishing & Vishing: The Ransom Leak

Scenario:
The learner is an employee responding to a simulated security incident involving
phishing, smishing, vishing, and a fictional ransomware/data-leak event.

## Learning Objectives

The learner should be able to:

1. Identify phishing indicators.
2. Identify smishing indicators.
3. Identify vishing/social-engineering indicators.
4. Verify suspicious requests independently.
5. Avoid submitting credentials or OTPs.
6. Report suspicious communications.
7. Respond appropriately to a simulated ransomware/data-leak incident.

## Interaction Requirements

Use realistic but fictional interfaces:

- Email inbox
- SMS interface
- Telephone call interface
- Security incident dashboard
- Ransomware/data-leak simulation
- Decision-based scenarios
- Final assessment

Every decision should produce immediate feedback.

## Scoring

Correct security decisions increase the score.

Unsafe decisions should:

- Explain why the decision was dangerous.
- Show the consequence in the simulation.
- Allow the learner to continue learning.

Do not permanently lock the learner out after a wrong answer.

## Code Quality

- Keep JavaScript modular.
- Avoid unnecessary dependencies.
- Use semantic HTML.
- Make the module responsive.
- Keep accessibility in mind.
- Avoid hard-coded duplicated scenario logic.
- Store scenario data separately from presentation logic.

## Testing

Before declaring the module complete:

- Test the module in Chromium.
- Test SCORM initialization.
- Test progress tracking.
- Test completion status.
- Test score reporting.
- Check browser console errors.
- Test all scenario branches.
- Test refresh/reload behavior.