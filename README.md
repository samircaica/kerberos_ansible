# Configure Kerberos for CM 7.1.7

- **tasks.yml:** install the Kerberos MIT server and set principal for CM, also set krb5.conf and kadm5.acl in CM and krb5.conf for workers.

- **tasks_cm_kerberos.yaml**: configure Kerberos in CM, and generate the credentials.

**Execution:**

```bash
1. ansible-playbook tasks.yml

2. ansible-playbook tasks_cm_kerberos.yaml
```
