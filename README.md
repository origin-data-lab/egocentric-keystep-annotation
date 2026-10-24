# Keystep Annotation for Egocentric Robot-Learning Data

Technical evaluation materials for Origin Data Lab Field Note #05.

**Primary technical source:** https://origindatalab.io/technical-field-notes/keystep-annotation-egocentric-robot-learning.html

## Included
- `annotation_example.json`: one documented keystep (`ks_A_01`), not the complete 25-keystep dataset.
- `evaluation_summary.json`: sample counts and evaluation context.

## Method and limits
The note evaluates 25 human-labelled keysteps across two cooking clips (13 + 12). Structural QA found zero gaps, overlaps and missing required values. A body-worn IMU can support review of coarse wearer motion, but cannot independently validate fine hand actions. Boundary comparison uses 2,000 random sets; results are a small demonstration on one operator, not population estimates.

See the primary technical source for detailed methods and results. No raw video, IMU streams or full annotation files are included in this public package.
