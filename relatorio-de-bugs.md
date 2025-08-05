# Relatório de Bugs - Projeto de Testes Manuais

## Bug 1 - Validação de e-mail inválido (CT02)

- **Descrição:** O sistema aceitou um e-mail sem o caractere "@" e permitiu o cadastro.  
- **Passos para reproduzir:**  
  1. Acessar a página de cadastro  
  2. Preencher o campo e-mail com "gabigabi.com" (sem "@")  
  3. Clicar em "Cadastrar"  
- **Resultado esperado:** Exibição de mensagem de erro: "E-mail inválido"  
- **Resultado real:** Cadastro permitido mesmo com e-mail inválido  
- **Severidade:** Média  
- **Status:** Aberto

---

## Bug 2 - Senha com menos de 6 caracteres aceita (CT04)

- **Descrição:** O sistema permitiu cadastrar uma senha com apenas 4 caracteres.  
- **Passos para reproduzir:**  
  1. Acessar a página de cadastro  
  2. Preencher o campo senha com "1234"  
  3. Clicar em "Cadastrar"  
- **Resultado esperado:** Exibição de alerta: "Senha muito curta"  
- **Resultado real:** Cadastro permitido com senha fraca  
- **Severidade:** Alta  
- **Status:** Aberto
