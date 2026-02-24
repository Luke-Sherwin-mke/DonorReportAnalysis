# DonorReportAnalysis

Title: Donor Retention & Campaign Targeting Analysis
Date: February 2026
Prepared for: Nonprofit Development & Executive Leadership
Prepared by: Luke Sherwin

### Executive Summary:

To protect revenue stability and strengthen donor retention, I analyzed 6 fiscal years of giving data across 21,433 confirmed donors. The analysis identifies 5,947 donors requiring immediate attention across three high-impact campaign segments.
The most urgent risk is 1,357 high-value donors currently lapsing, averaging $6,642 in lifetime giving. Additionally, 4,345 recently lapsed donors represent $15.2 million in historical giving and strong reactivation potential.
I recommend a three-tier campaign strategy:
Immediate personal outreach to lapsing top donors
Targeted re-engagement campaigns for recently lapsed donors
White-glove stewardship for active major donors
This structured segmentation enables focused outreach, protects high-value relationships, and prioritizes revenue retention efforts.

Business Task & Objective:
The organization requires a data-driven system to identify which donors are lapsing and which donors represent the highest lifetime value.
The objective of this analysis is to:
Identify lapsed donors requiring re-engagement
Identify top donors requiring retention prioritization
Quantify revenue at risk
Create actionable donor campaign lists



Data Source:
Kaggle fundraising dataset:
Donor dataset: 34,508 rows (21,433 confirmed donors after cleaning)
6 fiscal years of giving history
$81.5 million total lifetime giving

Data Cleaning:
Uploaded datasets to Google BigQuery via Google Cloud Storage
Cleaned donor dataset:
Removed non-confirmed donors
Stripped currency symbols
Converted NA strings to NULL
Cast giving fields to NUMERIC
Removed unnecessary columns
Validated total donation volume and row counts

Analysis:
Lapse Definition:
A donor is considered lapsed if:
No giving in the current fiscal year
At least one gift within the prior 5 fiscal years
Top Donor Definition:
Top donors are defined as:
Top 10% by lifetime giving using PERCENT_RANK()
Scored on recency, frequency, and average annual giving

Visualizations:


Key Findings:
21,433 confirmed donors analyzed
8,604 donors (40%) have lapsed
$15.2 million in giving from donors lapsed within last 2 fiscal years
1,357 top donors currently lapsing (avg lifetime giving: $6,642)
245 active major donors this fiscal year
Avg lifetime giving: $224,286
Avg annual giving: $17,783
Total donors requiring immediate strategic attention: 5,947


Recommendations:
Urgent Rescue Campaign — Top Donors Currently Lapsing
Donors: 1,357
Average Lifetime Giving: $6,642
Recommendation:
Immediate personal outreach including calls, personal emails, and relationship-based engagement.
Rationale:
These are high-value donors actively drifting away. The cost of losing them exceeds the cost of intervention.
Expected Impact:
Revenue protection and stabilization of high-value donor base.

Re-Engagement Campaign — Recently Lapsed Donors
Donors: 4,345
Total Historical Giving: $15.2 million
Recommendation:
Targeted email campaigns, phone outreach, and segmented appeals.
Rationale:
Recency indicates higher reactivation probability.
Expected Impact:
Mid-level revenue recovery with scalable outreach methods.

Stewardship Program — Active Major Donors
Donors: 245
Average Lifetime Giving: $224,286
Recommendation:
White-glove retention strategy: Personalized impact reports, Exclusive events, Dedicated major gift officer assignment
Rationale:
These donors represent long-term revenue stability.
Expected Impact:
Strengthened donor loyalty and reduced future attrition risk.
Impact:
This segmentation model transforms raw donor data into a prioritized action framework.
Rather than treating all donors equally, the organization can now:
Act immediately on high-risk, high-value donors
Launch cost-effective re-engagement campaigns
Protect its most significant revenue relationships
The result is a structured, scalable donor retention strategy grounded in data.

