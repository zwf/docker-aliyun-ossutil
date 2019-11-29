# docker-aliyun-ossutil
ossutil docker image base on busybox

## how to config as a native binary version

1. pull image from hub.docker.com

   ```bash
   docker pull zhangweifang/aliyun-ossutil
   ```

2. add alias to env

   ```bash
   alias ossutil='docker run --rm -ti -v $(your ossutilconfig file path):/root/.ossutilconfig -v $(pwd):/oss zhangweifang/aliyun-ossutil ossutil'
   ```
