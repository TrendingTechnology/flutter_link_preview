# flutter_link_preview

This is a URL preview plugin that previews the content of a URL

Language: [English](README.md) | [中文简体](README-ZH.md)

![Demo](demo.jpg)

## Special feature

-   Result caching and expiration mechanism for faster return of results
-   Better fault tolerance, multiple ways to find icons
-   Better support for Chinese, no garbled code.

## Getting Started

```
FlutterLinkPreview(
    url: "https://github.com",
    titleStyle: TextStyle(
        color: Colors.blue,
        fontWeight: FontWeight.bold,
    ),
)
```

Result:

![Result Image](web.jpg)

> You can also use builder to display custom styles
