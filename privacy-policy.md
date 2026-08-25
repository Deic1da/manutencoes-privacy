# Política de Privacidade — Lembrete de Manutenção

**Última atualização:** 26 de agosto de 2026
**Desenvolvedor:** Melqui · **Pacote:** com.melqui.manutencoes

O aplicativo **Lembrete de Manutenção** respeita a sua privacidade. Esta Política descreve quais dados são tratados e por quê ao utilizar o app. A versão navegável está em https://deic1da.github.io/manutencoes-privacy/

## 1. Dados no seu aparelho
As manutenções, categorias, datas, intervalos e o histórico de conclusões que você cadastra são salvos localmente no aparelho (Room/SQLite). Sem login, nada disso sai do dispositivo.

## 2. Backup na nuvem (opcional)
Se você optar por entrar com sua Conta do Google, o app ativa o backup na nuvem. Nesse caso são tratados:
- **E-mail, nome e ID da Conta do Google** (Firebase Authentication), para identificar sua conta;
- **Seus dados de manutenção** (manutenções, categorias, histórico e preferências), guardados no Google Cloud Firestore vinculados à sua conta, para sincronizar entre aparelhos.

O login é totalmente opcional. Sem ele, o app funciona apenas com dados locais.

## 3. Comprovantes de manutenção (opcional)

Ao marcar uma manutenção como feita, você pode anexar fotos ou arquivos como comprovante. A foto
pode vir da galeria ou ser tirada na hora pelo app de câmera do aparelho.

- O arquivo é salvo **no seu aparelho**, no armazenamento privado do app;
- Se você estiver com a Conta do Google conectada e autorizar o acesso, uma cópia é enviada para uma
  **pasta oculta do seu próprio Google Drive** (área reservada ao app), para que os comprovantes
  voltem se você reinstalar ou trocar de aparelho;
- No Firestore ficam apenas os **dados de referência** do anexo (nome do arquivo, tipo e o
  identificador do arquivo no seu Drive) — **nunca o conteúdo** da foto ou do documento.

Os arquivos ficam no seu aparelho e na sua conta do Google. Eles não passam por nenhum servidor do
desenvolvedor, e o desenvolvedor não tem acesso a eles. Anexar comprovante é opcional.

## 4. Relatórios de falha e métricas de uso
O app usa o Firebase Crashlytics, que coleta registros de falhas, diagnóstico e identificadores do dispositivo quando ocorre um erro.

Para entender como o app é utilizado, também usamos o Firebase Analytics, que coleta interações no app de forma agregada — por exemplo, quando um lembrete é enviado ou aberto. Esses dados são estatísticos e não identificam você pessoalmente.

## 5. Publicidade
O app exibe anúncios do Google AdMob, que pode coletar o ID de publicidade e dados do aparelho. Em regiões que exigem, é exibido um formulário de consentimento (Google User Messaging Platform) antes de carregar anúncios, e a escolha pode ser revista em Configurações → Privacidade dos anúncios.

## 6. Compartilhamento de dados
Não vendemos dados pessoais. Os serviços do Google (Authentication, Firestore, Crashlytics e Analytics) atuam como processadores em nosso nome. O ID de publicidade é tratado pelo Google AdMob. Consulte: https://policies.google.com/privacy

## 7. Permissões
- **Notificações** — enviar os lembretes;
- **Alarme exato** — disparar o lembrete no horário programado;
- **Executar ao iniciar / ignorar otimização de bateria** — manter os lembretes confiáveis com o app fechado;
- **Câmera** — apenas se você escolher tirar a foto do comprovante na hora;
- **Google Drive (pasta do app)** — se autorizado, guardar os comprovantes na sua conta. O app
  enxerga somente a própria pasta oculta, não o resto do seu Drive;
- **Internet** — backup na nuvem e anúncios.

## 8. Retenção e exclusão de dados
Você pode excluir sua conta e todos os dados a qualquer momento. Passo a passo em https://deic1da.github.io/manutencoes-privacy/data-deletion.html

## 9. Público
Este aplicativo não é direcionado a crianças.

## 10. Segurança
Os dados trafegam de forma criptografada (HTTPS). Nenhuma tecnologia é 100% segura.

## 11. Alterações
Esta Política pode ser atualizada a qualquer momento.

## 12. Contato
📧 melquenerd@gmail.com
