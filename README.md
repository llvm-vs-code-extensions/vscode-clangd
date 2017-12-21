# :no_entry: [DEPRECATED] The extension is maintained in LLVM [clang-tools-extra](http://llvm.org/svn/llvm-project/clang-tools-extra/trunk/clangd/clients/clangd-vscode/)

[clangd](https://clang.llvm.org/extra/clangd.html) is a [Language Server](https://github.com/Microsoft/language-server-protocol) leveraging clang.

## Usage
This extension connects Visual Studio Code with clangd, bringing language services such as formatting, code completion, fixits and goto definition.

This extension will attempt to find the clangd binary on your `PATH`.
Alternatively, the clangd executable can be specified in your vscode `settings.json` file:

```json
{
    "clangd.path": "/absolute/path/to/clangd"
}
```

To obtain clangd, currently you need to [build it from source](https://clang.llvm.org/extra/clangd.html#building-clangd).
