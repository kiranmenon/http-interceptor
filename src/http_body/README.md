docker run --rm -v $(pwd):/src --workdir=/src tinygo/tinygo:0.28.1  tinygo build -o builds/wasm.wasm -scheduler=none -target=wasi /src/http_body/main.go
