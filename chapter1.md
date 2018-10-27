---
title: 'Selecting Data in SQL'
description: 'This is a template chapter.'
---

## Column Selection

```yaml
type: NormalExercise
key: 6cbf507732
lang: sql
xp: 100
skills: 1
```

Do some data science.

`@instructions`
Here, We learn simply to show the table

`@hint`
use * for select all.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{sql}
/* 
select *
from table
*/





```

`@solution`
```{sql}
SELECT title FROM films;
```

`@sct`
```{python}
Ex().check_column('title').has_equal_value()
```
