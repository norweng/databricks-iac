# databricks-iac
databricks instantiation on aws based fom https://registry.terraform.io/providers/databrickslabs/databricks/latest/docs

## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_databricks"></a> [databricks](#provider\_databricks) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [databricks_job.this](https://registry.terraform.io/providers/hashicorp/databricks/latest/docs/resources/job) | resource |
| [databricks_notebook.this](https://registry.terraform.io/providers/hashicorp/databricks/latest/docs/resources/notebook) | resource |
| [databricks_current_user.me](https://registry.terraform.io/providers/hashicorp/databricks/latest/docs/data-sources/current_user) | data source |
| [databricks_node_type.smallest](https://registry.terraform.io/providers/hashicorp/databricks/latest/docs/data-sources/node_type) | data source |
| [databricks_spark_version.latest](https://registry.terraform.io/providers/hashicorp/databricks/latest/docs/data-sources/spark_version) | data source |

## Inputs

No inputs.

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_job_url"></a> [job\_url](#output\_job\_url) | n/a |
| <a name="output_notebook_url"></a> [notebook\_url](#output\_notebook\_url) | n/a |
