Create .env with the following params and place it in the root folder

```
DATASTORE=weaviate
BEARER_TOKEN=<any JWT>
OPENAI_APIKEY=<API KEY>
WEAVIATE_INDEX=Flow
```

Create .env in the setup-weaviate folder
```
OPENAI_APIKEY=<API KEY>
```

Setup Weaviate Locally
Run `docker-compose up -d && docker-compose logs -f weaviate`

Run Flow-gpt app
- Install pyenv
- run `pyenv install 3.10.11`
- Open new shell
- Follow instructions in https://github.com/harshav17/flow-retrieval-plugin#quickstart