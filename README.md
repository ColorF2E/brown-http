# brown-http

## Install
```shell
npm install brown-http
```

## Example
``` javascript
import http from 'brown-http';
const params = {
    id:1
}
http.$get('http://github.com',params).then(res => {
    //do something...
});
```
