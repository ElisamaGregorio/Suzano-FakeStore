# Suzano-FakeStore
# Desafio Técnico - QA Pleno | Suzano

Este projeto é a solução para o **Desafio Técnico para vaga de QA Pleno** na Suzano.  
A proposta do desafio é garantir a qualidade da **API FakeStore** (`https://fakestoreapi.com`), antecipando riscos tanto no backend quanto em possíveis implementações de frontend.

---


## Objetivo

Validar o comportamento da API da FakeStore em diferentes cenários, assegurando:
- Retorno de dados esperados para requisições válidas
- Tratamento adequado de erros e entradas inválidas
- Conformidade com os padrões HTTP
- Tempo de resposta satisfatório

## Ferramentas Utilizadas

- [Postman](https://www.postman.com/)
- [Newman](https://www.npmjs.com/package/newman) *(opcional para automação CLI)*
- FakeStoreAPI: https://fakestoreapi.com

---


## Estrutura dos Testes

Cada teste foi executado conforme os seguintes critérios:
- **Método HTTP**
- **Validação de status code**
- **Validação de corpo da resposta**
- **Validação de tipos de dados**
- **Tempo de resposta inferior a 2 segundos**

---

##  Evidências

As evidências de cada execução estão disponíveis nos casos de testes e nos registros de Bug


---

## Como Executar os Testes

### 1. Manualmente via Postman
- Importe os endpoints para o Postman
- Execute cada requisição conforme descrito nos cenários
- Valide os resultados esperados

### 2. Automatizado com Newman (opcional)
```bash
newman run FakeStoreAPI_Testes.postman_collection.json
