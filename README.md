# Webecon — Rust SDK (v17.2.6 PRO)

Official Rust SDK for the **Webecon Universal Animated Icon Engine**. 

### **1,031+ Premium Animated Icons | Professional Themes | 100% Free for Commercial Use**

Webecon is a professional-grade iconography ecosystem. This SDK allows Rust developers to generate themeable, animated icon tags natively in web frameworks like Axum, Rocket, or Actix.

---

## 🚀 Quick Start

### Installation
Add Webecon to your `Cargo.toml`:
```toml
[dependencies]
webecon = "17.2.6"
```

### Usage
```rust
use webecon::Webecon;

fn main() {
    // Generate a high-performance icon tag
    let icon = Webecon::icon("rocket")
        .size(64)
        .theme("shine")
        .trigger("hover")
        .build();

    println!("{}", icon); 
    // Output: <webecon-icon name='rocket' size='64' ...></webecon-icon>
}
```

---

## 🌟 Key Features
- **✨ Professional Themes**: Shine (Glossy), Duo Tone, Glitch, Neon, and Glassmorphism.
- **🎨 Dual-Color System**: Full support for Primary and Secondary branding colors.
- **🎬 20+ Motion Presets**: Pulse, Spin, Jello, Rubber-Band, and more.
- **🦾 Zero-Cost Abstractions**: High-performance Rust implementation with minimal overhead.

---

## 📝 Commercial License
Webecon is 100% Free for commercial projects. Standalone resale of the icons is prohibited.

Produced by **Aditya Divte Production**  
Official Website: [adityadivte.com](https://adityadivte.com)  
Visit - [webecon.adityadivte.com](https://webecon.adityadivte.com/) for more info