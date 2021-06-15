# Hello Yew

Sample app using Yew

ref: https://yew.rs/ja/getting-started/build-a-sample-app

```
# build app
wasm-pack build --target web --out-name wasm --out-dir ./static

# serve app (with miniserve)
cargo install miniserve
miniserve ./static --index index.html
```
