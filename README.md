# AWS VPC module for Terraform

A lightwieght module for Terraform.

## Usage

module "vpc" {
    source = "github.com/kylemartin901/tf_vpc"
    name = "vpc_name"
    cidr = "10.0.0.0/16"
    public_subnet = "10.0.1.0/24"
}

See `interface.tf` for additional configuration variables."

## License

MIT