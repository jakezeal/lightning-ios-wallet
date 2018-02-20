# Calling the Google Cloud Datastore API

This directory contains a very simple sample that calls the 
[Google Cloud Datastore API](https://cloud.google.com/datastore/docs/reference/rpc/google.datastore.v1).
Calls are made directly to the Datastore RPC interface. 
In practice, these would be wrapped in idiomatic code.

Use [RUNME](RUNME) to generate the necessary Protocol Buffer
and gRPC support code. It uses protoc and the Swift Protocol
Buffer and gRPC plugins, so please be sure these are in your
path. The plugins can be built by running `make` in the 
top-level Plugins directory.

## Prerequisites

Please be sure to perform the preliminary steps in 
[Examples/Google/README](../README.md).
