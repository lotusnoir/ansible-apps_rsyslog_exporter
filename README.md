# ansible-apps_rsyslog_exporter

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_rsyslog_exporter-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_rsyslog_exporter)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_rsyslog_exporter.svg)](https://github.com/lotusnoir/ansible-apps_rsyslog_exporter/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_rsyslog_exporter?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56111)](https://galaxy.ansible.com/lotusnoir/apps_rsyslog_exporter)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56111)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)


Deploy [rsyslog_exporter](https://github.com/momorientes/rsyslog_exporter) to expose rsyslog metrics to prometheus.

## Role variables

| Name                     | Default Value                | Description                           |
| ------------------------ | ---------------------------- | --------------------------------------|
| `rsyslog_exporter_port` | 9120                         | port to expose prometheus metrics     |
| `rsyslog_web_url`       | https://rsyslog.example.net | web url of the rsyslog application   |

## Examples

	---
	- hosts: apps_rsyslog_exporter
	  become: yes
	  become_method: sudo
	  gather_facts: yes
	  roles:
	    - role: ansible-apps_rsyslog_exporter
	  environment: 
	    http_proxy: "{{ http_proxy }}"
	    https_proxy: "{{ https_proxy }}"
	    no_proxy: "{{ no_proxy }}


## Grafana Dashboard

You can find a grafana dashboard [here](https://grafana.com/grafana/dashboards/13556)


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.
