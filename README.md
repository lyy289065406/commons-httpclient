# commons-httpclient

> 修复 commons-httpclient-3.1 自动重定向丢失 Response Header 中的 Set-Cookie 的 BUG

------

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

