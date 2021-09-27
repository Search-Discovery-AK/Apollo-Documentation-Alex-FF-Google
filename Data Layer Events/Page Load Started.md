# Page Load Started

### 

## Javascript Code
```js
window.dataLayer1 = window.dataLayer1 || [];
dataLayer1.push({
  "event": "Page Load Started",
    "country": "<country>",
    "language": "<language>",
    "page_location": "<page_location>",
    "page_title": "<page_title>",
    "page_type": "<page_type>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|country|string|The country the site is associated with.||||||||
|language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_location|string|The url of the page currently being viewed.||||||||
|page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_type|string|The type of page currently viewed.|home, pdp, article|||||||

## Attached Notes

<p>222</p>