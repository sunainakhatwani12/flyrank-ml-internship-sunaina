# Capstone Report — Content Refresh Prioritization

- **Author:** Sunaina Khatwani
- **Lane:** Content Refresh Prioritization
- **Repo:** https://github.com/sunainakhatwani12/flyrank-ml-internship-sunaina
- **Date:** July 2026

- 
## 0. Abstract

- This project investigates whether search performance signals can identify pages that should be reviewed for a content refresh. The analysis uses the FlyRank ML Internship dataset and focuses on historical search performance and content-level features while excluding client-identifying information. A transparent rule-based baseline was compared with machine learning models using grouped client validation to reduce information leakage. In the final evaluation, the transparent baseline achieved higher Precision@50 than the Random Forest model, showing that a simple and interpretable ranking strategy performed better for this task. The final output is a ranked review queue that helps editors prioritise which pages to inspect first while keeping the final decision under human control.

- ## 1. Problem framing
- 
- This project supports the decision of which content pages should be reviewed first for a potential content refresh.

The unit of analysis is an individual content page. The output is a ranked priority score that orders pages from highest to lowest refresh priority.

A FlyRank editor can use this ranked queue to decide which pages should be manually reviewed first. The system is intended to support editorial decisions rather than automate them.

An incorrect recommendation could waste editorial time by suggesting pages that do not require updates or by failing to identify pages that would benefit from a refresh.

Machine learning and data analysis are useful because historical search performance contains patterns that are difficult to capture with fixed rules alone. Comparing a transparent baseline with machine learning models helps determine whether a more complex model provides additional value.

## 2. Data safety

The project uses the FlyRank ML Internship dataset containing pseudonymized search-performance and content-level information.

The analysis uses features related to content age, impressions, clicks, CTR, average position, engagement signals, and other historical search metrics that support content refresh prioritization.

To reduce leakage, label-derived fields such as `trend_direction` and `trend_pct` were not used as model features because they directly describe the target outcome. Pseudonymous client identifiers were used only for grouped train/test splitting and were never included as predictive features.

No client names, domains, URLs, or other identifying information are included anywhere in the repository. The project reports only aggregated metrics, validation results, and ranked recommendations based on pseudonymized data.

All work in the `work/` directory follows the internship requirement to avoid exposing client-identifying information.

## 3. Baseline

The baseline is a transparent rule-based ranking system designed to prioritise pages for manual content review.

The rule combines content staleness and search visibility to rank pages that are more likely to benefit from a refresh. This baseline is fully interpretable because every recommendation can be traced back to simple measurable signals rather than complex model behaviour.

Using a transparent baseline provides a fair comparison for machine learning models because both approaches are evaluated on the same grouped validation split and with the same Precision@K metrics.

Final grouped validation results showed:

- Precision@20: 75%
- Precision@50: 70%
- Precision@100: 65%

In the final evaluation, the transparent baseline achieved higher Precision@50 than the Random Forest model, making it the preferred decision-support approach for this project.

## 4. Model / analysis

The project compares a transparent rule-based baseline with supervised machine learning models to determine whether model-based ranking improves content refresh prioritisation.

Two machine learning models were evaluated:

- Logistic Regression
- Random Forest Classifier

The target is a binary proxy label (`is_declining_label`) indicating whether a page shows evidence of declining search performance.

The feature set includes historical search-performance and content-level signals such as:

- Content age
- Search impressions
- Clicks
- Click-through rate (CTR)
- Average search position
- Engagement-related features

The following information was deliberately excluded:

- `trend_direction`
- `trend_pct`
- Client identifiers
- Any label-derived fields

These fields were excluded to reduce information leakage and ensure that the models learned from historical signals rather than directly observing the outcome being predicted.

The models were trained using grouped client validation so that pages from the same client did not appear in both training and testing datasets.

## 5. Evaluation

The project was evaluated using grouped client validation to ensure that pages from the same client did not appear in both the training and testing sets. This provides a more realistic estimate of how the approach performs on previously unseen clients and reduces information leakage.

Performance was measured using Precision@20, Precision@50, and Precision@100. Both the baseline and the machine learning models were evaluated on the same validation split to ensure a fair comparison.

### Final Results

| Method | Precision@20 | Precision@50 | Precision@100 |
|---------|-------------:|-------------:|--------------:|
| Rule-Based Baseline | 75% | 70% | 65% |
| Random Forest | 50% | 54% | 49% |

The final evaluation showed that the rule-based baseline outperformed the Random Forest model on the grouped validation split. Although the machine learning model captured useful patterns, the transparent baseline produced stronger ranking performance while remaining easier to interpret.

The main errors occurred when pages appeared stale based on historical signals but did not actually require a content refresh, or when declining pages were influenced by factors not captured in the available features, such as seasonality or technical SEO issues.

## 6. Interpretation

The analysis shows that simple, transparent ranking rules based on content staleness and search visibility are highly effective for this task.

The rule-based baseline consistently outperformed the Random Forest model on the grouped client validation split. This suggests that the available search-performance signals are already strong indicators for prioritising content review and that additional model complexity did not improve ranking performance in this evaluation.

One important finding is that interpretability has practical value. Editors can understand exactly why a page appears near the top of the ranked queue, making the recommendations easier to review and trust.

The evaluation also highlights that not every decline in search performance should lead to a content refresh. Some pages may decline because of seasonality, changing user intent, technical SEO issues, or external factors that are not represented in the dataset.

A negative but valuable result from this project is that a more complex machine learning model did not outperform the transparent baseline. This demonstrates that simple methods can sometimes provide better decision support while remaining easier to explain and maintain.


## 7. Recommendation

The final output of this project is a ranked content review queue designed to help FlyRank editors prioritise manual content reviews.

Based on the evaluation results, the transparent rule-based baseline is recommended for operational use because it achieved the strongest performance on the grouped client validation split while remaining easy to understand and explain.

Editors should use the ranked list as follows:

1. Review the highest-ranked pages first.
2. Confirm that the content is outdated or no longer matches current search intent.
3. Decide whether the page should be refreshed, monitored, consolidated, redirected, or left unchanged.
4. Record the action taken and monitor performance after publication.

Confidence in the highest-ranked recommendations is moderate because they are supported by measurable search-performance signals. However, every recommendation should be reviewed by a human editor before action is taken.

This project is intended to support editorial decision-making rather than replace professional judgement.


## 8. Reproducibility

The complete project is available in the GitHub repository together with the notebooks used throughout the internship.

The project can be reproduced by cloning the repository, installing the required Python packages, and executing the notebooks in order.

Recommended workflow:

1. Clone the repository.
2. Install the required dependencies.
3. Open the notebooks in Google Colab or Jupyter.
4. Execute the notebooks from Week 1 through the Capstone notebook using **Run All**.
5. Compare the generated outputs with the committed results.

Random seeds were fixed where appropriate to improve reproducibility. The grouped client validation notebook and the reported evaluation metrics are included in the repository so that the reported results can be independently verified.


## 9. Acknowledgments & data credit

This project was built as part of the FlyRank ML Internship.

Built on the **FlyRank ML Internship dataset**.

Data credit: https://flyrank.ai

Thanks to the FlyRank team for providing the internship structure, pseudonymized dataset, learning materials, and evaluation framework used throughout this capstone project.


