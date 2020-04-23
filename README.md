# Welcome to my dataform project!

### Installing dataform cli

```npm i -g @dataform/cli```

```
dataform [command]

Commands:
  dataform help [command]                                 Show help. If [command] is specified, the help is for the given command.
  dataform init <warehouse> [project-dir]                 Create a new dataform project.
  dataform install [project-dir]                          Install a project's NPM dependencies.
  dataform init-creds <warehouse> [project-dir]           Create a .df-credentials.json file for Dataform to use when accessing your warehouse.
  dataform compile [project-dir]                          Compile the dataform project. Produces JSON output describing the non-executable graph.
  dataform test [project-dir]                             Run the dataform project's unit tests on the configured data warehouse.
  dataform run [project-dir]                              Run the dataform project's scripts on the configured data warehouse.
  dataform format [project-dir]                           Format the dataform project's files.
  dataform listtables <warehouse>                         List tables on the configured data warehouse.
  dataform gettablemetadata <warehouse> <schema> <table>  Fetch metadata for a specified table.
```

### Using the sample project

Try running the following commands:
- ```dataform init <warehouse> [project-dir]```
- ```dataform init-creds <warehouse> [project-dir]```
- ```dataform compile```
- ```dataform test```
- ```dataform run --dry-run```
- ```dataform run```


### Resources:
- Learn more about dataform [in the docs](https://docs.dataform.co/getting-started)
- Check out [the blog](https://dataform.co/blog) for the latest news


