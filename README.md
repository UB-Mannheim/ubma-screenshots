# ubma-screenshots

This repository is used for storing images to be referenced by other
@UB-Mannheim projects, mostly screenshots of software we develop or recommend.

## How to link

Whenever possible, use [RawGit](https://rawgit.com/) to embed images:

```
https://cdn.rawgit.com/UB-Mannheim/ubma-screenshots/master/<path-to-file>
```

This is a [CDN-backed](https://en.wikipedia.org/wiki/Content_delivery_network) cached
version of the image that is fair to the RawGit servers but not always up-to-date.

When developing/testing, use the uncached version from RawGit or the raw link from Github:

```
https://rawgit.com/UB-Mannheim/ubma-screenshots/<branch>/<path-to-file>
```

```
https://github.com/UB-Mannheim/ubma-screenshots/raw/<branch>/<path-to-file>
```

## Syntax cheat sheet

Embed an image in Markdown:

```
![Alt Text](https://rawgit.com/UB-Mannheim/ubma-screenshots/<branch>/<path-to-file>)
```

Embed an image in a link in Markdown:

```
[![Alt Text](https://rawgit.com/UB-Mannheim/ubma-screenshots/<branch>/<path-to-file>)](https://example.org/link)
```

HTML with size restrictions (can also be used in Github Flavored Markdown):

```
<img src="https://rawgit.com/UB-Mannheim/ubma-screenshots/<branch>/<path-to-file>" height="<height>" width="<width>"/>
```
