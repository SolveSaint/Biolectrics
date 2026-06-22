# Biolectrics

Research support repository for Biolectrics-related literature tracking, mechanism notes, and feed infrastructure.

## RSS / OPML feed lists

The curated core feed list lives in [`feeds/biolectrics-core.opml`](feeds/biolectrics-core.opml). It is intended for daily monitoring of Biolectrics / ALS / stress-glutamate-excitability literature.

See [`feeds/README.md`](feeds/README.md) for the monitoring target, deduplication rule, reporting rule, and public-safety note about RSS proxy keys.

## Daily monitoring target

The RSS/OPML workflow is aimed at papers that materially affect this mechanism chain:

```text
stress → GR/FKBP5/NR3C1 → glutamate → Ca2+ → mitochondrial ROS →
lipid peroxidation / ferroptotic pressure → motor neuron vulnerability
```

Generic biomedical updates should be filtered out unless they support, challenge, patch, or materially alter the model.