## I/O

```shell
cat file | grep word | sort -u
```

### Terms
- < -- input
- > -- output
- | -- pipeline -- redirects first output as second input


### Pipelene example
```shell
cut -d: -f1 < /etc/passwd | sort -u | grep -v "[#*]" | wc -l
```

