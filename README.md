# cf-terraforming-docker

https://hub.docker.com/r/adrienbrault/cf-terraforming

```
$ docker run -it --rm adrienbrault/cf-terraforming
cf-terraforming is an application that allows Cloudflare users
to be able to adopt Terraform by giving them a feasible way to get
all of their existing Cloudflare configuration into Terraform.

Usage:
  cf-terraforming [command]

Available Commands:
  access_application     Import Access Application data into Terraform
  access_policy          Import Access Policy data into Terraform
  access_rule            Import Access Rule data into Terraform
  account_member         Import Account Member data into Terraform
  all                    Import all Cloudflare resources into Terraform
  custom_pages           Import Custom Pages data into Terraform
  filter                 Import Filter data into Terraform
  firewall_rule          Import Firewall Rule data into Terraform
  help                   Help about any command
  load_balancer          Import a load balancer into Terraform
  load_balancer_monitor  Import a load balancer monitor into Terraform
  load_balancer_pool     Import a load balancer pool into Terraform
  page_rule              Import Page Rule data into Terraform
  rate_limit             Import Rate Limit data into Terraform
  record                 Import Record data into Terraform
  spectrum_application   Import a spectrum application into Terraform
  version                Print the version number of cf-terraforming
  waf_rule               Import WAF Rule data into Terraform
  worker_route           Import a worker route into Terraform
  worker_script          Import a worker script into Terraform
  zone                   Import zone data into Terraform
  zone_lockdown          Import Zone Lockdown data into Terraform
  zone_settings_override Import Zone Settings Override data into Terraform

Flags:
  -a, --account string        Use specific account ID for import
  -c, --config string         config file (default is $HOME/.cf-terraforming.yaml)
  -e, --email string          API Email address associated with your account
  -h, --help                  help for cf-terraforming
  -k, --key string            API Key generated on the 'My Profile' page. See: https://dash.cloudflare.com/?account=profile
  -l, --loglevel string       Specify logging level: (trace, debug, info, warn, error, fatal, panic)
  -o, --organization string   Use specific organization ID for import
  -s, --tfstate               Export tfstate for the given resource instead of HCL Terraform config (default)
  -v, --verbose               Specify verbose output (same as setting log level to debug)
  -z, --zone string           Limit the export to a single zone (name or ID)

Use "cf-terraforming [command] --help" for more information about a command.

```
