(a) `init();` is illegal, must have at least one argument.

(b) `init(24, 10);` is legeal.

(c) `init(14, '*');` is legal, but unlikely to match the programer's intent. Because the character `*` will be promoted to `int` and match `wd`.

