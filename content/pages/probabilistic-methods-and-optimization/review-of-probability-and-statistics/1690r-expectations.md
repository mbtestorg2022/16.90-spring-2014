---
content_type: page
parent_title: 3.2 Review of Probability and Statistics
parent_uid: 972a23bc-2208-f9b1-2895-30de24175e7d
title: 3.2 Review of Probability and Statistics
uid: f11bfbbc-299e-7603-ff39-0e8071fc595e
---

*   [\<Distributions]({{< baseurl >}}/pages/probabilistic-methods-and-optimization/review-of-probability-and-statistics/1690r-distributions)
*   [3.2.1Random Variables]({{< baseurl >}}/pages/probabilistic-methods-and-optimization/review-of-probability-and-statistics)
*   [3.2.2Outcomes and Events]({{< baseurl >}}/pages/probabilistic-methods-and-optimization/review-of-probability-and-statistics/1690r-outcomes-and-events)
*   [3.2.3Distributions]({{< baseurl >}}/pages/probabilistic-methods-and-optimization/review-of-probability-and-statistics/1690r-distributions)
*   [3.2.4Expectations]({{< baseurl >}}/pages/probabilistic-methods-and-optimization/review-of-probability-and-statistics/1690r-expectations)
*   [3.2.5The Central Limit Theorem]({{< baseurl >}}/pages/probabilistic-methods-and-optimization/review-of-probability-and-statistics/1690r-the-central-limit-theorem)
*   [\>The Central Limit Theorem]({{< baseurl >}}/pages/probabilistic-methods-and-optimization/review-of-probability-and-statistics/1690r-the-central-limit-theorem)

3.2.4 Expectations
------------------

[Measurable Outcome 3.5]({{< baseurl >}}/pages/measurable-outcome-index/#anchorMO35), [Measurable Outcome 3.6]({{< baseurl >}}/pages/measurable-outcome-index/#anchorMO36), [Measurable Outcome 3.10]({{< baseurl >}}/pages/measurable-outcome-index/#anchorMO310)

Think back to the fact that the thickness of a turbine blade in an engine is a random variable. Even though we recognize the randomness of the blade thickness, this does not imply that the nominal value of the blade thickness that we would have used in a deterministic analysis is without any meaning. We understand that the nominal value of the blade thickness is the thickness we expect the manufacturer to produce. This nominal value provides us with a centre to base our further calculations relating to the random variable.

The nominal value is an example of an expected value of a random variable. Expected values of random variables are deterministic variables that help us understand the random variable.

Expected Value and Mean
-----------------------

Given a random variable \\(X\\) with PDF \\(f\_ X(x)\\), the expected value is defined as,

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
\\\[E\\{ X\\} \\equiv \\int \_{-\\infty }^{+\\infty } x f\_ X(x)\\, dx\\\]
{{< tdclose >}}
{{< tdopen >}}
(3.13)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

The expected value of \\(X\\) is also known as the mean value. We will also use the symbol \\(\\mu \_ X\\) for the expected value of \\(X\\).

Variance and Standard Deviation
-------------------------------

The variance is a measure of the variability in \\(X\\) about its mean value. The variance of \\(X\\) is defined as,

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
\\\[\\sigma \_ X^2 \\equiv \\int \_{-\\infty }^{+\\infty } (x - \\mu \_ X)^2 f\_ X(x)\\, dx.\\\]
{{< tdclose >}}
{{< tdopen >}}
(3.14)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

The value \\(\\sigma \_ X\\) is known as the standard deviation of \\(X\\). A frequently used relationship exists between the mean and variance,

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
\\\[\\sigma \_ X^2 = E\\{ X^2\\} - \\mu \_ X^2.\\\]
{{< tdclose >}}
{{< tdopen >}}
(3.15)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Try proving this!

Percentiles
-----------

The \\(u\\) percentile of \\(X\\) is the smallest number \\(x\_ u\\) such that,

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
\\\[u = P\\{ X \\leq x\_ u\\} = F(x\_ u).\\\]
{{< tdclose >}}
{{< tdopen >}}
(3.16)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Note, since \\(u\\) is a probability, its range is \\(0 \\leq u \\leq 1\\).

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}} Discrete Random Variable{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}} Continuous Random Variable{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}} Can either be a discrete or continuous random variable{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}} None of the above{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Answer:

\\(E(J)\\) is simply a number, i.e.??it is deterministic.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

BackDistributions ContinueThe Central Limit Theorem