# Week 11 Lab 01 — Bright Ntow

## Part A — Local tests
I ran the lab tests in Docker. All 256 unit tests and all 13 integration tests passed.

## Part B — IAM groups and policies
The AWS preflight check passed. The setup script created the TechTeam, BusinessTeam, and SecurityTeam groups and attached their policies.

## Part C — Storage and secrets
The script created both S3 buckets. The first run stopped at the CloudWatch Logs retention step because my IAM user did not have permission to run `logs:PutRetentionPolicy`.
