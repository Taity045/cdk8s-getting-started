# Getting started with cdk for the first time (in Python!)

You can apply this example into your own cluster with these step by step commands:

#### Import

```console
$ pipenv install
$ cdk8s import --language python
```

#### Synthesize the CDK into a k8s template
```console
$ cdk8s synth
```

#### Apply the k8s template to your cluster
```console
$ kubectl apply -f dist/cdk8s-app.k8s.yaml
```
