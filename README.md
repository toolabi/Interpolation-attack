# 📌 Interpolation Attack

🔒 **Interpolation Attack** is a cryptanalysis technique that targets cryptographic algorithms by leveraging polynomial interpolation to reconstruct secret information. This repository explores its implementation and practical implications.

---

## 🚀 Features  
- Implementation of **interpolation attacks** in Rust  
- Attacking polynomial-based cryptographic schemes  
- Examples and test cases for different attack scenarios  

---

## 🔧 Installation  

Clone the repository:  
```bash
git clone git@github.com:toolabi/Interpolation-attack.git
cd Interpolation-attack
```

Build the project:  
```bash
cargo build
```

Run tests:  
```bash
cargo test
```

---

## 🛠 Usage  

Run the attack implementation:  
```bash
cargo run
```

If you want to modify parameters, check `src/main.rs` and update configurations.

---

## 📖 Background  

The **interpolation attack** exploits the fact that a polynomial of degree `d` can be uniquely determined using `d+1` known points. If an attacker can obtain enough input-output pairs, they can reconstruct the secret polynomial used in cryptographic schemes such as:  
- **Lagrange interpolation attacks** on stream ciphers  
- **Polynomial-based encryption vulnerabilities**  
- **Shamir's Secret Sharing scheme weaknesses**  

This implementation demonstrates how an attacker can recover missing coefficients by analyzing given data points.



