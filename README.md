# Azure - Subscription Data Module

## Introduction

This module will return data about a specific Azure subscription<br />

<!--- BEGIN_TF_DOCS --->
## Providers

| Name | Version |
|------|---------|
| azurerm | >= 2.0.0 |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:-----:|
| subscription\_id | Subscription ID that you wish to lookup | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| output | Azure subscription |
<!--- END_TF_DOCS --->