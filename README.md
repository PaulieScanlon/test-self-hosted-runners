# test-self-hosted-runners

# test-self-hosted-runner-action-runner | repo

## Setup

Use the ARM64 setup option from GitHub. This avoids compatibility issues, ensures better performance, and prevents installation errors like the `brew` issues.

## Getting Started

Run the following to start the runner

```
./run.sh
```

Now check the Actions > runners section in the [repository](https://github.com/PaulieScanlon/test-self-hosted-runners/settings/actions/runners)

It should say `idle`

To kill the service in your terminal run us `ctrl + c`
