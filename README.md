# Mini-task CLI usage

This is a bare minimum usage of cli, according to mini task on **Day 1** (14/042025)

## without loop

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

## with loop

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
