# MMM Library (MMMLib)
MMMLib is a library for open-source alternatives of Marketing Mix Modelling tool.

# What is MMM?
Marketing Mix Modeling (MMM) is an analytical approach to evaluate:
1. how different marketing tactics (known as the marketing mix) influenced short-term/long-term business target in the past, and
2. how marketing mix could impact short-term/long-term business target in the future.

The term "Marketing Mix" was first introduced by Neil Borden (professor at Harvard Business School) in 1949.
During late 1990s and early 2000s, MMM lost popularity with the rise of digital marketing channels and real-time analytics and digital attribution modeling alternatives.
However, MMM has experienced a resurgence in popularity due to data privacy changes. With increasing restrictions on data collection and tracking, digital attribution is becoming more difficult and less accurate.
MMM turns out to be the only way to 
1. provide a holistic view of marketing effectiveness,
2. capture long-term effects of marketing instruments,
3. address the increasing complexity of the customer journey, and
4. help with strategic budget allocation.

# Popular MMM open-source libraries

| Feature | Meta Robyn | Google LightweightMMM | Uber Orbit |
|---|---|---|---|
| **Core Methodology** | Bayesian Time Series Modeling | Bayesian Regression | Bayesian Additive Regression Trees (BART) |
| **Adstock/Saturation Transformation** | Flexible (geometric, Weibull, S-curve) | Hill function (saturation), Geometric decay (adstock) | Implicit saturation (BART), Adstock (preprocessing) |
| **Media Channels** | Online & Offline | Primarily Digital | Online & Offline |
| **Hyperparameter Optimization** | Evolutionary Algorithm | Markov Chain Monte Carlo (MCMC) | MCMC |
| **Budget Allocation Optimization** | Built-in | Separate techniques | Separate procedures |
| **Model Diagnostics & Validation** | Extensive (MAPE, R-squared, decomposition, holdout) | Standard diagnostics, posterior checks | Posterior uncertainty, BART diagnostics |
| **Open Source Availability/GitHub Link** | [facebookexperimental/Robyn](https://github.com/facebookexperimental/Robyn) | [google/lightweight_mmm](https://github.com/google/lightweight_mmm) | [uber/orbit](https://github.com/uber/orbit) |
| **Platform** | R | Python | Python |
| **Scalability** | Medium to Large datasets | Smaller datasets, faster | Moderate datasets, BART complexity dependent |
| **Ease of Use** | Relatively easy, steeper learning curve | Easier (Python & stats knowledge) | BART & Bayesian knowledge needed |
| **Community Support** | Growing (forums, GitHub) | Strong (Google ecosystem) | Growing (GitHub, Uber) |
