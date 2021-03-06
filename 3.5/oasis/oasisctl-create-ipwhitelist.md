---
layout: default
description: Description of the oasisctl create ipwhitelist command
title: Oasisctl Create Ipwhitelist
---
# Oasisctl Create Ipwhitelist

Create a new IP whitelist

## Synopsis

Create a new IP whitelist

```
oasisctl create ipwhitelist [flags]
```

## Options

```
      --cidr-range strings       List of CIDR ranges from which deployments are accessible
      --description string       Description of the IP whitelist
  -h, --help                     help for ipwhitelist
      --name string              Name of the IP whitelist
  -o, --organization-id string   Identifier of the organization to create the IP whitelist in
  -p, --project-id string        Identifier of the project to create the IP whitelist in
```

## Options inherited from parent commands

```
      --endpoint string   API endpoint of the ArangoDB Oasis (default "api.cloud.arangodb.com")
      --format string     Output format (table|json) (default "table")
      --token string      Token used to authenticate at ArangoDB Oasis
```

## See also

* [oasisctl create](oasisctl-create.html)	 - Create resources

