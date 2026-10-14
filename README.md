# denv quickstart

The environment from the [denv quickstart](https://denv.ai/docs/tutorials/quickstart/): Postgres with data, an agent box that is never root, and a verifier that grades apart from the agent.

Connected to denv, every push to `main` deploys the `alpha` environment from `docker-compose.yaml`; a `denv` check run on the commit links to the deployment's phase log.

```
denv login
denv project create --kind rl-environment --source github:opencrew-ai/denv-quickstart quickstart
```
