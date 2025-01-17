## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_helm"></a> [helm](#provider\_helm) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [helm_release.ambassador](https://registry.terraform.io/providers/hashicorp/helm/latest/docs/resources/release) | resource |
| [helm_release.manifests](https://registry.terraform.io/providers/hashicorp/helm/latest/docs/resources/release) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_dns_provider"></a> [dns\_provider](#input\_dns\_provider) | DNS provider for cert-manager issuer; either clouddns or cloudflare by default | `string` | `"clouddns"` | no |
| <a name="input_tls_contexts"></a> [tls\_contexts](#input\_tls\_contexts) | Map from TLSContext name (all must be unique) to domain name for ambassador/emissary to host | `map(string)` | n/a | yes |

## Outputs

No outputs.
