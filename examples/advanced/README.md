# Advanced Example

This example demonstrates a complete Alibaba Cloud Private Zone setup with multiple DNS record types, VPC attachment with explicit region, and tags.

## Usage

To run this example:

```bash
terraform init
terraform plan
terraform apply
```

To remove the resources:

```bash
terraform destroy
```

## Cost

Note that this example may create resources that incur costs. Run `terraform destroy` when you no longer need these resources.

## Resources Created

- 1 Private Zone with remark and tags
- 1 VPC attachment with explicit region
- Multiple DNS records (A, CNAME, MX, TXT)
