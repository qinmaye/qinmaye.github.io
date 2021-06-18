---
title: "First"
date: 2021-04-03T14:11:55+08:00
draft: false
tags: ["测试"]
---
> 测试文章摘要
<!--more-->

# 测试新博客

## 这是二级标题

- 一
- 二
- 三

1. 111
2. 222
3. 333

```cpp
std::mutex mtx;
void critical() {
  std::lock_guard<std::mutex> lock(mtx);
  // do something
}
```
$
\begin{matrix}
  a & b \\
  c & d
\end{matrix}
$

`狗屁不通文章`

  那么， 对**我个人**而言，[中午吃什么](www.baidu.com)不仅仅是一个重大的事件，还可能会改变我的人生。 迈克尔·F·斯特利说过一句富有哲理的话，最具挑战性的挑战莫过于提升自我。这句话语虽然很短，但令我浮想联翩。 韩非说过一句富有哲理的话，内外相应，言行相称。这似乎解答了我的疑惑。 这种事实对本人来说意义重大，相信对这个世界也是有一定意义的。 中午吃什么的发生，到底需要如何做到，不中午吃什么的发生，又会如何产生。 马云曾经提到过，最大的挑战和突破在于用人，而用人最大的突破在于信任人。这似乎解答了我的疑惑。 经过上述讨论。

我认为， 总结的来说， 歌德曾经提到过，决定一个人的一生，以及整个命运的，只是一瞬之间。这启发了我， 我认为， 中午吃什么，到底应该如何实现。 日本谚语曾经提到过，不幸可能成为通向幸福的桥梁。这启发了我， 中午吃什么因何而发生？ 从这个角度来看， 本人也是经过了深思熟虑，在每个日日夜夜思考这个问题。 赫尔普斯曾经说过，有时候读书是一种巧妙地避开思考的方法。我希望诸位也能好好地体会这句话。 在这种困难的抉择下，本人思来想去，寝食难安。
　　
中午吃什么，发生了会如何，不发生又会如何。 郭沫若在不经意间这样说过，形成天才的决定因素应该是勤奋。带着这句话，我们还要更加慎重的审视这个问题： 中午吃什么，到底应该如何实现。 要想清楚，中午吃什么，到底是一种怎么样的存在。 我认为， 本人也是经过了深思熟虑，在每个日日夜夜思考这个问题。 中午吃什么的发生，到底需要如何做到，不中午吃什么的发生，又会如何产生。 每个人都不得不面对这些问题。 在面对这种问题时， 吉格·金克拉曾经提到过，如果你能做梦，你就能实现它。我希望诸位也能好好地体会这句话。 我们不得不面对一个非常尴尬的事实，那就是， 卡耐基曾经说过，我们若已接受最坏的，就再没有什么损失。这不禁令我深思。 我们一般认为，抓住了问题的关键，其他一切则会迎刃而解。 我们都知道，只要有意义，那么就必须慎重考虑。 我们一般认为，抓住了问题的关键，其他一切则会迎刃而解。
　　

生活中，若中午吃什么出现了，我们就不得不考虑它出现了的事实。 所谓中午吃什么，关键是中午吃什么需要如何写。 可是，即使是这样，中午吃什么的出现仍然代表了一定的意义。 要想清楚，中午吃什么，到底是一种怎么样的存在。 生活中，若中午吃什么出现了，我们就不得不考虑它出现了的事实。 每个人都不得不面对这些问题。 在面对这种问题时， 莎士比亚曾经说过，人的一生是短的，但如果卑劣地过这一生，就太长了。带着这句话，我们还要更加慎重的审视这个问题： 可是，即使是这样，中午吃什么的出现仍然代表了一定的意义。 这种事实对本人来说意义重大，相信对这个世界也是有一定意义的。 在这种困难的抉择下，本人思来想去，寝食难安。

```js
function helloWorld () {
  alert("Hello, World!")
}
```

<!--more-->

```java
public class HelloWorld {
  public static void main(String[] args) {
    System.out.println("Hello, World!");
  }
}
```

```kotlin
package hello

fun main(args: Array<String>) {
  println("Hello World!")
}
```

```c
#include <stdio.h>

/* Hello */
int main(void){
  printf("Hello, World!");
  return 0;
}
```

```cpp
// 'Hello World!' program 
 
#include <iostream>
 
int main(){
  std::cout << "Hello World!" << std::endl;
  return 0;
}
```

```cs
using System;
class HelloWorld{
  public static void Main(){ 
    System.Console.WriteLine("Hello, World!");
  }
}
```

```html
<html>
<body>
  Hello, World!
</body>
</html>
```

```go
package main
import fmt "fmt"

func main() 
{
   fmt.Printf("Hello, World!\n");
}
```

```scala
object HelloWorld with Application {
  Console.println("Hello, World!");
}
```

```php
<?php
  echo 'Hello, World!';
?>
```

```python
print("Hello, World!") 
```

```clojure
(defn hello-world
  "A function print 'Hello world'."
  []
  (prn "Hello world"))
```

```go-html-template
<!DOCTYPE html>
<html>
<head>
  <title>{{ .Title }}</title>
</head>
<body>
  <h1>{{ .Title }}</h1>
  {{ .Content }}
</body>
</html>
```

```go-html-template
{{ partial "header.html" . }}

  <h1>posts</h1>
  {{ range first 10 .Data.Pages }}
    {{ if eq .Type "post"}}
      <h2><a href="{{ .Permalink }}">{{ .Title }}</a></h2>
    {{ end }}
  {{ end }}

  <h1>pages</h1>
  {{ range .Data.Pages }}
    {{ if or (eq .Type "page") (eq .Type "about") }}
      <h2><a href="{{ .Permalink }}">{{ .Type }} - {{ .Title }} - {{ .RelPermalink }}</a></h2>
    {{ end }}
  {{ end }}

{{ partial "footer.html" . }}
```

---

Detect the language

```
package hello

fun main(args: Array<String>) {
  println("Hello World!")
}
```

```
<?php
  echo 'Hello, World!';
?>
```

---