# Toolkit

<div align="center">
  <img src="./img/logo3.jpeg" alt="Zyphria Banner" width="100%" />
</div>

A dual-language package (Go/Rust) for building and managing LLM function calling tools and toolkits. Built specifically for Zyphi.

## Features

1. Interface-driven development for LLM function integration.
2. Leverages functional options (Go) and builder pattern (Rust) for configuration.
3. Supports JSON Schema for parameter and return type validation.

## Installation

### Go

```bash
go get github.com/Zyphria/zyphria-toolkit/go
```

### Rust

```toml
[dependencies]
toolkit = { git = "https://github.com/Zyphria/zyphria-toolkit", subdirectory = "rust" }
```

## Usage

Both implementations provide similar functionality with language-specific idioms:

1. Go employs the functional options pattern for configuration, enabling composable and flexible configuration.
2. Rust utilizes the builder pattern for a structured and type-safe approach to configuration.
3. Both implementations support asynchronous execution of LLM functions, improving performance and responsiveness.
4. JSON Schema is used in both frameworks to define and validate function parameters and return types, ensuring type safety and data integrity.

For examples, see the language-specific directories:

- Go examples in [go/examples](go/examples)
- Rust examples in [rust/examples](rust/examples)
