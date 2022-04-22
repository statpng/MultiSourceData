# Types of rotation methods


## Table


| Name | Oblique | Principle | Comments
| ----------- | ----------- | ----------- | ----------- |
| Binormamin (Kaiser & Dickman, 1959) | Yes | Combines quartimin and covarimin criteria | |
| Biquartimin (Carroll, 1957) | Yes | Equally weights quartimin and covarimin criteria | Usually good, but occasional .8 correlation between two factors. |
| Covarimin (Kaiser, 1958) | Yes | Minimizes sum of covariances of squared factor loadings | GIves almost uncorrelated factors |
| Direct oblimin | Yes | Minimizes a function of factor pattern varying from covarimin to biquartimin to quartimin by user-set parameter | Available in many statistical packages. |
| Equamax (Saunders, 1962) | No | Combines quartimiax and varimax criteria | Spreads variance more equally across factors |
| Indirect oblimin (Carroll, 1960) | Yes | Same as direct oblimin except uses reference vector instead of factor pattern |  |
| max plane | Yes | Maximizes hyperplane count by simulating visual rotation | Solution often differs from other programs. |
| Oblinorm (Bentler and Wingard, 1977) | Yes | Scale-free version of binormamin |  |
| Oblimax (Pinzka and Saunders, 1954) | Yes | Maximizes kurtosis of all loadings | Gives highly correlated factors. |
| Obliquimax (Hofmann, 1970) | Yes | Early version of orthotran |  |
| Optres (Hakstian, 1972) | Yes | Uses a promax-type rotation with a salient variable target matrix | Also see Cureton, 1976. |
| Orthoblique | Yes | Generalizes an orthogonal solution to oblique; a class of rotations | Less similar to orthogonal starting solution than Promax. |
| Orthomax (Harman, 1960) | No | Combines both quartimax and varimax criteria | Gives quartimax, equamax, or varimax depending on user-set weighting of the criteria. |
| Orthotran | Yes | Heuristic search for simplest orthoblique solution |  |
| Promax | Yes | Generalizes any orthogonal solution to an oblique one with same high loadings. Factor correlations vary with user set parameter. | Efficient procedure giving good solution. |
| Quartimin (Carroll, 1957) | Yes | Minimizes sum of cross-products of squared loadings | Gives highly correlated factors |
| Quartimax | No | Simplified loadings for a variable | General plus group factors. |
| Tandem Criteria (Comrey, 1967) | Yes | Uses jointly the criteria that correlated variables should be loaded by same factors and uncorrelated variables loaded by different factors. |  |
| Varimax | No | Maximizes variance of squared loadings of a factor | The orthogonal procedure |


For more details, see
- Gorsuch, R. L. (2014). Factor analysis: Classic edition. Routledge.
- Bernaards, C. A., & Jennrich, R. I. (2005). Gradient projection algorithms and software for arbitrary rotation criteria in factor analysis. Educational and Psychological Measurement, 65(5), 676-696.
