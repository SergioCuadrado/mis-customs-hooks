# useAllFetch

Ejemplo de uso:

```javascript
const url = "endpoint_api";
const id = 5;
const body = { name: "Sergio", age: 23 };
const { get, post, put, del } = useAllFetch(url);
const info_get = get(id);
const info_post = post(body);
const info_put = put(id, body);
const info_delete = del(id);
```
