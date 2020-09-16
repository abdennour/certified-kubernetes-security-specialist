# Overview
About running https://github.com/dev-sec/cis-kubernetes-benchmark

# 1. install inspec
- For mac : `brew cask install chef/chef/inspec`
- For others: https://www.inspec.io/downloads/
- Validation: `inspec --version` (.e.g: 4.21.3)


# 2. Exec profile

`inspec exec . --controls=cis-kubernetes-benchmark-1.1.2 cis-kubernetes-benchmark-1.3.5`