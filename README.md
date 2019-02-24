[![Build Status](https://travis-ci.com/elasyaf/redis.svg?branch=master)](https://travis-ci.com/elasyaf/redis)

# redis

__Redis__ builder using docker

## How To

1. Clone.

   ```
   git clone https://github.com/elasyaf/redis
   ```

2. Build docker image.
 
   ```
   docker build -t <your_repo_name>/redis:<tag> 
   example : 0xelasyaf/redis:latest
   ``` 

3. With docker compose.
 
   ```
   version: "2.0"
   services:
      redis:
        image: '0xelasyaf/redis:latest'
        hostname: redis
        container_name: redis
        ports:
          - '6379:6379'
          
   ``` 
License
------------------

GPL-3.0


Author Information
------------------

elasyaf @ 2019

