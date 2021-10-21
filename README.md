nginxのlimit_req_zoneの動作確認

参考
https://qiita.com/niisan-tokyo/items/f7176fb0d4d3cff64f2c#limit_req_zone

index.phpやrateを変えて動作確認

```
$ ab -n 10 -c 1 http://localhost:8080/
```

