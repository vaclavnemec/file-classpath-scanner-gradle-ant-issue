# file-classpath-scanner-gradle-ant-issue
on Mac or Linux run `./gradlew clean replicate` on Windows something like `gradlew.bat clean replicate`

see the output, my is

```
[ant:replicate] Classpath finder found at least one class loader handler: false
[ant:replicate] ServiceLoader found at least one class loader handler: false
[ant:replicate] ServiceLoader found at least one class loader handler using provided classloader: true
```

please see MyTask.groovy
