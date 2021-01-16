# Python upload server e Docker

Projeto baseado no Gist [touilleMan/SimpleHTTPServerWithUpload.py](https://gist.github.com/touilleMan/eb02ea40b93e52604938)

## Uso

O serviço sobre na porta `10140` e os arquivos enviados ficam salvos na pasta `app`

```sh
# OBS: Comandos executados na raiz do projeto

# Subir container
docker-compose up -d

# Visualizar logs
docker-compose logs -f

# Remover container
docker-compose down --rmi local
```
