# Raku Multilingual Modules

*"Programming should be accessible to everyone, in every language."*

A collection of Raku programming language modules that provide native language support for programming in various languages. These modules allow developers to write Raku code using keywords, operators, and functions in their native language while maintaining full compatibility with standard Raku.

**Raku with raku-multilingual modules offers the most comprehensive polyglot programming experience of any programming language.** A polyglot programming language allows developers to write code using multiple natural languages within the same program or ecosystem. This goes beyond simple Unicode identifier support to include keywords, syntax, and programming constructs in different languages.

## Overview

The Raku Multilingual project enables programmers worldwide to code in their native languages. Each module provides:

- Translated keywords and operators
- Native language function names
- Cultural programming conventions
- Full Raku functionality in your language

## Available Language Modules

### European Languages

#### English

- **Repository**: [raku-english](https://github.com/raku-multilingual/raku-english)
- **Module names**: `English`
- **Features**: UK English keywords, operators, and functions (standard Raku with additional aliases)
- **Example**: `if True { say("Hello World") }`

#### German (Deutsch)

- **Repository**: [raku-german](https://github.com/raku-multilingual/raku-german)
- **Module names**: `German`, `Deutsch`
- **Features**: German keywords, operators, and functions
- **Example**: `wenn Wahr { sagen("Hallo Welt") }`

#### Spanish (Español)

- **Repository**: [raku-spanish](https://github.com/raku-multilingual/raku-spanish)
- **Module names**: `Spanish`, `Español`
- **Features**: Spanish keywords, operators, and functions
- **Example**: `si verdadero { decir("Hola Mundo") }`

#### Portuguese (Português)

- **Repository**: [raku-portuguese](https://github.com/raku-multilingual/raku-portuguese)
- **Module names**: `Portuguese`, `Português`
- **Features**: Portuguese keywords, operators, and functions
- **Example**: `se verdadeiro { dizer("Olá Mundo") }`

#### French (Français)

- **Repository**: [raku-french](https://github.com/raku-multilingual/raku-french)
- **Module names**: `French`, `Français`
- **Features**: French keywords, operators, and functions
- **Example**: `si vrai { dire("Bonjour le Monde") }`

#### Russian (Русский)

- **Repository**: [raku-russian](https://github.com/raku-multilingual/raku-russian)
- **Module names**: `Russian`, `Русский`
- **Features**: Russian keywords, operators, and functions
- **Example**: `если истина { сказать("Привет мир") }`

### Asian Languages

#### Chinese (中文)

- **Repository**: [raku-chinese](https://github.com/raku-multilingual/raku-chinese)
- **Module names**: `Chinese`, `中文`
- **Features**: Simplified and Traditional Chinese support
- **Example**: `如果 真 { 說("你好世界") }`

#### Classical Chinese (文言)

- **Repository**: [raku-classical-chinese](https://github.com/raku-multilingual/raku-classical-chinese)
- **Module names**: `ClassicalChinese`, `文言`, `文言文`, `古文`, `漢文`
- **Features**: Classical Chinese programming constructs
- **Example**: `若 真 { 曰("天下太平") }`

#### Japanese (日本語)

- **Repository**: [raku-japanese](https://github.com/raku-multilingual/raku-japanese)
- **Module names**: `Japanese`, `日本語`
- **Features**: Japanese keywords, operators, and functions
- **Example**: `もし 真 { 言う("こんにちは世界") }`

#### Korean (한국어)

- **Repository**: [raku-korean](https://github.com/raku-multilingual/raku-korean)
- **Module names**: `Korean`, `한국어`, `한글`
- **Features**: Korean keywords, operators, and functions
- **Example**: `만약 참 { 말하기("안녕하세요 세계") }`

## Installation

Each module can be installed using zef:

```bash
# Install individual modules
zef install English
zef install German
zef install Spanish
zef install French
# ... etc
```

## Usage Example

Here's how to use the French module:

```raku
use French;
# or: use Français;

# Variables and constants
mon $nombre = 42;
ma @liste = 1, 2, 3;

# Control structures
si $nombre > 40 {
    dire("Le nombre est grand!");
}

pour @liste -> $item {
    imprimer("$item ");
}

# Functions
dire(ajouter(2, 3));  # Prints: 5
```

## Features

All modules provide:

- ✅ Native language keywords (`if`→`si`, `for`→`pour`, etc.)
- ✅ Mathematical operators in native language
- ✅ String and array functions
- ✅ Type checking functions
- ✅ I/O operations
- ✅ Logical and comparison operators
- ✅ Full Raku functionality

## Contributing

Contributions are welcome! To add a new language or improve existing modules:

1. Fork the relevant repository
2. Create your feature branch
3. Add tests for new functionality
4. Submit a pull request

## Technical Notes

- All modules use Raku's EXPORT mechanism for clean namespace handling
- The `nil` function pattern (`sub word() { Nil }`) ensures proper Nil type handling
- Modules support multiple aliases for maximum accessibility

## License

All modules are released under the Artistic-2.0 license.

## Author

Danslav Slavenskoj

## Links

- [Raku Multilingual Organization](https://github.com/raku-multilingual)
- [Raku Programming Language](https://raku.org)
- [Raku Modules Directory](https://modules.raku.org)

---
