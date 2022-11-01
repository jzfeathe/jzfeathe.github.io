I would begin with backward elimination for speed and convenience. Since the smallest model that fits the data is generally considered the best option,
I would use this method to remove terms and check Adjusted R<sup>2</sup> to see if I'm satisfied with the results. If not (or if I'm interested in doing 
comparison), I would use criterion-based procedures as discussed in the 
[article from John Hopkins University](https://www.biostat.jhsph.edu/~iruczins/teaching/jf/ch10.pdf). As suggested in the article, I would try testing
Mallow's Cp because this statistic gives us the average MSE of prediction. If a predictor is to be used in the model, a Mallow's Cp value that is lower
than p will let us know that the predictor in question is a good fit. This statistic is easy to compute and is closely related to Adjusted R<sup>2</sup>
and AIC, which are also commonly used criteria for fitting models.
