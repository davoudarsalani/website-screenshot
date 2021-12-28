# Take a screenshot of websites currently only using [capture-website-cli](https://github.com/sindresorhus/capture-website-cli)
<div align='center'>
<img alt='last-commit' src='https://img.shields.io/github/last-commit/davoudarsalani/website-screenshot?&labelColor=black&color=grey&style=flat'>
<img alt='commit-activity' src='https://img.shields.io/github/commit-activity/m/davoudarsalani/website-screenshot?&labelColor=black&color=grey&style=flat'>
</div>
<br>

```yml
- name: Taking screenshot
  uses: ./.github/actions/capture-website-cli
  with:
    url: ${{ env.url }}
    name: ${{ env.photo_name }}
    TELEGRAM_TOKEN: ${{ secrets.TELEGRAM_TOKEN }}
    TELEGRAM_TO: ${{ secrets.TELEGRAM_TO }}
```
