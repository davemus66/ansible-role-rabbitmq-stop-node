ansible-role-rabbitmq-stop-node
=========

This role will ensure the RabbitMQ Node is stopped. 

Installing
------------

If you dont have the role on your machine simply cd into the roles directory and run:

    ansible-galaxy install -r requirements.yml
    
Below is an example command on how to run the playbook:

    ansible-playbook site.yml
  
Example Playbook
----------------
    
    - name: 
      hosts: all
      roles:
        - ansible-role-rabbitmq-stop-node


License
-------

BSD

Author Information
------------------

Helen Turner      
