# AWS API Base Terraform module

Terraform module which provides foundation for creating an API on AWS.

## Usage

```hcl
module "api-base" {
  source       = "genstackio/lambda/aws"

  name         = "name-of-the-lambda"
  code_dir     = "/path/to/the/code/dir"
  package_file = "/path/to/the/package.zip"
}
```
