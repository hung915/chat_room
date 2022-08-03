### Requirements
- **Python 3.8**
- PostgreSQL

### Setting up environment
- Create .env file in the main folder.
- Copy the content from .env.example file to .env file.
- Edit postgres info as needed

### Migrate DB
Run these commands:

```flask db init```

```flask db migrate -m "Initial migration."```

```flask db upgrade```


### Run pre-commit
- Run this command and fix all the warning before committing code to the repo
```
pre-commit run --all-files
```


### Run Server
```
flask run
```

### Branch naming convention:

- name-issue ID. E.g: lhnhat-SCP-001


