# 3 - Inspeção de Usabilidade
### 3.1 - Planejamento


### 3.2 - Detecção
Descrição: Cada inspetor realiza de forma isolada essa etapa, que envolve identificar potenciais problemas de usabilidade nas interações escolhidas.

**Inspetor**: **A1**

| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
| 1  |  Quando o usuário tenta se cadastrar no PayPal e pesquisa seu endereço, o sistema não fornece um feedback correto ou útil, resultando em dificuldades para completar o cadastro. | Ajuda ao usuário e documentação. | 3 | Estima-se 8 horas para revisar e melhorar o sistema de feedback de endereços no cadastro. |
| 2  | Usuários ficam perdidos ao entrar no aplicativo após se cadastrarem, pois a interface é diferente de outros aplicativos bancários, dificultando a navegação e o uso eficiente. | Consistência e padrões. | Média, pois, embora não impeça o uso, causa dificuldades e frustrações que podem levar ao abandono do aplicativo. | Estima-se 12 horas para redesenhar elementos-chave da interface para torná-la mais intuitiva e consistente com outros aplicativos bancários populares. |
| 3  |  As opções de pagamento são complexas, e poderia ser mais fácil se houvesse uma opção para pagar com Pix. |  Flexibilidade e eficiência de uso. | Média, pois a complexidade das opções de pagamento pode causar frustração e abandono do processo de compra. | Estima-se 10 horas para implementar a opção de pagamento via Pix e ajustar a interface para simplificar as opções de pagamento. |
| 4  | Quando solicitado um pagamento, a opção para visualizar o histórico de pagamentos pendentes é difícil de encontrar, e não mostra se a mensagem foi vista, causando confusão e frustração. | Visibilidade do status do sistema. | Média, pois afeta a usabilidade e clareza das informações, mas não impede totalmente o funcionamento. | Estima-se 8 horas para redesenhar a interface, tornando a opção de histórico mais visível e incluindo um indicador de mensagens vistas. |
| 5 | Não fornecer feedback claro sobre o status de transações ou pagamentos em andamento, deixando os usuários incertos sobre se a transação foi bem-sucedida. | Visibilidade do status do sistema. | Alta, pois causa incerteza e potencial frustração, podendo resultar em múltiplas tentativas de pagamento ou abandono do processo. | Estima-se 10 horas para implementar notificações claras e detalhadas sobre o status das transações, incluindo mensagens de confirmação.|
| 6 | Usa muitos termos técnicos e jargões financeiros que podem não ser familiares a todos os usuários, especialmente aqueles que não estão acostumados a transações online. | Compatibilidade entre o sistema e o mundo real. | Média, pois pode causar confusão e dificuldade na compreensão das informações, mas não impede totalmente o funcionamento. | Estima-se 8 horas para revisar e simplificar a linguagem utilizada no sistema, incluindo explicações ou dicas para termos mais técnicos.|
| 7 | Em alguns casos, pode ser difícil desfazer uma transação ou cancelar um pagamento, especialmente se a transação já estiver processada. | Controle e liberdade do usuário. | Alta, pois limita a capacidade do usuário de corrigir erros ou mudar de ideia, gerando frustração e possíveis problemas financeiros. | Estima-se 12 horas para implementar funcionalidades de cancelamento e desfazimento de transações, incluindo alertas e confirmações claras. |
| 8 | Exigir que os usuários lembrem de informações específicas, como números de referência ou detalhes de transações passadas, sem fornecer uma maneira fácil de recuperar essas informações. | Reconhecimento em vez de memorização. | Alta, pois sobrecarrega a memória do usuário e aumenta a chance de erros, gerando frustração. | Estima-se 10 horas para implementar uma funcionalidade que permita fácil recuperação de informações específicas diretamente no sistema. |
| 9 | Não oferece atalhos ou opções de personalização suficientes para tornar o processo de pagamento mais rápido e eficiente. |  Flexibilidade e eficiência de uso. |  Média, pois afeta a eficiência e pode causar frustração, mas não impede o funcionamento. |  Estima-se 8 horas para implementar atalhos e opções de personalização no processo de pagamento.|
| 10 | Algumas partes são visualmente sobrecarregadas com informações e opções desnecessárias, dificultando a navegação. |  Design estético e minimalista. |  Média, pois complica a navegação e pode gerar frustração, mas não impede o uso do sistema. | Estima-se 10 horas para simplificar a interface, removendo informações desnecessárias e reorganizando opções para uma melhor experiência de navegação. |
| 11 | Embora o PayPal ofereça suporte, às vezes a documentação e os guias de ajuda podem ser difíceis de encontrar ou entender, especialmente para novos usuários. | Ajuda e documentação. | Média, pois dificulta a resolução de problemas e o aprendizado do sistema, causando frustração.| Estima-se 8 horas para melhorar a visibilidade da documentação e simplificar os guias de ajuda, tornando-os mais acessíveis e compreensíveis para novos usuários.|
| 12 | As mensagens de erro podem ser vagas e não fornecer instruções claras sobre como resolver problemas específicos, deixando os usuários frustrados. | Reconhecimento, diagnóstico e recuperação de erros. |  Alta, pois impede o usuário de resolver problemas eficazmente e causa frustração. | Estima-se 10 horas para revisar e detalhar as mensagens de erro, fornecendo orientações claras e passos para a resolução de problemas específicos.|



**Inspetor**: **A3**

| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
| 1 | 

**Inspetor**: **A5**

| ID | Descrição do problema | Heurística Violada | Severidade | Carga Horária |
|----|-----------------------|--------------------|------------|---------------|
| 1 | Há uma certa difificulade para o aplicativo mostrar que o pagamento foi concluido| Visibilidade do sistema | Grande | 0:25|
|2| Ao enviar dinheiro por engano é dificultoso encontar uma opçao clara para corrigir/cancelar a transação| controle e liberdade do usúario| Pequeno| 0:42|
|3| Ao fazer transferências o aplicativo não da a opção do usúario verificar pela segunda vez se o destinatário está correto| Prevenção de erros |Grande | 00:20|
|4|Os ícones que remetem a "pagamentos" no aplicativos são diferentes dos que já estamos acostumados que dificulta a parte intuitiva do usúario| Reconhecer ao invés de relembrar| Pequeno| 00:5 |
|5| Apesar dde minimalista em seu menu a tela inicial que aparece após fazer login no aplicativo transmite o aspecto de bagunçado no qual não transmite o profissionalismo que deveria| Estética e desing minimalista |Cósmetico| 1:00 |

