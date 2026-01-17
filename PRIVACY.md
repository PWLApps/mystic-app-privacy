# Política de Privacidade - Mystic App

**Última atualização:** 17 de janeiro de 2026

**Desenvolvedor:** PWL Apps
**Email de contato:** contact.pwlapps@gmail.com
**Aplicativo:** Mystic - Leitura de Tarô com IA

---

## 1. Introdução

Esta Política de Privacidade descreve como o Mystic App ("nós", "nosso" ou "aplicativo") coleta, usa, armazena e protege suas informações pessoais quando você utiliza nosso aplicativo de leitura de tarô.

Ao usar o Mystic App, você concorda com a coleta e uso de informações de acordo com esta política. Recomendamos que você leia esta política com atenção antes de usar o aplicativo.

**Idade mínima:** Este aplicativo é destinado a usuários com 13 anos ou mais. Não coletamos intencionalmente informações de crianças menores de 13 anos.

---

## 2. Informações que Coletamos

### 2.1 Informações Fornecidas Voluntariamente

Quando você usa o Mystic App, você pode fornecer as seguintes informações:

- **Nome de usuário:** Nome que você escolhe fornecer ao fazer uma leitura (opcional)
- **Perguntas/Questões:** Texto que você escreve ao solicitar uma leitura de tarô
- **Leituras salvas:** Histórico de leituras que você escolheu salvar localmente

### 2.2 Informações Coletadas Automaticamente

- **Identificador único de usuário (UUID):** Um código único gerado automaticamente no primeiro uso do app, armazenado localmente em seu dispositivo. Este UUID não é vinculado à sua identidade pessoal.
- **Dados de uso do aplicativo:** Informações sobre como você interage com o app (cartas selecionadas, número de leituras realizadas)
- **Dados técnicos:** Informações sobre seu dispositivo, versão do sistema operacional, versão do aplicativo

### 2.3 Informações de Terceiros

#### Google AdMob (Anúncios Recompensados)
- ID de publicidade do dispositivo (IDFA/AAID)
- Endereço IP
- Dados de interação com anúncios
- Informações do dispositivo e navegador
- Dados de geolocalização aproximada

#### Supabase (Backend e Armazenamento)
- Endereço IP (logs de servidor)
- Dados de requisições HTTP
- Informações de validação de recompensas

---

## 3. Como Usamos Suas Informações

### 3.1 Finalidades Principais

Usamos suas informações para:

- **Gerar leituras de tarô personalizadas:** Seu nome e pergunta são enviados ao OpenAI para gerar interpretações personalizadas
- **Validar recompensas de anúncios:** UUID e dados da leitura são usados para verificar que você assistiu a um anúncio antes de gerar uma leitura
- **Armazenar leituras:** Suas leituras são salvas localmente no dispositivo e temporariamente em nosso servidor durante o processo de validação
- **Exibir anúncios relevantes:** O Google AdMob usa dados para personalizar anúncios mostrados a você
- **Melhorar o aplicativo:** Analisamos dados agregados e anônimos para melhorar a experiência do usuário

### 3.2 Base Legal (LGPD/GDPR)

- **Consentimento:** Ao usar o aplicativo e aceitar esta política, você consente com o processamento de seus dados
- **Execução de contrato:** Processar seus dados é necessário para fornecer o serviço solicitado (leituras de tarô)
- **Interesses legítimos:** Prevenir fraudes e melhorar nossos serviços

---

## 4. Compartilhamento de Informações

### 4.1 Serviços de Terceiros

Compartilhamos suas informações com os seguintes prestadores de serviços:

#### OpenAI (Geração de Leituras com IA)
- **Dados compartilhados:** Nome de usuário, pergunta/questão, cartas selecionadas
- **Finalidade:** Gerar interpretações personalizadas de tarô usando inteligência artificial
- **Retenção:** OpenAI retém dados conforme sua própria política de privacidade
- **Política:** [https://openai.com/policies/privacy-policy](https://openai.com/policies/privacy-policy)

#### Supabase (Backend e Banco de Dados)
- **Dados compartilhados:** UUID, nome de usuário, pergunta, ID da leitura, dados de validação de recompensas
- **Finalidade:** Validar que anúncios foram assistidos antes de processar leituras
- **Localização dos dados:** Servidores nos Estados Unidos (West US - Oregon)
- **Retenção:** Dados de validação são mantidos por 5 minutos e depois expiram automaticamente
- **Política:** [https://supabase.com/privacy](https://supabase.com/privacy)

#### Google AdMob (Anúncios Recompensados)
- **Dados compartilhados:** ID de publicidade, informações do dispositivo, dados de interação
- **Finalidade:** Exibir anúncios recompensados e validar visualizações
- **Política:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Personalização de anúncios:** Você pode desativar anúncios personalizados nas configurações do seu dispositivo

### 4.2 Transferência Internacional de Dados

Seus dados podem ser transferidos e processados em servidores localizados fora do Brasil, incluindo:
- Estados Unidos (Supabase, OpenAI, Google)

Garantimos que essas transferências são realizadas com salvaguardas adequadas, incluindo cláusulas contratuais padrão e conformidade com GDPR.

### 4.3 Situações Legais

Podemos divulgar suas informações se:
- Exigido por lei ou processo legal
- Para proteger nossos direitos, propriedade ou segurança
- Para prevenir fraudes ou atividades ilegais

---

## 5. Armazenamento e Segurança de Dados

### 5.1 Armazenamento Local

- **Leituras salvas:** Armazenadas localmente no seu dispositivo usando SharedPreferences (criptografado pelo sistema operacional)
- **UUID:** Armazenado localmente no seu dispositivo
- **Controle:** Você pode excluir leituras salvas a qualquer momento dentro do app ou desinstalando o aplicativo

### 5.2 Armazenamento em Servidor

- **Dados de validação:** Armazenados temporariamente no Supabase por até 5 minutos para validar recompensas
- **Segurança:** Dados transmitidos via HTTPS/TLS, banco de dados com Row Level Security (RLS)

### 5.3 Retenção de Dados

| Tipo de Dado | Período de Retenção | Localização |
|--------------|---------------------|-------------|
| Leituras salvas | Até você excluir ou desinstalar o app | Dispositivo local |
| Dados de validação de recompensas | 5 minutos | Servidor Supabase |
| Logs de servidor | 30 dias | Servidor Supabase |
| Dados do OpenAI | Conforme política da OpenAI | Servidores OpenAI |
| Dados do AdMob | Conforme política do Google | Servidores Google |

---

## 6. Seus Direitos (LGPD e GDPR)

Você tem os seguintes direitos em relação aos seus dados pessoais:

### 6.1 Direitos Garantidos

- **Acesso:** Solicitar cópias dos seus dados pessoais
- **Retificação:** Corrigir dados imprecisos ou incompletos
- **Exclusão:** Solicitar a exclusão dos seus dados ("direito ao esquecimento")
- **Portabilidade:** Receber seus dados em formato estruturado e legível por máquina
- **Oposição:** Opor-se ao processamento de seus dados
- **Revogação de consentimento:** Retirar seu consentimento a qualquer momento
- **Confirmação de tratamento:** Confirmar se seus dados estão sendo processados
- **Anonimização/bloqueio:** Solicitar anonimização ou bloqueio de dados

### 6.2 Como Exercer Seus Direitos

Para exercer qualquer um desses direitos, envie um email para:
**contact.pwlapps@gmail.com**

Responderemos sua solicitação em até 15 dias úteis (conforme LGPD).

### 6.3 Desativar Anúncios Personalizados

**Android:**
1. Configurações > Google > Anúncios
2. Ative "Desativar personalização de anúncios"

**iOS:**
1. Configurações > Privacidade > Publicidade
2. Ative "Limitar rastreamento de anúncios"

---

## 7. Cookies e Tecnologias de Rastreamento

### 7.1 Cookies de Terceiros

O Google AdMob pode usar cookies e tecnologias similares (web beacons, pixels) para:
- Exibir anúncios relevantes
- Medir eficácia de anúncios
- Detectar fraudes

Você pode gerenciar cookies nas configurações do seu navegador ou dispositivo.

### 7.2 Identificadores de Dispositivo

- **Android:** Google Advertising ID (GAID)
- **iOS:** Identifier for Advertisers (IDFA)

Esses identificadores podem ser redefinidos nas configurações de privacidade do seu dispositivo.

---

## 8. Analytics e Monitoramento (Futuro)

Atualmente, usamos apenas o dashboard administrativo do Supabase para monitorar o funcionamento técnico do aplicativo (logs de servidor, erros).

**No futuro, poderemos adicionar:**
- Firebase Analytics ou similar para entender como os usuários usam o app
- Ferramentas de monitoramento de performance

Se adicionarmos serviços de analytics, atualizaremos esta política e notificaremos os usuários.

---

## 9. Links Externos

O aplicativo pode conter links para sites ou serviços de terceiros (como políticas de privacidade do Google/OpenAI). Não somos responsáveis pelas práticas de privacidade desses sites. Recomendamos que você leia as políticas de privacidade de qualquer site que visitar.

---

## 10. Alterações nesta Política

Podemos atualizar esta Política de Privacidade periodicamente. Notificaremos você sobre mudanças significativas:
- Publicando a nova política dentro do aplicativo
- Enviando uma notificação no app
- Atualizando a data "Última atualização" no topo deste documento

Recomendamos que você revise esta política regularmente. O uso continuado do aplicativo após alterações constitui aceitação da política atualizada.

---

## 11. Segurança de Dados

Implementamos medidas técnicas e organizacionais para proteger seus dados:

### 11.1 Medidas Técnicas
- **Criptografia em trânsito:** HTTPS/TLS para todas as comunicações
- **Criptografia em repouso:** Dados do dispositivo protegidos pelo sistema operacional
- **Autenticação de servidor:** Validação de certificados SSL
- **Server-Side Verification:** Validação dupla de recompensas (Google + Supabase)

### 11.2 Medidas Organizacionais
- Acesso limitado aos dados apenas para pessoal autorizado
- Monitoramento de logs de segurança
- Revisões regulares de segurança

### 11.3 Limitações
Nenhum método de transmissão pela Internet ou armazenamento eletrônico é 100% seguro. Embora nos esforcemos para proteger seus dados, não podemos garantir segurança absoluta.

---

## 12. Dados de Menores de Idade

Este aplicativo **não é direcionado a crianças menores de 13 anos**.

Não coletamos intencionalmente informações pessoais de menores de 13 anos. Se você é pai/mãe ou responsável e acredita que seu filho forneceu dados pessoais, entre em contato conosco em **contact.pwlapps@gmail.com** para que possamos tomar as medidas apropriadas.

**Usuários entre 13-18 anos:** Recomendamos que menores de 18 anos obtenham permissão dos pais ou responsáveis antes de usar o aplicativo.

---

## 13. Jurisdição e Lei Aplicável

### 13.1 Usuários no Brasil
Esta política é regida pela Lei Geral de Proteção de Dados (LGPD - Lei 13.709/2018).

### 13.2 Usuários na União Europeia
Para usuários na UE, esta política também está em conformidade com o Regulamento Geral de Proteção de Dados (GDPR).

### 13.3 Reclamações
Você tem o direito de registrar uma reclamação junto à:
- **Brasil:** Autoridade Nacional de Proteção de Dados (ANPD) - [https://www.gov.br/anpd](https://www.gov.br/anpd)
- **UE:** Autoridade de proteção de dados do seu país

---

## 14. Contato

Se você tiver dúvidas, preocupações ou solicitações relacionadas a esta Política de Privacidade ou ao tratamento de seus dados pessoais, entre em contato:

**Email:** contact.pwlapps@gmail.com
**Desenvolvedor:** PWL Apps
**Aplicativo:** Mystic - Leitura de Tarô com IA

Responderemos suas solicitações em até 15 dias úteis.

---

## 15. Resumo Rápido (TL;DR)

**O que coletamos:**
- Nome (opcional), perguntas, leituras salvas
- UUID único (não identificável)
- Dados do AdMob (ID de publicidade, IP)

**Como usamos:**
- Gerar leituras de tarô com IA (OpenAI)
- Validar que você assistiu anúncios
- Exibir anúncios relevantes
- Melhorar o aplicativo

**Compartilhamento:**
- OpenAI (para gerar leituras)
- Supabase (validação temporária - 5 min)
- Google AdMob (anúncios)

**Seus direitos:**
- Acessar, corrigir ou excluir seus dados
- Revogar consentimento a qualquer momento
- Solicitar portabilidade de dados

**Contato:** contact.pwlapps@gmail.com

---

**Versão:** 1.0
**Data de vigência:** 17 de janeiro de 2026

© 2026 PWL Apps. Todos os direitos reservados.
