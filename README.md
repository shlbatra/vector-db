# vector-db
Exercises relevant to Vector Database

# Poetry environment setup instructions

- poetry new vector-db-env
- cd vector-db-env
- poetry init
- poetry install # (add packages in pyproject.toml)
- poetry shell
- poetry update
- poetry remove <package-name>

###### To make environment work with notebooks in VS code

- poetry add jupyter
- poetry add ipykernel
- poetry run python -m ipykernel install --user --name=vector-db-env --display-name "vector-db-env"
- poetry env info --path