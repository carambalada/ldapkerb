# ldapkerb
LDAP and Kerberos utils wrappers

Configuration example (usrmgmt.conf):

```bash
DC='dc=company,dc=domain'
REALM='COMPANY.DOMAIN'
LDAPUSER="uid=manager,ou=Staff,${DC}"
LDAPPASS='password'
PRINCOU="cn=${REALM},cn=kerberos,ou=kdcroot"
LDAPURI="ldap://ldap.${REALM}"
LDAPOUTPUT="/tmp/${RANDOM}"
FUNC=/usr/local/bin/usrmgmt_functions.sh
```
