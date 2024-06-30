This is an application [minigrep]

[minigrep] helps to find phrase or words from txt file

**How to use**

```
cargo run {key_word} {file_name}
```

If you want to find the words without interfere of upper_lower_case
You can set the environmental values
```
export CASE_INSENSITIVE=true
```
and reset by
```
unset CASE_INSENSITIVE
```


**You can export the output to the output.txt**

```
cargo run {key_word} {file_name} > output.txt
```
