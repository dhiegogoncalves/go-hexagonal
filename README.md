# Go - Hexagonal Architecture

## API

go run main.go http

- GET -> http://localhost:9000/product/bd543dec-fdec-4c6a-b1db-c86bd6f85c08
- GET -> http://localhost:9000/product/bd543dec-fdec-4c6a-b1db-c86bd6f85c08/enable
- GET -> http://localhost:9000/product/bd543dec-fdec-4c6a-b1db-c86bd6f85c08/disable
- POST -> http://localhost:9000/product
- PUT -> http://localhost:9000/product/bd543dec-fdec-4c6a-b1db-c86bd6f85c08

## CLI

- go run main.go cli -a=create -n="Product 1" -p=25.0
- go run main.go cli -a=update --id=bd543dec-fdec-4c6a-b1db-c86bd6f85c08 -n="Product 1" -p=25.0
- go run main.go cli -a=get --id=bd543dec-fdec-4c6a-b1db-c86bd6f85c08
- go run main.go cli -a=enable --id=bd543dec-fdec-4c6a-b1db-c86bd6f85c08
- go run main.go cli -a=disable --id=bd543dec-fdec-4c6a-b1db-c86bd6f85c08
