# Cloud Cleaner

Cloud Cleaner is a tool to assist in removing resources from public clouds. Currently only AWS accounts are supported.

## How It Works

Cloud Cleaner users [terraformer](https://github.com/GoogleCloudPlatform/terraformer) to generate terraform code and state and then destroy the resources.
