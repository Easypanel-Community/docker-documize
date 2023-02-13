# docker-documize
An unofficial documize docker image

---
[![Easypanel](https://raw.githubusercontent.com/Supernova3339/Supernova3339/main/easypanel.png)](https://easypanel.io/docs/templates/documize)

| ENV | Description | Required |
| ------ | ------ | ------ |
| DOCUMIZELOCATION | where it is located | YES
| DOCUMIZEDBTYPE | db type | YES
| DOCUMIZESALT | db salt | YES
| DOCUMIZEDB=host=hostname port=portnum sslmode=disable user=postgres password=password dbname=databasename | db conn | YES

[💡] For `DOCUMIZEDBTYPE` we used `postgresql` with an image of `postgres:12`
