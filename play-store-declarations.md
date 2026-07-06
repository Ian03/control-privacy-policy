# Declaracoes Para Google Play Console

Use este arquivo como base para preencher o Play Console.

## Conteudo Do App

- Contem anuncios: Nao.
- Publico-alvo recomendado: 18 anos ou mais.
- App de noticias: Nao.
- App governamental: Nao.
- App de saude: Nao.
- App financeiro: Nao.
- Jogo/apostas/dinheiro real: Nao.
- Conteudo gerado por usuarios: Nao.

## Permissoes

- Camera: anexar fotos aos registros de ponto.
- Fotos/imagens: selecionar imagens para anexos.
- Notificacoes: enviar lembretes locais de registro de ponto.
- Biometria: permitir desbloqueio local opcional.

O app nao usa SMS, Call Log, localizacao, microfone, acessibilidade, VPN, instalacao de pacotes ou permissao de overlay.

## Seguranca Dos Dados

O app armazena dados localmente no dispositivo. Nao ha envio automatico para servidores do desenvolvedor.

Dados tratados:

- Informacoes pessoais: nome e e-mail, usados para cadastro local.
- Credenciais: senha protegida por hash e dados de recuperacao protegidos por criptografia local.
- Fotos/imagens: anexos escolhidos pelo usuario para registros de ponto.
- Arquivos/documentos: backup criptografado e exportacao CSV quando acionados pelo usuario.
- Dados de atividade no app: registros de ponto, horarios, pausas, banco de horas e configuracoes de jornada.

Compartilhamento:

- O app nao compartilha dados automaticamente com terceiros.
- O usuario pode compartilhar manualmente backups, CSVs ou anexos usando o sistema de compartilhamento do dispositivo.

Exclusao:

- O usuario pode excluir registros, anexos e conta pelo app.
- Desinstalar o app ou limpar os dados do aplicativo tambem remove os dados locais.

## Criptografia E Leis De Exportacao Dos EUA

O app usa criptografia para protecao de dados locais:

- AES via crypto-js para dados sensiveis e backups.
- SecureStore para manter a chave local quando disponivel.
- SHA-256/hash para protecao da senha.

Declaracao sugerida:

"O aplicativo usa criptografia padrao apenas para proteger dados locais do usuario e backups exportados manualmente. A criptografia nao e a funcionalidade principal do produto, nao e destinada a uso militar, nao implementa VPN, comunicacao secreta, anonimato de rede, criptomoeda, assinatura digital de terceiros ou ferramenta de seguranca ofensiva."

Se o Play Console perguntar se o app usa criptografia, a resposta tecnica e: Sim.
