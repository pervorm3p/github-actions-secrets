## Using encrypted secrets in GitHub Actions

You can use secrets within GitHub Actions to prevent any sensitive information to leak anywhere in your CI/CD pipelines.

You can have secrets at three levels:

- Repository
- Environment
- Organization

### Test the action

After cloning this repository navigate to your repository settings and create a secret named `MY_SECRET` with the value `repo secret`. Then select manage environments and create an environment named `Dev`, then navigate back and create an environment secret with the same name `MY_SECRET` and this time set the value `env secret`.

Modify the README and navigate to the actions to see the results.

Add changes

__my_changes___
