## 2017-09-01 - Release v. 0.10.0

- Update version requirements for `puppetlabs/stdlib`
- Update version requirements for `puppetlabs/apt`

## 2017-01-28 - Release v. 0.9.0

 - Use Puppet 4 data types
 - Run apt update before installing packages

## 2016-11-06 - Release v. 0.8.0

 - Add param `plugins`
 - Add param `configs`
 - Remove deprecated params `plugin_names`, `plugin_ensure`, `plugin_source`,
   `plugin_provider`, `plugin_install_options`

## 2016-10-13 - Release v. 0.7.0

 - Add param `service_provider` (@larsks)
 - Plugin version can be specified (@denis-sorokin)
 - Add params `config_path` and `plugin_provider` (@paramite)
 - Add params `config_owner` and `config_group` (@MartinMeinhold)
 - Deprecate param `plugin_names`
 - Deprecate param `plugin_ensure`
 - Deprecate param `plugin_source`
 - Deprecate param `plugin_provider`
 - Deprecate param `plugin_install_options`

## 2016-04-20 - Release v. 0.6.1

 - Remove rubygems package
 - Fix the issue with Ruby load path

## 2016-04-11 - Release v. 0.6.0

 - Rework config generation

## 2016-03-23 - Release v. 0.5.1

 - Use fully qualified param names (@tosmi)

## 2016-02-20 - Release v. 0.5.0

 - Add param `plugin_install_options` (@dembaca)

## 2016-02-03 - Release v. 0.4.0

 - Support CentOS 6

## 2016-01-22 - Release v. 0.3.2

 - Purge unmanaged config files
 - Manage td-agent.conf file with a fully qualified path (@EmilienM)
 - Fix the issue with td-agent service being enabled on each run on EL7

## 2015-12-02 - Release v. 0.3.1

 - Add param `repo_desc`

## 2015-10-28 - Release v. 0.3.0

 - Remove class `fluentd::config`
 - Add defined type `fluentd::config`
 - Add defined type `fluentd::plugin`

## 2015-10-22 - Release v. 0.2.0

 - Add param `service_manage`
 - Add param `repo_gpgkeyid`
 - Add param `repo_install`
 - Add param `plugin_source`
 - Rename param `repo_baseurl` to `repo_url`
 - Remove param `config_template`
 - Param validation
 - Support Ubuntu 14.04
 - Support Debian 7.8
 - Support nested config tags

## 2015-10-19 - Release v. 0.1.0

 - Initial release
