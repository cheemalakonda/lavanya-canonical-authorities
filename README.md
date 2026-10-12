# Lavanya 2.0 — Canonical Authority Library

**Deployment status: awaiting upload of canonical image assets and versioned specifications.**

This public repository is intended to host the six original Lavanya Gate authority PNGs, together with a JSON authority manifest and portable character specification.

## Source-of-truth hierarchy

1. Gate 3 facial identity — `Lavanya Gate3.png`
2. Supplemental facial geometry — `Lavanya Facial Geometry.png`
3. Gate 4 expression mechanics — `02_Lavanya_Gate4_Expression_Authority.png`
4. Gate 5 body — `03_Lavanya_Gate5_Body_Authority.png`
5. Gate 6 everyday motion — `04_Lavanya_Gate6_Everyday_Motion_Preflight.png`
6. Gate 6 social reciprocity — `09_Lavanya_Gate6_Social_Reciprocity.png`

All six files must be original authority images, not third-party replacements or generated lookalikes.

## Planned layout

```
lavanya/v2.0/
  authorities/
    01_Gate3_Facial_Identity.png
    02_Facial_Geometry_Supplement.png
    03_Gate4_Expression_Authority.png
    04_Gate5_Body_Authority.png
    05_Gate6_Everyday_Motion.png
    06_Gate6_Social_Reciprocity.png
  manifest.json
  specifications/
    Lavanya_Character_Production_Spec_v2_0_GitHub.json
    Lavanya_Master_Reference_Sheet_v2_0.md
    Lavanya_Project_Mandate_v2_0.md
    Lavanya_Body_Geometry_Specification_v1.md
```

The deployment bundle is prepared in ChatGPT. **Do not consider any URLs live until the corresponding files are committed and verified.**

## Use by image/video generators

Load `manifest.json`, download canonical images from its URL fields, and supply the images to each provider's actual reference-image input. Links inside prompts alone do not ensure ingestion.

**Privacy:** This repository is public; canonical identity images will be downloadable by anyone after publication.
