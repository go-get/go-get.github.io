# ENUM

To Alter the enum created [Stackoverflow](https://stackoverflow.com/a/7834949)

## Add a value
```
ALTER TYPE enum_type ADD VALUE 'new_value'; -- appends to list
ALTER TYPE enum_type ADD VALUE 'new_value' BEFORE 'old_value';
ALTER TYPE enum_type ADD VALUE 'new_value' AFTER 'old_value';
```

## Remove a value