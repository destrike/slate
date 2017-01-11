# Documentation

## Introduction

Welcome to the MYSALE Marketplace Documentation. This documentation contain guidelines that will help you in putting the right code in creating the documentation page.

<hr>

## Highlighting

Code:

<span class="code-highlight">&lt;span class="code-highlight"&gt;Authorization: meowmeowmeow&lt;/span&gt;</span>

Result:

<span class="code-highlight">Authorization: meowmeowmeow</span>

Code:

<span class="code-highlight">&lt;aside class="notice"&gt;
Remember — a happy &lt;span class="code-high"&gt;kitten&lt;/span&gt; is an authenticated kitten!
&lt;/aside&gt;</span>

Result:

<aside class="notice">
Remember — a happy <span class="code-high">kitten</span> is an authenticated kitten!
</aside>

<hr>

## HTTP Verbs

Code:

<span class="code-highlight">&lt;span class="highlight-container"&gt;&lt;span class="post"&gt;post&lt;/span&gt;http://example.com/api/kittens&lt;/span&gt;</span>

Result:

<span class="highlight-container"><span class="post">post</span>http://example.com/api/kittens</span>

<aside class="notice">
You can replace &lt;span class="post"&gt;post&lt;/span&gt; with the following http verbs for intended purpose.
</aside>

Code:

<span class="code-highlight">&lt;span class="get"&gt;get&lt;/span&gt;</span>

Result:

<span class="highlight-container"><span class="get">get</span>http://example.com/api/kittens</span>

Code:

<span class="code-highlight">&lt;span class="delete"&gt;delete&lt;/span&gt;</span>

Result:

<span class="highlight-container"><span class="delete">delete</span>http://example.com/api/kittens</span>

Code:

<span class="code-highlight">&lt;span class="put"&gt;put&lt;/span&gt;</span>

Result:

<span class="highlight-container"><span class="put">put</span>http://example.com/api/kittens</span>

Code:

<span class="code-highlight">&lt;span class="patch"&gt;patch&lt;/span&gt;</span>

Result:

<span class="highlight-container"><span class="patch">patch</span>http://example.com/api/kittens</span>

<hr>

## Aside

#### Notice
Code:

<span class="code-highlight">&lt;aside class="notice"&gt;
Remember — a happy kitten is an authenticated kitten!
&lt;/aside&gt;</span>

Result:

<aside class="notice">
Remember — a happy kitten is an authenticated kitten!
</aside>

#### Success
Code:

<span class="code-highlight">&lt;aside class="success"&gt;
Remember — a happy kitten is an authenticated kitten!
&lt;/aside&gt;</span>

Result:

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>

#### Warning
Code:

<span class="code-highlight">&lt;aside class="warning"&gt;
Remember — a happy kitten is an authenticated kitten!
&lt;/aside&gt;</span>

Result:

<aside class="warning">
Remember — a happy kitten is an authenticated kitten!
</aside>

<hr>

## Table

Code:

<span class="code-highlight">
Parameter | Description<br>
<span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span> | <span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><span>-</span><br>
ID | The ID of the kitten to retrieve<br>
</span>

Result:

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve


<hr>

## Shell Code

Code:

<span class="code-highlight">
&gt; Result:<br>
&#96;&#96;&#96;<br>
&#35; With shell, you can just pass the correct header with each request<br>
curl "api_endpoint_here"<br>
&#32;<span>-</span>H "Authorization: meowmeowmeow"<br>
&#96;&#96;&#96;<br>
</span>


> Result:

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```

<hr>