# PIX Gateway Service

Bem-vindo à documentação do **PIX Gateway Service**. Este serviço é o ponto de entrada principal para as operações de PIX do Zetra Bank.

## 🚀 Visão Geral

O gateway é responsável por receber as requisições de transferências, consultar o chaves no DICT e rotear com segurança os payloads para o processamento core.

### Fluxos Principais
1. **Envio de PIX**: Validação de saldo e comunicação com o BACEN.
2. **Consulta DICT**: Resolução de chaves (CPF, E-mail, Celular).

## 🛠️ Stack Tecnológica

* **Linguagem:** GoLang / Gin Framework
* **Banco de Dados:** PostgreSQL

## 📦 Como Executar Localmente

```bash
# Clone o repositório
git clone [https://github.com/emanueldeveloper82/pix-gateway-service.git](https://github.com/emanueldeveloper82/pix-gateway-service.git)

# Execute a aplicação
go run main.go