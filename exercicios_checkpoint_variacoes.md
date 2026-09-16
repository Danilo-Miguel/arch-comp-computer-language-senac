# 20 Exercícios — Variações no estilo do Check Point 1

Baseados nos mesmos 5 tipos de questão do Check Point (conversão hex/dec/bin em tabela, endereçamento de memória, código de máquina, armazenamento ASCII e decodificação ASCII). Cada bloco abaixo tem 4 variações do mesmo tipo, com gabarito e cálculos.

## Tipo 1 — Sensor: hexadecimal → decimal e binário

Complete a tabela convertendo cada valor hexadecimal para decimal e binário, mostrando os cálculos.

**Variação 1 — Sensor de pressão**
| Hexadecimal | Decimal | Binário |
|---|---|---|
| 0x1C | | |
| 0x38 | | |
| 0x54 | | |
| 0x6F | | |

Gabarito:
0x1C = (1×16)+(12×1) = 28 → 00011100
0x38 = (3×16)+(8×1) = 56 → 00111000
0x54 = (5×16)+(4×1) = 84 → 01010100
0x6F = (6×16)+(15×1) = 111 → 01101111

**Variação 2 — Sensor de umidade**
| Hexadecimal | Decimal | Binário |
|---|---|---|
| 0x22 | | |
| 0x49 | | |
| 0x5D | | |
| 0x71 | | |

Gabarito:
0x22 = (2×16)+(2×1) = 34 → 00100010
0x49 = (4×16)+(9×1) = 73 → 01001001
0x5D = (5×16)+(13×1) = 93 → 01011101
0x71 = (7×16)+(1×1) = 113 → 01110001

**Variação 3 — Sensor de tensão**
| Hexadecimal | Decimal | Binário |
|---|---|---|
| 0x0E | | |
| 0x3A | | |
| 0x66 | | |
| 0x92 | | |

Gabarito:
0x0E = (0×16)+(14×1) = 14 → 00001110
0x3A = (3×16)+(10×1) = 58 → 00111010
0x66 = (6×16)+(6×1) = 102 → 01100110
0x92 = (9×16)+(2×1) = 146 → 10010010

**Variação 4 — Sensor de luminosidade**
| Hexadecimal | Decimal | Binário |
|---|---|---|
| 0x15 | | |
| 0x2B | | |
| 0x47 | | |
| 0x8C | | |

Gabarito:
0x15 = (1×16)+(5×1) = 21 → 00010101
0x2B = (2×16)+(11×1) = 43 → 00101011
0x47 = (4×16)+(7×1) = 71 → 01000111
0x8C = (8×16)+(12×1) = 140 → 10001100

---

## Tipo 2 — Endereçamento de memória: converta para hexadecimal

Converta cada endereço para hexadecimal, mostrando os cálculos.

**Variação 1**
a) Decimal: 198
b) Binário: 01011011
c) Decimal: 87
d) Binário: 11100011

Gabarito:
a) 198 = 12×16+6 → 0xC6
b) 01011011 = 91 = 5×16+11 → 0x5B
c) 87 = 5×16+7 → 0x57
d) 11100011 = 227 = 14×16+3 → 0xE3

**Variação 2**
a) Decimal: 132
b) Binário: 10011101
c) Decimal: 209
d) Binário: 01110110

Gabarito:
a) 132 = 8×16+4 → 0x84
b) 10011101 = 157 = 9×16+13 → 0x9D
c) 209 = 13×16+1 → 0xD1
d) 01110110 = 118 = 7×16+6 → 0x76

**Variação 3**
a) Decimal: 175
b) Binário: 11001011
c) Decimal: 94
d) Binário: 10110100

Gabarito:
a) 175 = 10×16+15 → 0xAF
b) 11001011 = 203 = 12×16+11 → 0xCB
c) 94 = 5×16+14 → 0x5E
d) 10110100 = 180 = 11×16+4 → 0xB4

**Variação 4**
a) Decimal: 221
b) Binário: 01001110
c) Decimal: 118
d) Binário: 11110001

Gabarito:
a) 221 = 13×16+13 → 0xDD
b) 01001110 = 78 = 4×16+14 → 0x4E
c) 118 = 7×16+6 → 0x76
d) 11110001 = 241 = 15×16+1 → 0xF1

---

## Tipo 3 — Código de máquina: hexadecimal → binário e decimal

Complete a tabela convertendo cada valor hexadecimal para binário e decimal, mostrando os cálculos.

**Variação 1**
| Posição | Hexadecimal | Binário | Decimal |
|---|---|---|---|
| 0x3000 | 0xB3 | | |
| 0x3001 | 0x2C | | |
| 0x3002 | 0x59 | | |
| 0x3003 | 0xE1 | | |

Gabarito: 0xB3 → 10110011 → 179 | 0x2C → 00101100 → 44 | 0x59 → 01011001 → 89 | 0xE1 → 11100001 → 225

**Variação 2**
| Posição | Hexadecimal | Binário | Decimal |
|---|---|---|---|
| 0x3004 | 0x47 | | |
| 0x3005 | 0x9A | | |
| 0x3006 | 0x1D | | |
| 0x3007 | 0xC6 | | |

Gabarito: 0x47 → 01000111 → 71 | 0x9A → 10011010 → 154 | 0x1D → 00011101 → 29 | 0xC6 → 11000110 → 198

**Variação 3**
| Posição | Hexadecimal | Binário | Decimal |
|---|---|---|---|
| 0x3008 | 0x88 | | |
| 0x3009 | 0x3F | | |
| 0x300A | 0x5B | | |
| 0x300B | 0xD2 | | |

Gabarito: 0x88 → 10001000 → 136 | 0x3F → 00111111 → 63 | 0x5B → 01011011 → 91 | 0xD2 → 11010010 → 210

**Variação 4**
| Posição | Hexadecimal | Binário | Decimal |
|---|---|---|---|
| 0x300C | 0x6E | | |
| 0x300D | 0xA1 | | |
| 0x300E | 0x24 | | |
| 0x300F | 0xF7 | | |

Gabarito: 0x6E → 01101110 → 110 | 0xA1 → 10100001 → 161 | 0x24 → 00100100 → 36 | 0xF7 → 11110111 → 247

---

## Tipo 4 — Armazenamento de palavra em ASCII

Calcule o espaço de armazenamento (bytes) e o código ASCII decimal de cada caractere da palavra.

**Variação 1 — "Processor"**
Bytes: 9 (1 byte por caractere)
P=80, r=114, o=111, c=99, e=101, s=115, s=115, o=111, r=114

**Variação 2 — "Register"**
Bytes: 8
R=82, e=101, g=103, i=105, s=115, t=116, e=101, r=114

**Variação 3 — "Compiler"**
Bytes: 8
C=67, o=111, m=109, p=112, i=105, l=108, e=101, r=114

**Variação 4 — "Hardware"**
Bytes: 8
H=72, a=97, r=114, d=100, w=119, a=97, r=114, e=101

---

## Tipo 5 — Decodificação hexadecimal ASCII e codificação de nome

a) Identifique os caracteres representados pela sequência hexadecimal e mostre a representação binária de cada um.
b) Calcule o espaço necessário, em bytes, para armazenar o nome indicado.
c) Apresente a representação hexadecimal e binária de cada caractere do nome (primeira letra maiúscula, demais minúsculas).

**Variação 1**
a) Sequência: 0x52 0x41 0x4D — Nome: Ana

Gabarito a): 0x52=R(01010010), 0x41=A(01000001), 0x4D=M(01001101) → "RAM"
Gabarito b): "Ana" = 3 bytes
Gabarito c): A=65=0x41=01000001 | n=110=0x6E=01101110 | a=97=0x61=01100001

**Variação 2**
a) Sequência: 0x42 0x55 0x53 — Nome: Davi

Gabarito a): 0x42=B(01000010), 0x55=U(01010101), 0x53=S(01010011) → "BUS"
Gabarito b): "Davi" = 4 bytes
Gabarito c): D=68=0x44=01000100 | a=97=0x61=01100001 | v=118=0x76=01110110 | i=105=0x69=01101001

**Variação 3**
a) Sequência: 0x42 0x49 0x54 — Nome: Rita

Gabarito a): 0x42=B(01000010), 0x49=I(01001001), 0x54=T(01010100) → "BIT"
Gabarito b): "Rita" = 4 bytes
Gabarito c): R=82=0x52=01010010 | i=105=0x69=01101001 | t=116=0x74=01110100 | a=97=0x61=01100001

**Variação 4**
a) Sequência: 0x4C 0x4F 0x47 — Nome: Caio

Gabarito a): 0x4C=L(01001100), 0x4F=O(01001111), 0x47=G(01000111) → "LOG"
Gabarito b): "Caio" = 4 bytes
Gabarito c): C=67=0x43=01000011 | a=97=0x61=01100001 | i=105=0x69=01101001 | o=111=0x6F=01101111
