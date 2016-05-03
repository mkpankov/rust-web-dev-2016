# Практика разработки веб-приложений на Rust

Rust позволяет писать быстрые и надёжные программы. Особенно когда они
многопоточные. Это делает его хорошим выбором для написания серверной части
разнообразных веб-приложений.

Но что для этого нужно? Зачем терпеть все эти длиннющие ошибки от borrow
checker'а? Что с продуктивностью разработки? Где взять библиотеки? А что если
библиотеки нет? Какой веб-фреймворк выбрать? Как отлаживать и профилировать код?

В своём докладе я отвечу на эти и другие вопросы. Ещё я расскажу, что нужно
делать, чтобы обойти проблемные места, которые у Rust, конечно, тоже есть.

Всё это — на примере кода инфраструктурного сервера, обеспечивающего «всегда
зелёный master» (commit gatekeeper, аналог homu и zuul).