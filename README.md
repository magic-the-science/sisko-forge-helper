# sisko-forge-helper

Extra GitHub Actions runners for [sisko-forge-tests](https://github.com/michaelsabramson/sisko-forge-tests).
Each test run there starts `helper.yml` here, which plays part of the test's games on this organization's runners.
Needs the secret `MAIN_TOKEN` (fine-grained token, Contents read/write on sisko-forge-tests).
