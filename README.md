# Desafio-Modelagem
```mermaid
classDiagram
direction TB
    class Iphone {
    }

    class AparelhoTelefonico {
	    ligar(String numero)
	    atender()
	    iniciarCorreioVoz()
    }

    class NavegadorInternet {
	    exibirPagina(String url)
	    adicionarNovaAba()
	    atualizarPagina()
    }

    class ReprodutorMusical {
	    tocar()
	    pausar()
	    selecionarMusica(String musica)
    }

    Iphone --|> ReprodutorMusical
    Iphone --|> AparelhoTelefonico
    Iphone --|> NavegadorInternet
```
