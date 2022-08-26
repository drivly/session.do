# session.do
Session Storage supporting both encrypted cookies and edge-persisted state

Worker to interact with session via <https://github.com/vvo/iron-session>

<https://session.do>
```
{
  "recentInteractions": 12
}
```

<https://session.do/set?name=John+Doe&email=john@example.com&image=https://favicon.com/john@example.com>

```
{
  "recentInteractions": 13,
  "name": "John Doe",
  "email": "john@example.com",
  "image": "https://favicon.com/john@example.com"
}
```
