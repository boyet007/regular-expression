regular-expression

website : regex101.com

/ninja/  -> harus match string ninja -> ninja NinJa NINJA
/[ng]inja/ -> harus match character n atau g diawal dan inja -> ninja ginja NINJA
/[^p]000/ -> karakter pertama bisa semua kecuali p -> a000 b000 3000 4000
/[a-zA-Z]inja/ -> karakter pertama antara a sampai z dan A sampai Z -> ninja Ninja Winja pinja
/[0-9]{5,8}/ -> karakter harus angka dengan jumlah karakter dari 5 - 8 karakter -> 12345, 245912, 11122233
/[0-9]{5,}/ -> karakter harus angka dengan jumlah karakter dari 5 - tak terhingga..

\d match any digit character (same as [0-9])
\w match any word character (a-z, A-Z, 0-9 and _'s)
\s match a whitespace character (spaces, tabs, etc)
\t match a tab character only

/\d{3}\s\w{5} -> 3 karakter pertama harus angka kemudian 1 karakter spasi kemudian 5 karakter berikut.. -> 123 ninja

+ -> the one or more quantifier
\ -> the escape character
[] -> the character set
[^]  -> the negate symbols in a character sest
? the zero or one quantifier (makes a preceding char optional)
. any character whatsoever (except the newline character)
* the 0 or more quantifier (a bit like +)

