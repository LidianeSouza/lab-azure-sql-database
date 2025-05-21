# 💡 Dicas e Aprendizados — Laboratório Azure SQL

Este arquivo reúne minhas observações pessoais, aprendizados práticos e pequenas dicas que fizeram diferença durante a configuração de uma instância de banco de dados SQL na plataforma Microsoft Azure.

---

## ✅ Dicas práticas

- **Crie um Grupo de Recursos exclusivo** para o laboratório. Facilita o gerenciamento e permite excluir tudo de uma vez ao finalizar os testes.
- **Escolha a camada de serviço adequada**: para estudos e validação, a opção **Básica** é suficiente e mais econômica.
- **Guarde com segurança o login e a senha** do SQL Server. O Azure não exibe essas informações novamente após a criação.
- Sempre revise o que está sendo criado antes de clicar em "Criar" para evitar erros e cobranças inesperadas.

---

## 🧠 O que eu aprendi

- Como **criar uma instância de SQL Database** no Azure do zero, com todos os recursos relacionados.
- Diferença entre **servidor e banco de dados**: o servidor é o “container” que hospeda múltiplos bancos.
- A importância de uma documentação simples e visual — **prints e anotações ajudam muito na revisão posterior**.
- Que a documentação oficial ajuda, mas ter um **passo a passo direto e descomplicado** faz muita diferença
- Configuração em nuvem pode parecer complexa no início, mas é **muito mais acessível com prática e organização**.
- Anotar e registrar com prints o processo, ajuda tanto a mim quanto a outras pessoas a repetir o passo a passo futuramente.

---

### 📌 Dica Importante

> ✅ **Após finalizar o laboratório, exclua o grupo de recursos que você criou.**  
> Isso garante que você **não seja cobrado** por recursos ativos na sua conta Azure, mesmo se não estiver usando.

**Como fazer:**

1. Acesse o [Portal do Azure](https://portal.azure.com/)
2. Vá em **Grupos de Recursos**
3. Selecione o grupo criado (ex: `lab-sql-database_group`)
4. Clique em **Excluir grupo de recursos**
5. Digite o nome do grupo para confirmar

---

## 🤖 Apoio com Inteligência Artificial

Usei o **ChatGPT** como apoio durante o laboratório. Ele me ajudou a:

- Revisar comandos e explicações
- Criar este arquivo README.md
- Organizar o guia de dicas
- Tirar dúvidas rápidas sobre o Azure

Se estiver travado, vale a pena usar ferramentas de IA como apoio.

---

## 👨‍💻 Sobre mim

Este laboratório é parte dos meus estudos práticos sobre computação em nuvem. Gosto de aprender de forma aplicada e compartilhar o que funciona. Se este conteúdo te ajudou, fico feliz!

---

## 🔗 Links úteis

- [Portal Microsoft Azure](https://portal.azure.com/)
- [Documentação Oficial do Azure SQL Database](https://learn.microsoft.com/pt-br/azure/azure-sql/)
- [Microsoft Learn – Treinamentos Gratuitos](https://learn.microsoft.com/pt-br/training/)
- [ChatGPT da OpenAI](https://chat.openai.com/)
