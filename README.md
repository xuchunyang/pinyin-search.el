# Search Chinese by Pinyin
---
[![MELPA](http://melpa.org/packages/pinyin-search-badge.svg)](http://melpa.org/#/pinyin-search)

## Introduction

Search Chinese by the first letter of Chinese pinyin.

使用拼音首字母搜索中文。

e.g. use `zw` to search `中文` (*Z*hong *W*en).

This package is similar to
[vim-PinyinSearch](https://github.com/ppwwyyxx/vim-PinyinSearch), but
probably more powerful for
[Incremental Search](http://www.gnu.org/software/emacs/manual/html_node/emacs/Incremental-Search.html)
and Emacs itself.

## Screenshot

![Imgur](http://i.imgur.com/nYdtila.gif)

*Notes*: in the above demo, both `叙述` and `小说` are searched by `xs`.

## Installation

Install from Melpa with:

    M-x package-install RET pinyin-search RET

## Usage

- `isearch-forward-pinyin`
- `isearch-backword-pinyin`

## Known Bugs and Limitations

- [anzu.el](https://github.com/syohex/emacs-anzu) compatibility
