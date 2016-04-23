# digitalocean
Infrastructure as code on digitalocean

# to clone this repository
```
$ git clone git@github.com:bvenkysubbu/digitalocean.git
```

# install ansible
# http://docs.ansible.com/ansible/intro_installation.html

# install dopy
# https://pypi.python.org/pypi/dopy
```
$ pip install dopy
```

# cd to the directory 'digitalocean'
```
$ cd digitalocean/
```

# export digital ocean api token
```
$ export DO_API_TOKEN=YOUR_DO_API_TOKEN
```

# run the ansible-playbook
```
$ ansible-playbook create_droplet.yml
```
