# AWS Automation Using Ansible

This project contains Ansible scripts for AWS automation. It covers several major AWS services.

## Contents

- `ansible.cfg`: Main Ansible configuration file
- `hosts`: Host configuration file
- `aws_ec2.yml`: AWS EC2 variables file
- `keys.yml`: Security keys file
- `AWS_Modules.txt`: List of used modules

### Main Directories

1. `EC2_Labs`: Contains Ansible scripts for EC2 Instances management
2. `IAM_Labs`: Contains Ansible scripts for AWS IAM management
3. `S3_Labs`: Contains Ansible scripts for Amazon S3 management

## Requirements

- Ansible (2.x or newer)
- AWS CLI
- AWS account with appropriate permissions

## Installation

1. Install Ansible:
```bash
pip install ansible
```

2. Install AWS CLI:
```bash
pip install awscli
```

3. Configure AWS CLI:
```bash
aws configure
```

## Usage

1. Update the `hosts` file with appropriate hosts
2. Update `keys.yml` with appropriate credentials
3. Run the required Ansible playbook:
```bash
ansible-playbook <filename>.yml
```

## Notes

- Ensure you have appropriate permissions in AWS
- Update variables in files according to your needs
- Keep backups of sensitive configuration files

## License

Copyright © 2025
