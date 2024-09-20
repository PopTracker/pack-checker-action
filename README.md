# PopTracker pack-checker action

Action to automate PopTracker pack checking / schema validation.


## Usage

```yaml
    steps:
      - uses: PopTracker/pack-checker-action@v1
```

or

```yaml
    steps:
      - uses: PopTracker/pack-checker-action@v1
        with:
          strict: true
          schema: path/to/schema
          pack: path/to/pack
          check-legacy-compat: true
```
