command to resize images:  
`for file in *; do convert "${file}" -resize 800x600! "${file/_original/}"; done
`