panINI
====

panINI (parse all INI) is a bash ini parser that can display or set ini configurations files into variables.

Supports both Bash 3 & 4.

Now supports modifying values that are in sections!

Bash 3 sets variables in sections like:

```
Array {
	"key0=value0"
	"key1=value1"
}

echo ${Array[0]}
key0=value0
```

Bash 4 sets variables in sections like:

```
Array {
	"key0" => "value0"
	"key1" => "value1"
}

echo ${Array[key0]}
value0
```
