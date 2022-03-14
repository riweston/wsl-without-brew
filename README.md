# wsl-without-brew

## Overview

This repo is a place to capture my regular dev tooling in an environment where I can't use brew and have to get compiled binaries straight from the source, everything is deployed with ansible and tested with molecule.

## Quickstart

```shell
ansible-galaxy install -r requirements.yml

ansible-playbook main.yml
```

# Testing

All tests in `./packages/molcule/default/verify.yml`

```shell
molecule test
```
