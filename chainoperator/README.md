## Setup

1) Make sure you have the latest version of hugo.

```
brew upgrade hugo
```

2) Clone this repo and cd into it.

3) Run the hugo dev server.

```
hugo server -D
```

4) The homepage should be at http://localhost:8888/ and you can see an example article at http://localhost:8888/article/hello-world/

The homepage file that you'll want to edit is located at: `layouts/_default/list.html`

The article file is: `layouts/_default/single.html`

There are partial files for the head, header, and footer. Also a 404.html page.