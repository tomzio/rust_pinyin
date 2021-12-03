# rust-pinyin
Change chinese sentence to pinyin initials

将汉字转成拼音首字母，用于自动完成的快捷拼音输入

## Installation

Add this to your Cargo.toml:

```
[dependencies]
rust-pinyin = "0.1"
```
## How to use:

```rust
use rust_pinyin::get_pinyin;

assert_eq!("kjpysr123abc", get_pinyin("快捷拼音输入123abc"));
assert_eq!("amxlklwsjp", get_pinyin("阿莫西林克拉维酸钾片"));
assert_eq!("aboddka.kbddcd", get_pinyin("ABO滴度（抗A.抗B滴度测定）"));
assert_eq!("pttzsy", get_pinyin("葡萄糖注射夜"));

```


# Add this to your package.json

```npm
import { get_pinyin, greet } from "@tomzio/rust-pinyin";

console.log("kjpysr123abc", get_pinyin("快捷拼音输入123abc"));
console.log("amxlklwsjp", get_pinyin("阿莫西林克拉维酸钾片"));
console.log("aboddka.kbddcd", get_pinyin("ABO滴度（抗A.抗B滴度测定）"));
console.log("pttzsy", get_pinyin("葡萄糖注射夜"));

```
