# List most used commands

	$ history 1 | awk '{a[$2]++}END{for(i in a){print a[i] " " i}}' | sort -rn | head
