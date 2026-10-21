# Assistente Gemini

Exemplo de um assistente técnico simples usando a API do Google Gemini.

## Requisitos

- Python 3.10 ou superior
- Uma chave de API do Gemini

## Configuração

1. Crie e ative um ambiente virtual:

   ```bash
   python -m venv .venv
   ```

   No Windows (PowerShell):

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

   No Windows (Git Bash):

   ```bash
   source .venv/Scripts/activate
   ```

2. Instale as dependências:

   ```bash
   python -m pip install -r requirements.txt
   ```

3. Copie `.env.example` para `.env` e substitua `sua_chave_aqui` pela sua chave de API.

4. Execute o programa:

   ```bash
   python app.py
   ```

O arquivo `.env` é ignorado pelo Git. Nunca publique sua chave de API.
