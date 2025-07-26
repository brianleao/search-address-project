# Projeto de Busca de Endereços

<img width="3104" height="1974" alt="image" src="https://github.com/user-attachments/assets/7162eb71-24ee-464f-822a-0404380becb4" />


Este projeto utiliza a API do Google Maps para buscar endereços e exibir no mapa.

## Configuração das Variáveis de Ambiente

1. Copie o arquivo `.env.example` para `.env`:
   ```bash
   cp .env.example .env
   ```

2. Edite o arquivo `.env` e substitua `your_google_api_key_here` pela sua chave da API do Google Maps:
   ```
   GOOGLE_API_KEY=sua_chave_aqui
   ```

3. Certifique-se de que o arquivo `.env` está listado no `.gitignore` (já está configurado).

## Como executar

1. Instale as dependências:
   ```bash
   npm install
   ```

2. Inicie o servidor de desenvolvimento:
   ```bash
   npm start
   ```

3. Acesse o projeto em `http://localhost:8081`

## Importante

- Nunca commite o arquivo `.env` no repositório
- Use o `.env.example` como template para outros desenvolvedores
- Mantenha suas chaves de API seguras
