# n8n_personnal_project
Repository to store assets around an n8n project


## Steps

```shell
docker volume create n8n_data
```

```shell
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:{personnal_path}/.n8n docker.n8n.io/n8nio/n8n
```

