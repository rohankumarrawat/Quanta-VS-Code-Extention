
# Quanta Language Support for VS Code

This extension provides comprehensive language support for the **Quanta** programming language (`.qnt`) in Visual Studio Code. It includes syntax highlighting, code snippets, and language configuration features to streamline your Quanta development.

## 🚀 Features

* **File Association**: Automatically detects and associates `.qnt` files as Quanta language files.
* **Syntax Highlighting**: robust highlighting for Quanta-specific keywords, types, control structures, and strings.
* **Code Snippets**: Built-in snippets for common patterns like loops, variable declarations, and the main function.
* **Comment Support**: Support for both single-line (`@` or `//`) and block comments (`'''` or `"""`).
* **Bracket Matching**: Auto-closing and matching for `{ }`, `[ ]`, and `( )`.

## 📝 Syntax Highlighting

The extension highlights the following elements of the Quanta language:

* **Keywords**: `if`, `else`, `loop`, `return`, `def`, `extern`.
* **Types**: `int`, `float`, `bool`, `char`, `string`, `var`.
* **Functions**: `print`.
* **Comments**:
* Line comments starting with `@` .
* Block comments enclosed in `'''` or `"""`.



### Example Code

```quanta
@ This is a single line comment using '@'
// This is also a comment

int main() {
    int count = 10;
    
    loop (count > 0) {
        print(count);
    }
}

```

## ✂️ Snippets

Use the following snippets to quickly generate code:

| Trigger | Description | Output Preview |
| --- | --- | --- |
| `main` | Main Function | `int main() { ... }` |
| `loop` | Loop Statement | `loop (condition) { ... }` |
| `print` | Print Statement | `print(variable);` |
| `var` | Declare Variable | `int/float/bool name = value;` |

*Ref:*

## ⚙️ Installation

1. Open **Visual Studio Code**.
2. Go to the **Extensions** view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
3. Search for "Quanta".
4. Click **Install**.
5. Open any `.qnt` file to see the extension in action.

## 📋 Requirements

* **VS Code Version**: `^1.70.0` or higher.

## 📅 Release Notes

### 0.0.1

* Initial release of the Quanta Language extension.
* Added syntax highlighting for basic keywords and types.
* Added snippets for `main`, `loop`, `print`, and `var`.
* Added icon and language configuration.

---

**Publisher**: Rohan

**License**: MIT
