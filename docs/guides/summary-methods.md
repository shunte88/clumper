
The `Clumper` object also offers useful methods that aren't verbs. In
particular there's a lovely set that can calculate summaries on keys.
Each of these methods has a string equivalent that is used in `.agg()`
when making aggregations. Here's a few common ones.

## Common Examples

### `.mean()`

You can calculate the mean of values for which a key exists.

![](../img/mean.png)

### `.count()`

You can count the number of rows for which a key exists.

![](../img/count.png)

### `.unique()`

You can retreive all unique values for a certain key.

![](../img/unique.png)

### `.n_unique()`

You can the number of unique values for a certain key.

![](../img/nunique.png)

### `.sum()`

You can calculate the sum of values for which a key exists.

![](../img/sum.png)

### `.min()`

You can calculate the minimum of values for which a key exists.

![](../img/min.png)

### `.max()`

You can calculate the maximum of values for which a key exists.

![](../img/max.png)

## More?

If you'd like to see more information these methods check the API
of the `Clumper` object. That's where you'll find them.