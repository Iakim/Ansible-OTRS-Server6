[![PyPI version](https://img.shields.io/pypi/v/ansible.svg)](https://pypi.python.org/pypi/ansible/2.4.2.0)
# Ansible for install a OTRS Server 6

### Please note the following detail:
- Your server will restart after a playbook run
- After connecting again, execute the command:
    
          su -c "/opt/otrs/bin/otrs.Daemon.pl start" -s /bin/bash otrs

- After running the command go to http://yourip_or_hotname/otrs/installer.pl and make the necessary settings.
- Visit https://www.otrs.com for more details.
