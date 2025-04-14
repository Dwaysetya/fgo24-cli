# Mini-task CLI usage

This is a bare minimum usage of cli, according to mini task on **Day 1** (14/042025)

## without loop (CMD)

```bash
mkdir   "Latihan LCI Dasar"
cd      "Latihan LCI Dasar"
touch   "latihan1.txt"
touch   "latihan2.txt"
touch   "latihan3.txt"
touch   "latihan4.txt"
touch   "latihan5.txt"
ls
rmdir   "latihan4.txt"
mkdir   "latihan4.txt"
rmdir   "latihan5.txt"
mkdir   "latihan5.txt"
ls
rmdir   "latihan4.txt"

```

## with loop (CMD)

```bash

mkdir   "Latihan LCI Dasar"
cd      "Latihan LCI Dasar"
for i in {1..5}; do
touch Latihan$i.txt
done

 "latihan1.txt"
 "latihan2.txt"
 "latihan3.txt"
 "latihan4.txt"
 "latihan5.txt"

```

## Memindahkan Lagu (CMD)

```bash

mkdir "Blackpink" "Evanescence" "Linkin"

for file in Linkin*.mp3; do
  mv "$file" "Linkin/$file"
done

for file in Evanescence*.mp3; do
  mv "$file" "Evanescence/$file"
done

for file in Blackpink*.mp3; do
  mv "$file" "Blackpink/$file"
done


```
