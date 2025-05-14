RM556325 - Felipe Camargo

RM555997 - Caio Marques

RM558640 - Caio Amarante

## 💡 Objetivo do Projeto

Este projeto consiste na criação de uma API REST utilizando Java com Spring Boot que suporta a solução para o desafio proposto pela FIAP no sprint de Java Advanced.

A API é responsável por gerenciar entidades relacionadas ao controle de motos em filiais, incluindo funcionalidades completas de CRUD para pelo menos duas entidades, além de implementar:

   - Uso do Spring Web para criação da API RESTful
   -  Integração com banco de dados Oracle ou H2 via Spring Data JPA
   -  Relacionamentos entre entidades conforme modelo relacional fornecido
   -  Validação de campos utilizando Bean Validation
   -  Implementação de paginação, ordenação e busca por parâmetros para resultados
   -  Utilização de cache para otimizar requisições
   -  Aplicação de boas práticas de design REST
   -  Tratamento centralizado de erros para maior robustez da API
   -  Uso de DTOs para transferência segura e eficiente dos dados
     
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

| Método | Endpoint       | Descrição                 |
| ------ | -------------- | ------------------------- |
| POST   | `/paises`      | Criar um novo país        |
| GET    | `/paises`      | Listar todos os países    |
| PUT    | `/paises/{id}` | Atualizar um país pelo ID |
| DELETE | `/paises/{id}` | Deletar um país pelo ID   |

| Método | Endpoint        | Descrição                   |
| ------ | --------------- | --------------------------- |
| POST   | `/estados`      | Criar um novo estado        |
| GET    | `/estados`      | Listar todos os estados     |
| PUT    | `/estados/{id}` | Atualizar um estado pelo ID |
| DELETE | `/estados/{id}` | Deletar um estado pelo ID   |

| Método | Endpoint        | Descrição                   |
| ------ | --------------- | --------------------------- |
| POST   | `/clientes`      | Criar um novo estado        |
| GET    | `/clientes`      | Listar todos os estados     |
| PUT    | `/clientes/{id}` | Atualizar um estado pelo ID |
| DELETE | `/clientes/{id}` | Deletar um estado pelo ID   |

| Método | Endpoint        | Descrição                    |
| ------ | --------------- | ---------------------------- |
| POST   | `/cidades`      | Criar uma nova cidade        |
| GET    | `/cidades`      | Listar todas as cidades      |
| PUT    | `/cidades/{id}` | Atualizar uma cidade pelo ID |
| DELETE | `/cidades/{id}` | Deletar uma cidade pelo ID   |

| Método | Endpoint        | Descrição                    |
| ------ | --------------- | ---------------------------- |
| POST   | `/filiais`      | Criar uma nova filial        |
| GET    | `/filiais`      | Listar todas as filiais      |
| PUT    | `/filiais/{id}` | Atualizar uma filial pelo ID |
| DELETE | `/filiais/{id}` | Deletar uma filial pelo ID   |

| Método | Endpoint      | Descrição                  |
| ------ | ------------- | -------------------------- |
| POST   | `/motos`      | Criar uma nova moto        |
| GET    | `/motos`      | Listar todas as motos      |
| PUT    | `/motos/{id}` | Atualizar uma moto pelo ID |
| DELETE | `/motos/{id}` | Deletar uma moto pelo ID   |

| Método | Endpoint         | Descrição                    |
| ------ | ---------------- | ---------------------------- |
| POST   | `/usuarios`      | Criar um novo usuário        |
| GET    | `/usuarios`      | Listar todos os usuários     |
| PUT    | `/usuarios/{id}` | Atualizar um usuário pelo ID |
| DELETE | `/usuarios/{id}` | Deletar um usuário pelo ID   |

| Método | Endpoint           | Descrição                      |
| ------ | ------------------ | ------------------------------ |
| POST   | `/movimentacao-moto`      | Criar um novo movimento        |
| GET    | `/movimentacao-moto`      | Listar todos os movimentos     |
| PUT    | `/movimentacao-moto/{id}` | Atualizar um movimento pelo ID |
| DELETE | `/movimentacao-moto/{id}` | Deletar um movimento pelo ID   |

| Método | Endpoint            | Descrição                        |
| ------ | ------------------- | -------------------------------- |
| POST   | `/manutencao-moto`      | Criar uma nova manutenção        |
| GET    | `/manutencao-moto`      | Listar todas as manutenções      |
| PUT    | `/manutencao-moto/{id}` | Atualizar uma manutenção pelo ID |
| DELETE | `/manutencao-moto/{id}` | Deletar uma manutenção pelo ID   |

| Método | Endpoint             | Descrição                         |
| ------ | -------------------- | --------------------------------- |
| POST   | `/localizacao-moto`      | Criar uma nova localização        |
| GET    | `/localizacao-moto`      | Listar todas as localizações      |
| PUT    | `/localizacao-moto/{id}` | Atualizar uma localização pelo ID |
| DELETE | `/localizacao-moto/{id}` | Deletar uma localização pelo ID   |

| Método | Endpoint         | Descrição                   |
| ------ | ---------------- | --------------------------- |
| POST   | `/sensor-moto`      | Criar um novo sensor        |
| GET    | `/sensor-moto`      | Listar todos os sensores    |
| PUT    | `/sensor-moto/{id}` | Atualizar um sensor pelo ID |
| DELETE | `/sensor-moto/{id}` | Deletar um sensor pelo ID   |

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
