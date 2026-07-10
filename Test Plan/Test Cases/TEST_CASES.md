# Casos de Teste

## Login

| ID | Caso | Resultado Esperado |
|----|------|--------------------|
| TC001 | Login válido | Usuário entra no sistema |
| TC002 | Senha incorreta | Mensagem de erro |
| TC003 | Usuário inexistente | Mensagem de erro |
| TC004 | Campo usuário vazio | Campo obrigatório |
| TC005 | Campo senha vazio | Campo obrigatório |

---

## Produtos

| ID | Caso | Resultado Esperado |
|----|------|--------------------|
| TC006 | Visualizar produtos | Produtos aparecem |
| TC007 | Ordenar A-Z | Produtos ordenados |
| TC008 | Ordenar Z-A | Produtos ordenados |

---

## Carrinho

| ID | Caso | Resultado Esperado |
|----|------|--------------------|
| TC009 | Adicionar produto | Produto aparece no carrinho |
| TC010 | Remover produto | Produto removido |

---

## Checkout

| ID | Caso | Resultado Esperado |
|----|------|--------------------|
| TC011 | Comprar produto | Compra concluída |
| TC012 | CEP vazio | Mensagem de erro |

---

## Logout

| ID | Caso | Resultado Esperado |
|----|------|--------------------|
| TC013 | Fazer logout | Retorna para tela de login |