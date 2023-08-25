🌐 Testes Automatizados com Behave e Selenium

Bem-vindo ao repositório behave_py_ge! Este é um projeto de demonstração que utiliza a biblioteca Behave e o Selenium para executar testes automatizados de comportamento em páginas web, especificamente no site do Globo Esporte.

Funcionalidade Testada ✨

Consultar o primeiro colocado na classificação do Brasileirão no site do Globo Esporte.

Pré-Requisitos 📋
Antes de executar os testes, certifique-se de ter as seguintes ferramentas instaladas:

Python: Download Python

ChromeDriver: Download ChromeDriver

Instalação e Execução 🚀

Clone o repositório:

git clone https://github.com/Gardene10/behave_py_ge.git

Acesse o diretório do projeto:

cd behave_py_ge

Instale as dependências:

pip install -r requirements.txt

Execute os testes:

behave

Cenário de Teste 📝

O teste automatizado é baseado no seguinte cenário de Gherkin:
gherkin

Funcionalidade: Consultar classificacao do Brasileirão

Cenario: Consultar Primeiro Colocado no Brasileirão
    Dado acesso a pagina inicial do globo esporte
    Quando clico no menu do brasileirao
    E a classificacao e exibida
    Então devo saber quem e o primeiro colocado
    
Contribuição 💬
Contribuições são bem-vindas! Se você encontrar problemas ou tiver melhorias para sugerir, fique à vontade para abrir uma issue ou um pull request.

Desenvolvido por Gardene 👋
Sinta-se à vontade para entrar em contato ou seguir meu perfil para mais projetos e colaborações futuras.

