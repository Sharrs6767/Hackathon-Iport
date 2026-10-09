EQUIPE- RESTRUCT
-PARTICIPANTES - Gabriel Barretto/Augusto da Paz
Criamos um sistema web com uma interface simples e visualmente organizada para que o usuário (gestor de negócios) possa criar um perfil de seus funcoionários,
atribuir a ele uma equipe e sua capacidade semanal. O sistema também conta com a opção de criar um projeto onde usaremos na área planejamentos para que o programa
calcule e notifique qual funcionário está sobrecarregado/qual projeto está recebendo mais horas e um protótipo de assistente de IA que sugere mudanças nos DRAG AND DROP da tabela dinâmica.
Dedicamos bastante tempo para criar uma heatmap que mostra o percentual gasto de um funcionário em relação a sua tarefa e horas e a programação altera cartões de cada funcionário de acordo com uma cor de nivel de uso.




## Instalação e execução local

O Nosso programa foi desenvolvido com HTML, CSS, JavaScript, PHP e MySQL, utilizando o XAMPP como ambiente de desenvolvimento.

### Dependências (importantes para o funcionamento)

- XAMPP com Apache, PHP e MySQL
- Navegador atualizado
- Banco de dados disponibilizado no arquivo `hackathon.sql`

### Instruções

1. Instale o XAMPP.
2. Copie a pasta do programa baixada no repositório para o diretório `C:\xampp\htdocs\`.
3. Inicie os serviços Apache e MySQL no XAMPP CONTROL PANEL
4. Acesse `http://localhost/phpmyadmin`.CLicando em "Admin" em Mysql no xampp
5. Crie o banco de dados utilizado pelo projeto com o nome exatamente "hackathon"
6. Importe o arquivo `hackathon.sql` disponibilizado no Repositório para o banco criado
7. Configure a conexão PHP com o MySQL, conforme os dados do seu ambiente local.
8. Acesse a aplicação com o banco de dados aberto pelo endereço:

   `http://localhost/Hackaton3/iport.html`
