---
title: "SpaceVim lang#tcl layer"
description: "This layer is for Tcl development, provide syntax checking, code runner and repl support for tcl file."
---

# [Available Layers](../../) >> lang#tcl

<!-- vim-markdown-toc GFM -->

- [Description](#description)
- [Install](#install)
- [Features](#features)
- [Key bindings](#key-bindings)
  - [Running current script](#running-current-script)
  - [Inferior REPL process](#inferior-repl-process)

<!-- vim-markdown-toc -->

## Description

This layer is for Tcl development.

## Install

To use this configuration layer, update custom configuration file with:

```toml
[[layers]]
  name = "lang#tcl"
```
## Features

- repl support
- code runner

## Key bindings

### Running current script

To running a Tcl file, you can press `SPC l r` to run current file without loss focus, and the result will be shown in a runner buffer.

### Inferior REPL process

Start a `tclsh` inferior REPL process with `SPC l s i`.

Send code to inferior process commands:

| Key Bindings | Descriptions                                     |
| ------------ | ------------------------------------------------ |
| `SPC l s b`  | send buffer and keep code buffer focused         |
| `SPC l s l`  | send line and keep code buffer focused           |
| `SPC l s s`  | send selection text and keep code buffer focused |
