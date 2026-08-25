# Política de privacidade do Print3D Manager

**Última atualização: 25 de agosto de 2026**

_Esta é uma tradução da versão canónica em espanhol, [PRIVACY_POLICY.md](../../PRIVACY_POLICY.md). Em caso de divergência, prevalece a versão em espanhol._

Esta política explica que dados o Print3D Manager ("a app") trata, com que finalidade, com que base legal, durante quanto tempo são conservados, e que opções tens. Está escrita para descrever exatamente o que a app faz hoje, não funcionalidades futuras.

## 1. Quem trata os dados

O Print3D Manager é uma app desenvolvida de forma independente para a gestão de uma oficina de impressão 3D (custos, impressoras, materiais, projetos, clientes, orçamentos e faturas).

Contacto: **zhop3dlab@gmail.com**.

## 2. Princípio geral: a app é local por predefinição

Toda a informação que introduzes (impressoras, materiais, projetos, clientes, orçamentos, faturas, inventário) é guardada **no teu próprio dispositivo** por predefinição. Não precisas de criar uma conta nem de ter ligação à internet para usar a app com todas as suas funções principais.

Nenhum dado do teu negócio é enviado para os nossos servidores nem para terceiros, salvo se tiveres o plano Business e ativares voluntariamente a sincronização com a nuvem (ver secção 3), ou enquanto é apresentado um anúncio (ver secção 6).

## 3. Conta e sincronização com a nuvem (plano Business, opcional)

Se tiveres o plano Business e decidires criar uma conta (com email e palavra-passe, ou com a tua conta Google) para guardar também os teus dados na nuvem e usá-los em mais do que um dispositivo:

- **Dados da conta**: endereço de email e, se usares o Google, o nome e a imagem de perfil associados a essa conta Google.
- **Dados do teu negócio**: se ativares a sincronização, é guardada uma cópia dos teus projetos, clientes, impressoras, materiais, orçamentos e faturas numa base de dados na nuvem (Google Firebase/Firestore), associada apenas à tua conta e ao teu espaço de trabalho. Ninguém fora da tua conta pode aceder a estes dados.
- Podes deixar de usar a nuvem a qualquer momento e voltar a fazer com que a app funcione apenas localmente.
- Podes **eliminar a tua conta e todos os dados associados na nuvem** a qualquer momento a partir da própria app, em **Mais → Conta → Eliminar conta e dados**. Esta ação é permanente e imediata.

Usamos o Google Firebase (Authentication e Firestore) como fornecedor de infraestrutura para a conta e a nuvem. A Google atua como subcontratante destes dados de acordo com as suas próprias condições: <https://firebase.google.com/support/privacy>.

**Base legal**: tratamos estes dados porque é necessário para te prestar o serviço que contrataste (execução de um contrato/utilização do plano Business) e, no caso do email de contacto, com o teu consentimento ao criares a conta.

**Conservação**: enquanto mantiveres a tua conta ativa. Se a eliminares (Mais → Conta → Eliminar conta e dados), os dados na nuvem são apagados de imediato. Se nunca criares uma conta, não é gerado nenhum dado na nuvem.

**Transferências internacionais**: a infraestrutura do Google Firebase pode processar e armazenar dados em centros de dados fora do teu país, incluindo fora do Espaço Económico Europeu. A Google oferece garantias em conformidade com o RGPD (cláusulas contratuais-tipo) para estas transferências — mais detalhes na ligação anterior.

## 4. Se usares a app para gerir dados dos teus próprios clientes

Se guardares na app dados dos teus clientes (nome, morada, identificação fiscal, email...) para orçamentos e faturas, **és tu o responsável pelo tratamento desses dados** perante os teus próprios clientes — tal como se os tivesses numa folha de cálculo ou num programa de faturação. O Print3D Manager é apenas a ferramenta que usas para os guardar (e, se tiveres o plano Business com a sincronização ativada, o subcontratante na nuvem).

Isto significa que és tu quem deve garantir que tem uma base legal adequada para tratar os dados dos teus clientes (normalmente, a relação comercial/contratual com eles) e atender aos seus próprios pedidos de acesso, retificação ou eliminação caso te os façam diretamente.

## 5. Dados que nunca saem do teu dispositivo

- **Ficheiros G-code**: se usares o analisador de G-code, o ficheiro é lido e analisado inteiramente no teu dispositivo. O conteúdo do ficheiro nunca é carregado para a internet nem partilhado com ninguém; só tu vês os dados extraídos (tempo estimado, gramas, temperaturas).
- **Cópias de segurança locais**: exportar/importar os teus dados num ficheiro JSON (planos Pro e Business) é uma operação totalmente local — o ficheiro é guardado onde tu decidires (por exemplo, partilhando-o tu mesmo por email ou guardando-o no teu próprio armazenamento).
- **PDFs de orçamentos e faturas**: são gerados no teu dispositivo. Partilhá-los ou descarregá-los é uma ação explícita tua; a app não os envia para nenhum servidor nosso.

## 6. Publicidade

A app apresenta anúncios através do **Google AdMob** aos utilizadores do plano gratuito. O AdMob pode recolher identificadores de publicidade do teu dispositivo para apresentar anúncios (personalizados ou não, consoante as definições de privacidade do teu sistema operativo) e medir o seu desempenho. Este tratamento é realizado pela Google de acordo com a sua própria política de privacidade: <https://policies.google.com/privacy> e a sua política específica para o AdMob: <https://support.google.com/admob/answer/6128543>.

**Base legal**: consentimento (gerido através das definições de privacidade do teu dispositivo/da Google) e interesse legítimo em financiar a app gratuita através de publicidade.

Os utilizadores dos planos pagos (Pro e Business) não veem anúncios.

## 7. O que NÃO fazemos

- Não vendemos os teus dados a ninguém.
- Não acedemos ao conteúdo dos teus projetos, clientes ou faturas, salvo se tiveres o plano Business e ativares expressamente a sincronização na nuvem — e mesmo nesse caso não os revemos manualmente.
- Não usamos os teus dados de negócio para treinar modelos de inteligência artificial.
- Não pedimos permissões de câmara, contactos, localização nem microfone — a app não precisa delas e não as solicita.

## 8. Os teus direitos

Tens direito a aceder, retificar, eliminar, limitar o tratamento, opor-te e solicitar a portabilidade dos teus dados. Na prática, a partir da própria app podes:

- **Ver** quantos dados tens guardados localmente e na nuvem (Mais → Conta).
- **Descarregar** uma cópia dos teus dados num ficheiro JSON (planos Pro e Business, Mais → Dados).
- **Eliminar** a tua conta e todos os dados associados na nuvem a partir da própria app (Mais → Conta → Eliminar conta e dados).
- **Desinstalar a app** a qualquer momento, o que remove todos os dados guardados localmente no teu dispositivo.

Se precisares de ajuda com qualquer um destes direitos, ou tiveres dúvidas sobre esta política, contacta **zhop3dlab@gmail.com**.

Se considerares que o teu pedido não foi tratado corretamente, tens o direito de apresentar uma reclamação junto da autoridade de controlo de proteção de dados do teu país (em Espanha, a **Agencia Española de Protección de Datos**, <https://www.aepd.es>).

## 9. Menores de idade

A app não se dirige a menores de idade e não recolhemos conscientemente dados de menores.

## 10. Alterações a esta política

Se esta política mudar de forma relevante, a data no início do documento será atualizada. O uso continuado da app após uma alteração implica a aceitação da política atualizada.
