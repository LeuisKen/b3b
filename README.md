# b3b

buffer convert util

### convert map

```
ArrayBuffer -------- Buffer
\                      /
 \                    /
   ----  base64  -----
```


### api

- #### <a href="index.js?source#L7" target="_blank"><b>0 </b></a>

  - **file**:  

    buffer convert util

  - **author**:  

    junmer

  - **description**:  

    ArrayBuffer / Buffer / base64 convert util

- #### <a href="index.js?source#L16" target="_blank"><b>ab2b (ab)  <small>(alias: arrayBufferToBuffer)</small> </b></a>
    convert arrayBuffer to buffer

  - **param**: `ab` { _ArrayBuffer_ }

    arrayBuffer

  - **return**:  { _buffer_ }

    buffer

- #### <a href="index.js?source#L36" target="_blank"><b>b2ab (buffer)  <small>(alias: bufferToArrayBuffer)</small> </b></a>
    convert buffer to arrayBuffer

  - **param**: `buffer` { _buffer_ }

    buffer

  - **return**:  { _ArrayBuffer_ }

    arrayBuffer

- #### <a href="index.js?source#L56" target="_blank"><b>a2b (str)  <small>(alias: base64ToBuffer)</small> </b></a>
    convert base64 string to buffer

  - **param**: `str` { _string_ }

    base64 string

  - **return**:  { _Buffer_ }

    buffer

- #### <a href="index.js?source#L67" target="_blank"><b>b2a (str)  <small>(alias: bufferToBase64)</small> </b></a>
    convert buffer to base64 string

  - **param**: `str` { _string|Buffer_ }

    string or buffer

  - **return**:  { _string_ }

    base64 string

- #### <a href="index.js?source#L87" target="_blank"><b>b2b (ab)  <small>(alias: bytesToBase64)</small> </b></a>
    convert arraybuffer to base64 string

  - **param**: `ab` { _ArrayBuffer|Array_ }

    ArrayBuffer or Array

  - **return**:  { _string_ }

    base64 string

