# Splunk Enterprise Deployment with AWS Integration

![Splunk Logo](https://www.splunk.com/content/dam/splunk2/images/social/splunk-social-share.jpg) ![AWS Logo](https://d1.awsstatic.com/logos/aws-logo-lockups/poweredbyaws/PB_AWS_logo_RGB_stacked_REV_SQ.91cd4af40773cbfbd15577a3c2b8a346fe3e8fa2.png)

## Project Overview
An end-to-end implementation of Splunk Enterprise for log analysis, featuring:
- **Multi-source log ingestion** (Linux system logs, custom applications)
- **AWS S3 cloud integration** for centralized log storage
- **Distributed architecture** with Universal Forwarders
- **Operational dashboards** and alerting mechanisms

## Key Components Implemented
| Component | Description |
|-----------|-------------|
| **Splunk Indexer** | Central log processing and storage |
| **Universal Forwarder** | Lightweight log collection agents |
| **Search Head** | Interactive data analysis interface |
| **AWS S3 Integration** | Cloud-based log ingestion pipeline |

## Architecture
![architecture](image.png)

## Getting Started

### Prerequisites
- Ubuntu 20.04+ server
- AWS account with S3 access
- Splunk Enterprise license (free tier available)

### Installation
```bash
# Download and install Splunk
wget -O splunk-9.1.2.deb "https://download.splunk.com........."
sudo dpkg -i splunk-9.1.2.deb
sudo /opt/splunk/bin/splunk start --accept-license