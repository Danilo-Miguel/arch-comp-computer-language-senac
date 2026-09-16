<h2 align="center">Decodificação Hex→ASCII e Codificação de Nome — "Davi"</h2>

a) A sequência hexadecimal abaixo representa 3 caracteres ASCII.
Decodifique e descubra a sigla formada:

```
0x42 0x55 0x53
```

b) Calcule quantos **bytes** são necessários para armazenar o nome
**"Davi"**.

c) Para cada caractere do nome **"Davi"** (primeira letra maiúscula,
demais minúsculas), apresente o código em **hexadecimal** e em
**binário (8 bits)**.

## 1. Calcule

Use a tabela ASCII (código → caractere e caractere → código). Você
pode conferir no terminal:

```bash
python3 -c "print(chr(0x42))"
python3 -c "v=ord('D'); print(hex(v), format(v,'08b'))"
```

## 2. Salve a resposta

Crie o arquivo `/home/hacker/resposta.txt` com **3 linhas**:

- linha 1: a sigla decodificada no item (a), em **maiúsculas** (ex.:
  `RAM`);
- linha 2: a quantidade de bytes do item (b), só o número;
- linha 3: um par `HEX:BINARIO` para cada caractere do nome (item c),
  na ordem, separados por espaço, com os dígitos hexadecimais em
  **maiúsculas** e prefixo `0x` (ex.: `0x41:01000001
  0x6E:01101110 0x61:01100001`).

## 3. Confira

```bash
/challenge/check
```

Se as 3 linhas baterem com o gabarito, a flag é liberada.
