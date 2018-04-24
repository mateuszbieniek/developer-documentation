# test 2

??? summary "HTML (please only in special cases)"

    In special cases, you can also use raw HTML in your document.

        <style>.special img {height:32px; vertical-align:middle}</style>
        <div class="special">
        [![](https://www.gstatic.com/webp/gallery3/5.png)](https://developers.google.com/speed/webp/gallery2)
        Click on this icon
        </div>

    <style>.special img {height:32px; vertical-align:middle}</style>
    <div class="special">
    [![](https://www.gstatic.com/webp/gallery3/5.png)](https://developers.google.com/speed/webp/gallery2)
    Click on this icon
    </div>


??? summary "HTML (please only in special cases)"

    In special cases, you can also use raw HTML in your document.

    ~~~.markdown
    <style>.special img {height:32px; vertical-align:middle}</style>
    <div class="special">
    [![](https://www.gstatic.com/webp/gallery3/5.png)](https://developers.google.com/speed/webp/gallery2)
    Click on this icon
    </div>
    ~~~

    <style>.special img {height:32px; vertical-align:middle}</style>
    <div class="special">
    [![](https://www.gstatic.com/webp/gallery3/5.png)](https://developers.google.com/speed/webp/gallery2)
    Click on this icon
    </div>


??? summary "Sequence diagrams"

    ~~~.markdown
    ```sequence
    Title: Example sequence diagram
    A->B: Sync call
    B-->A: Sync return
    A->C: Another sync call
    C->>D: Async call
    D-->>C: Async return
    ```
    ~~~

    ```sequence
    Title: Example sequence diagram
    A->B: Sync call
    B-->A: Sync return
    A->C: Another sync call
    C->>D: Async call
    D-->>C: Async return
    ```

```html
{% block my_fieldtype_widget %}
    Hello world!
    {{ block('form_widget') }}
{% endblock %}
```


## test 2

$$$
    In special cases, you can also use raw HTML in your document.

    ~~~.markdown
    <style>.special img {height:32px; vertical-align:middle}</style>
    <div class="special">
    [![](https://www.gstatic.com/webp/gallery3/5.png)](https://developers.google.com/speed/webp/gallery2)
    Click on this icon
    </div>
    ~~~

    <style>.special img {height:32px; vertical-align:middle}</style>
    <div class="special">
        [![](https://www.gstatic.com/webp/gallery3/5.png)](https://developers.google.com/speed/webp/gallery2)
        Click on this icon
    </div>
$$$


test started here:

[[code_example
function test() {
  console.log("notice the blank line before this function?");
}
code_example]]


test end


test2:

[[code_example
<a href="#"><span class="supertest">to je test</span></a>
code_example]]

test2 end



test3:

<div>

[[code_example
<button type="button" class="ez-button ez-button-ghost">Show 10 more results</button>
code_example]]


</div>
