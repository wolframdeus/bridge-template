# bridge

**bridge** contains shared types between frontend and backend and defines,
which data both parts of application exchange

`yarn commit` - commit changes

`yarn release` - release new version of bridge 

## Development

To commit project changes `conventional-github-releaser` is used. It means,
`CONVENTIONAL_GITHUB_RELEASER_TOKEN` env variable is required. To get it, 
follow this [link](https://github.com/settings/tokens/new) and create a token
with scope `repo`. 

Then, add variable `CONVENTIONAL_GITHUB_RELEASER_TOKEN=my_token` to `.env` file.
