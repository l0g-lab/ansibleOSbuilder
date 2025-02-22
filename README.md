# ansibleOSbuilder

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

3. Run the ansible playbook to deploy the configurations:
    ```bash
    $ ansible-playbook main.yml
    ```