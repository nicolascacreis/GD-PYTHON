## README - 🌱 Sistema de Gestão de Resíduos Coletados e Filtrados para Reciclagem ♻️

### Descrição
Este programa em Python é um sistema simples de gestão de resíduos coletados e filtrados para reciclagem. Ele permite ao usuário registrar resíduos, verificar se as metas de coleta foram atingidas e visualizar os resíduos já registrados. O sistema é projetado para funcionar em um loop contínuo até que o usuário opte por sair.

#### Funcionalidades
O sistema possui quatro funcionalidades principais:

Registrar resíduo coletado 📝: O usuário pode registrar a quantidade de um determinado resíduo que foi coletado.

Verificar metas dos resíduos filtrados 🎯: O sistema compara as quantidades registradas de cada tipo de resíduo com as metas estabelecidas e informa se as metas foram alcançadas ou não.

Visualizar resíduos registrados 👀: Permite ao usuário visualizar a quantidade de cada tipo de resíduo que foi registrada até o momento.

Sair 🚪: Finaliza o sistema.

### Estrutura do Código
Funções
forcaNumerico(msg) 🔢:

Força o usuário a inserir um valor numérico. Continua solicitando a entrada até que o usuário forneça um número válido.
forcaEscolha(lista, msg) ✅:

Força o usuário a escolher uma opção válida de uma lista de opções predefinidas. Continua solicitando a entrada até que o usuário forneça uma escolha válida.
buscaIndice(elemento, lista) 🔍:

### Busca o índice de um elemento em uma lista e o retorna. Esta função é útil para associar o resíduo escolhido pelo usuário à sua quantidade correspondente.
Listas
lista_opcoes 📋: Lista das opções de funcionalidades do sistema (Registrar, Metas, Registros, Sair).

lista_residuos 🗑️: Lista dos tipos de resíduos disponíveis para registro (Plásticos, Microplásticos, Poluentes Líquidos, Orgânicos).

lista_quantidades 📊: Lista das quantidades de cada tipo de resíduo coletado, iniciada em 0 para todos os resíduos.

lista_metas 🎯: Lista das metas de coleta para cada tipo de resíduo.

### Loop do Sistema
O sistema entra em um loop que continua até que o usuário escolha a opção "Sair". Dentro desse loop:

### O sistema exibe um menu com as funcionalidades disponíveis.
O usuário faz uma escolha utilizando a função forcaEscolha.
Dependendo da escolha, uma das funcionalidades (Registrar, Metas, Registros) é executada.
O processo se repete até que o usuário escolha "Sair".
Uso do Sistema
Execução 🖥️: Execute o programa em um ambiente Python.
Interação 🛠️: Siga as instruções apresentadas pelo sistema para registrar resíduos, verificar metas ou visualizar registros.
Encerramento 🚪: Para sair do sistema, selecione a opção "Sair".
Exemplo de Uso
### O sistema apresenta o menu principal.
O usuário escolhe "Registrar" e insere a quantidade de um resíduo coletado.
O sistema confirma o registro e retorna ao menu principal.
O usuário pode escolher "Metas" para verificar se as metas foram alcançadas.
O sistema informa o status das metas e retorna ao menu principal.
O usuário pode escolher "Registros" para visualizar os resíduos coletados até o momento.
Para encerrar o programa, o usuário escolhe "Sair".
Requisitos
Python 3.x
### Observações
Certifique-se de inserir valores numéricos e opções válidas conforme solicitado pelo sistema.
O sistema é simples e não possui persistência de dados; todas as informações são mantidas na memória durante a execução do programa.
