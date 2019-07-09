# ansible-role-hostname

Role which sets target hostname.

### Prerequisites

It is adviced to set your hostname to a FQDN, for example: server1.example.com.

## Deployment

Example playbook:

```
- hosts: web
  roles:
    - 'ansible-role-hostname'
```

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/2.8/index.html)

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## Company

* **Delta.BG**

## License

This project is licensed under the MIT License.
