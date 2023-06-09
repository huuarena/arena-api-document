# PRIVACY

Base URL:

---

#####

<details>
<summary><code><b>JSON</b></code></summary>

#####

```
{
  "content": "" // string, required
}
```

</details>

#####

<details>
<summary><code><b>GET</b></code> <code><b>/privacies</b> Get list privacies</code></summary>

##### Endpoint

```
/privacies?pagination[page]=1&pagination[pageSize]=20&sort=id:desc
```

##### Parameter

```
{
  "pagination": {
    "page": "1",
    "pageSize": "20"
  },
  "sort": "id:desc"
}
```

##### Response

```
{
  "data": [
    {
      "id": 4,
      "attributes": {
        "content": "<p>Privacy</p>",
        "createdAt": "2023-04-07T10:13:54.171Z",
        "updatedAt": "2023-04-07T10:13:54.171Z"
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

#####

<details>
<summary><code><b>GET</b></code> <code><b>/privacies</b> Get list privacies by app </code></summary>

##### Endpoint

```
/privacies?filters[app][uid]=wishlist
```

##### Parameter

```
{
  "filters": {
    "app": {
      "uid": "wishlist"
    }
  }
}
```

##### Response

```
{
  "data": [
    {
      "id": 3,
      "attributes": {
        "content": "<p>Privacy</p>",
        "createdAt": "2022-11-22T02:17:04.349Z",
        "updatedAt": "2022-11-22T02:17:04.349Z"
      }
    }
  ],
  "meta": {
    "pagination": {
      "page": 1,
      "pageSize": 25,
      "pageCount": 1,
      "total": 1
    }
  }
}
```

</details>
