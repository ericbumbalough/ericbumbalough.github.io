
Sample data was used for the plots utilizing non-public data. Some parameters have been renamed and units are arbitrary.

## Sample Selection Visualization
![Sample Selection Visualization](/img/SampleSelectionVisualization.png)

The sample selection visualization was designed to help decision makers balance multiple priorities when deciding which manufacturing lot to test next. The optimal choice would be high importance and high urgency (upper right) with a long time since last test (large diameter). Additionally, the color of the marker indicates whether the decision maker would need to obtain new batteries for testing. 

Decision makers were also given a list of Pareto optimal lots that considered even more factors to narrow their choices down.

## Bayesian Multilevel Model of Battery Aging
![Bayesian Multilevel Model of Battery Aging](/img/BayesMLleft.png =75%x)![Bayesian Multilevel Model of Battery Aging](/img/BayesMLright.png =75%x)

A Bayesian multilevel model of battery aging was built with manufacturing lot as a level. In the plots above, each line represents and equally likely simulated battery’s aging. The model is able to capture differences between lots A and B even though there are only two aged data points for each lot. The Bayesian model predicted the median 50% better than the previous model.

## Bayesian Piecewise Linear Model of New Battery Performance
![Bayesian Piecewise Linear Model of New Battery Performance](/img/piecewise.png)

The piecewise linear model above can capture step changes in the manufacturing of batteries (i.e. new machinery or process) and drifts (i.e. tool wear).

This model could be combined with the multilevel model above to improve lot-to-lot variation modeling.

Change point detection is currently manual, but it will be automated in the future.

## Heatmap of Predictions with Accuracy
![Heatmap of Predictions with Accuracy](/img/heatmap.png)

This plot was designed to communicate predictions and predictive accuracy of various battery aging models to technical audiences.

Color indicates the value of the prediction, and the size of the marker represents the predictive accuracy. The additional whitespace around lower accuracy areas intuitively reduces their importance.


## Other Visualizations
![Temperature Records](/img/CourseraWeatherGraphAssignment.jpg)


![Interactive Bar Graph](/img/Interactiveplot-barcoloring.gif)


