<h1 align="center">
    Coding Standard
</h1>

Carefully chosen fixers and sniffs.

Installation & usage
--------------------

1. Install this package:

    ```bash
    $ composer require pamil/coding-standard
    ```
    
2. Include a configuration file in your `easy-coding-standard.neon`:

    ```neon
    includes:
        - vendor/pamil/coding-standard/fixers/standard.neon # should not break anything
        - vendor/pamil/coding-standard/fixers/risky.neon # might break the app (force void return type, strict param etc.)
    ```
