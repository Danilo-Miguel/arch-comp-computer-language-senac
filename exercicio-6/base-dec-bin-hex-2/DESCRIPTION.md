<h2 align="center">Endereçamento de Memória → Hexadecimal (Variação 2)</h2>

Converta os 4 endereços de memória abaixo para **hexadecimal**,
mostrando os cálculos.

a) Decimal: 132
b) Binário: 10011101
c) Decimal: 209
d) Binário: 01110110

## 1. Calcule

Para um valor **decimal**, divida por 16: o quociente é o primeiro
dígito hex, o resto é o segundo. Para um valor **binário**, primeiro
converta para decimal e depois para hexadecimal. Exemplo de
conferência para um valor que **não** está na lista acima:
`77 = 4×16+13 → 0x4D`. Você pode conferir no terminal:

```bash
python3 -c "print(hex(132))"
python3 -c "print(hex(int('10011101', 2)))"
```

## 2. Salve a resposta

Crie o arquivo `/home/hacker/resposta.txt` com **4 linhas**, uma por
item, na ordem a, b, c, d. Cada linha deve conter só o valor
hexadecimal, com prefixo `0x` e dígitos em **maiúsculas** (ex.:
`0xC6`).

## 3. Confira

```bash
/challenge/check
```

Se as 4 linhas baterem com o gabarito, a flag é liberada.
