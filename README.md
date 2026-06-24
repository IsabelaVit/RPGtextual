# Desafios da Rotina

RPG textual acessivel para deficientes visuais em C e jogável no terminal.

É um simulador narrativo de rotina doméstica com pegada de comédia e crítica social:

O protagonista é um homem de 25 anos, sedentário, faminto e com TDAH, são 8h da manhã e sua missão é cumprir três tarefas simples antes do meio-dia: tirar o lixo do banheiro, comer algo e tomar banho.

Documentação principal:

- `docs/README_JOGADOR.md`
- `docs/README_TECNICO.md`
- `docs/TESTES_MANUAIS.md`
- `docs/CHECKLIST_ACESSIBILIDADE.md`
- `docs/LIMITACOES_CONHECIDAS.md`

Execução rápida no Windows, a partir da pasta:

```powershell
.\desafios_da_rotina.exe
```

Compilação manual com MinGW:

```powershell
gcc -std=c17 -Wall -Wextra -pedantic -Iinclude src\*.c -o desafios_da_rotina.exe
```

Linux:

```bash
make
./desafios_da_rotina
```
