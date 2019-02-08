Ansible role to add trusted certificates to a server


Example:
```
pki_certs_trusted:
  - name: 'packet solutions ca'
    src: '/src/packetsolutionsca.crt'
    dest: 'packetsolutionsca.crt'
    state: 'present'
```

| Tested on    |
| ------------ |
| ubuntu 14.04 |
| ubuntu 18.04 |
