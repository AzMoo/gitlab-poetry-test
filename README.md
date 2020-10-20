# Gitlab Runner Poetry Failure Test

Repo that replicates the error described at https://github.com/python-poetry/poetry/issues/3199

# How to make it happen
1) Install the gitlab runner as described here: https://docs.gitlab.com/runner/install/. I've replicated this on CentOS, debian and MacOS so host OS probably isn't a big deal.
2) Clone the repo

```
git clone https://github.com/AzMoo/gitlab-poetry-test.git
```

3) Run the gitlab runner

```
gitlab-runner exec docker test
```

