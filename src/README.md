# Parametrising clusters as Terraform modules

You can provision development EKS cluster with a single `terraform apply`:

```bash
terraform init
terraform plan
terraform apply
```

It might take a while for the cluster to be creates (up to 15-20 minutes).

At the end you will have:

1. A cluster for development.
2. NGINX+ Controller Instance
