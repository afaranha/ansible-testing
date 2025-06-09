Current output:

```
$ ansible-playbook main.yml 
[WARNING]: provided hosts list is empty, only localhost is available. Note that the implicit localhost does not match 'all'

PLAY [Run federation SSO setup on reproducer] *********************************************************************************************************************************************************************

TASK [Gathering Facts] ********************************************************************************************************************************************************************************************
ok: [localhost]

TASK [debug] ******************************************************************************************************************************************************************************************************
ok: [localhost] => {
    "cifmw_federation_keycloak_url": "https://keycloak-openstack.apps.ocp.openstack.lab"
}

PLAY RECAP ********************************************************************************************************************************************************************************************************
localhost                  : ok=2    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
```
