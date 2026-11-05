# terraform-modules

Reusable, versioned Terraform modules for kalico-labs projects (app service, database,
storage, GitHub OIDC deploy roles and similar building blocks).

Pin modules to a tag or commit:

```hcl
module "example" {
  source = "git::https://github.com/kalico-labs/terraform-modules.git//modules/<name>?ref=<commit-sha>"
}
```

## License
MIT
