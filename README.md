# Take a screenshot of websites currently only using [capture-website-cli](https://github.com/sindresorhus/capture-website-cli)

```yml
- name: Taking screenshot
  uses: ./.github/actions/capture-website-cli
  with:
    url: ${{ env.url }}
    name: ${{ env.photo_name }}
```
