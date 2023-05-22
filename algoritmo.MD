Inicio principal  
    VAR opcao_selecionada: STRING
    VAR valor: INTEIRO
    VAR saldo: INTEIRO
    VAR encerrar_programa: BOOLEANO

    DEFINIR encerrar_programa -> Falso
        
    ENQUANTO encerrar_programa IGUAL_A Falso
        CHAMAR MOSTRAR_MENU -> opcao_selecionada
        SE opcao_selecionada IGUAL_A a
            MOSTRAR "Seu saldo é: ", saldo
        OU_SE opcao_selecionada IGUAL_A b
            MOSTRAR "Digite o valor a depositar: "
            ESPERAR_DIGITACAO -> valor
            SOMAR valor, saldo -> saldo
            MOSTRAR "Deposito efetuado"
        OU_SE opcao_selecionada IGUAL_A c
            MOSTRAR "Digite o valor a retirar: "
            ESPERAR_DIGITACAO -> valor
            SE valor MAIOR_QUE saldo
                MOSTRAR "Saque não permitido, saldo insuficiente"
            SENAO 
                SUBTRARI valor, saldo -> saldo
            FIM SE
            Mostrar "Saque efetuado"
         OU_SE opcao_selecionada IGUAL_A d
            DEFINIR VERDADEIRO -> encerrar programa
        SENAO
            MOSTRAR "opcao inválida, tente novamente"
        FIM SE
    FIM ENQUANTO
FINAL

INICIO MOSTRAR_MENU
    VAR opcao_selecionada: STRING
    MOSTRAR "MENU de operacao"
    MOSTRAR "[a] Mostrar Saldo"
    MOSTRAR "[b] Efetuar Depósito"
    MOSTRAR "[c] Efetuar Saque"
    MOSTRAR "[d] Finalizar"
    ESPERAR_DIGITACAO -> opcao_selecionada
    RETORNAR opcao_selecionada
FIM MOSTRAR_MENU
````

