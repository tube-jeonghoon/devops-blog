---
title: Scaling My Kubernetes Deployment
date: 2019-02-02
tags: ["kubernetes", "code"]
---

Scaling my kubernetes deployment

<!--more-->

```sh
    $ kubectl scale deployments/kubernetes-bootcamp --replicas=4
```

Now, check wheter it is scaled up:
```sh
$ kubectl get deployments
```
