# Blog

The new blog of YoderBacon.com

This blog was created with [Hugo](https://gohugo.io).

It uses the theme [Blowfish](https://themes.gohugo.io/themes/blowfish/).

## Installation and How to Use

See the [Hugo quick start guide](https://gohugo.io/getting-started/quick-start).

## Editing Locally

Start the server with `hugo server --buildDrafts`

> Note: `--buildDrafts` shows posts where `draft = true`.

## Adding a New Page

Adding a new page can be done with the `hugo` CLI:

```shell
hugo new content posts/[folder]/index.md
```

## Publishing

1. Change `draft = true` to `draft = false`

2. Create a new build

    ```shell
    hugo
    ```

3. Commit and push all files

    ```shell
    git add -A
    git commit -m "Blog updates"
    git push
    ```
