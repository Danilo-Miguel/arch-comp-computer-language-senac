# Gabarito — Conversão de Base e Tabela ASCII (20 exercícios)

Gabarito de referência para os 20 módulos do dojo (`exercicio-1` a
`exercicio-20`). Cada exercício pede uma conversão entre hexadecimal,
decimal e binário, ou uma leitura/escrita de caracteres em ASCII. O
aluno calcula (no papel), salva a resposta em
`/home/hacker/resposta.txt` no formato pedido e roda o `check`. As
respostas abaixo são exatamente o conteúdo esperado de
`resposta.txt` em cada exercício.

---

## Exercício 1 — `base-hex-dec-bin-1` (Sensor de pressão)

0x1C = (1×16)+(12×1) = 28 → 00011100
0x38 = (3×16)+(8×1) = 56 → 00111000
0x54 = (5×16)+(4×1) = 84 → 01010100
0x6F = (6×16)+(15×1) = 111 → 01101111

`resposta.txt`:
```
28 00011100
56 00111000
84 01010100
111 01101111
```

---

## Exercício 2 — `base-hex-dec-bin-2` (Sensor de umidade)

0x22 = (2×16)+(2×1) = 34 → 00100010
0x49 = (4×16)+(9×1) = 73 → 01001001
0x5D = (5×16)+(13×1) = 93 → 01011101
0x71 = (7×16)+(1×1) = 113 → 01110001

`resposta.txt`:
```
34 00100010
73 01001001
93 01011101
113 01110001
```

---

## Exercício 3 — `base-hex-dec-bin-3` (Sensor de tensão)

0x0E = (0×16)+(14×1) = 14 → 00001110
0x3A = (3×16)+(10×1) = 58 → 00111010
0x66 = (6×16)+(6×1) = 102 → 01100110
0x92 = (9×16)+(2×1) = 146 → 10010010

`resposta.txt`:
```
14 00001110
58 00111010
102 01100110
146 10010010
```

---

## Exercício 4 — `base-hex-dec-bin-4` (Sensor de luminosidade)

0x15 = (1×16)+(5×1) = 21 → 00010101
0x2B = (2×16)+(11×1) = 43 → 00101011
0x47 = (4×16)+(7×1) = 71 → 01000111
0x8C = (8×16)+(12×1) = 140 → 10001100

`resposta.txt`:
```
21 00010101
43 00101011
71 01000111
140 10001100
```

---

## Exercício 5 — `base-dec-bin-hex-1` (Endereçamento de memória)

a) 198 = 12×16+6 → 0xC6
b) 01011011 = 91 = 5×16+11 → 0x5B
c) 87 = 5×16+7 → 0x57
d) 11100011 = 227 = 14×16+3 → 0xE3

`resposta.txt`:
```
0xC6
0x5B
0x57
0xE3
```

---

## Exercício 6 — `base-dec-bin-hex-2` (Endereçamento de memória)

a) 132 = 8×16+4 → 0x84
b) 10011101 = 157 = 9×16+13 → 0x9D
c) 209 = 13×16+1 → 0xD1
d) 01110110 = 118 = 7×16+6 → 0x76

`resposta.txt`:
```
0x84
0x9D
0xD1
0x76
```

---

## Exercício 7 — `base-dec-bin-hex-3` (Endereçamento de memória)

a) 175 = 10×16+15 → 0xAF
b) 11001011 = 203 = 12×16+11 → 0xCB
c) 94 = 5×16+14 → 0x5E
d) 10110100 = 180 = 11×16+4 → 0xB4

`resposta.txt`:
```
0xAF
0xCB
0x5E
0xB4
```

---

## Exercício 8 — `base-dec-bin-hex-4` (Endereçamento de memória)

a) 221 = 13×16+13 → 0xDD
b) 01001110 = 78 = 4×16+14 → 0x4E
c) 118 = 7×16+6 → 0x76
d) 11110001 = 241 = 15×16+1 → 0xF1

`resposta.txt`:
```
0xDD
0x4E
0x76
0xF1
```

---

## Exercício 9 — `base-hex-bin-dec-1` (Código de máquina)

0xB3 → 10110011 → 179
0x2C → 00101100 → 44
0x59 → 01011001 → 89
0xE1 → 11100001 → 225

`resposta.txt`:
```
10110011 179
00101100 44
01011001 89
11100001 225
```

---

## Exercício 10 — `base-hex-bin-dec-2` (Código de máquina)

0x47 → 01000111 → 71
0x9A → 10011010 → 154
0x1D → 00011101 → 29
0xC6 → 11000110 → 198

`resposta.txt`:
```
01000111 71
10011010 154
00011101 29
11000110 198
```

---

## Exercício 11 — `base-hex-bin-dec-3` (Código de máquina)

0x88 → 10001000 → 136
0x3F → 00111111 → 63
0x5B → 01011011 → 91
0xD2 → 11010010 → 210

`resposta.txt`:
```
10001000 136
00111111 63
01011011 91
11010010 210
```

---

## Exercício 12 — `base-hex-bin-dec-4` (Código de máquina)

0x6E → 01101110 → 110
0xA1 → 10100001 → 161
0x24 → 00100100 → 36
0xF7 → 11110111 → 247

`resposta.txt`:
```
01101110 110
10100001 161
00100100 36
11110111 247
```

---

## Exercício 13 — `ascii-storage-1` ("Processor")

Bytes: 9 (1 byte por caractere)
P=80, r=114, o=111, c=99, e=101, s=115, s=115, o=111, r=114

`resposta.txt`:
```
9
80 114 111 99 101 115 115 111 114
```

---

## Exercício 14 — `ascii-storage-2` ("Register")

Bytes: 8
R=82, e=101, g=103, i=105, s=115, t=116, e=101, r=114

`resposta.txt`:
```
8
82 101 103 105 115 116 101 114
```

---

## Exercício 15 — `ascii-storage-3` ("Compiler")

Bytes: 8
C=67, o=111, m=109, p=112, i=105, l=108, e=101, r=114

`resposta.txt`:
```
8
67 111 109 112 105 108 101 114
```

---

## Exercício 16 — `ascii-storage-4` ("Hardware")

Bytes: 8
H=72, a=97, r=114, d=100, w=119, a=97, r=114, e=101

`resposta.txt`:
```
8
72 97 114 100 119 97 114 101
```

---

## Exercício 17 — `ascii-decode-encode-1` (Ana)

a) 0x52=R(01010010), 0x41=A(01000001), 0x4D=M(01001101) → "RAM"
b) "Ana" = 3 bytes
c) A=65=0x41=01000001 | n=110=0x6E=01101110 | a=97=0x61=01100001

`resposta.txt`:
```
RAM
3
0x41:01000001 0x6E:01101110 0x61:01100001
```

---

## Exercício 18 — `ascii-decode-encode-2` (Davi)

a) 0x42=B(01000010), 0x55=U(01010101), 0x53=S(01010011) → "BUS"
b) "Davi" = 4 bytes
c) D=68=0x44=01000100 | a=97=0x61=01100001 | v=118=0x76=01110110 |
   i=105=0x69=01101001

`resposta.txt`:
```
BUS
4
0x44:01000100 0x61:01100001 0x76:01110110 0x69:01101001
```

---

## Exercício 19 — `ascii-decode-encode-3` (Rita)

a) 0x42=B(01000010), 0x49=I(01001001), 0x54=T(01010100) → "BIT"
b) "Rita" = 4 bytes
c) R=82=0x52=01010010 | i=105=0x69=01101001 | t=116=0x74=01110100 |
   a=97=0x61=01100001

`resposta.txt`:
```
BIT
4
0x52:01010010 0x69:01101001 0x74:01110100 0x61:01100001
```

---

## Exercício 20 — `ascii-decode-encode-4` (Caio)

a) 0x4C=L(01001100), 0x4F=O(01001111), 0x47=G(01000111) → "LOG"
b) "Caio" = 4 bytes
c) C=67=0x43=01000011 | a=97=0x61=01100001 | i=105=0x69=01101001 |
   o=111=0x6F=01101111

`resposta.txt`:
```
LOG
4
0x43:01000011 0x61:01100001 0x69:01101001 0x6F:01101111
```

---

## Resumo (tipo de conversão e resposta esperada por exercício)

| Exercício | Tipo | Conteúdo `resposta.txt` |
|---|---|---|
| 1 | Hex → Dec/Bin | `28 00011100` / `56 00111000` / `84 01010100` / `111 01101111` |
| 2 | Hex → Dec/Bin | `34 00100010` / `73 01001001` / `93 01011101` / `113 01110001` |
| 3 | Hex → Dec/Bin | `14 00001110` / `58 00111010` / `102 01100110` / `146 10010010` |
| 4 | Hex → Dec/Bin | `21 00010101` / `43 00101011` / `71 01000111` / `140 10001100` |
| 5 | Dec/Bin → Hex | `0xC6` / `0x5B` / `0x57` / `0xE3` |
| 6 | Dec/Bin → Hex | `0x84` / `0x9D` / `0xD1` / `0x76` |
| 7 | Dec/Bin → Hex | `0xAF` / `0xCB` / `0x5E` / `0xB4` |
| 8 | Dec/Bin → Hex | `0xDD` / `0x4E` / `0x76` / `0xF1` |
| 9 | Hex → Bin/Dec | `10110011 179` / `00101100 44` / `01011001 89` / `11100001 225` |
| 10 | Hex → Bin/Dec | `01000111 71` / `10011010 154` / `00011101 29` / `11000110 198` |
| 11 | Hex → Bin/Dec | `10001000 136` / `00111111 63` / `01011011 91` / `11010010 210` |
| 12 | Hex → Bin/Dec | `01101110 110` / `10100001 161` / `00100100 36` / `11110111 247` |
| 13 | ASCII storage | `9` / `80 114 111 99 101 115 115 111 114` |
| 14 | ASCII storage | `8` / `82 101 103 105 115 116 101 114` |
| 15 | ASCII storage | `8` / `67 111 109 112 105 108 101 114` |
| 16 | ASCII storage | `8` / `72 97 114 100 119 97 114 101` |
| 17 | Hex↔ASCII | `RAM` / `3` / `0x41:01000001 0x6E:01101110 0x61:01100001` |
| 18 | Hex↔ASCII | `BUS` / `4` / `0x44:01000100 0x61:01100001 0x76:01110110 0x69:01101001` |
| 19 | Hex↔ASCII | `BIT` / `4` / `0x52:01010010 0x69:01101001 0x74:01110100 0x61:01100001` |
| 20 | Hex↔ASCII | `LOG` / `4` / `0x43:01000011 0x61:01100001 0x69:01101001 0x6F:01101111` |
