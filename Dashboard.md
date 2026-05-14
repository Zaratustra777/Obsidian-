# Dashboard

## Активы

```dataview
TABLE category, status, priority, monthlyPay, comments
FROM "Assets"
WHERE type = "asset"
SORT category
```
