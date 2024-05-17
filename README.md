<div align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo-full.svg" alt="Logo Bootcamp" width="80">
<h1> Coding The Future Vivo <br> Python AI Backend Developer </h1>
<img src="https://hermes.dio.me/files/assets/ef695d25-f647-45eb-b1ad-a25c124b28ca.png" alt="Logo Bootcamp" width="220">
</div>
 
 <h1 align="center"> Sistema Bancário em POO com Python </h1>

Este é um desafio de projeto do **Coding The Future Vivo - Python AI Backend Developer** 

Desafio: Criando Uma API Com FastAPI Utilizando TDD

**Funcionalidades** 🛠️

## Instalando o Invoke Para automação de tarefas
Para usar o invoke, você precisa instalá-lo no ambiente do seu projeto Python. Você pode fazer isso usando o pip, o gerenciador de pacotes Python.

Abra o terminal do PyCharm e execute o seguinte comando:

```
pip install invoke
```
## Usando o Invoke
Após a instalação do invoke, você pode criar um arquivo tasks.py no diretório raiz do seu projeto para definir suas tarefas. Para configurar o invoke para um projeto FastAPI com Uvicorn, você pode criar tarefas no arquivo tasks.py para iniciar o servidor Uvicorn e realizar outras tarefas relacionadas ao desenvolvimento do seu projeto.

Linhas de comando utilizadas:

Rodando o projeto
````commandline
invoke start
````
Instalando o pre-commit
````commandline
invoke precommit-install
````
Rodanto os testes
````commandline
invoke test
````
Executando testes que correspondam a uma determinada expressão
````commandline
invoke test-matching -k "test_usecases_query_should_return_success"
````

