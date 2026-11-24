# Política de Privacidade

Esta política explica como o **It Is Done** (o "App"), operado pela **Ring** (empresa individual representada por Yuseung Jang, "nós"), trata as suas informações.

Data de vigência: **2026-11-25** (versão anterior: 2026-11-20)

## 1. Resumo

- O App **não tem cadastro nem login.** Não coletamos seu nome, e-mail, número de telefone, localização, contatos ou fotos.
- Sua afirmação, seu nome, sua cena, o áudio da sua cena e seus registros diários ficam **armazenados no seu iPhone.** Não mantemos cópia em nenhum servidor. Os rascunhos da cena são escritos no próprio aparelho pelo modelo on-device da Apple (ou por modelos de texto incluídos no App), então suas palavras não saem do aparelho para isso. (Se o Backup do iCloud estiver ativado, esses dados entram no seu backup da Apple.)
- Os dados só saem do seu aparelho em dois casos, e apenas quando você escolhe:
  1. **Sua cena na voz de um narrador.** Se você tocar em **Enviar e ouvir**, o texto da sua cena passa pelo nosso servidor intermediário e chega à Typecast, um serviço de síntese de voz operado pela Neosapience. A partir daqui, "texto da cena" significa a cena e a afirmação que você escreveu. Se você tocar em **Só ver o texto**, nada é enviado, e sua cena e sua afirmação aparecem como texto na tela.
  2. **Backups que você exporta.** Em **Ajustes > Exportar / importar backup**, a exportação cria um único arquivo com sua cena, seus registros e o áudio, e a planilha de compartilhamento o envia para onde você escolher (Arquivos, AirDrop, Mail etc.). Nós nunca recebemos esse arquivo.
- Não usamos SDKs de publicidade nem a Transparência no Rastreamento de Apps (App Tracking Transparency), e não rastreamos você em apps ou sites de outras empresas.
- **Dados de uso anônimos e relatórios de erro** só são enviados **se você tocar em Permitir** no App. Se você recusar, todos os recursos e compras funcionam exatamente do mesmo jeito.
- Os dados de uso anônimos nunca incluem o que você digita nem o conteúdo das suas respostas iniciais. Alguns eventos trazem apenas um valor sim/não (por exemplo, se uma palavra de exemplo em cinza acabou entrando na sua resposta) ou uma faixa de tamanho (por exemplo, o tamanho de uma cena reescrita).

## 2. O que tratamos e por quê

| Categoria | Dados | Finalidade | Quando |
|---|---|---|---|
| Dados de uso anônimos | Um ID anônimo aleatório; um conjunto fixo de eventos (como o avanço nas etapas iniciais e a visualização da tela de compra) e seus valores (como número da etapa, valores sim/não, faixas de tamanho, produto comprado, preço e moeda); versão do app; tipo de aparelho e versão do sistema; idioma; país/cidade aproximados a partir do endereço IP | Descobrir onde as pessoas travam e melhorar o App | **Só com o seu consentimento** |
| Relatórios de erro | Nome e mensagem do erro (só o nome, se a mensagem for longa ou puder conter o que você digitou), local no código, versão do app e do sistema | Encontrar e corrigir travamentos e bugs | **Só com o seu consentimento** |
| Status de compra | ID anônimo de comprador; histórico de compras e assinaturas (produto, período, teste, status de renovação/cancelamento); país da loja | Liberar o que você comprou e restaurar compras | Quando você compra ou restaura (independentemente da chave de consentimento) |
| E-mail de suporte | Seu endereço de e-mail e sua mensagem, além da versão e build do app, versão do iOS, modelo do aparelho e idioma adicionados ao final do e-mail | Responder à sua mensagem | Quando você nos escreve em Ajustes > Fale conosco |
| Voz da cena | O texto da sua cena (escrito por você), o idioma, um ID aleatório do aparelho usado para o limite diário, seu endereço IP | Transformar sua cena em um arquivo de áudio salvo no seu aparelho | **Só se você permitir** no App, quando a cena é criada pela primeira vez ou muda |

- Os dados de pagamento (como números de cartão) são tratados pela Apple. Nós nunca os recebemos.
- O arquivo de backup é criado no seu aparelho e só vai para onde você o enviar, então não o tratamos. Ele contém suas próprias palavras e seu áudio; guarde-o como guardaria um documento pessoal.
- Não tentamos identificar você pessoalmente a partir desses dados.

## 3. Prestadores de serviço e transferência internacional

Usamos os prestadores de serviço abaixo. Cada um protege seus dados conforme a própria política de privacidade e os próprios termos contratuais (como um acordo de tratamento de dados).

| Destinatário | Finalidade | Dados | Local · momento · forma | Retenção |
|---|---|---|---|---|
| PostHog, Inc. | Armazenar e analisar dados de uso anônimos e erros | Dados de uso e relatórios de erro (seção 2) | Estados Unidos · enquanto você usa o App · pela internet, com criptografia | Seção 4 |
| RevenueCat, Inc. | Verificar e restaurar o status de compra | Status de compra (seção 2) | Estados Unidos · quando você compra ou restaura · pela internet, com criptografia | Seção 4 |
| Apple Inc. | Pagamentos, distribuição do app, pedido de avaliação | Dados de pagamento e assinatura (vinculados à sua Conta Apple) | Estados Unidos e outros países · quando você paga · sistema de pagamento da Apple | Conforme a política da Apple |
| Google LLC (Gmail) | Receber e-mails de suporte | E-mail de suporte (seção 2) | Estados Unidos e outros países · quando você nos escreve · e-mail | Seção 4 |
| Neosapience, Inc. (Typecast) | Sintetizar voz a partir do texto da sua cena | Texto da cena, idioma | República da Coreia e outros países · quando a voz de uma cena é criada · pela internet, com criptografia | Conforme a política da Typecast |
| Cloudflare, Inc. | Servidor intermediário entre o App e a Typecast (operado por nós), limite diário | Texto da cena (repassado, não armazenado); hashes unidirecionais do ID aleatório do aparelho e do IP com a contagem do dia | Estados Unidos e outros países · quando a voz de uma cena é criada · pela internet, com criptografia | Contagens: 2 dias |

- Políticas desses prestadores: PostHog <https://posthog.com/privacy>, RevenueCat <https://www.revenuecat.com/privacy>, Apple <https://www.apple.com/legal/privacy/>, Google <https://policies.google.com/privacy>, Typecast <https://typecast.ai>, Cloudflare <https://www.cloudflare.com/privacypolicy/>
- Nosso servidor intermediário não registra nem armazena o texto da sua cena. O arquivo de áudio que ele devolve fica salvo apenas no seu iPhone.
- Para que esses dados não saiam do seu aparelho, desative em Ajustes a chave de dados de uso e a chave de voz. O status de compra é necessário para os recursos pagos.

## 4. Retenção e exclusão

- Dados de uso anônimos e relatórios de erro: mantidos por **1 ano** e depois excluídos automaticamente no PostHog.
- Status de compra: mantido enquanto sua compra ou assinatura estiver ativa e pelo prazo exigido por lei (por exemplo, 5 anos para registros de pagamento segundo a lei coreana de proteção ao consumidor).
- E-mails de suporte: mantidos por **1 ano** após a nossa resposta e depois excluídos.
- Texto da cena: não é mantido por nós nem pelo servidor intermediário. As contagens diárias (valores em hash) são excluídas automaticamente após **2 dias**.
- Os dados no seu aparelho (afirmação, cena, registros, arquivos de áudio, escolhas de consentimento) são apagados quando você exclui o App. Um arquivo de backup que você exportou continua onde você o salvou até que você o apague.
- Forma de exclusão: arquivos eletrônicos são apagados de modo que não possam ser recuperados. Não mantemos registros em papel.

## 5. Retirada do consentimento e seus direitos

- **Dados de uso:** no App, vá em **Ajustes > Enviar dados de uso anônimos** e desative. O envio para na hora. Ative de novo para retomar. Tudo, inclusive as compras, funciona igual nos dois casos.
- **Voz da cena:** no App, vá em **Ajustes > Voz > Criar com voz de narrador** e desative. A partir daí, o texto da sua cena não é enviado e a cena aparece como texto. Tudo, inclusive as compras, funciona igual.
- Você pode pedir acesso, correção, exclusão ou restrição do tratamento dos seus dados por e-mail (seção 7). Responderemos sem demora (em até 10 dias). Como os dados ficam guardados apenas sob um ID anônimo aleatório, talvez não consigamos encontrar dados que não possamos vincular a você. Excluir o App remove o ID anônimo do seu aparelho, então os dados futuros não ficam vinculados aos anteriores.
- O cancelamento e o reembolso de assinaturas são feitos pela Apple (Ajustes do iPhone > Conta Apple > Assinaturas, ou Ajustes > Gerenciar assinatura no App; reembolsos em <https://reportaproblem.apple.com>).

## 6. Cookies, crianças, segurança

- O App não usa cookies. Os dados de uso são agrupados por um ID aleatório criado no seu aparelho e não são enviados se você recusar.
- O App não é direcionado a menores de 14 anos (ou da idade mínima no seu país), e não coletamos intencionalmente dados deles.
- Segurança: transmissão criptografada (HTTPS), acesso com privilégio mínimo e autenticação de dois fatores nas contas dos prestadores, e coleta apenas do que é necessário.

## 7. Contato

- Responsável pela privacidade: Yuseung Jang, representante
- E-mail: <tomokijang30@gmail.com>
- Operadora: Ring (empresa individual) · Representante: Yuseung Jang

## 8. Alterações

Se alterarmos esta política, publicaremos a nova versão nesta página com a data de vigência. Em mudanças importantes, como a coleta de novos tipos de dados, avisaremos com pelo menos 7 dias de antecedência.
