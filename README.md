# Wartburg Algae Feeding Calculator

A web-based dilution calculator designed for laboratory use at Wartburg College.

This tool converts spectrophotometer absorbance readings (445 nm) into stock algae concentration and calculates the required feeding volume per well using the dilution equation:

C₁V₁ = C₂V₂

---

## Purpose

This calculator was developed to help students:

- Understand how absorbance relates to concentration
- Apply Beer–Lambert–based regression models
- Use the dilution equation correctly
- Avoid manual calculation errors in laboratory settings

The website makes the mathematical process visible so students can see how values are derived.

---

## Scientific Background

### 1. Stock Concentration (C₁)

Stock concentration is calculated from absorbance using a linear regression model derived from calibration data:

ABS = (3 × 10⁻⁷)(cells/mL) + 0.0658  
R² = 0.9908

Rearranged:

cells/mL = (ABS − intercept) / slope

---

### 2. Dilution Equation

The feeding volume is calculated using:

C₁V₁ = C₂V₂

Where:

- C₁ = Stock concentration (cells/mL)
- V₁ = Volume of stock added (mL)
- C₂ = Desired final concentration (cells/mL)
- V₂ = Final well volume (mL)

Rearranged to solve for V₁:

V₁ = (C₂ × V₂) / C₁

---

## How to Use

1. Enter the measured absorbance value.
2. Enter the well volume.
3. Enter the desired final concentration.
4. Click "Calculate".
5. The tool outputs:
   - Stock concentration (cells/mL)
   - Volume of stock algae to add (µL per well)

---

## Live Website

https://superkandy.github.io/Algae-Counts-and-Absorbance/

---

## Intended Use

This tool is intended for:

- Undergraduate laboratory instruction
- Algae culture preparation
- Tigriopus feeding experiments
- Demonstrating dilution principles

Ensure proper calibration and blanking before use.

---

## Author

Sameer Sarwar  
Biology & Computer Science  
Wartburg College  

Version 1.1
