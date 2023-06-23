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
- [ ] find possible correlations
- [ ] visualize results

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

## Experiments
Try these (although overkill for this task). 
- [ ] neural net for ```winpercent```