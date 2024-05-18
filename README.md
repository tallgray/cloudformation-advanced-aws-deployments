# cloudformation-advanced-aws-deployments
This repository contains CloudFormation templates for building a secure, scalable, and fault-tolerant multi-VPC architecture on AWS. It includes configurations for IAM roles, VPCs, security groups, VPC peering, Transit Gateway, and AWS Network Firewall, accompanying a detailed article series on advanced AWS deployments.

## Overview

The templates and code in this repository are designed to accompany a series of articles detailing the step-by-step process of leveraging AWS CloudFormation for advanced infrastructure deployments. The series covers:

1. Building a Secure Multi-VPC Architecture with AWS CloudFormation
2. Enhancing AWS Security and Monitoring with CloudFormation and Flow Logs
3. Simplifying Access Management and Connectivity with AWS CloudFormation
4. Streamlining AWS Infrastructure Deployment with CloudFormation and Nested Stacks
5. Mastering AWS Infrastructure Orchestration with CloudFormation

## Repository Structure

- `templates/` - Contains CloudFormation templates for various components of the architecture.
- `scripts/` - Contains auxiliary scripts for deployment and management.
- `docs/` - Documentation and guides related to the templates and their usage.
- `images/` - Image files.

## Getting Started

### Prerequisites

- AWS CLI installed and configured
- AWS CloudFormation permissions
- Basic knowledge of AWS services and CloudFormation

### Deployment

1. Clone the repository:
   ```bash
   git clone https://github.com/tallgray/cloudformation-advanced-aws-deployments.git
   cd cloudformation-advanced-aws-deployments
