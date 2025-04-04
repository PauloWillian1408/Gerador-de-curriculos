# Gerador-de-curriculos
Meu primeiro projeto em html.
Este é um projeto web simples que permite aos usuários criar currículos de forma rápida e eficiente, com a opção de gerar um PDF. O sistema conta com funcionalidades de login e registro (simulados no lado do cliente), preenchimento de informações do currículo e download do arquivo gerado.

Tecnologias Utilizadas

1- HTML: Estrutura da página

2- CSS: Estilização responsiva e animações

3- JavaScript: Manipulação do DOM e geração de PDF

4- jsPDF: Biblioteca usada para criar e baixar o PDF

Funcionalidades
1- Autenticação Simples

*Simulação de login e registro de usuário (sem backend)

*Alternação entre as telas de login, registro e preenchimento do currículo

2- Formulário de Currículo

*Campos para nome, email, telefone, experiência, formação acadêmica, certificados e habilidades

3- Geração de PDF

*Usa jsPDF para criar e baixar o currículo em formato PDF

*Formatação organizada do conteúdo no PDF

Estrutura do Código

1- HTML

*Contém três seções principais:

*Login (id="auth")

*Registro (id="register")

*Formulário do currículo (id="app")

*Cada seção tem inputs e botões para interação do usuário

2- CSS

*Layout responsivo com max-width para dispositivos menores

*Gradiente de fundo para um design moderno

*Animação fadeIn para suavizar a entrada da interface

3- JavaScript

*Funções de login e registro:

*showRegister(): Mostra o formulário de registro

*showLogin(): Volta para a tela de login

*login(): Simula autenticação e exibe o formulário do currículo

*register(): Simula um cadastro e volta para a tela de login

Geração do PDF:

*generatePDF(): Captura os valores dos campos e gera um PDF formatado

*Define cabeçalhos e posiciona o texto no documento

*Salva o PDF com o nome do usuário

Melhorias Futuras

*Implementação de um backend para autenticação real

*Personalização do layout do PDF

*Opção para salvar e editar currículos anteriores
