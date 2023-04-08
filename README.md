# Terraform 

## :computer: instalação - Terraform Amazon Linux

Instalacão
```bash
https://learn.microsoft.com/pt-br/ef/core/cli/powershell
```

⚡ MultiCloud com DevOps 
## 🛠 Provisionar Bucket no S3 AWS - Executando o arquivo main.tf

1. No terminal da AWS opçao action efetuar o upload do arquivo "main.tf"  👋
2. Depois do upoload do Arquivo iremos executar comando do "Terraform "  👋

```bash
  terraform init
  terraform plan
  terraform apply
```

```bash
Tornar o Bucket Privado
```
```bash
  resource "aws_s3_bucket_public_access_block" "s3_block" {
  bucket = aws_s3_bucket.s3_bucket.id

  block_public_acls       = true
  block_public_policy     = true
  ignore_public_acls      = true
  restrict_public_buckets = true
}
```
