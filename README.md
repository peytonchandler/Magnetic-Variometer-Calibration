# Calibrating Magnetic Variometers Using Quantitative Error Metrics
**Spring 2026 Capstone Design Project — Colorado School of Mines**
Julia Berglind & Peyton Chandler | Department of Geophysics | Advisors: Rich Krahenbuhl (CSM), Brian Shiro (USGS), Adam Ringler (USGS), Josh Rigler (USGS), & John Spritzer (USGS)

---

## Overview

The USGS has deployed several fluxgate variometers across the United States for geomagnetic monitoring. These instruments are well-suited for resolving short-period temporal variations but are not designed to recover absolute field values. Without a co-located geomagnetic observatory, there is no straightforward way to correct for these errors.

This project develops quantitative error metrics to characterize and correct variometer measurements, with the goal of making standalone variometer deployments more scientifically reliable. Corrections are referenced against the International Geomagnetic Reference Field (IGRF) and validated against observatory data from the Boulder Geomagnetic Observatory.

---

## Research Question

How can we develop quantitative metrics to improve the absolute accuracy of magnetic variometer measurements at stations without co-located geomagnetic observatories?

---

## Hypothesis

Systematic errors in variometer deployments are quantifiable via observatory comparison and correctable using IGRF-referenced metrics, enabling more reliable absolute field estimation at sites without co-located observatories.

---

## Objectives

1. Quantify the error characteristics of variometer relative to Boulder Geomagnetic Observatory data
2. Develop correction metrics: baseline offset, secular drift rate, angular misalignment, sensitivity coefficients — benchmarked against the IGRF
3. Apply the correction scheme to independent standalone USGS variometer deployments
4. Validate corrected output against IGRF and assess whether results approach INTERMAGNET accuracy thresholds (±5 nT)

---

## Workflow

1. **Deploy** — Install Mag690-100 adjacent to the Boulder Geomagnetic Observatory to collect simultaneous high-accuracy reference data
2. **Characterize** — Compare variometer output to observatory data to quantify errors across X, Y, Z components
3. **Correct** — Build a correction scheme using characterized errors referenced against IGRF, designed to be applicable without a co-located observatory
4. **Apply** — Implement the correction on independent USGS variometer deployments across the US
5. **Validate** — Compare corrected variometer output to IGRF at independent sites and quantify improvement

---

## Data Sources

- **Boulder Geomagnetic Observatory** — high-accuracy absolute reference (USGS/NOAA)
- **USGS variometer network** — standalone variometer deployments across the US
- **IGRF-14** — global geomagnetic reference model used for benchmarking and validation

---

## Student Team

**Julia Berglind** — Julia has a background in computational geoscience, including modeling magma dynamics and volcanic evolution.

**Peyton Chandler** — Peyton has worked on seismic interpretation for structural analysis and developing machine learning-based tsunami classification algorithms.

Both students have extensive coursework and practical experience in magnetic methods under Dr. Yaoguo Li at Colorado School of Mines.


