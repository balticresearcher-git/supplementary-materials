# Supplementary Materials: Spatial Risk Mapping of Maritime Accidents in the Baltic Sea

> **Notice:** *This repository has been fully anonymized to comply with Double-Blind Peer Review requirements.*

## Overview

This repository contains the reproducible analytical workflow, R scripts, and Bayesian modeling diagnostic outputs (using Stan and the `brms` package) necessary to replicate the findings of our manuscript: **"Spatial Risk Mapping of Maritime Accidents in the Baltic Sea: A Bayesian Hierarchical Approach using AIS and Environmental Data"**.

## 🌐 Interactive Website

To make the review process as seamless and transparent as possible, we have compiled the entire methodology, extended MCMC diagnostics, and high-resolution spatial plots into an interactive Quarto website. 

**Please access the supplementary materials here:** 👉 [Click here to view the Interactive Supplementary Website](: https://balticresearcher-
git.github.io/supplementary-materials/)

## Contents of the Website

1. **Data Preparation:** Reproducible code for spatial grid generation and merging EMSA/AIS records.
2. **Model Setup:** Mathematical formulation of the Zero-Inflated Negative Binomial (ZINB) model.
3. **MCMC Diagnostics:** Traceplots, rank histograms, and effective sample size (ESS) verifications.
4. **Results:** LOO-CV evaluation, conditional marginal effects, and code for generating spatial risk maps.

## Reproducibility Statement

All models were estimated in `R`. The interactive website contains embedded code chunks that can be expanded by clicking the **"Show the code"** buttons scattered throughout the document.
