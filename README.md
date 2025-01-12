# Lite XL Markdown Preview
A markdown previewer for [Lite XL](https://github.com/lite-xl/lite-xl) using [luamd](https://github.com/bakpakin/luamd).

![preview of the previewer](assets/mdpreview.gif)

## Installation

Clone this repository into Lite XL's `plugins` folder:
```sh
git clone "https://not-a-web-developer/lite-xl-mdpreview ~/.config/lite-xl/plugins/mdpreview"
```

**Note**: There's a bug with `luamd` which causes finnicky behaviour with fenced codeblocks that don't have a language specified in them; this causes the preview to fail. if this happens to you, you can try the `pandoc` branch instead.

