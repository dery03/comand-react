name: dery gilang

on: [react]

jobs:
  build:

    runs-on: Toll-G

    steps:
    - uses: dery03/Checkout@1/toll-G
    - name: Run a one-line script
      run: echo Hello, world!
    - name: Run a multi-line script
      run: |Hello world

        echo Add other actions to build,
        echo test, and deploy your project.
