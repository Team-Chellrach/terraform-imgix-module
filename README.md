# Terraform Module for Imgix Integration

This module is developed and maintained by [Team Chellrach](https://github.com/Team-Chellrach) to simplify integration with Imgix CDN services using Terraform.

## 🚀 Features
- Easy deployment of Imgix image delivery settings
- Supports linking to S3/GCS as sources
- Configurable custom domains, secure tokens, etc.

## 📦 Usage

```hcl
module "imgix" {
  source  = "github.com/Team-Chellrach/terraform-imgix"

  source_name = "my-source"
  domain      = "images.mysite.com"
  secure_token = "your_secure_token"
}
