<h1>Select the best model for a dataset</h1>
<p>
The best way to find the best model for a given data set is
to test all models. The performance of a regression model
can be evaluated using the r2-score. The closer 
the r2-score is to 1, the better the model performs.
</p>

```python
from sklearn.metrics import r2_score

print(r2_score(y, regressor.predict(X)))
```