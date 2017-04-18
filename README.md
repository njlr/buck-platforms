# buck-platforms

Run the following to check if the `platform_srcs` argument is working correctly!

```
buck run :hello
```

Or to specify a target...

```
buck run :hello#macosx-x86_64
buck run :hello#linux-x86_64
```
