# ODBC
This allows hosts to define generic odbc connections to MS SQL Server and Sybase database servers.

## Dependencies
- City-of-Bloomington.linux

Example Playbook
----------------

```yml
- hosts: odbc
  become: yes
  roles:
    - City-of-Bloomington.odbc
```

Copying and License
-------
This material is copyright 2021 City of Bloomington, Indiana
It is open and licensed under the GNU General Public License (GPL) v3.0 whose full text may be found at:
https://www.gnu.org/licenses/gpl.txt
