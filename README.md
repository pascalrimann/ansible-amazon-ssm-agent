# amazon-ssm-agent


Ansible role to install Amazon SSM Agent.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [amazon_ssm_agent_package](#amazon_ssm_agent_package)
  - [amazon_ssm_agent_version](#amazon_ssm_agent_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### amazon_ssm_agent_package

Download URL for the package to install

#### Default value

```YAML
amazon_ssm_agent_package: https://s3.amazonaws.com/ec2-downloads-windows/SSMAgent/{{
  amazon_ssm_agent_version }}/debian_amd64/amazon-ssm-agent.deb
```

### amazon_ssm_agent_version

Version of the release to install

#### Default value

```YAML
amazon_ssm_agent_version: latest
```

## Discovered Tags

**_amazon-ssm-agent_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Pascal Rimann](https://github.com/pascalrimann)
