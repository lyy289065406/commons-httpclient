# commons-httpclient

> 修复 commons-httpclient-3.1 自动重定向丢失 Response Header 中的 Set-Cookie 的 BUG

------

## 简介

因此构件的官方组织/作者已放弃维护，且在 maven 中央仓库无法下载原版，故有了此项目，同时很可能会顺便修复一些 BUG。

## 使用方式

maven 的 `settings.yml` 配置 sonatype 中央仓库：

```xml
<mirror>
  <id>sonatype</id>
  <mirrorOf>sonatype</mirrorOf>
  <url>https://s01.oss.sonatype.org/</url>
</mirror>
```

项目的 `pom.xml` 配置构件坐标：

```xml
<dependency>
  <groupId>com.exp-blog</groupId>
  <artifactId>commons-httpclient</artifactId>
  <version>3.2-alpha-SNAPSHOT</version>
</dependency>
```

