## 📦 Instalação

⬇️ Link para Download: 

- https://git-scm.com/
---
⬇️ Via terminal Linux baseado em Debian/Ubuntu:
```
apt-get install git
```

## ⚙️ Configuração de Usuário

⬛ Utilizando o bash: 

```bash
git config --global user.name <"nome do seu usuário">
```

```bash
git config --global user.email <"seu e-mail">
```

## ⚙️ Configuração de Chave SSH


chave SSH estabelece uma conexão segura e autenticada com repositórios Git remotos.

**Gere as chaves publicas e privadas SSH (pelo bash):**

```bash
ssh-keygen -t ed25519 -c <seu-email>
```
- confirme com uma senha
- no diretório informado no terminal, foi gerado duas chaves: uma pública e a outra privada 
- entre no diretório em questão e copie o conteúdo da chave pública id_ed25519.pub 

```bash
cat <caminho-das-chaves-geradas>/.ssh/id_ed25519.pub
```
- agora, com o conteúdo da chave copiada, insira no seu repositório remoto ([Github](https://github.com/settings/keys))
- caso ouver dúvidas, veja o [▶️Tutorial](https://www.youtube.com/watch?v=g5Pmwmirczo&t=1s&ab_channel=DIO)

| [🏠 home](../README.md) | [↩️ sumário](_sumario.md) |





