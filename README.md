Detective Quest - Nível: Novato 🕵️‍♂️
📝 Descrição do ProjetoO Detective Quest é um jogo de exploração em modo texto desenvolvido para a Enigma Studios. 
O objetivo é aplicar conceitos de Estrutura de Dados para criar um mapa de uma mansão onde o jogador navega entre os cômodos para completar uma investigação.
🛠️ Conceitos Técnicos AplicadosEste projeto foi desenvolvido em C/C++ utilizando os seguintes conceitos fundamentais:
Árvore Binária: Utilizada para representar a hierarquia e as ramificações do mapa da mansão.
Alocação Dinâmica: Uso de malloc para criação de nós (salas) em tempo de execução.
Structs: Criação de um tipo personalizado Sala para armazenar o nome e os ponteiros de navegação.
Recursividade: Aplicada na função de liberação de memória para percorrer e limpar a árvore.
🎮 Como Jogar: O jogo inicia no Hall de Entrada. 
O jogador visualiza as opções de caminhos disponíveis (Esquerda ou Direita).
A navegação prossegue até que o jogador alcance um nó-folha (um cômodo sem saídas extras).Durante a jornada, o sistema exibe o nome de cada sala visitada para orientação.
🚀 Estrutura do CódigocriarSala(): Aloca memória dinamicamente e inicializa um novo cômodo.
explorarSalas(): Gerencia a interação com o usuário e a movimentação pelos ponteiros da árvore.
main(): Responsável por montar a estrutura fixa da mansão e disparar a lógica do jogo.
👩‍🎓 IdentificaçãoEstudante: Geise Severo Eduardo
Cursos: Bacharelado em Ciências da Computação e Engenharia de Software (3º Semestre)
Instituição: Estácio