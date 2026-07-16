# Additional Resources

A short list of resources for going deeper on agricultural yield simulation. (Not exhaustive — PRs welcome.) This field combines a decades-old mechanistic modeling tradition with fast-moving remote sensing and ML methods — cross-check any specific yield figure, model accuracy claim, or data source availability against current literature before an interview.

## Foundational Reading
- Jones et al., "The DSSAT cropping system model" — foundational documentation for one of the most widely used process-based crop model families, good grounding for sections 1 and 2.
- Holzworth et al., "APSIM – Evolution towards a new generation of agricultural systems simulation" — foundational documentation for another widely used process-based modeling framework.
- Lobell & Burke (eds.), *Climate Change and Food Security: Adapting Agriculture to a Warmer World* — solid grounding in the climate-impact modeling concepts discussed in section 4.
- Jiang et al. and related reviews on ML/deep learning for crop yield prediction from remote sensing — good grounding for sections 3 and 5's ML-specific content.
- Companion **Genomics Data Scientist** and **Computational Biologist** repos — relevant for general statistical modeling, cross-validation rigor, and reproducibility practices this repo builds on.

## Key Models & Data Sources (good to be conversationally familiar with)
- DSSAT and APSIM — the two most widely used, actively maintained process-based crop modeling frameworks.
- Major satellite earth observation programs providing the optical and radar imagery discussed in section 3.
- Major weather/climate reanalysis products and gridded weather datasets used widely in agricultural applications.
- Public agricultural statistics and yield reporting sources relevant to model validation.

## Communities & Discussion
- The Agricultural Model Intercomparison and Improvement Project (AgMIP) community, a major collaborative effort specifically focused on crop model intercomparison, climate-impact assessment, and model improvement.
- r/agtech and relevant precision agriculture and remote sensing discussion communities for broader discussion threads.
- Major agronomy, crop science, and remote-sensing-for-agriculture conferences and journals for current state-of-the-art research.

## Companion Repos (adjacent, complementary content)
- **Genomics Data Scientist** — statistical modeling rigor, cross-validation practices, and confounding/covariate concepts relevant to sections 5 and 6.
- **Computational Biologist** — general statistical modeling, reproducibility, and scientific computing practices relevant throughout.
- **Foundation-Model Scientist (BioAI)** — transfer learning and fine-tuning concepts directly relevant to section 5's cross-region transfer learning discussion.
- **Bioremediation AI Engineer** — closely analogous data-scarcity, field-deployment, and domain-generalization challenges, discussed there in an environmental biotechnology context but directly parallel to this repo's sections 3, 5, and 6.

## Staying Current
- Satellite remote sensing capabilities (resolution, revisit frequency, new sensor types) and ML methods for agricultural applications are both advancing quickly — recent literature is far more reliable than any static reference, including this repo, for current state-of-the-art capabilities.
- Climate change is actively shifting the historical baseline conditions many established crop models were originally calibrated against — stay current on ongoing model validation and recalibration efforts specific to your region and crop of interest.
