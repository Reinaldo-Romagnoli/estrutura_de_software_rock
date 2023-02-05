# estrutura_de_software_rock
Banco de dados: Armazene informações sobre o número total de ingressos disponíveis, bem como informações sobre as pessoas que já compraram ingressos.

API de acesso ao banco de dados: Esta camada fornece uma interface para a camada de front-end para acessar e atualizar informações no banco de dados.

Camada de front-end: Esta camada é responsável por apresentar a interface do usuário para os compradores de ingressos. O usuário pode verificar a disponibilidade de ingressos e fazer uma compra através desta camada.

Controlador de solicitação: Esta camada é responsável por lidar com as solicitações de compra de ingressos vindas da camada de front-end. Ele verifica se há ingressos disponíveis antes de permitir que a compra seja concluída.

Processador de pagamento: Esta camada é responsável por lidar com as transações de pagamento. Verifica se o pagamento foi concluído com sucesso antes de permitir que o ingresso seja marcado como vendido.

Balanceador de carga: Este componente garante que o sistema não fique sobrecarregado durante períodos de alta demanda. Ele distribui a carga de trabalho de maneira equilibrada entre vários servidores, o que permite a escalabilidade do sistema.
