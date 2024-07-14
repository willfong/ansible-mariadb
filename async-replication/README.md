# Async Replication

This creates a three node async-replication cluster.

## Requirements

1. 3x RockyLinux 9 VMs

## Getting Started

1. Copy `inventory_example` to `inventory`
1. Modify `inventory` with the IP address
1. Run `ansible-playbook -i inventory playbook.yml`
