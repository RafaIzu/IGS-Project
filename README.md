<h1>Projeto IGS</h1>
<p>Candidato: Rafael Belmonte Izukawa</p>
<br>
<hr>
<h2>Obtenção do código e preparo do ambiente</h2>
<ol>
    <li>Clone o repositório</li>
    <li>Crie um ambiente virtual do Python</li>
    <li>Ative o ambiente</li>
    <li>Atualize o PIP</li>
    <li>Instale as dependências  contidas em requirements.txt</li>
</ol>
<br>
<hr>
<h2>Instalação e execução da API</h2>
<ol>
    <li>Em seu terminal, vá até a pasta EmployeeAPI</li>
    <li>digite o comando: "python3 manage.py makemigrations"</li>
    <li>digite o comando: "python3 manage.py migrate"</li>
    <li>Crie um admin utilizando o comando "python3 manage.py createsuperuser"</li>
    <li>Inicie o servidor na porta padrão. Utilize o comando "python3 manage.py runserver"</li>
    <li>Abra o navegador e digite: "http://127.0.0.1:8000/api/department" na barra de navegação</li>
    <li>Insira alguns registros usando o campo DepatName</li>
    <li>Digite: "http://127.0.0.1:8000/api/employee" na barra de navegação</li>
    <li>Insira alguns registros usando o campo Empname, Email e Depat</li>
    <li><strong>Deixe o servidor ligado</strong></li>
</ol>
<br>
<hr>
<h2>Instalação da página de visualização de dos dados </h2>
<ol>
    <li>Em seu terminal, vá até a pasta EmployeeView</li>
    <li>Inicie o servidor utilizando a porta 7000 ou outro da sua escolha. Utilize o comando "python3 manage.py runserver 7000"</li>
    <li>Abra o navegador e digite: "http://127.0.0.1:7000/" na barra de navegação</li>
    <li>Os dados da API serão mostrados em uma tabela.</li>
</ol>
<br>
<h3>Fim</h3>