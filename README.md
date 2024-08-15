# Trilha-Java-Basico
Exercicios realizados no curso da DIO

## Código Realizado para Demonstração de um iPhone e Suas Funções

### Diagrama de Classes

```plaintext
    +-----------------------+
    |   ReprodutorMusical   |
    +-----------------------+
    | +tocar()              |
    | +pausar()             |
    | +selecionarMusica()   |
    +-----------------------+
                ^
                |
                |
    +-----------------------+
    |      iPhone           |
    +-----------------------+
    | +String musica        |
    | +String numero        |
    | +String url           |
    +-----------------------+
        /        |       \
       /         |        \
      /          |         \
+------------------+    +-------------------+    +---------------------+
| AparelhoTelefonico|    | NavegadorInternet |    |   ReprodutorMusical |
+-------------------+    +-------------------+    +---------------------+
| +atender()        |    | +adicionarNovaAba()|    | +tocar()           |
| +iniciarCorreioVoz() | | +atualizarPagina() |   | +pausar()          |
| +ligar(String numero)| | +exibirPagina()   |    | +selecionarMusica()|
+---------------------+  +-------------------+    +---------------------+
