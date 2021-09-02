# rust_pinyin
Chinese pinyin initials in rust

中文词句的拼音首字母缩写, 通过输入拼音获取全部词句, 适合项目中的自动完成功能

## Installation

Add this to your Cargo.toml:

```
[dependencies]
rust-pinyin = "0.1"
```
## How to use:

```rust
use rust-pinyin::get_pinyin;

assert_eq!("zhq123vc", get_pinyin("张华强123vc"));
assert_eq!("bjyrysmyxgs", get_pinyin("北京益瑞盈商贸有限公司"));
assert_eq!("xnbjjsyxgs", get_pinyin("信念（北京）技术有限公司"));

```

