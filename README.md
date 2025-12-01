# GenAI-Final-Project

# Q1 & Q2 Analysis: 8BitDo Retro Mechanical Keyboard
**94-844 Generative AI Lab (Fall 2025) - Final Project**

## Project Overview
This repository contains the **Product Selection (Q1)** and **Customer Review Analysis (Q2)** for the third group product: the **8BitDo Retro Mechanical Keyboard**.

The goal of this module is to extract high-fidelity visual descriptions from text-based customer reviews using LLMs (GPT-4o-mini). These outputs are structured specifically to support the Image Generation phase (Q3).

## Product Details
* **Product Name:** 8BitDo Retro Mechanical Keyboard
* **Category:** Electronics > Computers & Accessories
* **ASIN:** B0CCP8KYGG
* **Rationale:** Selected for its distinct "Nintendo NES" retro aesthetic (boxy shape, creamy grey/red colors, large buttons), which provides a unique challenge for diffusion models compared to organic or kitchen products.

## File Structure

```text
├── Final_Project_8BitDo_Keyboard.ipynb   # Main analysis notebook (Q1 & Q2 code)
├── README.md                             # This documentation
└── data/                                 # Generated output files
    ├── product_info.json                 # Rationale and metadata
    ├── product_description.json          # Raw product specs
    ├── customer_reviews.json             # Raw customer review text
    ├── visual_features.json              # LLM-extracted visual attributes (colors, shapes)
    ├── product_features.json             # Functional & design feature extraction
    ├── sentiment_analysis.json           # User sentiment breakdown
    └── image_generation_summary.json     # CRITICAL: Final input for Q3
