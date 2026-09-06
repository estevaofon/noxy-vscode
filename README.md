# Nox Language Support for VSCode

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code-Marketplace-blue)](https://marketplace.visualstudio.com/items?itemName=estev.nox-language)

Syntax highlighting and language support for the Nox programming language in Visual Studio Code.

## Features

- **Syntax Highlighting** - Complete syntax highlighting for Nox language files (`.nx`, `.nox`)
- **Auto-completion** - Bracket auto-closing and smart indentation
- **Code Folding** - Support for folding code blocks
- **Comment Toggle** - Easy commenting with `Ctrl+/`

## Supported Syntax

### Keywords
- `func`, `struct`, `let`, `ref`
- `if`, `then`, `else`, `while`, `do`, `for`, `in`, `end`
- `return`

### Types
- `int`, `string`, `bool`, `void`

### Built-in Functions
- `print()`, `strlen()`, `ord()`, `to_str()`, `str_eq()`

### Operators
- Arithmetic: `+`, `-`, `*`, `/`, `%`
- Comparison: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Assignment: `=`
- Arrow: `->`
- Range: `..`

## Installation

### From VSCode Marketplace
1. Open VSCode
2. Go to Extensions view (`Ctrl+Shift+X`)
3. Search for "Nox Language Support"
4. Click Install

### From VSIX File
1. Download the latest `.vsix` file from [Releases](https://github.com/estevaofon/noxy-vscode/releases)
2. Open VSCode
3. Go to Extensions view (`Ctrl+Shift+X`)
4. Click the three dots menu `...`
5. Select "Install from VSIX..."
6. Choose the downloaded `.vsix` file

## Example Code

```nox
// Nox Language Example
func main() -> int
    let nome: string = "Nox Language"
    let idade: int = 25
    let ativo: bool = true
    
    if idade > 18 then
        print("Maior de idade")
    else
        print("Menor de idade")
    end
    
    return 0
end

struct Pessoa
    nome: string
    idade: int
    ativo: bool
end
```

## File Extensions

This extension activates for files with the following extensions:
- `.nx`
- `.nox`

## Language Configuration

The extension provides:
- Line comments with `//`
- Auto-closing pairs for `()`, `[]`, `{}`, `""`
- Smart indentation based on language structure
- Code folding for functions, structs, and control blocks

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Release Notes

### 1.0.0
- Initial release
- Complete syntax highlighting for Nox language
- Support for functions, structs, variables, and control flow
- Auto-completion and bracket matching
- Code folding support

## Issues and Feedback

If you encounter any issues or have suggestions, please [open an issue](https://github.com/estevaofon/noxy-vscode/issues) on GitHub.

---

**Enjoy coding in Nox! 🚀**
