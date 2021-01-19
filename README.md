# morsebinary

An executable that translates morse code expressed in binary.

## Installation
### Install

```commandline
./morsebinary --install
```

### Uninstall

To delete using the file in this repo:
```commandline
./morsebinary --uninstall
```

To delete using the installed file:
```commandline
morsebinary --uninstall --force
```

## Usage

### Encode

```commandline
morsebinary decoded.txt --encode [--output test_encoded.txt]
```

or
```commandline
morsebinary decoded.txt --encode > test_encoded.txt
```

### Decode

```commandline
morsebinary encoded.txt --decode [--output test_decoded.txt]
```
or
```commandline
morsebinary encoded.txt --decode > test_decoded.txt
```

### Piping

It is also possible to pipe input, for example:
```commandline
cat encoded.txt | morsebinary --decode > test_decoded.txt
```
