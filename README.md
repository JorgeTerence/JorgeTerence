```rust
struct Student {
    name: String,
    age: u8,
    college: String,
    languages: Vec<String>,
    cats: Vec<Cat>,
}

fn main() {
    let me = Student {
        name: String::from("Jorge Terence"),
        age: 18,
        college: String::from("Fatec São Caetano do Sul"),
        languages: vec![&"Português", &"English", &"日本語"],
        cats: vec![nico],
    };
}
```
