# Generate from Template
```
cargo generate --git https://github.com/rustwasm/wasm-pack-template

name=game-of-life
```

# build
```
cd $name
wasm-pack build
```

# init /www dir
```
npm init wasm-app www
```
