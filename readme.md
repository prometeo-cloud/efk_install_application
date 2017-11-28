# efk_install_application

## Description:

Install ELK

## Behaviour:

**Feature:** Install EFK
As a System Admin 
I want to ensure that EFK is installed
So that I can collect and collate logs for the customer

**Feature:** Install EFK
- **Given** the RHEL machine is configured as a Docker host
- **Given** a Fluentd image is available from a specified registry
- **Given** an Elasticsearch Docker image is available from a specified registry
- **Given** a Kibana image is available from a specified registry
- **Given** Docker Compose is installed on the host
- **When** Docker Compose is requested to run the application containers
- **Then** the Fluentd container is running
- **Then** the Elasticsearch container is running
- **Then** the Kibana container is running
- **Then** EFK containers are linked

## Configuration:

### Default variables

The following is a list of default variables used by this role.

| Variable  | Description  | Default  |
|---|---|---|
| **config** | some description | some default |

