# Simple Project README
# Simple shell script count itens in /etc directory.
#!/bin/sh

echo "Uniq Itens"
ls /etc | cut -d ' ' -f 1 | sort | uniq | wc -l

