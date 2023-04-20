# GPG Appunti

### Generare un file cryptato partendo da una password
```gpg -a -c nome_file```

### Generare una coppia di chiavi per la crittografia asimmetrica
```gpg --full-generate-key```

### Esportare la chiave pubblica
```gpg -a --export "nome_chiave" > pub.gpg```

### Esportare la chiave privata
```gpg -a --export-secret-keys "nome_chiave" > priv.gpg```

### Elenco di tutte le chiavi presenti nel portachiavi
```gpg --list-keys```

### Cifrare un file
```gpg -a --output secret.gpg --encrypt --recipient h4shell@gmail.com nome_file```

### Decifrare un file
```gpg --output output.txt --decrypt nome_file.gpg```

### Firmare un file
```gpg -s nome_file```

### Ottenere un file leggibile una volta ricevuto
```gpg --crearsign nome_file```

### Verificare un file firmato
```gpg --verify nome_file.asc```


