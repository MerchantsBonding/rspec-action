# RSpec Composite Action

This action includes the checkout action, the setup ruby action and the step to run RSpec tests.

## Usage
Add the below to your GitHub Workflow file
```yml
steps:
  - name: RSpec
    uses: merchantsbonding/rspec-action@master
    env: #Add ENV's specific to your repo
      MBC_CRYPTO_PASSWORD: foo
```
