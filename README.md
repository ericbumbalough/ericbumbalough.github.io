# Eric Bumbalough Portfolio
Sample data was used for the plots utilizing non-public data. Some parameters have been renamed and units are arbitrary.

## Sample Selection Visualization

The sample selection visualization was designed to help decision makers balance multiple priorities when deciding which manufacturing lot to test next. The optimal choice would be high importance and high urgency (upper right) with a long time since last test (large diameter). Additionally, the color of the marker indicates whether the decision maker would need to obtain new batteries for testing. 

Decision makers were also given a list of Pareto optimal lots that considered even more factors to narrow their choices down.

## Bayesian Multilevel Model of Battery Aging

A Bayesian multilevel model of battery aging was built with manufacturing lot as a level. In the plots above, each line represents and equally likely simulated battery’s aging. The model is able to capture differences between lots A and B even though there are only two aged data points for each lot. The Bayesian model predicted the median 50% better than the previous model.



