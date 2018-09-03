<p><img src="http://1000logos.net/wp-content/uploads/2017/07/Logo-Docker-500x394.jpg" alt="docker logo" title="docker" align="right" height="60" /></p>

# Ansible-Role-Syslog-Generator

Deploy Syslog-Generator for SPLUNK as Docker Image

## Requirements

 - Ansible >= 2.4

## Role Variables


| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| `syslog_gen_rsyslog` | syslog-gen-rsyslog  | Name of the Container |
| `syslog_gen_hec` | syslog-gen-hec  | Name of the Container |
| `syslog_gen_image` | stackware/sysgen:1.6| Docker Image (incl.tag) |
| `syslog_gen_syslog` | "true" | Syslog-Generator with RSYSLOG as Provider |
| `syslog_gen_syslog` | "true" | Syslog-Generator with RSYSLOG as Provider |
| `hec_token` | "abcd-efgh-123ada-0815" | HEC Token - If defined - Syslog-Generator with HEC as Provider|


## Author Information

You can find me on Twitter: [@itkombinat](https://twitter.com/itkombinat)
