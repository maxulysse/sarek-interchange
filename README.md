# Sarek Interchange

Metro map of the nf-core pipelines and resources that feed nf-core/sarek or use its results: https://maxulysse.github.io/sarek-interchange/

Everything lives in `index.html`. Stations are in `S`, handoffs (lines) in `E`:

- `line`: `reads` (input data), `res` (resources) or `out` (results out)
- `st`: `native` (both ends support it), `reshape` (samplesheet built by hand) or `planned`

Changes go through pull requests. The Render workflow loads the page in headless Chrome and fails on script errors.
