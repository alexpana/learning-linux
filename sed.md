# sed

Stream editor for filtering and transforming text.

### Replace all occurences of {from} to {to} from {input_file}

`$ sed 's/{from}/{to}/g' {input_file}`

This will write the output to stdout. Use the `-i` flag to modify the file in-place.

### Delete lines matching {regex} from {input_file}

`$ sed '/{regex}/d' {input_file}`

### Pipe multiple transforms {a} and {b} from {input_file}

`$ sed '{a};{b}' {input_file}` 
