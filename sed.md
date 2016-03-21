# sed

Stream editor for filtering and transforming text.

### Replace all occurences of {from} to {to} from {input_file}

`$ sed 's/{from}/{to}/g' {input_file}`

This will write the output to stdout. Use the `-i` flag to modify the file in-place.
