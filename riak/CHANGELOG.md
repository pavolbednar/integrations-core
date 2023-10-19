# CHANGELOG - riak

## Unreleased

## 3.3.1 / 2023-08-18 / Agent 7.48.0

***Fixed***:

* Update datadog-checks-base dependency version to 32.6.0 ([#15604](https://github.com/DataDog/integrations-core/pull/15604))

## 3.3.0 / 2023-08-10

***Added***:

* Update generated config models ([#15212](https://github.com/DataDog/integrations-core/pull/15212))

***Fixed***:

* Fix types for generated config models ([#15334](https://github.com/DataDog/integrations-core/pull/15334))

## 3.2.1 / 2023-07-10 / Agent 7.47.0

***Fixed***:

* Bump Python version from py3.8 to py3.9 ([#14701](https://github.com/DataDog/integrations-core/pull/14701))

## 3.2.0 / 2022-09-16 / Agent 7.40.0

***Added***:

* Update HTTP config spec templates ([#12890](https://github.com/DataDog/integrations-core/pull/12890))

## 3.1.0 / 2022-04-05 / Agent 7.36.0

***Added***:

* Add metric_patterns options to filter all metric submission by a list of regexes ([#11695](https://github.com/DataDog/integrations-core/pull/11695))

***Fixed***:

* Remove outdated warning in the description for the `tls_ignore_warning` option ([#11591](https://github.com/DataDog/integrations-core/pull/11591))

## 3.0.0 / 2022-02-19 / Agent 7.35.0

***Changed***:

* Add tls_protocols_allowed option documentation ([#11251](https://github.com/DataDog/integrations-core/pull/11251))

***Added***:

* Add `pyproject.toml` file ([#11426](https://github.com/DataDog/integrations-core/pull/11426))

***Fixed***:

* Fix namespace packaging on Python 2 ([#11532](https://github.com/DataDog/integrations-core/pull/11532))

## 2.4.1 / 2022-01-08 / Agent 7.34.0

***Fixed***:

* Add comment to autogenerated model files ([#10945](https://github.com/DataDog/integrations-core/pull/10945))

## 2.4.0 / 2021-10-04 / Agent 7.32.0

***Added***:

* Add HTTP option to control the size of streaming responses ([#10183](https://github.com/DataDog/integrations-core/pull/10183))
* Add allow_redirect option ([#10160](https://github.com/DataDog/integrations-core/pull/10160))
* Disable generic tags ([#10027](https://github.com/DataDog/integrations-core/pull/10027))

***Fixed***:

* Fix the description of the `allow_redirects` HTTP option ([#10195](https://github.com/DataDog/integrations-core/pull/10195))

## 2.3.0 / 2021-07-12 / Agent 7.30.0

***Added***:

* Add runtime configuration validation ([#8979](https://github.com/DataDog/integrations-core/pull/8979))

## 2.2.1 / 2021-03-07 / Agent 7.27.0

***Fixed***:

* Bump minimum base package version ([#8443](https://github.com/DataDog/integrations-core/pull/8443))

## 2.2.0 / 2020-10-31 / Agent 7.24.0

***Added***:

* Add ability to dynamically get authentication information ([#7660](https://github.com/DataDog/integrations-core/pull/7660))
* [doc] Add encoding in log config sample ([#7708](https://github.com/DataDog/integrations-core/pull/7708))

## 2.1.0 / 2020-09-21 / Agent 7.23.0

***Added***:

* Add RequestsWrapper option to support UTF-8 for basic auth ([#7441](https://github.com/DataDog/integrations-core/pull/7441))

***Fixed***:

* Update proxy section in conf.yaml ([#7336](https://github.com/DataDog/integrations-core/pull/7336))

## 2.0.0 / 2020-08-10 / Agent 7.22.0

***Changed***:

* Use requests wrapper and remove httplib2 dependency ([#7247](https://github.com/DataDog/integrations-core/pull/7247))

***Added***:

* Add config specs ([#7068](https://github.com/DataDog/integrations-core/pull/7068))

***Fixed***:

* Update logs config service field to optional ([#7209](https://github.com/DataDog/integrations-core/pull/7209))

## 1.9.0 / 2020-05-20 / Agent 7.20.0

***Added***:

* Upgrade httplib2 to 0.18.1 ([#6702](https://github.com/DataDog/integrations-core/pull/6702))

## 1.8.0 / 2020-05-17

***Added***:

* Allow optional dependency installation for all checks ([#6589](https://github.com/DataDog/integrations-core/pull/6589))

***Fixed***:

* Use Agent 6 signature ([#6448](https://github.com/DataDog/integrations-core/pull/6448))

## 1.7.1 / 2020-04-04 / Agent 7.19.0

***Fixed***:

* Update deprecated imports ([#6088](https://github.com/DataDog/integrations-core/pull/6088))
* Remove logs sourcecategory ([#6121](https://github.com/DataDog/integrations-core/pull/6121))

## 1.7.0 / 2020-01-13 / Agent 7.17.0

***Added***:

* Use lazy logging format ([#5398](https://github.com/DataDog/integrations-core/pull/5398))

## 1.6.0 / 2019-07-12 / Agent 6.13.0

***Added***:

* Add logs section ([#3995](https://github.com/DataDog/integrations-core/pull/3995))

## 1.5.0 / 2019-05-14 / Agent 6.12.0

***Added***:

* Adhere to code style ([#3563](https://github.com/DataDog/integrations-core/pull/3563))

## 1.4.0 / 2019-01-04 / Agent 6.9.0

***Added***:

* Support Python 3 ([#2774](https://github.com/DataDog/integrations-core/pull/2774))

## 1.3.1 / 2018-09-04 / Agent 6.5.0

***Fixed***:

* Add data files to the wheel package ([#1727](https://github.com/DataDog/integrations-core/pull/1727))

## 1.3.0 / 2018-06-07

***Added***:

* Package `auto_conf.yaml` for appropriate integrations ([#1664](https://github.com/DataDog/integrations-core/pull/1664))

## 1.2.0 / 2018-05-11

***Added***:

* Hardcode the 8098 port in the Autodiscovery template ([#1444](https://github.com/DataDog/integrations-core/pull/1444) for more information)

## 1.1.0 / 2017-11-21

***Added***:

* Update auto_conf template to support agent 6 and 5.20+ ([#860](https://github)com/DataDog/integrations-core/issues/860)

## 1.0.0 / 2017-03-22

***Added***:

* adds riak integration.