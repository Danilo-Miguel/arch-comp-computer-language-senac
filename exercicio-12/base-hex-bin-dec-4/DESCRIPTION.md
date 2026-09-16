<h2 align="center">Código de Máquina: Hexadecimal → Binário e Decimal (Variação 4)</h2>

A memória abaixo guarda 4 bytes de código de máquina, em posições
sequenciais. Converta cada byte hexadecimal para **binário (8 bits)**
e para **decimal**.

| Posição | Hexadecimal | Binário | Decimal |
|---|---|---|---|
| 0x300C | 0x6E | ? | ? |
| 0x300D | 0xA1 | ? | ? |
| 0x300E | 0x24 | ? | ? |
| 0x300F | 0xF7 | ? | ? |

## 1. Calcule

Para cada byte, escreva o binário em 8 dígitos e depois o decimal
(dígito da dezena×16 + dígito da unidade×1). Exemplo de conferência
para um valor que **não** está na tabela acima: `0x0A = 00001010 =
10`. Você pode conferir no terminal:

```bash
python3 -c "v=int('6E',16); print(format(v,'08b'), v)"
```

## 2. Salve a resposta

Crie o arquivo `/home/hacker/resposta.txt` com **4 linhas**, uma para
cada posição, na ordem da tabela, no formato:

```
BINARIO DECIMAL
```

(binário sempre com 8 dígitos, sem prefixo `0b`, seguido de um
espaço e o valor decimal).

## 3. Confira

```bash
/challenge/check
```

Se as 4 linhas baterem com o gabarito, a flag é liberada.
