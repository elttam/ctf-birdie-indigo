# Overview

**Title:** Birdie Indigo  
**Category:** Crypto  
**Flag:** `libctf{2868ee14-472a-4ace-bbb4-bdba4b33cb54}`  
**Difficulty:** Medium

# Usage

The following will pull the latest 'elttam/ctf-birdie-indigo' image from DockerHub, run a new container named 'libctfso-birdie-indigo', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-birdie-indigo \
  elttam/ctf-birdie-indigo:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-birdie-indigo' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-birdie-indigo:latest
```
