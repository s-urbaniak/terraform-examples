## terraform-examples

This is a very simple (and most probably incomplete) tool to generate example terraform.tfvars from files or stdin with variable declarations.

## Installation

  - `go get github.com/s_urbaniak/terraform-examples`
  - `cd terraform-examples`
  - `go install`
  
  It should be noted that GOBIN will need set prior to running go install otherwise it will fail.

## Usage
```
$ usage: terraform-example [-|<FILE>...]
