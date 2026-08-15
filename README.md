# markdownlint-docker

Unofficial docker distribution of markdownlint-cli based on:

* [markdownlint-cli on Github](https://github.com/igorshubovych/markdownlint-cli)
* [markdownlint-cli on NPMJS](https://www.npmjs.com/package/markdownlint-cli)

## Example of use

```bash
docker run --rm \
    --workdir /workspace \
    -v "$(pwd):/workspace" \
    goncl/markdownlint-cli:latest '/workspace/**/*.md' \
&& echo '✔  Your code looks good.'
```
