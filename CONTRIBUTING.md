# Contributing

Thanks for helping keep this guide accurate.

## Reporting a change

GitHub changes achievements without announcing it. If something in the README is wrong or outdated, open an [achievement correction](https://github.com/NiraphatK/achievements-playground/issues/new?template=correction.yml) issue and include evidence, such as a link to a profile, a GitHub blog post, or a community discussion.

Ask questions in [Discussions](https://github.com/NiraphatK/achievements-playground/discussions/categories/q-a), not in issues.

## Pull requests

1. Keep each pull request to one topic.
2. Update both `README.md` and `README.th.md`. If you cannot write Thai, say so in the pull request and the maintainer will translate.
3. Link to a source for any claim about how an achievement is earned.
4. Make sure the **Docs** workflow passes. It runs markdownlint and a link check.

To run the checks locally:

```sh
npx markdownlint-cli2 "**/*.md"
lychee --config lychee.toml "**/*.md"
```

## Do not

- Open pull requests or issues here only to earn achievements. Practice in your own repository instead. The Quickdraw issue template is the only exception.
- Ask people to star, answer, or co-author for achievements.

By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
