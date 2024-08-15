# Trilha-Java-Basico
Exercicios realizados no curso da DIO

# Código realizado para demonstração de um iPhone e suas funções.

## Diagrama de Classes

![Diagrama UML](\mermaid-diagram-2024-08-15-093408.png")
### Descrição das Classes

- **ReprodutorMusical**
  - `+tocar()`
  - `+pausar()`
  - `+selecionarMusica(String musica)`

- **AparelhoTelefonico**
  - `+atender()`
  - `+iniciarCorreioVoz()`
  - `+ligar(String numero)`

- **NavegadorInternet**
  - `+adicionarNovaAba()`
  - `+atualizarPagina()`
  - `+exibirPagina(String url)`

- **iPhone**
  - `+String musica`
  - `+String numero`
  - `+String url`

Relacionamentos:
- `iPhone --> ReprodutorMusical`
- `iPhone --> AparelhoTelefonico`
- `iPhone --> NavegadorInternet`
