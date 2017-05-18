# Container Live Migration Research

## About C/R Migration

## Phase 1

Add two Kubernetes command: checkpoint and restore to support offline migration.

Checkpoint has the similar logic with exec command.

API: 

* https://github.com/moby/moby/blob/master/api/types/client.go
* https://github.com/docker/cli/blob/master/client/checkpoint_create.go

### Exec Code

Key word: ExecInContainer

pkg/registry/core/pod/strategy.go:ExecLocation

## Phase 2

Allow Kubernetes scheduler migrate containers.

## Phase 3

Try to live migration.
