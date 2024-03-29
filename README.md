# Github Runner Ansible Playbook

This repository contains an Ansible playbook. It automates the deployment and configuration of a github runner.

## Prerequisites

Before running this playbook, ensure that the following prerequisites are met on your computer:

- ansible

Before running this playbook, ensure that the following prerequisites are met on your machine:

- python

## Usage

To use this playbook, follow these steps:

1. Clone this repository.
2. Copy templated inventory hosts file (`inventories/hosts.template`) to (`inventories/runners/hosts`)
3. Update the inventory file (`inventories/runners/hosts`).
4. Run the playbook using the following command:

  ```shell
  ansible-playbook -k -i inventories/runners runners.yml
  ```

## Troubleshooting

If you encounter any issues while running the playbook, please open an issue in this repository, providing detailed information about the problem and any error messages you encountered.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please submit a pull request or open an issue.