# Sanghyuk Jung

I build small tools that run without configuration — one command, no install, no config file.

[benelog.net](https://benelog.net)

## File transfer

- **[one-ftpserver](https://github.com/benelog/one-ftpserver)** `Go` — A complete FTP server started by one command, with no configuration file. Every setting is a flag, so `--help` is the entire reference, and `--ssl` is all FTPS takes: the certificate is generated in memory at startup.
- **[uploader](https://github.com/benelog/uploader)** `Go` — A single-binary web app for putting a file on a server through a browser. Handy when SSH is not at hand; uploads are streamed to disk, so file size is not a concern.

## Documents and notes

- **[md-lens](https://github.com/benelog/md-lens)** `Go` — A rich terminal Markdown viewer (`mdl`): syntax-highlighted code, inline images, and large font headings.
- **[pdf-refinery](https://github.com/benelog/pdf-refinery)** `Python` — A CLI that turns scanned book PDFs into searchable documents. [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) text is laid over the page invisibly, so the original appearance is kept while the text becomes searchable and selectable.
- **[obsidian-site](https://github.com/benelog/obsidian-site)** `TypeScript` — A static site generator for Obsidian vaults, with wikilink navigation, auto-generated backlinks, and an interactive link graph. To start from scratch, use [obsidian-site-template](https://github.com/benelog/obsidian-site-template).

## Reaching a running server

- **[shell-proxy](https://github.com/benelog/shell-proxy)** `Java` — A proxy server that executes shell commands through URL calls.
- **[dumper](https://github.com/benelog/dumper)** `Java` — A small web application for downloading a Java stack dump from a browser.
