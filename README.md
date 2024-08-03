```rs
// *** About Me ***
fn main() {
    let me = Person {
        name: String::from("Archil"),
        surname: String::from("Beraia"),
        country: String::from("Georgia"),
        nickname: String::from("arch_il"),
        availability: Availability::Free,
        discord_tag: String::from("arch_il"),
        fav_lang: Language::Rust,
        current_project: String::from("rusty_notes"),
    };
    println!("{:?}", me);
}
```
