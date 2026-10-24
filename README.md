# PopTracker pack-checker action

Action to automate PopTracker pack checking / schema validation.


## Usage

```yaml
    steps:
      - uses: actions/checkout@v7
      - uses: PopTracker/pack-checker-action@v1
```

or

```yaml
    steps:
      - uses: actions/checkout@v7
      - uses: PopTracker/pack-checker-action@v1.7
        with:
          strict: true
          schema: path/to/schema
          pack: path/to/pack
          check-legacy-compat: true
          validate-external: true
```
