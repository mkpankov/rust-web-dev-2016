# Заметки

* Разные версии крейтов в одном бинарнике

```text
± % ➜  cargo check                                                                                                                                                                                           !5626
   Compiling shurik v0.1.0 (file:///home/mkpankov/shurik_git)
<std macros>:6:1: 6:32 error: the trait `core::convert::From<url::parser::ParseError>` is not implemented for the type `url::parser::ParseError` [E0277]
<std macros>:6 $ crate:: convert:: From:: from ( err ) ) } } )
               ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/gitlab.rs:40:19: 40:45 note: in this expansion of try! (defined in <std macros>)
<std macros>:6:1: 6:32 help: run `rustc --explain E0277` to see a detailed explanation
<std macros>:6:1: 6:32 note: required by `core::convert::From::from`
src/gitlab.rs:43:9: 46:10 error: mismatched types:
 expected `core::result::Result<gitlab::Api, url::parser::ParseError>`,
    found `gitlab::Api`
(expected enum `core::result::Result`,
    found struct `gitlab::Api`) [E0308]
src/gitlab.rs:43         Api {
src/gitlab.rs:44             root: url,
src/gitlab.rs:45             key_path: path,
src/gitlab.rs:46         }
src/gitlab.rs:43:9: 46:10 help: run `rustc --explain E0308` to see a detailed explanation
error: aborting due to 2 previous errors
Could not compile `shurik`.

To learn more, run the command again with --verbose.
An unknown error occurred

To learn more, run the command again with --verbose.

```

* Сильный дрифт вправо

* Инфраструктура - racer, Emacs, IDE
