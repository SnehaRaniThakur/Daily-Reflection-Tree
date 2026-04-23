# Design Rationale

## Overview

This project implements a deterministic end-of-day reflection system using a structured decision tree.

## Psychological Framework

The design is based on three axes:

1. **Locus of Control (Rotter, 1954)**
   Internal vs external perception of control.

2. **Contribution vs Entitlement**
   Based on Organizational Citizenship Behavior and entitlement theory.

3. **Radius of Concern (Maslow, Batson)**
   Expanding perspective from self to others.

## Design Approach

* Questions reflect real workplace scenarios
* Each option maps to a predefined signal
* Signals accumulate to determine dominant orientation

## Determinism

* No AI used at runtime
* Fixed options only
* Same inputs always produce the same outputs

## Trade-offs

* Limited emotional nuance
* Simplified signal aggregation
* No cross-day memory

## Improvements

* Deeper branching paths
* More personalized summaries
* UI-based interaction
