# UML-iphone-dio-
classDiagram

    class ReprodutorMusical {
        +tocar(): void
        +pausar(): void
        +selecionarMusica(): void
    }

    class AparelhoTelefonico {
        +ligar(numero: String): void
        +iniciarCorreioVoz(): void
        +atender(): void
    }

    class NavegadorInternet {
        +exibirPagina(): void
        +atualizarPagina(): void
        +adicionarNovaAba(): void
    }

    class iPhone {
        +modelo: String
        +cor: String
        +capacidadeBateria: Int
        +armazenamentoInterno: Int

        +ligar(): void
        +desligar(): void
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
