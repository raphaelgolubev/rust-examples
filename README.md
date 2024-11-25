# Rust examples

Репозиторий, содержащий примеры работы с Rust.

# VS Code

В репозитории есть директория `.vscode`, которая содержит файл `extensions.json`, 
перечисляющий рекомендуемые расширения для работы с языком `Rust` в `VS Code`.
При открытии папки проекта в `VS Code`, IDE должна предложить Вам установить их.

# Использование

- Клонируйте репозиторий:

    ```bash
    git clone https://github.com/raphaelgolubev/rust-examples.git
    ```

- Перейдите в директорию проекта:

    ```bash
    cd rust-examples
    ```

## MacOS / Linux / WSL

- Скачать и установить Rust: 

    ```bash
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    ```

- Установите Rust, затем выполните команду:

    ```bash
    rustc --version
    ```
    Если установка прошла успешно, то выведется информация о версии Rust

- Компиляция:

    После выполнения этой команды в корневом каталоге должен появиться файл `main`:
    ```bash
    rustc src/main.rs
    ```

- Запуск:
    ```bash
    ./main
    ```

## Windows

- Скачать и установить Rust:

    - Скачайте и установите [Microsoft C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)

    - Перейдите на страницу https://www.rust-lang.org/tools/install. Нажмите на странице кнопку Download Rustup-init.exe (64-bit), если у нас 64-битная версия (как в большинстве случаев), либо Download Rustup-init.exe (32-bit) (если система 32-х битная)

    - Установите Rust, затем выполните команду:

        ```bash
        rustc --version
        ```
        Если установка прошла успешно, то выведется информация о версии Rust

- Компиляция:

    После выполнения этой команды в корневом каталоге должен появиться файл `main.exe`:
    ```bash
    rustc src/main.rs
    ```

- Запуск:
    ```bash
    main
    ```
