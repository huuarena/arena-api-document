# APP

Base URL:

---

#####

<details>
<summary><code><b>JSON</b></code></summary>

#####

```
{
  "name": "", // string, required
  "uid": "", // string, required
  "url": "" // string, required
  "token": "" // string, required
}
```

</details>

#####

<details>
<summary><code><b>GET</b></code> <code><b>/apps</b> Get list apps</code></summary>

##### Endpoint

```
/apps?pagination[page]=1&pagination[pageSize]=20
```

##### Parameter

```
{
  "pagination": {
    "page": "1",
    "pageSize": "20"
  }
}
```

##### Response

```
{
  "data": [
    {
      "id": 4,
      "attributes": {
        "name": "Wishlist Compare",
        "uid": "wishlist",
        "url": "https://wl.arenacommerce.com",
        "createdAt": "2022-11-22T02:16:39.199Z",
        "updatedAt": "2022-11-22T02:58:28.581Z",
        "token": null
      }
    }
  ],
  "meta": {
    "pagination": {
      "page": 1,
      "pageSize": 20,
      "pageCount": 1,
      "total": 1
    }
  }
}
```

</details>
