# Project Details

## Overview
This project showcases a Python application deployed using Docker, CI/CD pipeline, and infrastructure automation.

### Tools Used
- **AWS**: EC2, S3, CloudWatch, CodePipeline, CodeBuild
- **Terraform**: Infrastructure provisioning
- **Docker**: Containerization
- **Prometheus/Grafana**: Monitoring and dashboards

### How to Set Up
1. Deploy infrastructure using `terraform apply` in the `infra/` folder.
2. Build and push the Docker image using the pipeline in `ci-cd/`.
3. Monitor application logs and metrics via CloudWatch and Grafana.
