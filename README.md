# WAF + Shield + CloudFront Protection

**Layered edge security. Auto-integrated. Globally distributed.**

This Terraform module deploys an AWS WAF Web ACL, attaches it to a CloudFront distribution, and sets the stage for Shield Advanced integration.

---

## ✅ Features

- Deploys WAFv2 with AWS Managed Rules  
- Protects CloudFront distribution at the edge  
- Automatically enforces HTTPS  
- Global content delivery  
- Modular and tag-ready

---

## ☁️ Tech Stack

- **Cloud**: AWS  
- **IaC**: Terraform  
- **Security Services**: WAFv2, CloudFront, Shield (optional)

---

## 🚀 Usage Example

```hcl
module "edge_protection" {
  source        = "./modules/waf_shield_cloudfront"
  origin_domain = "my-backend.example.com"
  tags = {
    Owner       = "SecurityTeam"
    Environment = "prod"
  }
}
```

---

### [Deploy Global Protection →](https://opscontractordev.super.site)

*Generated on 2025-05-22 by The Contractor.*
