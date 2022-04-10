+++
title = "关于我"
menu = "main"
+++

# About Me

{{ $image := .Resources.GetMatch "images/1.gif" }}
<img src="{{ $image.RelPermalink }}" width="{{ $image.Width }}" height="{{ $image.Height }}">
[GitHub](https://github.com/jiezai-cbd).
