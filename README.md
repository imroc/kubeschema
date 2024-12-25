# kubeschema

## Install

```bash
go install github.com/imroc/kubeschema@latest
```

## Requirements

- Make sure `kubectl` is installed and can operate current cluster.

## Usage

Dump json schema from current cluster:

```bash
kubeschema dump
```

Index json schema in current directory:

```bash
kubeschema index
```

Dump json schema and index all json schema file:

```bash
kubeschema dump --index
```

Dump json schema and index with extra directory:

```bash
kubeschema dump --index --extra-dir=../other-dir
```

## Public Kubernetes Schemas

[kubeschemas](https://github.com/imroc/kubeschemas) is generated by [kubeschema](https://github.com/imroc/kubeschema), which contains a lot of well known and open source project's CRD schemas.
