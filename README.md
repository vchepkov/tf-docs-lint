# tf-docs-lint

Demonstrate out of date version

Documentation is not present, terraform-docs detects it
```
$ terraform-docs markdown --lockfile=false --output-check=true --output-file README.md .
Error: README.md is out of date
```

Hook does not

<!-- BEGIN_TF_DOCS -->
<!-- END_TF_DOCS -->
