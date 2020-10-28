
### Research paper

[A primer on casual analysis](https://arxiv.org/abs/1806.01488)  
*arXiv* 2018

### Authors

  - Finnian Lattimore  
  - Cheng Soon Ong

### Thoughts

**Introduction**

The authors define causal inference distinct from statistical or
probabilistic inference. Causal inference features the mathematical
expression of a cause (i.e. an extra requirement is manually added to a
conditional probability model). <br>

[Estimating conditional
independence](https://people.richland.edu/james/lecture/m170/ch05-rul.html)
from data is already a challenge in itself. I.e. identifying the true
factors that cause selection bias (if they are considered, we can
estimate conditional independence as the influence of confounding
factors are accounted for). <br>

Three types of causal inference questions:  
1\. **Association** - seeing and observing the environment.  
2\. **Intervention** - performing an intervention on the environment.  
3\. **Counterfactuals** - retrospectively imagining an alternate
scenario and its impact. <br>

The authors also consider the following distinctions in causal analysis
tasks:  
\+ Inferring the graph of causes.  
\+ Using the graph of causes to infer the effect of an action (requires
post-intervention data collection). <br>

**Reinchenbachs common cause principle** states that if \(X\) and \(Y\)
are not statistically independent (\(P(X|Y) > P(X)\) or vice versa, or
\(P(XY) > P (X)\times P (Y)\)), a third variable \(Z\) exists that
causally influences both. \(Z\) screens \(X\) and \(Y\) so that \(X\)
and \(Y\) are statistically independent conditional on \(Z\).

**Note:** this principle does not explain the presence of other
unobserved variables (i.e. selection bias), or a common time rather than
conceptual variable dependency, or guarantee that the designated
variable \(Z\) is true as it may have been determined from multiple
testing.
