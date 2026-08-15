# markdownlint-docker

Example of use:

```bash
docker run --rm \
    --workdir /workspace \
    -v "$(pwd):/workspace" \
    goncl/markdownlint-cli:latest '/workspace/**/*.md' \
&& echo '✔  Your code looks good.'
```
