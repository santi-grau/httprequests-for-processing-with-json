# httprequests-for-processing-with-json

```java
  PostRequest post = new PostRequest("http://remolacha.herokuapp.com/api");
  post.addHeader("Content-Type", "application/json");
  post.addJson("{\"key\": value }");
  post.send();
```
