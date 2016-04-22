# ratings

```bash
$ gunzip ratings.dat.gz
$ influx -execute "create database ML1M"
$ go run main.go
$ influx -database ML1M -execute "select count(rating) from movielens"
$ influx -database ML1M -execute "show series"
```
