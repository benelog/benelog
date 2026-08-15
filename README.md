# Sanghyuk Jung

Software Engineer in NAVER corp.

* Homepage: [https://benelog.net](https://benelog.net)
* LinkedIn : <https://www.linkedin.com/in/benelog>

## Open source projects

Small tools I have released: one command, no install, no config file.

### File transfer

- **[one-ftpserver](https://github.com/benelog/one-ftpserver)** `Go`: A complete FTP server started by one command, with no configuration file. Every setting is a flag, so `--help` is the entire reference, and `--ssl` is all FTPS takes: the certificate is generated in memory at startup.
- **[uploader](https://github.com/benelog/uploader)** `Go`: A single-binary web app for putting a file on a server through a browser. Handy when SSH is not at hand; uploads are streamed to disk, so file size is not a concern.

### Documents and notes

- **[md-lens](https://github.com/benelog/md-lens)** `Go`: A rich terminal Markdown viewer (`mdl`) with syntax-highlighted code, inline images, and large font headings.
- **[pdf-refinery](https://github.com/benelog/pdf-refinery)** `Python`: A CLI that turns scanned book PDFs into searchable documents. [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) text is laid over the page invisibly, so the original appearance is kept while the text becomes searchable and selectable.
- **[obsidian-site](https://github.com/benelog/obsidian-site)** `TypeScript`: A static site generator for Obsidian vaults, with wikilink navigation, auto-generated backlinks, and an interactive link graph. To start from scratch, use [obsidian-site-template](https://github.com/benelog/obsidian-site-template).

### Reaching a running server

- **[shell-proxy](https://github.com/benelog/shell-proxy)** `Go`: An HTTP server that runs shell commands and returns the result as JSON, with a terminal-style web UI. Stateless by default as a single static binary, or `--interactive` for a real PTY streamed to a browser terminal, enough to run `vi` or `top`.
- **[dumper](https://github.com/benelog/dumper)** `Java`: A small web application for downloading a Java stack dump from a browser.

## Open source contributions

Each link opens the pull requests I sent to that project.

- **[Spring Batch](https://github.com/spring-projects/spring-batch/pulls?q=is%3Apr+author%3Abenelog)**: Bug fixes and API additions, including `JobParameters` propagation in `MetaDataInstanceFactory`, delete operations for `ResourcelessJobRepository`, and a `Callable` constructor for `CallableTaskletAdapter`.
- **[Spring Boot](https://github.com/spring-projects/spring-boot/pulls?q=is%3Apr+author%3Abenelog)**: Corrections to the Batch auto-configuration properties and their documentation.
- **[Robolectric](https://github.com/robolectric/robolectric/pulls?q=is%3Apr+author%3Abenelog)**: Shadow implementations, including `ShadowProcess` and a reimplementation of `ShadowCookieManager` on top of Apache HttpClient's `CookieStore`.
- **[Apache Struts](https://github.com/apache/struts/pulls?q=is%3Apr+author%3Abenelog)**: Corrections to logging messages, applied to both the 2.3.x and 2.5.x branches.
- **[Fixture Monkey](https://github.com/naver/fixture-monkey/pulls?q=is%3Apr+author%3Abenelog)**: Build and CI work, including test, SpotBugs and Checkstyle reporting on GitHub Actions, and the release build setup.
- **[Spring JDBC Plus](https://github.com/naver/spring-jdbc-plus/pulls?q=is%3Apr+author%3Abenelog)**: Test and Checkstyle reporting on GitHub Actions, and an expanded README.
- **[tz database](https://github.com/eggert/tz/commit/929c14a3d8ce505a9b8fb7099bee3a03ccf7e8e4)**: Corrections to Korean time zone history. Many pre-1989 time stamps for `Asia/Seoul` and `Asia/Pyongyang` were fixed from my report, released in tzdata 2014j. The tz project takes patches by mailing list, so this one links to the commit instead.
