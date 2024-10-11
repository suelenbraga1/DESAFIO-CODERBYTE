![image](https://github.com/user-attachments/assets/f690c889-9864-4f44-8b7a-e359b9550fd2)

🏁 DESAFIO:

Imagine que você é o(a) arquiteto(a) responsável pelo desenho de um sistema de logins para um site extremamente concorrido de ingressos de um mega show de Rock em Rio (got it?).
Dado que o número de ingressos é limitado e muito inferior a quantidade de acessos no dia venda, você precisa garantir que o site só irá finalizar a venda para pessoas que realmente
vão receber o ingresso, ou seja, você não pode deixar uma pessoa comprar um ingresso sem que haja mais disponíveis. 
Além disso, um cliente com internet mais lenta não ficaria feliz de não conseguir comprar seu ingresso pois uma pessoa com internet mais veloz passou sua frente.


Desenhe uma estrutura de software que sustente esse serviço, pode ser um desenho simples, da maneira que você preferir, desde que o mesmo transmita a ideia da arquitetura que você teve para quem o lê.

📋 Descrição: 

- <strong>Frontend (Web/Mobile):</strong> Interface do usuário que permite a interação com o sistema, como login e compra de ingressos.
- <strong>API Gateway:</strong> Ponto de entrada para todas as requisições, direcionando-as aos serviços apropriados.
- <strong>Services:</strong> Auth Service: Gerencia o login e o registro dos usuários. Ticket Service: Responsável por verificar a disponibilidade de ingressos, reservar e confirmar compras. User Service: Gerencia dados do usuário, como perfil e histórico de pedidos.
- <strong>Database Service:</strong> Armazena informações do usuário, inventário de ingressos e histórico de transações.


