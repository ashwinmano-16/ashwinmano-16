Hi, I'm Ashwin Manoharan 👋

I'm a final-year B.Tech student at NIT Tiruchirappalli and a Student Member of the Institute and Faculty of Actuaries (IFoA), sitting CM1, CS1 and CB1 in April 2027. I'm interested in life insurance, annuities, and risk modelling, and I like turning messy real-world data into models that support pricing and capital decisions.

ashwinmano16@gmail.com

Research: Reducing Basis Risk in Parametric Crop Insurance with Satellite Vegetation Indices

Research Intern, NIT Trichy and IRMA, Gujarat (May 2026 to present). Manuscript in preparation.

Parametric insurance pays farmers based on an index instead of a field inspection. It is fast and cheap, but it often pays the wrong amount. That gap is basis risk. I built an end-to-end pipeline for rain-fed groundnut across 12 districts in three agro-climatic zones of India to measure how far satellite data can reduce it.

Highlights (all out-of-sample):

A transparent, graded payout based on satellite NDVI raised the correlation with farmer loss from 0.35 → 0.49, compared with a conventional rainfall index (gain significant, p ≈ 0.01).
About 9% less farmer underpayment at the same premium.
Transferred well to an unseen climate zone: 0.71, against 0.48 for rainfall.
Copula-based portfolio pricing showed that correlated droughts raise the 1-in-100 payout by about 43% compared with assuming districts are independent. This matters directly for an insurer's capital.
Showed where the satellite signal runs out: adding more satellite channels or a gradient-boosted model did not improve skill.

Methods: de-trended loss modelling · sign-constrained payout design · leakage-free nested and leave-one-zone-out cross-validation · year-blocked bootstrap · Gaussian, t, Clayton and vine copulas · Generalised Pareto tails · Monte-Carlo pricing

Data: NASA POWER (41 years of weather) · Government of India yield records (25 years) · MODIS satellite vegetation indices

The code is private until publication and available on request.

🛠️ Tools

Python (pandas, NumPy, statsmodels, scikit-learn) · R · SQL · Excel

📚 Currently learning

IFoA CM1 (financial mathematics and life contingencies), CS1 (actuarial statistics in R), and CB1 (business finance), plus copula and extreme-value theory in depth.

<!--
**ashwinmano-16/ashwinmano-16** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
