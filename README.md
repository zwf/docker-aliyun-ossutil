# docker-aliyun-ossutil
ossutil docker image base on busybox

## add alias to env

```bash
alias ossutil='docker run --rm -ti
               -v $(your ossutilconfig file path):/root/.ossutilconfig 
               -v $(pwd):/oss
               zhangweifang/docker-aliyun-ossutil ossutil'
```

