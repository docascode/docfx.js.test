# docfx.js.test
A simple tool to help test DocFX's template preprocessor. 

## Usage:
1. Preare the templates with `docfx template export` to get JS preprocessor. More info: https://dotnet.github.io/docfx/tutorial/howto_create_custom_template.html

2. Prepare raw model:
```
docfx --exportRawModel
```

3. Run the preprocessor in [Node](https://nodejs.org/en/) to get detailed stack trace.
```
node test {docfxJsPreprocessor} {rawModel}
```
