AWS VPC
├── Public Subnet
│   └── Bastion Host (Ansible Control Node)
│
└── Private Subnet
    ├── App Server 1
    └── App Server 2

    ansible-aws-project/
├── inventory/
│   └── hosts.ini
├── playbooks/
│   ├── site.yml
│   └── roles/
│       └── common/
│           ├── tasks/main.yml
│           └── handlers/main.yml
├── files/
├── templates/
├── group_vars/
│   └── all.yml
├── ansible.cfg
└── README.md

