# ML Foundations for Trustworthy AI in Healthcare

Slides on practical checks for catching common failure modes in healthcare ML models: cross-validation, bootstrapping, and data leakage.

Each section covers what commonly goes wrong (with real-world examples of models that looked great in training but failed in deployment), why the standard check catches it, and how to run it in practice.

Topics covered:
- Cross-validation: Proving a model generalises beyond the data it was trained on
- Bootstrapping: Quantifying how stable a model's estimates really are
- Data leakage: Catching features that wouldn't exist yet at the moment of prediction

Presented at DASH 2026 (22 July 2026).
