```rust
struct Student<'a> {
    name: &'a str,
    age: u8,
    college: &'a str,
    languages: Vec<&'a str>,
    cats: Vec<Cat>,
}

fn main() {
    let me = Student {
        name: "Jorge Terence",
        age: 19,
        college: "Fatec SCS",
        languages: vec!["Português", "English", "日本語"],
        cats: vec![nico],
    };
}
```
