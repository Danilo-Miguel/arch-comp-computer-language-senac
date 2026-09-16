<h2 align="center">Conversão Hexadecimal → Decimal e Binário — Sensor de Luminosidade</h2>

Um sensor de luminosidade registra 4 leituras em **hexadecimal**.
Converta cada uma para **decimal** e para **binário (8 bits)**.

| Hexadecimal | Decimal | Binário |
|---|---|---|
| 0x15 | ? | ? |
| 0x2B | ? | ? |
| 0x47 | ? | ? |
| 0x8C | ? | ? |

## 1. Calcule

Para cada valor, calcule o decimal (dígito da dezena×16 + dígito da
unidade×1) e depois escreva o binário em 8 dígitos. Exemplo de
conferência para um valor que **não** está na tabela acima:
`0x0A = (0×16)+(10×1) = 10 → 00001010`. Você pode conferir suas
contas no terminal:

```bash
python3 -c "v=int('15',16); print(v, format(v,'08b'))"
```

## 2. Salve a resposta

Crie o arquivo `/home/hacker/resposta.txt` com **4 linhas**, uma para
cada linha da tabela, na mesma ordem, no formato:

```
DECIMAL BINARIO
```

(decimal e binário separados por um espaço, binário sempre com 8
dígitos, sem o prefixo `0b`).

## 3. Confira

```bash
/challenge/check
```

Se as 4 linhas baterem com o gabarito, a flag é liberada.
