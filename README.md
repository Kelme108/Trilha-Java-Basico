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

[![](https://mermaid.ink/img/pako:eNptksFuwjAMhl-lymnT4AV6mIS2yw5DaEw75WIS01pK48pN0Abi3Rcgmwghlza_nXy_Yx-UYYuqVcbBNL0SdAKD9k1aZ6X5wFHYxsDyHicy4JrDJXxaT4ENyMPjlTJCnG6kCR0aYg_5iod1EPJdM5x3OfOo_TV2MYKg6_kznd2yJ8MFFwJ6iyWGUhaBvLAIEn_xvog66pKtTPZxQOH75CXssAPL8uYDisdQgi1dSlnyDhYbKBgQIjjag6ygI1_G8Js29BfINqK4-x5o1bPHAly8Wa1fKqr1hLgh5Lvn8-e6t1VG3YYqpXov7dVMJTcDkE2DdS5Cq9DjgFq16dfiFqILWml_TKmQDKx_vFFtkIgzJRy7XrVbcFPaxdGmZufB_FfR0sl1Ht3T5_gLMAzjsg?type=png)](https://mermaid.live/edit#pako:eNptksFuwjAMhl-lymnT4AV6mIS2yw5DaEw75WIS01pK48pN0Abi3Rcgmwghlza_nXy_Yx-UYYuqVcbBNL0SdAKD9k1aZ6X5wFHYxsDyHicy4JrDJXxaT4ENyMPjlTJCnG6kCR0aYg_5iod1EPJdM5x3OfOo_TV2MYKg6_kznd2yJ8MFFwJ6iyWGUhaBvLAIEn_xvog66pKtTPZxQOH75CXssAPL8uYDisdQgi1dSlnyDhYbKBgQIjjag6ygI1_G8Js29BfINqK4-x5o1bPHAly8Wa1fKqr1hLgh5Lvn8-e6t1VG3YYqpXov7dVMJTcDkE2DdS5Cq9DjgFq16dfiFqILWml_TKmQDKx_vFFtkIgzJRy7XrVbcFPaxdGmZufB_FfR0sl1Ht3T5_gLMAzjsg)
