# DESAFIO-QA-BEEDOO-2026

- Qual você acredita ser o objetivo da aplicação?
  
Durante a exploração da aplicação, foi possível entender que ela tem como objetivo permitir o cadastro e a visualização de cursos.
A interface apresenta duas funcionalidades principais: o cadastro de novos cursos e a listagem dos cursos já cadastrados. A navegação entre essas funcionalidades acontece através do menu superior, onde existem as opções “Listar Cursos” e “Cadastrar Curso”.
A proposta da aplicação parece ser um sistema simples de gerenciamento de cursos, onde o usuário pode registrar novas informações e posteriormente consultar os cursos cadastrados.

- Quais são os principais fluxos disponíveis
  
1. Cadastro de curso: 
Nesse fluxo o usuário acessa a opção Cadastrar Curso, preenche os campos do formulário e realiza o cadastro de um novo curso. Após o cadastro, espera-se que esse curso passe a fazer parte da listagem disponível na aplicação.

2. Listagem de cursos: 
Esse fluxo permite visualizar todos os cursos que foram cadastrados no sistema. A expectativa é que a lista seja atualizada sempre que um novo curso for registrado.
Esses dois fluxos representam a funcionalidade central da aplicação, já que todo o uso do sistema gira em torno de cadastrar e consultar cursos.

- Quais pontos do sistema você considera mais críticos para teste?
  
Durante a exploração da aplicação, alguns pontos chamaram mais atenção e foram priorizados na criação dos cenários de teste.

Cadastro de cursos:
O formulário de cadastro é um ponto crítico porque é nele que os dados são inseridos no sistema. Por isso, é importante validar:
comportamento dos campos obrigatórios
tratamento de campos vazios
validação de formatos de dados
comportamento ao inserir valores inesperados

Persistência das informações:
Outro ponto importante é garantir que os cursos cadastrados realmente apareçam na listagem após o cadastro, garantindo que os dados estejam sendo corretamente registrados e exibidos na aplicação.

Listagem de cursos:
A tela de listagem também foi considerada relevante para testes, pois ela representa o retorno visual das informações cadastradas. É importante validar se:
os cursos aparecem corretamente após o cadastro
a lista se atualiza conforme esperado
o sistema lida corretamente com cenários onde não existem cursos cadastrados.
