#  Simulação de Crescimento Exponencial em Python

Este projeto simula o crescimento de um valor inicial de R$ 0,01 dobrando a cada dia durante 28 dias.

É um exemplo clássico usado para demonstrar crescimento exponencial, juros compostos e lógica de programação em Python.

---

##  Objetivo

Demonstrar:

- Uso de loops em Python
- Acumuladores
- Crescimento exponencial
- Formatação de valores monetários
- Estrutura básica de um projeto Python

---

##  Conceito

O valor começa em:

R$ 0,01

E dobra a cada dia:

Dia 1 → R$ 0,01  
Dia 2 → R$ 0,02  
Dia 3 → R$ 0,04  
...

Total após 28 dias:

R$ 2.684.354,55

---

##  Código

```python
valor = 0.01
total = 0

for dia in range(1, 29):
    total += valor
    print(f'Dia {dia}: R$ {valor:.2f}')
    valor *= 2

print(f'\nTotal acumulado: R$ {total:.2f}')
