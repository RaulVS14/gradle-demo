## Create tasks to gradle

```groovy
tasks.register('helloGradle'){
    doLast {
        println 'Hello World'
    }
}
```
## List tasks

```
gradle tasks --all
```

