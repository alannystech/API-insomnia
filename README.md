
# 📚 Projeto de Testes Manuais - API Educacional

Este repositório apresenta os testes manuais realizados na *API Educacional, disponível em [https://educational-api-75qy.onrender.com/swagger.json](https://educational-api-75qy.onrender.com/swagger.json), utilizando a ferramenta **Insomnia* para criação, execução e validação de requisições REST.

---

## 🎯 Objetivo

Demonstrar conhecimentos em *testes manuais de API REST*, aplicando os métodos HTTP mais utilizados (GET, POST, PUT, DELETE) e registrando *evidências visuais* dos testes.

---

## 🛠 Ferramentas Utilizadas

- [Insomnia](https://insomnia.rest/)
- API REST (Swagger disponível)
- JSON como formato de payload
- GitHub para versionamento

---

## 🔍 Endpoints testados

| Método  | Endpoint              | Ação Realizada                             |
|---------|-----------------------|--------------------------------------------|
| POST  | /categorias         | Criação de nova categoria                  |
| PUT   | /produtos/{id}      | Atualização de produto existente           |
| DELETE| /produtos/{id}      | Exclusão de produto                        |
| GET   | /usuarios           | Busca/listagem de usuários                 |
| GET   | /produtos           | Consulta de produtos                       |
| GET   | /categorias         | Verificação das categorias disponíveis     |

---

## 📂 Estrutura do Repositório

portfolio-api-educacional-insomnia/
├── README.md                 # Este documento
├── insomnia-export.json      # Exportação dos testes realizados no Insomnia
├── prints/                   # Evidências dos testes com prints
│   ├── post_categoria_sucesso.png
│   ├── put_produto_edicao.png
│   ├── delete_produto_ok.png
│   ├── get_usuarios.png
│   └── get_categorias.png


---

## 🧪 Como executar os testes

1. Clone este repositório ou baixe os arquivos.
2. Abra o Insomnia e importe o arquivo insomnia-export.json.
3. Execute os testes manualmente nos endpoints.
4. Verifique as evidências na pasta prints/.

---

## 🧾 Notas

- Os testes foram realizados manualmente com a API 100% funcional e pública.
- Todos os status de resposta foram verificados (200, 201, 400...).
- A API foi testada em diferentes cenários: sucesso, erro, e alteração de dados.

---

## 👩‍💻 Autor

*Alane*  
Estudante de QA Manual e Automação  
📍 Lisboa – Portugal

Criação do README.md com a descrição do projeto.
