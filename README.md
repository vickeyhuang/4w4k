# AWS CloudPatterns

## Setup AWS CLI:

1. Install `awscli` and `ansible` for you platforms.

2. Configure your `awscli` via `aws configure`.

3. the `AWS Access Key ID` and `AWS Secret Access Key` can be generated from IAM console.

4. To use `vagrant` to generate a virtual machine for awscli you have to 


## Setup Vagrant:

1. Install `vagrant` and `virtualbox`.

2. In the `aws/` folder run `vagrant up` in your terminal to provision a virtual machine.

3. You can login the virtual machine via `vagrant ssh` in your terminal.


## Run Playbook via ansible

1. Setup up your AWS CLI.

2. Run `ansible-playbook <playbook file> -i inventory/<inventory file>` under the folder. for week1-1, you need to run `ansible-playbook playbook.yml -i inventory/week1-1`, the `playbook.yml` is the ansible playbook, `week1-1` is the inventory file.

3. Check the result in the cloudformation in your AWS console.