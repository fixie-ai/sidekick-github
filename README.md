# Fixie GitHub Sidekick

This repo has an example Fixie Sidekick that lets you query GitHub documentation,
and take action on GitHub via its GraphQL API.

To get started:

1. Create a Fixie account at https://console.fixie.ai.
2. Create a GitHub Personal Access Token at https://github.com/settings/tokens.
You **must** create a "Fine Grained" access token. Be sure to give the token
**read only** access to things you want to ask the Sidekick about -- we recommend
adding access to repository contents, issues, and pull requests, at a minimum.
3. Create a file named ```.env``` in this project.

* Add your GitHub token to the ```.env`` file as follows:

```terminal
GITHUB_TOKEN=YOUR-TOKEN-HERE
```

* Save the file.

4. Get your Sidekick up and running with:

```
npm install
npm run dev
```
