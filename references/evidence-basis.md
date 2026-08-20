# Evidence Basis

This reference records why the skill contains its non-obvious rules. It is for maintenance and audit, not routine product-research tasks.

## Decision structure

Multi-criteria decision analysis separates problem formulation, constraints, criteria, preferences, scoring, and sensitivity. The UK government's manual recommends testing whether different plausible weights alter the ordering of options. NASA's decision-analysis guidance distinguishes mandatory requirements from enhancing criteria and recommends objective, measurable criteria, acceptable ranges, and relative importance. These principles support defining the use case before searching, separating hard constraints from preferences, avoiding arbitrary cutoffs, and reporting when the winner is sensitive to assumptions.

- [UK Government: Multi-criteria analysis manual](https://assets.publishing.service.gov.uk/media/5a790545e5274a2acd18b975/1132618.pdf)
- [NASA: Decision Analysis](https://www.nasa.gov/reference/6-8-decision-analysis/)

## Comparison scope and offer facts

The US Federal Trade Commission's consumer guidance recommends recording exact manufacturer or model identifiers, comparing sellers, checking the total cost including delivery and fees, reading deal conditions and product descriptions, and checking return costs and windows. It also warns that comparison sites may rank only paying sellers. These points support exact identity matching, product-versus-offer separation, delivered-total comparison, and disclosure of source coverage.

- [FTC: Online Shopping](https://consumer.ftc.gov/articles/online-shopping)

Consumer Reports describes selecting representative products across popular outlets and a wide price range, buying retail units anonymously, and using tests designed around real consumer use. Its limited, representative selection also illustrates why “best tested” should not be restated as “best on the market” without broader coverage.

- [Consumer Reports: Home and Appliance Testing](https://www.consumerreports.org/about-us/what-we-do/research-and-testing/appliances-and-home-products/)

## Comparable performance evidence

Which? says it buys almost every product it tests and applies consistent category tests designed to reflect real-world use. RTINGS documents standardised test benches, repeatability checks, methodology versions, and the information loss that occurs when measurements are collapsed into one weighted score. These practices support preferring comparable independent tests and inspecting underlying metrics when a publisher's weights differ from the user's priorities.

- [Which?: How we test products](https://www.which.co.uk/about-which/which-tests-aO40c9I5iXNM)
- [RTINGS: Test Benches and Scoring System](https://www.rtings.com/company/test-benches-and-scoring-system)

## Limits of ratings and reviews

The FTC advises checking customer reviews across a variety of sites and not relying on star ratings alone because reviews can be fake, misleading, or incentivised. The OECD identifies deceptive practices, inaccuracy, and consumer biases as policy problems in online ratings. Besbes and Scarsini model selection distortions in sequential ratings and show that a review mean can overestimate underlying quality. Together, these sources support treating reviews as noisy evidence, checking review context and recurring issues, and avoiding universal star or count thresholds.

- [FTC: Online Shopping](https://consumer.ftc.gov/articles/online-shopping)
- [OECD: Understanding online consumer ratings and reviews](https://doi.org/10.1787/eb018587-en)
- [Besbes and Scarsini: On Information Distortions in Online Ratings](https://doi.org/10.1287/opre.2017.1676)

## Safety

Official alert databases contain recalls and safety reports for products that may still appear on marketplaces. This supports a risk-proportionate official safety check rather than treating availability or positive reviews as evidence of safety.

- [UK Product Safety Alerts, Reports and Recalls](https://www.gov.uk/product-safety-alerts-reports-recalls)

Use the equivalent regulator for the buyer's market when outside the UK.

## Observed case: cheapest toner

In the user-supplied ChatGPT conversation “Find cheapest toner” (20 August 2026), the request was for the cheapest compatible toner for a Brother HL-L2375DW. The response found a lower-priced eligible cartridge but recommended a £17.99 specialist-retailer option after introducing an unrequested supplier-reliability preference. It also failed to search marketplace listings broadly enough before answering. The user then supplied a Timink offer shown at £11.99 with a 4.3 rating from 443 reviews, which met the requested price objective and the response's own informal quality sanity check.

The narrow lessons are to preserve the explicit optimisation target, search broadly enough for the strength of the claim, use reviews as evidence rather than post-hoc justification, and verify exact listing and pooled-variant review data. The case does not justify a universal marketplace preference or a fixed review threshold.

## Observed case: fishing setup

In the user-supplied ChatGPT conversation “Fishing Rod and Reel Setup” (August 2026), recommendations changed repeatedly because the research began before the use cases and purchase constraints were stable. Nominal ranges were treated as arbitrary cutoffs, real product weight and action were initially overlooked, and recommendations were made before a broad retailer sweep. General search results favoured well-indexed products and missed retailer catalogue options. Product-family availability and generic delivery messaging were also conflated with exact-variant stock and address-specific delivery.

The productive corrections were to define the venue and methods first, distinguish hard constraints from preferred ranges and tolerances, assess complete rod-and-reel setups, inspect physical attributes relevant to use, search retailer catalogues and internal search rather than relying only on general web ranking, and verify exact-variant delivery at the strongest accessible level. When the use-case analysis later shifted the preferred casting range, the options needed reranking rather than defence of the previous favourite.

These observations informed the positive workflow in `SKILL.md`; they are not intended as category-specific fishing rules.
