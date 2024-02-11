motd
=========

The motd Ansible role dynamically generates a Message of the Day (MOTD) for Linux servers, displaying essential system information and a customizable security warning for unauthorized access.

````
-----------------------------
SERVER INFORMATION
-----------------------------
  Hostname: .................. niobe.example.com.br
  Distro: .................... RedHat 9.3
  Kernel: .................... 5.14.0-362.18.1.el9_3.x86_64
  CPUs ....................... 12
  Memory: .................... 30.84 GB
  IPV4: ...................... ['192.168.0.206', '192.168.100.1']
  SELinux: ................... enabled
  Runlevel: .................. graphical.target
  Time Zone: ................. -03
  Uptime: .................... 11 hours

  ______________________________________
 / UNAUTHORIZED ACCESS IS PROHIBITED.   \
 | Explicit, authorized permission is    |
 | required for access or configuration. |
 | Unauthorized attempts will result in  |
 | legal actions. All activities are     |
 \ logged and monitored.                 /
  ---------------------------------------
         \   ^__^
          \  (oo)\_______
             (__)\       )\/\
                 ||----w |
                 ||     ||

---------------

````

Requirements
------------

Ansible >= 2.10
No specific requirements. Designed to work on RHEL 8 and 9.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - allanroque.motd

License
-------

MIT
