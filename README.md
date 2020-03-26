# golang-http

Demo application created by `jx create quickstart`.

```
Watch pipeline activity via:    jx get activity -f jx-quickstart-go-app -w
Browse the pipeline log via:    jx get build logs cheesydev-labs/jx-quickstart-go-app/master
You can list the pipelines via: jx get pipelines
When the pipeline is complete:  jx get applications
```

To list applications and versions deployed in the environments:
```
jx get applications
```

To promote a new version to production:
```
jx promote --app jx-quickstart-go-app --version 0.0.1 --env production
```
