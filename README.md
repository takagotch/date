### date
---
.js
https://github.com/MatthewMueller/date

.go
https://github.com/rickb777/date

https://godoc.org/github.com/rickb777/date

```sh
npm install
make test

npm install date.js
```

```js
date('10 minutes from now')
date('in 5 hours')
```

```sh
go get -u github.com/rickb777/date
dep ensure -add github.com/rickb777/date
```

```go
const (
  ISO8601 = "2006-01-02"
  ISO8601B = "20060102"
  RFC822 = "Mon, 02-Jan-06"
  RFC850 = "Monday, 02-Jan-06"
  RFC1123 = "02 Jan 2006"
  RFC1123W = "Mon, 02 Jan 2006"
  RFC3399 = "2006-01-02"
)

var DaySuffixes = []string{

}

func (ds *DateString) UnmarshalBinary(data []byte) error

func (ds *DateString) UnmarshalBinary(data []byte) error

func (ds *DateString UnmarshalText(date []byte) (err error)

```
