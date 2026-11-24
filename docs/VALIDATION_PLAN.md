# Validation Plan

This document defines non-proprietary gates required before investor materials should use validated performance language.

## Gate 1 - Arithmetic and model integrity

- Unit-check every equation.
- Separate scalar back-of-envelope calculations from 3-axis CMG dynamics.
- Run sensitivity analysis over rotor inertia, spin speed, gimbal rate, helmet/head inertia, and impact waveform.
- Define uncertainty bounds.

**Exit criterion:** reproducible calculations with versioned assumptions and no unit/arithmetic defects.

## Gate 2 - Rotor and gimbal feasibility

- Rotor stress and containment analysis at target RPM.
- Bearing-loss characterization.
- Gimbal torque/rate characterization under representative loads.
- Overspeed, imbalance, and fail-safe analysis.

**Exit criterion:** component test data showing the target operating envelope is mechanically achievable.

## Gate 3 - Power and thermal budget

- Measure steady-state rotor losses.
- Measure gimbal transient power.
- Include control electronics, sensors, conversion losses, thermal-management load, and any vacuum-system burden.
- Derive runtime from measured system power rather than cell specific energy alone.

**Exit criterion:** measured Wh and W budget with thermal margins.

## Gate 4 - Control authority

- Implement a 3-axis CMG steering law.
- Characterize singularities and saturation.
- Measure sensor-to-command and command-to-torque latency independently.
- Validate torque-vector tracking under impact-like transients.

**Exit criterion:** commanded vs. measured torque-vector response with bounded latency/error.

## Gate 5 - Benchtop impulse testing

- Apply repeatable angular impulses to an instrumented rigid-body surrogate.
- Compare active-on, active-off, and passive baseline conditions.
- Pre-register primary endpoints.

**Exit criterion:** statistically reproducible reduction in defined rotational kinematic metrics without unacceptable secondary loads.

## Gate 6 - Headform and neck testing

- Use an applicable NOCSAE method such as ND081 where appropriate.
- Capture linear acceleration, rotational acceleration, rotational velocity, neck loads, device state, and timing.
- Compare against matched baseline helmets.

**Exit criterion:** independent or third-party reproducible performance with no adverse load transfer.

## Gate 7 - Claim conversion

Only after the applicable gates are passed may language move from:

- "modeled target" -> "measured in benchtop testing"
- "measured in benchtop testing" -> "measured in instrumented headform testing"
- "headform performance" -> any injury-risk statement, only with an appropriate validated risk model and careful limitations

No test result should be described as preventing concussion/TBI without evidence sufficient for that exact claim.
