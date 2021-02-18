1. $ docker stack deploy -c stack.yaml haydenstack
2. docker service scale haydenstack_app1=7
3. docker stack rm haydenstack