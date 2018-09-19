ignore
===

## Installation
You can install this utility using `pip` using the package name `ignore-from-github`.
```
pip install ignore-from-github
```

## Usage
`ignore` allows you to quickly add common sets of file types to your `.gitignore` file. It pulls from `https://github.com/github/gitignore`.
```
    $   ignore python
    $   cat .gitignore

    # Byte-compiled / optimized / DLL files
    __pycache__/
    *.py[cod]
    *$py.class

    # C extensions
    *.so
    .
    .
    .
```
