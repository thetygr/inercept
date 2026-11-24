# Public Evidence Register

This register distinguishes external evidence from project-specific hypotheses. It does **not** disclose non-public invention details.

## Biomechanics

**Claim status:** Rotational kinematics matter, but concussion/TBI biomechanics are multi-factorial.

- Rowson et al. reported a football concussion risk function using rotational kinematics; their nominal 50% risk point was substantially above 1,700 rad/s² and was probabilistic rather than a universal threshold.
- Reviews describe rotational loading as important for shear strain/diffuse injury while noting that real-world impacts include both linear and rotational loading.
- A 2026 multi-sport instrumented-mouthguard study found peak rotational acceleration was not a superior independent concussion classifier to linear acceleration and supported considering multiple kinematic variables.

Public sources:
- https://pmc.ncbi.nlm.nih.gov/articles/PMC10465647/
- https://www.ncbi.nlm.nih.gov/books/NBK185338/
- https://link.springer.com/article/10.1007/s10439-026-04437-7

**Public-material rule:** do not state that one rotational-acceleration value is a universal "safe" or "concussion" threshold.

## Impact duration

Published NFL helmet-to-ground impacts have been reported in the ~15-30 ms range for the studied impact class.

- https://pubmed.ncbi.nlm.nih.gov/31837745/

**Public-material rule:** use this as an impact-duration benchmark, not a guarantee that every football impact has the same duration.

## CMG physics

The fundamental CMG relation is vectorial: generated torque depends on angular momentum and commanded gimbal rate; multi-CMG arrays require a steering law and can encounter singularities.

- NASA spacecraft-control reference:
  https://ntrs.nasa.gov/api/citations/20240009554/downloads/Space%20Attitude%20Development%20Control.pdf

**Arithmetic correction in this repository:** with the original deck inputs
`I = 2.4e-4 kg m²`, `omega = 15,700 rad/s`, and `gimbal_rate = 180 rad/s`,
the nominal scalar product is approximately **678 N m**, not **0.68 N m**.

Likewise, `0.0222 kg m² × (4500 - 1700) rad/s²` is approximately **62.2 N m**, not **0.62 N m**.

These corrected values do **not** establish device feasibility or a safety margin.

## NOCSAE

NOCSAE ND081 is a **test method** for pneumatic-ram evaluation of protective headgear/faceguards and is designed to capture both linear and rotational acceleration.

- https://nocsae.org/standard-pneumatic-ram-test-method-and-equipment-used-in-evaluating-the-performance-characteristic-of-protective-headgear-and-faceguards/
- https://nocsae.org/football-standards/

**Public-material rule:** do not describe ND081 itself as an active-helmet "compliance standard." Determine the applicable performance/certification specification with NOCSAE.

## Mips benchmark

Mips publicly describes an ingredient-brand model and reports a patent portfolio of roughly 60 patent families and more than 400 granted patents.

- https://mipscorp.com/about-mips/business-model-and-strategy/
- https://mipscorp.com/about-mips/ingredient-brand/
- https://mipscorp.com/about-mips/research-and-development/

**Public-material rule:** do not attribute Mips' company value to a "single patent." Use Mips as a business-model benchmark, not proof that Inercept's market adoption is validated.

## Market sizing

A 2026 third-party market report estimated the global head-protection-equipment market at approximately **$7.69B by 2030**. Market definitions differ substantially across sports helmets, industrial head protection, military/defense, and other segments.

- https://www.thebusinessresearchcompany.com/report/head-protection-equipment-global-market-report

**Public-material rule:** label TAM figures by market definition and source. Project-specific segment rollups require source-level validation before circulation.

## Market projection arithmetic

The investor materials state a **$3.9B 2024 sports-helmet market** growing at **6.8% CAGR** while also showing a **$7.4B 2030** cover figure.

Those figures are not internally equivalent:

- $3.9B compounded at 6.8% for six years is approximately **$5.79B in 2030**.
- Reaching $7.4B from a $3.9B 2024 base by 2030 requires approximately **11.3% CAGR**.

**Public-material rule:** if the $7.4B figure refers to a broader head-protection market rather than the sports-helmet segment, label the category explicitly and source it separately. Do not present the $3.9B base, 6.8% CAGR, and $7.4B endpoint as one continuous forecast.

## IP and trademark claims

Project materials contain statements regarding provisional-patent status, prior-art search results, and trademark screening. These are **project-reported legal/IP statements** and are not independently verified by this evidence register.

**Public-material rule:** patentability, freedom to operate, filing status, PCT deadlines, and trademark clearance should be confirmed with responsible counsel before external circulation.
