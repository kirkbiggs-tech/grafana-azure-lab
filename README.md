# Grafana and Azure Data Explorer Lab

A hands-on monitoring and visualization lab built with Grafana, Ubuntu Server, VMware Workstation, and Azure Data Explorer.

## Project Overview

This project documents my progress building a home lab for learning industrial data monitoring, visualization, and troubleshooting.

The lab is designed to develop skills relevant to process technology and industrial data systems, including Grafana, Azure Data Explorer, Aspen InfoPlus.21, Linux administration, and time-series data.
## Dashboard Preview

![Grafana process monitoring dashboard](screenshots/process-monitoring-dashboard.png)

This dashboard visualizes simulated industrial process data, including reactor temperature, feed flow, pump status, and a gauge measurement.
## Lab Architecture

```text
Home PC
   |
VMware Workstation
   |
Ubuntu Server 24.04 LTS
   |
Grafana Server
   |
Azure Data Explorer
   |
Dashboards and Visualizations
```

## Technologies Used

* Grafana
* Ubuntu Server 24.04 LTS
* VMware Workstation
* Microsoft Azure
* Azure Data Explorer
* Kusto Query Language (KQL)
* Remote Desktop
* Google Chrome
* Aspen InfoPlus.21 concepts

## Work Completed

* Created an Ubuntu Server virtual machine
* Configured remote desktop access
* Installed and started Grafana
* Accessed the Grafana web interface
* Created an Azure Data Explorer environment
* Began configuring Azure Data Explorer as a Grafana data source
* Practiced troubleshooting Linux, Grafana, Azure, and Aspen InfoPlus.21 connectivity

## Planned Improvements

* Create sample process data
* Build Grafana dashboards
* Write KQL queries
* Add alarms and alerting
* Add dashboard screenshots
* Document Azure Data Explorer integration
* Explore Aspen InfoPlus.21 data integration

## Repository Structure

```text
grafana-azure-lab/
├── README.md
├── docs/
├── screenshots/
├── diagrams/
├── dashboards/
└── queries/
```

## Security Notice

This repository contains lab documentation only. Passwords, client secrets, access tokens, private IP addresses, company data, and other sensitive information are not included.

## Author

**Kirk Biggs**
GitHub: [kirkbiggs-tech](https://github.com/kirkbiggs-tech)

## License

This project is licensed under the MIT License.

