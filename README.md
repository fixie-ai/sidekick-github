# Fixie GitHub Sidekick

This repo has an example Fixie Sidekick that lets you query GitHub documentation,
and take action on GitHub via its GraphQL API.

To get started:

1. Create a Fixie account at https://console.fixie.ai.
2. Create a GitHub Personal Access Token at https://github.com/settings/tokens.
3. Create the file `.env` in this directory, containing:
```
GITHUB_TOKEN=<Your Github Token>
```
Then, you can run:

```
$ npm install
$ npm run dev
```
