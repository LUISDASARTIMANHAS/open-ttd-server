Scripts
---------

OpenTTD oferece suporte a scripts.

scripts locais:
  - 'autoexec.scr' é executado no início do jogo [todos - use isto para aliases personalizados por ex.]

+scripts de rede:
    deve ser usado para definir as configurações de otimização do cliente:
  - 'on_client.scr' é executado quando você entra em um servidor [todos os clientes]

  - 'on_server_connect.scr' é executado no servidor quando um cliente entra (MOTD)

    deve ser usado para definir a porta/ip dos servidores e/ou configurações/patches de otimização do servidor:
  - 'pre_server.scr' é executado antes da pilha tcp do servidor ser iniciada [somente no jogo]
  - 'pre_dedicated.scr' é executado antes que a pilha tcp do servidor seja iniciada [somente dedicado]

    deve ser usado para definir o nome dos servidores, senha e assim por diante:
  - 'on_server.scr' é executado após iniciar um servidor [dedicado e dentro do jogo]
  - 'on_dedicated.scr' é executado adicionalmente após iniciar um servidor [somente dedicado]

Para obter exemplos de como um script pode parecer, verifique os exemplos .example.