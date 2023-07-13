# .github

This repo contains items that are shared by all repositories in the Myriad Group org.

## Workflow templates

The workflow templates are github actions that you can add to your Myriad Group org repo. These action templates rely on Myriad Group org secrets, also privately managed for you.

Instructions on using org workflow templates can be found in github docs.
[Using a workflow template from your organization](https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization#using-a-workflow-template-from-your-organization)

To use workflow templates in the private repositories, the organization must be part of an enterprise or GitHub One plan. For other plans, the workflow templates are not available to private repositories currently.


## Runing actions localy

using act:

```bash
sudo ~/bin/act --workflows .github/workflows/local.yml --s $SSH_KEY
```