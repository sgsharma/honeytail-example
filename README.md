# honeytail-example

## Quickstart

Install honeytail:

```
go install github.com/honeycombio/honeytail@v1.8.1
```

Run with `.ini` or `.conf` config files

```
$ export HONEYCOMB_API_KEY=<YOUR_API_KEY>

$ honeytail --config ./honeytail-example.ini -k ${HONEYCOMB_API_KEY} --debug --parser keyval
```
Run with `.yaml` config file:

```
$ export HONEYCOMB_API_KEY=<YOUR_API_KEY>

$ honeytail --config_yaml ./honeytail-example.yaml -k ${HONEYCOMB_API_KEY} --debug --parser keyval --file ./honeytail-example.log --dataset honeytail-example
```
