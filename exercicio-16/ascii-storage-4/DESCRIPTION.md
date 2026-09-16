<h2 align="center">Armazenamento em ASCII — Palavra "Hardware"</h2>

Considere a palavra **"Hardware"**. Calcule quantos **bytes** são
necessários para armazená-la (1 byte por caractere, sem terminador)
e o **código ASCII decimal** de cada caractere, na ordem em que
aparecem na palavra.

## 1. Calcule

Use a tabela ASCII para achar o código decimal de cada letra
(maiúscula ou minúscula conforme escrito na palavra). Você pode
conferir no terminal:

```bash
python3 -c "print(ord('H'))"
```

## 2. Salve a resposta

Crie o arquivo `/home/hacker/resposta.txt` com **2 linhas**:

- linha 1: a quantidade de bytes (só o número);
- linha 2: o código ASCII decimal de cada caractere da palavra, na
  ordem, separados por um espaço.

## 3. Confira

```bash
/challenge/check
```

Se as 2 linhas baterem com o gabarito, a flag é liberada.
