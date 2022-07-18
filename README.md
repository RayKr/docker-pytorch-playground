# Docker Pytorch Playground

Running models faster and easier, support for x86 and ARM (M1, M1Pro).

## How to Use

It's easy to use:

```bash
docker pull raykr/docker-pytorch-playground
```

## Docker Images

- raykr/docker-pytorch-playground:latest

## Build

```bash
docker build -t raykr/docker-pytorch-playground .
```

If you need to replace the software source:

```bash
docker build --build-arg USE_MIRROR=true -t raykr/docker-pytorch-playground .
```
