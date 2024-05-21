TRABALHO CAROL
Sistema de Gerenciamento de Receitas
Índice
Descrição
Configuração
Requisitos
Progresso Atual
Briefing do Projeto

1. Descrição
Este é um sistema de gerenciamento de receitas que permite adicionar, visualizar, atualizar, excluir, filtrar, listar receitas favoritas, obter uma receita aleatória e avaliar receitas. As receitas são armazenadas em um arquivo CSV.

Funcionalidades:
Adicionar Receita: Permite adicionar uma nova receita ao sistema.
Visualizar Receitas: Exibe todas as receitas armazenadas.
Atualizar Receita: Permite atualizar os detalhes de uma receita existente.
Excluir Receita: Permite excluir uma receita existente.
Filtrar por País: Filtra as receitas pelo país de origem.
Listar Receitas Favoritas: Exibe todas as receitas marcadas como favoritas.
Receita Aleatória: Exibe uma receita aleatória.
Dar Nota à Receita: Permite dar uma nota a uma receita e calcular a média das avaliações.

2. Configuração
Pacotes utilizados:
Python 3.8+
Python 3.8 Virtual Environment (venv)
Pip
Passo a passo de instalação e configuração:
Clone este repositório:
(git clone https://github.com/seu_usuario/seu_repositorio.git)

2.  Dentro da pasta raiz, recrie o ambiente virtual:
(python3 -m venv venv)

3.  Ative o ambiente virtual:
No Linux e MacOS:
(. venv/bin/activate)
No Windows:
(venv\Scripts\activate)

4.  Instale os pacotes necessários:
(pip install -r requirements.txt)

5.  Crie um arquivo CSV vazio se ele não existir:
(touch recipes.csv)

7.  Execute a aplicação:
(python3 app.py)

3. Requisitos
O sistema deve:
Possuir um menu interativo para navegação entre as funcionalidades.
Armazenar as receitas em um arquivo CSV.
Permitir a adição, visualização, atualização e exclusão de receitas.
Permitir filtrar receitas por país de origem.
Permitir marcar receitas como favoritas.
Permitir obter uma receita aleatória.
Permitir avaliar receitas e calcular a média das avaliações.

4. Progresso Atual
Lista de funcionalidades:
Adicionar Receita
Visualizar Receitas
Atualizar Receita
Excluir Receita
Filtrar por País
Listar Receitas Favoritas
Receita Aleatória
Dar Nota à Receita
Armazenamento em CSV
                                                                                                                                                             Para próxima versão:
Interface gráfica
Integração com banco de dados
Autenticação de usuários

5. Briefing do Projeto
Definição do desafio:
Crie um sistema de gerenciamento de receitas que permita ao usuário adicionar, visualizar, atualizar, excluir, filtrar e avaliar receitas. As receitas devem ser armazenadas em um arquivo CSV e o sistema deve ser acessível através de um menu interativo no terminal.

Objetivo:
O objetivo é criar uma solução que permita o gerenciamento completo de receitas, utilizando Python para manipulação de dados e interação com o usuário via terminal. A arquitetura deve ser modular e escalável, permitindo futuras expansões como a adição de uma interface gráfica ou integração com um banco de dados.

Estrutura do Código:
Classe Recipe: Representa uma receita e possui métodos para inicialização, exibição e manipulação de avaliações.
Funções Utilitárias: Funções para limpar a tela, ler e escrever receitas em um arquivo CSV.
Funções de Interface: Funções para exibir o menu, adicionar, visualizar, atualizar, excluir, filtrar, listar, obter receita aleatória e avaliar receitas.
Função Principal: Controla o fluxo principal do programa, exibindo o menu e chamando as funções apropriadas com base na escolha do usuário.

Motivações:
Escolhemos armazenar as receitas em um arquivo CSV por ser uma solução simples e eficiente para o escopo atual do projeto. A utilização de um menu interativo no terminal facilita a interação do usuário sem a necessidade de interfaces gráficas complexas.

Futuras Expansões:
Se tivermos mais tempo, poderemos adicionar uma interface gráfica utilizando bibliotecas como Tkinter ou PyQt, integrar o sistema a um banco de dados como SQLite ou PostgreSQL para melhor gerenciamento de dados, e implementar autenticação de usuários para maior segurança e personalização.


FLUXOGRAMA:

![image](https://github.com/arthurvemery/bibliotecaemeratos/assets/151037686/da82a200-0dd9-4df0-bfc2-3518e5b4ef4e)
