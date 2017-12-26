# application-rs
Rust graphical application starter, uses stdweb for wasm32 & glutin for the rest


```rust
fn main() {
    let config = AppConfig::new("Title Sample",(600,400));
    let mut app = App::new(config);
    app.run(||{

    });
}
```