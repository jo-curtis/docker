# Useful Docker Commands

### Enter an interactive shell session on an already-running container:
- ``` docker exec --interactive --tty {{container_name}} {{/bin/bash}} ```
- ``` docker exec -it {{container_name}} {{/bin/bash}} ```

### Safely exit a docker container that was entered using docker exec
- ``` exit ```

### View all containers on a host
- ``` docker ps --all ```
