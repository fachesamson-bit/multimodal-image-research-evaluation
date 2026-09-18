# Evaluation Example 01 — Real-World Location Identification

## Task Type

Multimodal visual identification and web research.

## Objective

Determine the identity of a real-world location from a partially obscured photograph using visual evidence and external research.

## Evaluation Design

The original photograph contains identifying information that can make direct identification substantially easier.

A controlled crop or occlusion is applied to conceal those details while preserving secondary visual clues such as:

- Building architecture
- Surrounding structures
- Road layout
- Landscape
- Sign shapes
- Windows and doors
- Distinctive architectural features
- Environmental context

The resulting image is used as the evaluation input.

## Required Model Behavior

The model should:

1. Inspect the visible visual evidence.
2. Identify useful distinguishing features.
3. Conduct external research where appropriate.
4. Compare the observed features against reliable sources.
5. Determine the most specific supported identity.
6. Explain the evidence supporting the identification.

## Evaluation Materials

This example contains:

- Original source image
- Evaluation image
- Image provenance record
- Evaluation prompt
- Grading criterion
- Solution notes
- Research evidence

## Quality Requirements

The obscured image must not introduce artificial objects or visual information that was absent from the original photograph.

The hidden information should be concealed while retaining enough legitimate visual evidence for a research-capable multimodal system to investigate the subject.

## Status

Portfolio demonstration.
