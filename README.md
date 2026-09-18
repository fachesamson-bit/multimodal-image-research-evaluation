# Multimodal Image Research & Evaluation

A portfolio project demonstrating workflows for creating multimodal evaluation materials from authentic, verifiably licensed real-world images.

The project focuses on evaluation tasks where an AI system must use visual clues and multi-step web research to identify or reconstruct information hidden by cropping, masking, occlusion, or controlled image degradation.

## Project Objectives

This project demonstrates the ability to:

- Source authentic real-world photographs
- Verify image licensing and provenance
- Research visual subjects using multiple web sources
- Identify subjects from partial visual evidence
- Create realistic cropped and occluded image variants
- Write concise evaluation prompts
- Develop objective grading criteria
- Document ground-truth answers and supporting evidence
- Maintain reproducible research records
- Separate observable evidence from assumptions

## Evaluation Workflow

Each evaluation instance follows this workflow:

1. Select an authentic real-world image.
2. Verify the source and licensing status.
3. Record the original source and provenance.
4. Research the subject using multiple reliable sources.
5. Identify important visual clues.
6. Create a controlled crop, mask, occlusion, or degradation.
7. Write an English-language evaluation prompt.
8. Create an objective grading criterion.
9. Document the ground-truth answer.
10. Record the research path and supporting evidence.
11. Package the complete evaluation instance.

## Research Methods

Depending on the evaluation task, research may involve:

- Search-engine queries
- Reverse image search
- Google Lens
- Official organization websites
- Government websites
- University websites
- Museum and cultural institution databases
- Wikimedia Commons
- Creative Commons resources
- Public-domain collections
- Reliable news and reference sources

The purpose of multi-step research is to establish the identity of the subject from incomplete visual information rather than relying on a single source.

## Image Provenance

Every source image should have a provenance record containing:

- Source URL
- Image title
- Creator or photographer, when available
- License
- License URL, when available
- Source platform
- Date accessed
- Evidence supporting the licensing status

Images should only be used when their licensing and provenance can be documented appropriately.

## Evaluation Instance

Each completed instance contains:

```text
Source image
       ↓
License & provenance verification
       ↓
Visual research
       ↓
Ground-truth identification
       ↓
Crop / mask / occlusion
       ↓
Evaluation prompt
       ↓
Grading criterion
       ↓
Solution notes
       ↓
Supporting evidence

Example Evaluation Task

An evaluation image may show a real building with its sign, street name, or other identifying information removed.

The prompt should require the model to determine the subject using the remaining visual evidence and external research.

Example prompt structure:

Identify the real-world location shown in the image. Use the visible architectural, environmental, and contextual clues to research the location. Provide the most specific supported identification and briefly explain the evidence used.

The target identity is intentionally excluded from the prompt.

Grading Criteria

Criteria should be concise and objectively verifiable.

Example:

The response identifies the correct real-world location and provides evidence that is consistent with the visible features in the image.

Solution Notes

Solution notes document the ground truth and research process without changing the original evaluation prompt.

They may include:

Ground-truth identity
Original image source
Licensing information
Search queries
Research sources
Visual evidence
Identification reasoning
Expected answer
Verification sources
Quality Principles
Authenticity

Use real-world imagery and preserve the original visual context.

Verifiability

Ground-truth answers should be supported by reliable external evidence.

Realistic Degradation

Crops, masks, and occlusions should conceal important identifying information without introducing artificial visual clues.

Non-Hallucination

Do not add objects, architecture, text, people, or environmental features that were not present in the source image.

Objective Evaluation

Prompts and grading criteria should be specific enough to evaluate consistently.

Reproducibility

Another researcher should be able to follow the documented research process and verify the conclusion.

Skills Demonstrated
Multimodal AI evaluation
Image research
Web research
Reverse image investigation
Visual reasoning
Image annotation
Image cropping and masking
Data provenance
Copyright and licensing verification
Prompt writing
Evaluation rubric design
Ground-truth verification
Quality assurance
Structured documentation
Portfolio Demonstration

This repository contains portfolio demonstrations of multimodal research, image evaluation, annotation, and quality-assurance workflows.

Examples are clearly identified as demonstrations where applicable and do not represent confidential client work or fabricated employment results.

Author

Samson Fache

AI Trainer · LLM Evaluator · Data Quality Analyst

GitHub: https://github.com/fachesamson-bit
