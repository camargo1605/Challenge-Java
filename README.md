RM556325 - Felipe Camargo

RM555997 - Caio Marques

RM558640 - Caio Amarante

## 💡 Objetivo do Projeto

Este projeto consiste na criação de uma API REST utilizando Java com Spring Boot que suporta a solução para o desafio proposto pela FIAP no sprint de Java Advanced.

A API é responsável por gerenciar entidades relacionadas ao controle de motos em filiais, incluindo funcionalidades completas de CRUD para pelo menos duas entidades, além de implementar:

    Uso do Spring Web para criação da API RESTful;

    Integração com banco de dados Oracle ou H2 via Spring Data JPA;

    Relacionamentos entre entidades conforme modelo relacional fornecido;

    Validação de campos utilizando Bean Validation;

    Implementação de paginação, ordenação e busca por parâmetros para resultados;

    Utilização de cache para otimizar requisições;

    Aplicação de boas práticas de design REST;

    Tratamento centralizado de erros para maior robustez da API;

    Uso de DTOs para transferência segura e eficiente dos dados.

Este projeto busca atender os requisitos técnicos e critérios de avaliação definidos para o sprint, entregando uma solução organizada, inovadora e aderente ao desafio proposto.

---

## 🧸 Atributos da entidade `Brinquedo`

A entidade `Brinquedo` possui os seguintes atributos:

- `id` (Long)
- `nome` (String)
- `tipo` (String)
- `classificacao` (String)
- `tamanho` (String)
- `preco` (Double)

---

## 🔗 Endpoints da API

| Método | Rota               | Descrição                  |
|--------|--------------------|----------------------------|
| POST   | /brinquedos        | Cadastrar um brinquedo     |
| GET    | /brinquedos        | Listar todos os brinquedos |
| PUT    | /brinquedos/{id}   | Atualizar um brinquedo     |
| DELETE | /brinquedos/{id}   | Deletar um brinquedo       |

## Spring da aplicação
![image](https://github.com/user-attachments/assets/dfafe874-3f4d-4045-81af-92060b28eb38)

---

## 🧪 Exemplo de JSON para POST

```json
{
  "nome": "Boneca Mágica",
  "tipo": "Educativo",
  "classificacao": "4+",
  "tamanho": "Pequeno",
  "preco": 89.90
}
