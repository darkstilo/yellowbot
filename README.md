# CHANGELOG YellOwBot [BETA]

## Comando Cadastrar Usuário:

**Funcionalidades**

> STATUS [EM ANDAMENTO]

- [x] Verificar se o `id` já possui algum cadastro no banco de dados; [3]

- [ ] Verificar se o `usuário` informado no comando /cadastrar `[usuário]` já existe no banco de dados; [2]

- [ ] Não permitir cadastrar com usuário tendo caracteres especiais, somente letras e números; [4]

- [x] Enviar no privado `mensagem` de retorno com detalhes do cadastro. Contendo os seguintes detalhes:
```
💬 Grupo:
🕐 Validade:

🖥 IP:
👤 Usuário: 
🔑 Senha:

> Acoplar o botão de deletar o cadastro a qualquer momento, por opção do usuário.
```

- [x] Enviar no grupo `mensagens` de retorno:

**Mensagens de Retorno**
> `Cadastro concluido com sucesso. Inicie uma conversa comigo para que eu possa lhe enviar seus dados de cadastro.`

> `Desculpe, mas o usuário informado já existe.`

> `Você já possui um cadastro em nosso sistema.`

> `Somente letras e números.`

- [x] Adicionar botão na mensagem de retorno do grupo, para que o usuário possa iniciar uma conversa com o bot.

> Permitir o uso do comando apenas em grupo.

## GRUPOS E ADMINISTRADORES > SERVIDORES ##

- [ ] Criar comando para adicionar IDs de grupos que possam usar as funcionalidades do BOT;

- [ ] Criar comando para adicionar IDs de usuários que podem usar o comando para adicionar o Servidor

**Mensagens de Retorno**

> `Usuário cadastrado com sucesso.` [MASTER]
> `Desculpe, mas você não tem previlegios para usar este comando.`[MEMBROS NÃO CADASTRADOS]
