# AdaLogit
Implementation and reproducibility code for AdaLogit: Adaptive Logistic Regression for Interpretable Credit Scoring

## Overview
We introduce AdaLogit, an adaptive logistic regression framework with elastic net regularization, which is particularly well suited to credit scoring applications. Unlike traditional Lp-regularized logistic regression, AdaLogit enjoys the oracle properties, ensuring consistent recovery of the true feature support even under complex correlation structures. Through a comprehensive empirical evaluation on synthetic and real-world credit scoring datasets, we show that AdaLogit matches standard linear baselines in out-of-sample discrimination and balanced accuracy, while identifying significantly sparser and more stable feature sets. Compared with state-of-the-art black-box classifiers such as TabPFN, AdaLogit approaches their predictive performance while remaining interpretable and providing better-calibrated probability estimates. For comparable balanced accuracy, AdaLogit often yields lower false negative rates than black-box alternatives. The combination of transparency, stable feature selection and coefficient estimation, as well as accurate probability calibration, allows AdaLogit to decisively facilitate compliance with the Basel Internal Ratings-Based (IRB) framework, the regulatory requirements of the EU Artificial Intelligence Act for high-risk AI systems, and any other regulatory framework requiring algorithmic transparency, such as the Equal Credit Opportunity Act (15 U.S.C. § 1691(d)(2)).

[Preprint](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7431058)


## Installation



## Usage



## Reproducing the Paper Results



## License

This repository, including the implementation of `AdaLogit`, simulation scripts, and derivative works, is provided for non-commercial use under the **PolyForm Noncommercial License 1.0.0** (see `LICENSE`).

- **Permitted Use:** Academic research, peer review, reproducibility verification, personal study, and non-commercial benchmarking.
- **90-Day Internal Evaluation:** Prospective commercial users may evaluate the software internally for up to **90 calendar days** to assess technical fit and performance, subject to the conditions in [`EVALUATION_TERMS.md`](EVALUATION_TERMS.md).
- **Prohibited Without a Commercial License:** Production deployment, live customer/client scoring, revenue-generating services, integration into commercial products, redistribution, or continued use beyond the 90-day evaluation window without a separate commercial agreement.

For commercial licensing, reach out at albert@whiteboxlab.ai.
