# FAQ

Base URL:

---

#####

<details>
<summary><code><b>JSON</b></code></summary>

#####

```
{
  "title": "", // string, required
  "body_html": "", // string
  "handle": "", // string, required
  "page": "", // string
  "top": 0 // number
}
```

</details>

#####

<details>
<summary><code><b>GET</b></code> <code><b>/faqs</b> Get list faqs</code></summary>

##### Endpoint

```
/faqs?filters[app][uid]=native-translate&sort=top:desc&pagination[page]=1&pagination[pageSize]=20
```

##### Parameter

```
{
  "filters":{
    "app":{
      "uid":"native-translate"
    }
  },
  "sort":"top:desc",
  "pagination":{
    "page":"1",
    "pageSize":"20"
  }
}
```

##### Response

```
{
  "data": [
    {
      "id": 35,
      "attributes": {
        "title": "How to activate Language Selector app embed",
        "body_html": "How to activate Language Selector app embed",
        "handle": "how-to-activate-language-selector-app-embed",
        "createdAt": "2023-06-08T10:35:12.985Z",
        "updatedAt": "2023-06-09T04:48:20.815Z",
        "page": null,
        "top": 0,
        "order": null
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
