[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)
# DEPRECATED

This is no longer supported, please consider using [IONOS Cloud Terraform Provider](https://github.com/ionos-cloud/terraform-provider-ionoscloud) instead.

# Terraform Provider for ProfitBricks

The official repository is located here:

[https://github.com/terraform-providers/terraform-provider-profitbricks](https://github.com/terraform-providers/terraform-provider-profitbricks)

## Getting Started

The Terraform Provider for ProfitBricks is currently available through Terraform. The provider must first be defined as a provider or resource block within a Terraform config file. For example, `main.tf`:

    provider "profitbricks" {
      username = "profitbricks_username"
      password = "profitbricks_password"
      retries  = 100
    }

Terraform `init` will now automatically download the latest provider binary.

    terraform init

## Documentation

The [ProfitBricks Provider Documentation](https://www.terraform.io/docs/providers/profitbricks/index.html) will offer more details on provider configuration and resources.

## Support and Contributions

Please report any issues [here](https://github.com/terraform-providers/terraform-provider-profitbricks/issues) or feel free to ask questions at the [ProfitBricks DevOps Central](https://devops.profitbricks.com/community/) Community.
