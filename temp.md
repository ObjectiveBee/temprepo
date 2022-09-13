```http
POST https://batchlogging4-noneu.truecaller.com/truecaller.logging.v1.LoggingService/Log HTTP/2.0
user-agent: truecaller-android/1242006 (grpc-java-okhttp) grpc-java-okhttp/1.37.0
content-type: application/grpc
te: trailers
grpc-accept-encoding: gzip
authorization: Bearer a2i0G--aTVqKek7-jBRabFPK204y-AHQnzt4BuuoGLmri6T87Dee-mEdT6V2_q2s
grpc-timeout: 29616198u
content-length: 328

b'\x00\x00\x00\x01C\n\xc0\x02\n\x0cAppHeartBeat\x10\xca\x02\x1a\xac\x02\x00\x02\xbc\x83\x82\x9f\xe1`\xee\xcf\xa3\x9f\xe4`\x00 ddeb582c5777cd7f\x14Truecaller\x0e12.42.6\x16GOOGLE_PLAY\x02\x0e12.42.6\x08WIFI\x0eMegaFon\x00\x1efirstactivation\x0cVertex\x18Impress_Play\x02\x1e358113090015776\x80\x1e\xf0\x10\xc0\x07\x0eAndroid\x067.0\x08WIFI\x0eMegaFon\x02\x02\x1a192.168.0.110\x00\x08auto\x08auto\x04en\x00\x00\x00\x04\x04\xf4\x03\x04\x00\x00\x0eMegaFon\x00\xf4\x03\x04\x00\x00\x0eMegaFon\x00\x00\x02H78c04a15-cac9-4c33-aa9c-ec930ae38a28\x02&com.android.vending\x0c<null>'
```
--- DECODED ---
```
1 {
  1: "AppHeartBeat"
  2: 330
  3: "\000\002\274\203\202\237\341`\356\317\243\237\344`\000 ddeb582c5777cd7f\024Truecaller\01612.42.6\026GOOGLE_PLAY\002\01612.42.6\010WIFI\016MegaFon\000\036firstactivation\014Vertex\030Impress_Play\002\036358113090015776\200\036\360\020\300\007\016Android\0067.0\010WIFI\016MegaFon\002\002\032192.168.0.110\000\010auto\010auto\004en\000\000\000\004\004\364\003\004\000\000\016MegaFon\000\364\003\004\000\000\016MegaFon\000\000\002H78c04a15-cac9-4c33-aa9c-ec930ae38a28\002&com.android.vending\014<null>"
}
```
```http
HTTP/2.0 200 
content-type: application/grpc
grpc-encoding: identity
grpc-accept-encoding: gzip
x-envoy-upstream-service-time: 36
date: Fri, 09 Sep 2022 11:13:33 GMT
server: istio-envoy
via: 1.1 google
alt-svc: h3=":443"; ma=2592000,h3-29=":443"; ma=2592000

b'\x00\x00\x00\x00\x00'
```

-----
-----
-----
-----

```http
POST https://presence-grpc-noneu.truecaller.com/truecaller.presence.v1.Presence/GetPresence HTTP/2.0
user-agent: truecaller-android/1242006 (grpc-java-okhttp) grpc-java-okhttp/1.37.0
content-type: application/grpc
te: trailers
grpc-accept-encoding: gzip
authorization: Bearer a2i0G--aTVqKek7-jBRabFPK204y-AHQnzt4BuuoGLmri6T87Dee-mEdT6V2_q2s
grpc-timeout: 9999538u

b'\x00\x00\x00\x00*\n\x0c+79206223757\n\x0c+79242571432\n\x0c+79256370259'
```
--- DECODED ---
```
1: "+79206223757"
1: "+79242571432"
1: "+79256370259"
```
```http
HTTP/2.0 200 
content-type: application/grpc
x-envoy-upstream-service-time: 13
date: Fri, 09 Sep 2022 11:13:31 GMT
server: istio-envoy
via: 1.1 google
alt-svc: h3=":443"; ma=2592000,h3-29=":443"; ma=2592000

b'\x00\x00\x00\x00\x87\n+\n\x0c+79206223757\x12\x1b\n\x02\x08\x03\x1a\x00"\x03\x98\x06\x01*\x02\x08\x012\x00B\x02\x08\x01J\x00b\x02\x08\x01\n+\n\x0c+79242571432\x12\x1b\n\x02\x08\x03\x1a\x00"\x03\x98\x06\x01*\x02\x08\x012\x00B\x02\x08\x01J\x00b\x02\x08\x01\n+\n\x0c+79256370259\x12\x1b\n\x02\x08\x03\x1a\x00"\x03\x98\x06\x01*\x02\x08\x012\x00B\x02\x08\x01J\x00b\x02\x08\x01'
```
--- DECODED ---
```
1 {
  1: "+79206223757"
  2 {
    1 {
      1: 3
    }
    3: ""
    4 {
      99: 1
    }
    5 {
      1: 1
    }
    6: ""
    8 {
      1: 1
    }
    9: ""
    12 {
      1: 1
    }
  }
}
1 {
  1: "+79242571432"
  2 {
    1 {
      1: 3
    }
    3: ""
    4 {
      99: 1
    }
    5 {
      1: 1
    }
    6: ""
    8 {
      1: 1
    }
    9: ""
    12 {
      1: 1
    }
  }
}
1 {
  1: "+79256370259"
  2 {
    1 {
      1: 3
    }
    3: ""
    4 {
      99: 1
    }
    5 {
      1: 1
    }
    6: ""
    8 {
      1: 1
    }
    9: ""
    12 {
      1: 1
    }
  }
}
```

----
----
----
----
```http
POST https://presence-grpc-noneu.truecaller.com/truecaller.presence.v1.Presence/SetPresence HTTP/2.0
user-agent: truecaller-android/1242006 (grpc-java-okhttp) grpc-java-okhttp/1.37.0
content-type: application/grpc
te: trailers
grpc-accept-encoding: gzip
authorization: Bearer a2i0G--aTVqKek7-jBRabFPK204y-AHQnzt4BuuoGLmri6T87Dee-mEdT6V2_q2s
grpc-timeout: 9999397u

b'\x00\x00\x00\x00+\n\x02\x08\x01\x12\x04\x12\x02\x08\x06\x1a\r\n\x0bUSER_ACTION"\x002\x02\x10\x04B\x00J\x02\x10\x02Z\x00b\x02\x10\x01'
```
--- DECODED ---
```
1 {
  1: 1
}
2 {
  2 {
    1: 6
  }
}
3 {
  1: "USER_ACTION"
}
4: ""
6 {
  2: 4
}
8: ""
9 {
  2: 2
}
11: ""
12 {
  2: 1
}
```
```http
HTTP/2.0 200 
content-type: application/grpc
x-envoy-upstream-service-time: 5
date: Fri, 09 Sep 2022 11:13:29 GMT
server: istio-envoy
via: 1.1 google
alt-svc: h3=":443"; ma=2592000,h3-29=":443"; ma=2592000

b'\x00\x00\x00\x00\x00'
```
