Resumo da aula

1- O entregável da aula é um resumo conciso com suas palavras sobre os principais pontos abordados.
O objetivo do aplicativo é ser uma interface de viagens onde o usuário pode explorar possíveis destinos que queira viajar

2- O resumo deve sintetizar a estrutura inicial do aplicativo de viagens.
Home.jsx:
É a página inicial do aplicativo
Destinos.jsx:
Onde fica a lista de destinos de viagem e onde os usuários podem adicionar novos destinos aparecendo na tela
Contato.jsx:
Onde ficam as informações sobre contato
Destino.jsx:
Mostra as informações de um destino, com nome e descrição
FormDestino.jsx:
É um formulário que permite inserir o nome e a descrição de um novo destino, aparecendo na lista de destinos
App.jsx:
Controla a navegação das páginas do aplicativo

3- Destacar as regras de negócio fundamentais, como os destinos pré-cadastrados.

-Todos os pontos para calcular distância partem do Brasil
-Temos 10 destinos pré cadastrados com suas distâncias
-Calcular a distância até o destino escolhido
-Distâncias acima de 2000 Km pega 2 voos
-Voos com menos de 2 meses de antecedência custam 1500 reais
-Voos com 2 meses ou mais custam 700 reais
-Acima de 2000 km, cada km adicional custa 1 real a mais
-Estalagem padrão: 400 reais a semana; Estalagem de luxo: 700 reais a semana
-Cada participante adicional aumenta os custos de estalagem em 25%
-O subtotal da viagem é exibido em tempo real
-Após selecionar as opções, o usuário é redirecionado para a tela de pagamento. Métodos disponíveis: pix ou cartão de crédito.


4- Explicar brevemente a lógica do cálculo de distância e custos da viagem.
-Distância > 2000 km, o custo é multiplicado por 2, resultando em um custo de 3000. Ou o custo é fixado em 1500
-Se for agendada com menos de dois meses de antecedência, o voo custa 1500, independentemente da distância
-Normal: 400 por semana; Modo rico: 700 por semana

5- Detalhar a interface de seleção e exibição do subtotal da viagem.
Seleção de Datas
Os usuários podem selecionar as datas de ida e volta da viagem, fazendo o sistema
calcula automaticamente a duração da viagem
Tipo de Estalagem
Pode ser escolhido dois tipos de estalagem, a padrão ou a de luxo, o custo varia dependendo de qual estalagem for escolhida
Número de Participantes
Cada participante extra depois da primeira pessoa tem uma taxa adicional de 25% 

Subtotal
Após selecionar tudo que estava acima, o sistema vai calcular o subtotal da viagem, incluindo o custo do voo e o custo total da estalagem.

6- Sugestões e melhorias ao aplicativo desenvolvido.
Uma coisa muito importante que ta faltando é um botão para poder excluir ou editar o destino e provavelmente algumas fotos

