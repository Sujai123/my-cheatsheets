# HTML Cheatsheets

## Table of contents
-----------------

1.  [Head](#head)
    - [Common Tags](#common-tags)
    - [Meta Tag](#meta-tag)
2.  [Headings](#headings)
3.  [Typography](#typography)
4.  [Images](#images)
    - [Responsive images](#responsive-images)
5.  [Inputs](#inputs)
    - [Types](#types)
    - [Attributes](#attributes)
6.  [Audio & Video](#audio-video)
7.  [Basic Layout](#basic-layout)

- [ ] Add Global Attributes and Event Attributes
- [ ] Accessibility
- [ ] Update Description

### Head
#### Common Tags
| Tag Name  | Available Attribute | UseCase |
| ------------- | ------------- | --- |
| title  | NA  | NA  |
| link  | rel | `<link rel="stylesheet" href="style.css" />` <br> `<link rel="icon" type="image/svg+xml" href="/logo.svg" />` |
| script | type, src, defer, async | NA |

#### Meta Tag
| Attribute | Possible Values |
|-----------|-----------------|
|charset 	  | character_set(utf-8) |
|content 	  | text |
|http-equiv |	content-security-policy, content-type, default-style, refresh |
|name       | 	application-name, author, description, generator, keywords, viewport |

### Headings
| Available Tag  | Fontsize | Weight | pixel height |
| -------------- | -------- | ------ | ------------ |
| h1             | 2em      | bolder | 32px         |
| h2             | 1.5em    | bolder | 24px         |
| h3             | 1.17em   | bolder | 18.72px      |
| h4             | 1em      | bolder | 16px         |
| h5             | .83em    | bolder | 13.28px      |
| h6             | .67em    | bolder | 10.72px      |

### Typography
| Available Tag  |
| -------------  |
| p              |
| b              |
| i              |
| em             |
| u              |
| a              |
| superscript    |
| subscript      |

### Images

#### Responsive Images

```html
 <img
  srcset="elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w"
  sizes="(max-width: 600px) 480px,
         800px"
  src="elva-fairy-800w.jpg"
  alt="Elva dressed as a fairy" />
```

### Inputs

#### Types
| Name      |
| --------  |
| text      |
| password  |
| search    |
| tel       |
| number    |
| hidden    |
| email     |
| date      |
| time      |
| file      |
| radio     |
| checkbox  |
| range     |

#### Attributes

| Name              | Description   |
| -------------     | ------------- |
| disabled          | NA            |
| required          | NA            |
| checked           | NA            |
| autofocus         | NA            |
| disabled          | NA            |
| autocomplete      | NA            |
| autocompletetype  | NA            |
| autocapitalize    | NA            |
| pattern           | NA            |


### Audio Video
audio and video is used to render audio and video in website respectively. It is used along with the source tag

UseCase
```html
 <audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
 <video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```
#### Attributes

| Name      | Description |
| --------- | ----------- |
| autoplay  | NA          |
| controls  | NA          |
| width     | NA          |
| height    | NA          |
| loop      | NA          |
| muted     | NA          |
| poster    | NA          |
| preload   | NA          |
| src       | NA          |
| width     | NA          |

### Basic Layout
```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <script defer src=""></script>
</head>
<body>
    
</body>
</html>
```
