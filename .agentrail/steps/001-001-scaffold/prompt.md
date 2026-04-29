Scaffold the web-tf24a Yew/WASM project:

1. Set up Cargo.toml with dependencies:
   - cor24-emulator (path = "../../sw-embed/cor24-rs", default-features = false)
   - cor24-isa (path = "../../sw-embed/cor24-rs/isa", features = ["serde"])
   - yew 0.21 (features = ["csr"])
   - wasm-bindgen, web-sys, gloo
2. Create Trunk.toml (dist output, port 9181)
3. Create index.html with Catppuccin Mocha dark theme
4. Create src/main.rs (Yew app entry)
5. Create src/lib.rs (App component with header/footer)
6. Create asm/ directory, copy forth.s from tf24a
7. Create src/config.rs with ForthTier enum (planning for multiple tiers, starting with Phase1)
8. Create scripts/serve.sh
9. Verify WASM build compiles with trunk build

Follow web-tml24c patterns for structure. Focus on assembly-level debugger initially since tf24a is Phase 1-2.