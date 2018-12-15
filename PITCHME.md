---?color=#e58537
@title[Introduction]

@snap[west montserrat-heavy h2-white span-60]
## @css[text-85](GitPitch Pro Code Presenting)
@snapend

@snap[east span-40]
@code[go zoom-06](src/go/sample.go)
<br>
@code[http zoom-06](src/http/sample.http)
<br>
@code[sql zoom-06](src/sql/sample.sql)
@snapend

---
@title[Live Code Presenting]

@snap[west montserrat-heavy span-100]
#### Zoom-in, zoom-out, and step-through @css[text-11 text-italic](source code) on any slide within your deck.
@snapend

---?code=src/go/sample.go&lang=golang
@title[Code Delimiter Syntax]

@snap[north-east span-100 text-05]
You can inject code from any repository source file onto a slide using [code delimiter syntax @fa[external-link]](https://gitpitch.com/docs/code-features/source-files).
@snapend

---
@title[Code Shortcut Syntax]

@code[golang](src/go/sample.go)

@snap[north-east span-100 text-05]
But to take advantage of pro rendering capabilities for your source code, use [&#64;code shortcut syntax @fa[external-link]](https://gitpitch.com/docs/markdown-features/pro-widgets).<br>By default, the result is the same. A nicely highlighted code block on your slide.
@snapend

---
@title[Zoom-Out Example]

@snap[west span-40]
@code[golang zoom-07](src/go/sample.go)
@snapend

@snap[east montserrat-heavy span-50]
### Live Code Presenting
@snapend

@snap[north-east span-100 text-05]
To _**zoom-out**_ on a code block, use **&#64;code shortcut syntax** and one of the **built-in zoom** CSS styles.<br>This approach gives you a nice way way to introduce code on upcoming slides.
@snapend

---?color=#333
@title[Blend Code Background]

@code[golang](src/go/sample.go)

@snap[north-east span-100 text-05]
Remember, you can easily blend a code block with the slide background using **color delimiter syntax**.
@snapend

---?color=#333
@title[Zoom-In Example]

@code[golang zoom-21](src/go/sample.go)

@[1](And of course, you can step through your code directly within your slide deck.)
@[3](Using the GitPitch live code presentating with annotations feature.)
@[5-7](Which means no need to switch back and forth between your slide deck and IDE.)

@snap[north-east span-100 text-05]
To _**zoom-in**_ on a code block, use **&#64;code shortcut syntax** and one of the **built-in zoom** CSS styles.
@snapend

---

@snap[west montserrat-heavy]
### Further code examples...
@snapend

---?code=src/css/sample.css
@title[Standard CSS Snippet]

@snap[north-east span-100 text-05]
Standard display of a **CSS Stylesheet** snippet.
@snapend

---
@title[Zoomed CSS Snippet]

@code[css zoom-18](src/css/sample.css)

@snap[north-east span-100 text-05]
Custom zoom on a **CSS Stylesheet** snippet.
@snapend

---?code=src/php/sample.php&lang=php&color=#333
@title[Standard PHP Snippet]

@snap[north-east span-100 text-05]
Standard display of a **PHP Code** snippet.
@snapend

---?color=#333
@title[Zoomed PHP Snippet]

@code[php zoom-19](src/php/sample.php)

@snap[north-east span-100 text-05]
Custom zoom on a **PHP Code** snippet.
@snapend

---?code=src/http/sample.http&lang=http
@title[Standard HTTP Snippet]

@snap[north-east span-100 text-05]
Standard display of **HTTP Response Data** snippet.
@snapend

---
@title[Zoomed HTTP Snippet]

@code[http zoom-15](src/http/sample.http)

@snap[north-east span-100 text-05]
Custom zoom on a **HTTP Response Data** snippet.
@snapend

---?code=src/sql/sample.sql&lang=sql&color=#333
@title[Standard SQL Snippet]

@snap[north-east span-100 text-05]
Standard display of a **SQL** snippet.
@snapend

---?color=#333
@title[Zoomed SQL Snippet]

@code[sql zoom-19](src/sql/sample.sql)

@snap[north-east span-100 text-05]
Custom zoom on a **SQL** snippet.
@snapend

---?code=src/tree/sample.txt&lang=text&color=#333
@title[Standard Tree Snippet]

@snap[north-east span-100 text-05]
Standard display of a **Tree Directory Structure** snippet.
@snapend

---?color=#333
@title[Zoomed Tree Snippet]

@code[text zoom-13](src/tree/sample.txt)

@[2](You can also step through any text-based file content in your repository.)
@[4-16](That includes log files, console output, data files, directory structures, etc.)

@snap[north-east span-100 text-05]
Custom zoom on a **Tree Directory Structure** snippet.
@snapend

---?gist=ValeriiVasin/1548808
@title[Standard GIST Snippet]

@snap[north-east span-100 text-05]
You can also render any **GitHub GIST** on your slides using [&#64;gist shortcut syntax](https://gitpitch.com/docs/markdown-features/pro-widgets).<br>
Standard display of GIST source code snippet.
@snapend

---
@title[Zoomed GIST Snippet]

@gist[js zoom-20](ValeriiVasin/1548808)

@snap[north-east span-100 text-05]
Custom zoom on a GIST source code snippet.
@snapend

---
@title[Documentation Link]

#### See the [Markdown Pro Widgets Guide](https://gitpitch.com/docs/markdown-features/pro-widgets) for further details.

---?image=assets/img/presenter.jpg
@title[Present Like A Pro]

@snap[north-west h4-gray]
#### Present @css[text-gold text-bold]({)@css[text-darkgray text-bold]( your , code ) @css[text-gold text-bold](}) like a **Pro**.
@snapend

@snap[south-west montserrat-heavy h3-white h4-gray span-100]
#### With
### GitPitch @css[text-gold](Code) Presenting
@snapend

