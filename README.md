### running concourse tasks directly
- assumes you are in the `tasks` dir

### setting pipelines
- assumes you are in the `pipelines` dir

```bash
# login and define target
fly login -t tutorial -c http://127.0.0.1:8080 -n main

# set a new pipeline
fly -t tutorial set-pipeline -p hello_word -c pipelines/hello_world.yml
```