# ZSOFTLY Capstone Part 2 — Docker + ECR + GitHub Actions

## Overview
Automated CI/CD pipeline that builds and pushes Docker images to Amazon ECR on every Pull Request.

## Environments
| Branch | Environment | ECR Tag |
|--------|------------|---------|
| dev | Development | dev-latest |
| staging | Staging | staging-latest |
| main | Production | prod-latest |

## Tech Stack
- Docker
- GitHub Actions
- Amazon ECR
- AWS IAM
