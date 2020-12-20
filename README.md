# gradle-14972

https://github.com/gradle/gradle/issues/14972

To reproduce the bug please execute

```bash
gradle :clean :build --warning-mode all ; cat ./build/tmp/jar/MANIFEST.MF
```

