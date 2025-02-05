# CHANGELOG

## 0.3.17

* added different error codes for each error on puppet_last_run.sh
* added chek to review if puppet agent was manualy disabled on puppet_last_run.sh

## 0.3.16

* added support for **Ubuntu 20.04**

## 0.3.14

* added description for cron-based and agent base agents

## 0.3.13

* Added resource report to snmpd's puppetlr check
* Improved **check_last_puppet_run** performance data report

## 0.3.12

* Improved **check_last_puppet_run**
* Added snmpd compatible last run check

## 0.3.10

* added support for **RHEL 8**

## 0.3.9

* Added ssldir option to **puppet::agent::cron**

## 0.3.8

* bugfix for **Debian 10**/**Rapbian 10**

## 0.3.5

* added support for **Debian 10**

## 0.3.4

* added **puppet::agent::cron**

## 0.3.3

* added **noop** to **puppet::agent**

## 0.3.2

* added runinterval setting for **puppet::agent**

## 0.3.1

* bugfix

## 0.3.0

* environment variable for puppet agent

## 0.2.3

* added support for **SLES11SP4**

## 0.2.2

* added support for **SLES11SP3**

## 0.2.1

* added option to disable management of puppet agent's configuration

## 0.2.0

* updated to **puppet 5**
* Added SLES12SP3 support
* **puppet::client** renamed to **puppet::agent**
* added **puppet::client** compatibility class that translats variables to **puppet::agent**

## 0.1.27

* added Ubuntu 18.04 support

## 0.1.26

* improved nagios check: **check_last_puppet_run** and moved to the files directory

## 0.1.25

* added service_enable varible to **puppet::client**

## 0.1.24

* Ubuntu 16.04 support

## 0.1.23

* bugfix **check_last_puppet_run**

## 0.1.22

* added **check_last_puppet_run**
