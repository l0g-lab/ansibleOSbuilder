# ansibleOSbuilder

## Information

This repository includes a `main.yml` play which will deploy all configurations against your localhost

You'll find individual playbooks in the `playbooks` directory to apply single configurations. This is useful if you only want to install the packages, or only apply certain configurations to your system.

## Instructions

1. Clone the repo:
    ```bash
    $ git clone https://github.com/l0g-lab/ansibleOSbuilder
    $ cd ansibleOSbuilder
    ```

2. Install ansible via your local package manager or pip:
    * Package Manager (apt in this example)
    ```bash
    $ sudo apt-get install ansible
    ```
    * Python pip3
    ```bash
    $ python3 -m venv .venv
    $ source .venv/bin/activate
    $ pip3 install ansible
    ```
3. Get a sudo token
    ```bash
    $ sudo -l
    ```

4. Run the ansible playbook to deploy the configurations:
    ```bash
    $ ansible-playbook main.yml
    ```
