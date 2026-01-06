# cadastrar-conta-zimbra

## Instruções para rodar o projeto:

### Criar o ambiente virtual:

- python3 -m venv .venv

### Ativar o ambiente virtual:

- source .venv/bin/activate (linux/mac)
- .\env\Scripts\activate.bat (windows)

### Instalar as dependências:

- pip install -r requirements.txt

### Instalar o Playwright

- playwright install

### Configurar o ambiente:

- Copiar o arquivo .env.example para .env e preencher os valores

### Planilha com as contas a serem cadastradas:

- Use o arquvo estagiarios-exemplo.xlsx como exemplo
- A planilha deve ter as colunas: nome, lotação e funcional
- O nome dela deve ser estagiarios.xlsx (sem acentos)
