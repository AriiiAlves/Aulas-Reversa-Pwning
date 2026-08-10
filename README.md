# Aulas-Reversa-Pwning

Olá! Esse repositório foi criado para ter materiais de apoio da frente de Engenharia Reversa/Pwning do grupo de cibersegurança Ganesh-ICMC.

## Aula 1 - Engenharia Reversa Estática/Dinâmica: Assembly, Stack, Endianness, Ghidra/IDA, pwndbg, pwntools, Array Indexing, Integer Overflow

- **Entendendo Assembly (1)**: [hello_world](./modules-nightmare/01-intro_assembly/reversing_assembly/hello_world) - Um Hello World Simples.
- **Entendendo Assembly (2)**: [if_then](./modules-nightmare/01-intro_assembly/reversing_assembly/if_then) - Um If/Else simples.
- **Entendendo Assembly (3)**: [loop](./modules-nightmare/01-intro_assembly/reversing_assembly/loop) - Um loop simples.
- **GDB-GEF**: [hello_world](./modules-nightmare/02-intro_tooling/gdb-gef/hello_world) - Use o GDB para navegar por esse programa simples.
- **Começando em Rev (1)**: [stage1](./modules-nightmare/03-beginner_re/csaw18_x86tour_pt1/stage1.asm) - Responda algumas perguntas.
    - Qual o valor de `dh` depois que a linha 129 executa?
    - Qual o valor de `gs` depois que a linha 145 executa?
    - Qual o valor de `si` depois que a linha 151 executa?
    - Qual o valor de `ax` depois que a linha 169 executa?
    - Qual o valor de `ax` depois que a linha 199 executa pela primeira vez?
- **Começando em Rev (2)**: [beleaf](./modules-nightmare/03-beginner_re/csaw19_beleaf/beleaf) - Apenas analisando o programa, descubra a flag escondida.
- **Começando em Rev (3)**: [helithumper_re](./modules-nightmare/03-beginner_re/helithumper_re/rev) - Apenas analisando o programa, descubra a flag.
- **Começando em Rev (4)**: [strings](./modules-nightmare/03-beginner_re/pico18_strings/strings) - Você por acaso já usou o comando `strings <program>` no terminal? Talvez seja uma boa tentar.

## Aula 2 - Stack Exploitation (1): Proteções, BOF, Format Strings

# Créditos

Os desafios aqui presentes vieram do repositório de guyinatuxedo, [Nightmare](https://github.com/guyinatuxedo/nightmare/)

Se tiver dúvidas, me manda um email! alvzariel@gmail.com