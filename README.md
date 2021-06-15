# Hello Yew

Sample app using Yew

ref: https://yew.rs/ja/getting-started/build-a-sample-app

```
# build app
wasm-pack build --target web --out-name wasm --out-dir ./pkg

# serve app (with miniserve)
cargo install miniserve
miniserve . --index index.html
```
