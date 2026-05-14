# Dashboard

## Активы

```dataview
TABLE category, status, priority
FROM "Assets"
WHERE type = "asset"
SORT category
cat > Dashboard.md << 'EOF'
# Dashboard

## Активы

```dataview
TABLE category, status, priority
FROM "Assets"
WHERE type = "asset"
SORT category
```

