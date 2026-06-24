# Desafios da Rotina

RPG textual acessivel para deficientes visuais em C, jogável no terminal.

Documentação principal:

- `docs/README_JOGADOR.md`
- `docs/README_TECNICO.md`
- `docs/TESTES_MANUAIS.md`
- `docs/CHECKLIST_ACESSIBILIDADE.md`
- `docs/LIMITACOES_CONHECIDAS.md`

Execução rápida no Windows, a partir desta pasta:

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
