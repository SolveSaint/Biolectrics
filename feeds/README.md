# Biolectrics RSS / OPML Feeds

This directory contains curated RSS/Atom feed lists for Biolectrics-related literature monitoring.

## Files

- [`biolectrics-core.opml`](biolectrics-core.opml) — curated core feed list, currently 112 public feeds. Intended for daily monitoring of Biolectrics / ALS / stress-glutamate-excitability literature.

## Intended filter target

Use this feed set for items that materially affect the Biolectrics model:

```text
stress → GR/FKBP5/NR3C1 → glutamate → Ca2+ → mitochondrial ROS →
lipid peroxidation / ferroptotic pressure → motor neuron vulnerability
```

High-priority terms include FKBP5, NR3C1, glucocorticoid receptor, HPA axis, chronic stress, glutamate, NMDA, AMPA, mGluR5, calcium overload, mitochondrial ROS, lipid peroxidation, ferroptosis, ALS, motor neuron excitability, REM sleep behavior disorder, REM atonia, basal ganglia, and PPN.

## Deduplication rule

When importing into a feed reader or monitoring agent, deduplicate by DOI when available. If no DOI is present, deduplicate by normalized title plus first author and year.

Normalize titles by:

- lowercasing
- removing punctuation
- collapsing whitespace
- stripping feed labels such as `current issue`, `recent articles`, `early view`, `advance article`, and `in press`

## Reporting rule

Only surface items that support, challenge, patch, or materially alter the model. Suppress generic biomedical noise, broad wellness articles, weak association-only papers, duplicate titles, and items that do not change interpretation.

## Public-safety note

This OPML uses public upstream feed URLs. Private RSS proxy keys should not be committed to this repository.