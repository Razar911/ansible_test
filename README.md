# ansible_test
#### to configure server run playbook with parameters
#### use file hosts.txt to add servers to different environments
#### for example, command to configure STAGE server with project name INCREDIBLE on project group ONE will be:

` ansible-playbook nginx_php.yml --extra-var "APP_PROJECT_GROUP=one" --extra-var "APP_PROJECT_NAME=incredible" --extra-var "APP_ENV=stage" `

#### to see result, go to browser link
`http://your_server_ip/index.php`

#### for example:
`http://18.197.100.202/index.php`
