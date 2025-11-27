# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/3.1.0...3.2.0) - 2025-11-27

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`a754de5`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/a754de554f6521b0a2e8993f021b8bfa418e1963)

## [3.1.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`950b78b`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/950b78b2754fad8ea8defd10084639a034155216)
- add oraclelinux10 support + lint and core fixes [`fe16250`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/fe16250e5f8b688d319ed57ba18b685424d3eb16)
- add trixie (debian13) support [`707d775`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/707d77574f6bc4f7a6e52d797d899a1b942355e4)

## [3.0.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/2.1.0...3.0.0) - 2025-10-24

### Commits

- update core, molecule + gitlab-ci [`37e2ce6`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/37e2ce639f740a6c8811d38bd26c7a5d06446129)
- changes on molecule [`d60e624`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/d60e624700b9aa6e075641f2ddcd421f4253bb55)
- upgrade to last release [`06a0a53`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/06a0a535c546aff94cbf1ee50b53d784545df4c2)
- remove task for redhat7 [`6e4bf04`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/6e4bf04419df26b081b187d0e8182278885b868c)

## [2.1.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/2.0.0...2.1.0) - 2024-09-07

### Commits

- add version on molecule play image to maintain support on old release [`200cd06`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/200cd065a183ec80d203666bc71376d09936e0c9)
- remove support for debian10 / ubuntu18 / redhat8 [`90f0f31`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/90f0f31b26e1eec7b943ff1c8d6d09e7ce4dfc28)
- update molecule [`090db08`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/090db08d7f5534da86b39f5157c4cd6e60c66210)
- remove rocky support [`296a832`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/296a832cf3af952ba326466654ce6016a39a16ea)
- remove redhat molecule checks [`e829655`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/e829655484f31c7a5707edeb631b26373816cb27)
- sort testing distrib to avoid random changes [`e552c29`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/e552c2949e2569b53b0cc4447f5993bf8f6fe728)
- update pre-commit and lint fix [`bd54e10`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/bd54e1008930e394afd8bc8d19963b9547748953)
- remove support for rhel7 and docker dind on gitlab [`5c114b1`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/5c114b154b319fdc956b3c81ecb7a3194122521a)
- remove unsupported rhel7 [`5450e3c`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/5450e3ccdfdad54cdf18b899438edc1b34a4390a)
- add retries on packages install, to avoid error if temp pkg lock [`5006843`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/5006843c33f444a4f5e95b6bcd42c82396d25743)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`af0b303`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/af0b3035859788853779afc2aa2674921316f0fc)
- remove precommit gitlab [`2ed356a`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/2ed356a3e43bcc0bc85ca6a3f885cc014b048805)
- update readme + precommit + include vars [`1063f93`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/1063f93ba69a47be14658ac0df03dfb50a6ce588)
- rename template files [`dbc4e6f`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/dbc4e6fea10b4cddae893c269dd90018ef2d3066)
- fix vars [`4d7b4d4`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/4d7b4d4edf55ae00e3bb6ff36719d567981cbf15)
- remove ubuntu18 support [`3e1dc92`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/3e1dc92f6384a1ebbe9c6d2f7684d7339ca1b7dd)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`fcb7cc4`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/fcb7cc4cd919ba28db5adc58743035cc8eb020e5)
- add precommit for lint [`b0d790b`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/b0d790b25dc052d5eec2647dcdeac76bd656b883)
- fix checks [`8d93d4f`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/8d93d4fc2e6533c3debc5c93ec8f7bce8102350d)
- add new molecule all scenario [`5f875d2`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/5f875d20e57e1aa06f4db174adda3cd6fabf05f2)
- split distro for molecule tests on ci [`23538de`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/23538ded3e9086033b5899f5751876e7e84fb2b1)
- update checks and Readme [`5cc4771`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/5cc4771e7b6b251fc03e31a8870095605eda6e31)
- remove verify [`a479c58`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/a479c58286efa5ea20bf1034485f4cb6b7d3efbc)
- fix checks [`e4ae3a0`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/e4ae3a0dc4a28549f1cebd464d5b62af4cf1c6b1)
- change dnf to yum for major7 compatibility [`8d3b3d0`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/8d3b3d0d6fffb94125bb8d36306a6d2c8687e6f7)

## [0.3.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`1b01840`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/1b01840e1e7acfe9a673ab1d18de02854ac693a2)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/compare/0.1.0...0.2.0) - 2022-06-27

### Commits

- minor: add oracleLinux support + little fixes [`5bbb97d`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/5bbb97dac2054f9bffaf0dea24c113714fb514f2)
- fix: remove unsupported centos8 + minor fixes [`5245451`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/52454511d7c8e0834dabac98f5540290ed3ce32d)
- fix: Changes on README + molecule container names [`7a03ea2`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/7a03ea2ef0c259270da71921097370ad9454040c)

## 0.1.0 - 2021-11-16

### Commits

- fix: add role name on molecule container names to avoid concurrent conflict on runners [`10ae040`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/10ae040c5138c5f3254bf3608ebe10ae8eb626cf)
- minor: add changelog + automatic files checks [`129ea7c`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/129ea7c6161ba873379d8b79f6701dd6b0b32a1a)
- initial commit [`cefb200`](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/commit/cefb2007ad6820d01e9faa303c30a12d84250f73)
