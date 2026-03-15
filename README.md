_For my website_

# Usage

### Docker

``docker build . -t portfol``

``docker run -p 8080:80 portfol``

it will be on __http://localhost:8080/__

### Ansible
__To use ansible add yours hosts.ini !!!__

``ansible-galaxy collection install community.docker``

``ansible-playbook -i hosts.ini deploy.yml``