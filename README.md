# Remove_Hidden_Characters
Methods to remove special-hidden characters by unix commands <br>
Some commands work for some situations, just try

```
sed $'s/[^[:print:]\t]//g' filename
```
