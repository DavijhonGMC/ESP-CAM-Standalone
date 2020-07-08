# ESP-CAM-Standalone
ESP-CAM Standalone não assistido com Armazenamento em Flash

ESP-CAM-Standalone

Utilizar ESP-CAM para reconhecimento Facial que salve as ID em Flash interno Mantendo os Usuarios cadastrados mesmo em caso de renicialização ou Reset "Botão RST" Ao Iniciar o ESP-CAM cria uma Rede Wifi "XXXX" com senha "SSSS" pré-definida. (Passivél de alteração) só é possível cadastrar Usuários conectando nessa Rede direto do ESP-CAM "Sem Acesso a internet". ESP-CAM Inicia o sistema e o reconhecimento ao ser alimentado com 5v, sem precisar ter alguém conectado solicitando isso... Ele Inicia ao ser alimentado com 5V e já começa o reconhecimento!. se alguém Autorizado alinhar na frente da camera ele aciona o Pin-X para Output-High, se alguém não Autorizado alinhar na frente da camera ou sem ninguém o Pìn-X fica setado em Output-Low, ele precisa funcionar sem supervisão, o ESP-CAM precisa fucnionar como um "Stand-Alone" sem cliente conectado nele, ele realizar o processo sozinho assim que for Ligado/reiniciado.
