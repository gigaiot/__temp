# 마크다운 문서 연습

마크다운(md, Mark Down)은 단순한 포메팅으로 문서를 간단하고 빠르게 작성하도록 도와줍니다.

이를테면 이런거...

 Type some Markdown on the left
  - See HTML in the right
  - Magic
  - dcdcd

  똥 이렁거

  
> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

## 소스코드 입력도

```sh
$ cd dillinger
$ npm install -d
$ node app
$ node ddd
```

## 테이블도...

.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md] [PlDb] |
| Github | [plugins/github/README.md] [PlGh] |
| Google Drive | [plugins/googledrive/README.md] [PlGd] |
| OneDrive | [plugins/onedrive/README.md] [PlOd] |
| Medium | [plugins/medium/README.md] [PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md] [PlGa] |


## 이미지 삽입도...

JPG파일
![IoTMakers](./images/img001.JPG "IoTMakers")

### PNG파일
![IoTMakers](./images/img001.PNG "IoTMakers")


## 리스트

* ㄴㄴㄴㄴ
* ㅂㅂㅂㅂ



```sh
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0000: 00 00 00 74 11 01 00 23 | 60 e0 8b c5 8b 59 00 00   ...t...#`....Y..
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0010: 00 00 00 00 00 00 00 00 | 00 00 00 00 00 00 00 00   ................
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0020: 00 00 01 01 03 00 00 7b | 22 65 78 74 72 53 79 73   .......{"extrSys
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0030: 49 64 22 3a 22 4f 50 45 | 4e 5f 54 43 50 5f 30 30   Id":"OPEN_TCP_00
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0040: 31 50 54 4c 30 30 31 5f | 31 30 30 30 30 30 31 34   1PTL001_10000014
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0050: 33 33 22 2c 22 64 65 76 | 49 64 22 3a 22 58 58 58   33","devId":"XXX
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0060: 58 58 22 2c 22 61 74 68 | 6e 52 71 74 4e 6f 22 3a   XX","athnRqtNo":
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0070: 22 58 58 58 58 58 22 7d |                           "XXXXX"}
```


```bin
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0000: 00 00 00 74 11 01 00 23 | 60 e0 8b c5 8b 59 00 00   ...t...#`....Y..
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0010: 00 00 00 00 00 00 00 00 | 00 00 00 00 00 00 00 00   ................
```


```pre
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0000: 00 00 00 74 11 01 00 23 | 60 e0 8b c5 8b 59 00 00   ...t...#`....Y..
11:31:39 DBG ../iotmakers_sdk_c_ver_3.0.15/src/util/log.c 0176 im_log_wri: 0010: 00 00 00 00 00 00 00 00 | 00 00 00 00 00 00 00 00   ................
```

```json
{
"extrSysId":"OPEN_TCP_001PTL001_1000001433",
"devId":"XXXXX",
"athnRqtNo":"XXXXX"
}
```

```javascript
{"extrSysId":"OPEN_TCP_001PTL001_1000001433","devId":"XXXXX","athnRqtNo":"XXXXX"}
```




