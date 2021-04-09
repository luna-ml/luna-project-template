# Luna ML Project Template

You can create a repository setup for [Luna ML](https://github.com/luna-ml/luna) Project from this template.
See the [Quickstart](https://luna-ml.github.io/luna/quickstart/index.html) guide for more details.

This template includes two Github workflows

| Workflow | Description      |
| -------- | ---------------- |
| [pullrequest.yml](https://github.com/luna-ml/luna-project-template/blob/main/.github/workflows/pullrequest.yml) | Run on Pull Request to validate Luna ML Project and model changes|
| [submit.yml](https://github.com/luna-ml/luna-project-template/blob/main/.github/workflows/submit.yml) | Run on Pull Request merge (push to 'main') to sync changes with Luna ML Server and trigger evaluation on server |
