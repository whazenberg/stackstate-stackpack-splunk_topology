# Splunk Topology beta StackPack for StackState

Moved to [https://github.com/StackVista/stackpack-splunk](https://github.com/StackVista/stackpack-splunk)


Beta.

Developed against StackState 4.0.0.


## Packaging

1. zip contents of `stackpack/`:

*Note*: rename zip to use sts extension.

Example:
```
zip -r splunk-topology-0.0.13.sts stackpack.conf provisioning resources
```

```
.
├── provisioning
├── resources
└── stackpack.conf
```

2. upload with the StackState CLI

```
sts stackpack upload <path to sts file>
```
