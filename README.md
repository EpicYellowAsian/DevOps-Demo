name: Demo workflow

on: workflow_dispatch

jobs: 
  print-stuff: 
    runs-on: ubuntu-latest
    steps: 
      - uses: actions/checkout@v4
      - run: pwd
      - run: ls
