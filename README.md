# RustDesk — Suporte Connect

Acesso remoto do **suporte Connect**. Instale no computador que vai receber atendimento: o RustDesk já fica
configurado para o servidor de suporte da Connect, sem nenhum ajuste manual.

## Download

**[⬇ Baixar instalar-rustdesk-connect.bat (versão mais recente)](https://github.com/Marcelo-connect/rustdesk-connect/releases/latest/download/instalar-rustdesk-connect.bat)**

Windows 10 ou 11, 64 bits. Precisa de internet durante a instalação.

## Como instalar

1. Baixe o arquivo pelo link acima.
2. Dê dois cliques em `instalar-rustdesk-connect.bat`.
3. Se o Windows exibir um aviso de segurança ou do **SmartScreen**, clique em **Mais informações → Executar assim
   mesmo** (ou **Executar**).
4. Quando o Windows pedir permissão de administrador, clique em **Sim**.
5. Aguarde: o instalador baixa o RustDesk oficial, confere a integridade, instala e configura o servidor.
6. No fim aparece **"Informe este ID ao suporte Connect"** com um número. Passe esse número para o suporte.

O RustDesk inicia junto com o Windows. Para cada atendimento, o suporte vai pedir o **ID** e a **senha** que aparecem
na tela do RustDesk.

## O que o instalador faz

- Baixa o **RustDesk oficial** da release oficial ([github.com/rustdesk/rustdesk](https://github.com/rustdesk/rustdesk/releases))
  e só instala se o arquivo for idêntico ao publicado (sha256 conferido).
- Instala em modo silencioso e aponta para o servidor de suporte Connect.
- Se o RustDesk já estiver instalado, mantém a instalação e só aplica o servidor.

## Atualizar

Baixe o instalador pelo link acima e execute de novo.
