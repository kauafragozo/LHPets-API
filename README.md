LH Pets MVC
Este é um projeto ASP.NET Core MVC que gerencia informações sobre clientes e fornecedores de uma loja de produtos para animais de estimação.

Requisitos
Certifique-se de ter o ambiente de desenvolvimento ASP.NET Core configurado em sua máquina antes de executar este projeto.

Configuração do Projeto
Clone este repositório para o seu ambiente local.
Abra o projeto em seu ambiente de desenvolvimento ASP.NET Core (por exemplo, Visual Studio Code ou Visual Studio).
Execute o projeto.
Ao ser executado, o projeto carregará uma lista de clientes e fornecedores e exibirá essas informações na página inicial.

Estrutura do Projeto
Controllers/HomeController.cs: Controlador responsável por gerenciar as ações relacionadas às páginas.
Models/Clientes.cs e Models/Fornecedores.cs: Classes que representam clientes e fornecedores, respectivamente, com atributos como ID, nome, CPF, e-mail, entre outros.
Views/Home/Index.cshtml: Página HTML que exibe listas de clientes e fornecedores.
Views/Home/Privacy.cshtml e Views/Home/Error.cshtml: Páginas de exemplo que podem ser personalizadas conforme necessário.
Funcionalidades
Página Inicial (/Home/Index)
Exibe uma tabela de clientes e uma tabela de fornecedores.
Cada cliente possui informações como ID, nome, CPF, e-mail e animal de estimação.
Cada fornecedor possui informações como ID, nome, CNPJ e e-mail.
Página de Privacidade (/Home/Privacy)
Página de exemplo que pode ser personalizada conforme necessário.
Página de Erro (/Home/Error)
Exibe informações sobre erros, incluindo um identificador de solicitação para rastreamento.
Visualização de Dados
Lista de Clientes
A tabela exibe os seguintes campos:

ID
Nome
CPF
E-mail
Paciente (pet)
Lista de Fornecedores
A tabela exibe os seguintes campos:

ID
Nome
CNPJ
E-mail
