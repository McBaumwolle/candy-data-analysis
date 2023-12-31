# candy-data-analysis
Data analysis on the candy-power-ranking dataset. <br>

## Dataset
The headers are 
```
competitorname, chocolate, fruity, caramel, peanutyalmondy, nougat, crispedricewafer, hard, bar, pluribus, sugarpercent, pricepercent, winpercent
```
where  ```winpercent``` is the target variable. <br>

## Tasks
- [x] setup repository
- [x] get to know data 
- [x] find possible correlations
- [x] visualize results

## Results
A simple correlation analysis with ```df.corr()``` shows the following results.
```python
winpercent          1.000000
chocolate           0.636517
bar                 0.429929
peanutyalmondy      0.406192
pricepercent        0.345325
crispedricewafer    0.324680
sugarpercent        0.229151
caramel             0.213416
nougat              0.199375
pluribus           -0.247448
hard               -0.310382
fruity             -0.380938
Name: winpercent, dtype: float64
```

<!-- more results to come -->

I also found some interesting correlations between the popularity, sugar and price of the candy.

<details><summary>Visualization</summary>

![three correlations](results/analysis_a.png)

</details>

Looking at the number of ingredients, ther are also a number of interesting correlations.

<details><summary>Visualization</summary>

![three correlations](results/analysis_b.png)

</details>

## Ideas
Further ideas to explore I did not further go into.
- [ ] Cluster Analysis (grouping of candies)
- [ ] PCA (dimensionality reduction)
- [ ] Outlier Detection (e.g. in price)
- [ ] Data Splitting (e.g. in nut types)

## Experiments
Try these (although overkill for this task). 
- [ ] neural net for ```winpercent```
- [ ] Data Augmentation (very small dataset)
