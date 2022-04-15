---
title: Notas de versão mais recentes
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação dos produtos e serviços para  [!DNL Experience Cloud] . Encontre ajuda e novos tutoriais sobre o [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: April 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: e6a44b87d3c4f39a6e0304d44213d866ae43aec4
workflow-type: tm+mt
source-wordcount: '6116'
ht-degree: 43%

---

# Notas de versão da Adobe Experience Cloud - Abril de 2022

![Banner](assets/experience-cloud-banner-3.png)

Como um criador de experiências, o seu caminho para o sucesso começa com a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home). Encontre uma vasta biblioteca de documentação de instruções, tutoriais autoguiados, vídeos de instruções e cursos para todos os níveis e funções, uma comunidade online de pares e uma porta de suporte de especialistas sempre que precisar.

Está pronto para começar? [Conclua esse teste de 5 minutos](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp).

>[!NOTE]
>
>Para receber uma notificação por email mensal sobre atualizações nessa página, assine a [Atualização Prioritária de Produto da Adobe](https://www.adobe.com/subscription/priority-product-update.html). Verifique com frequência para ficar por dentro do que está acontecendo na Experience League.

Última atualização: **15 de abril de 2022**

* [Eventos da [!DNL Experience League]](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud — componentes e administração da interface central](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Blueprints de experiência digital - tutoriais](#blueprints)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insights da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/experience-league.png) Eventos da [!DNL Experience League] {#events}

Os eventos da Experience League são um excelente local para aprender, interagir e obter respostas de especialistas sobre produtos da Adobe.

Atualizado **5 de abril de 2022**

| Evento | Tipo | Descrição |
| -----------|---------- | ----|
| [Adobe Summit 2022](https://business.adobe.com/summit/adobe-summit.html) | Sessões sob demanda | Aprenda com os executivos da Adobe, Ryan Reynolds, Rosalind Brewer, CEO, Walgreens Boots Alliance, Inc, John Donahoe, CEO, NIKE, Inc. e Gail J. McGovernn, CEO, American Red Cross, pois eles compartilham como as experiências dos clientes são a moeda de nossa economia digital.<br>Explorar [sessões sob demanda](https://business.adobe.com/summit/2022/sessions.html) de Adobe Summit 2022. |
| [AEM de Cabeça para Sem Cabeça (e tudo no meio)](https://www.youtube.com/watch?v=idByz7WrhbQ) | Experience League LIVE  | Assista a um detalhamento das implementações mais comuns do Adobe Experience Manager Sites com o host Danny Gordon e os convidados Amol Anand, Sachin Mali e Sean Steimer. <br>**Data:** 21 de abril de 2022 às 9 horas PDT<br>[Agendar eventos anteriores](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=pt-BR) |
| [Como faço para lidar com todos esses públicos-alvo?](https://www.youtube.com/watch?v=I8HKFkx16-E) | Experience League LIVE  | Desmistificar a estratégia do público-alvo com o Audience Manager e a CDP em tempo real. O anfitrião Doug Moore dá as boas-vindas a Nick Cammuso e Jackie Chevallier neste evento Experience League LIVE.<br>**Data:** 28 de abril de 2022 às 9 horas PDT<br>[Agendar eventos anteriores](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [Adobe Campaign Classic v7 e Campaign v8](https://experienceleaguecommunities.adobe.com/t5/adobe-campaign-classic/adobe-campaign-community-q-amp-a-coffee-break-april-21st-8am-pt/td-p/444060) | Quebra de Café de Perguntas e Respostas | Junte-se a Scott Segrin, Eric Knee, David Loyd e Peter Mancuso - Adobe Campaign Enterprise Architecture Team na Comunidade Adobe Campaign para obter perguntas e respostas ao vivo.<br>**Data:** 21 de abril de 2022 às 8 horas PDT<br>[Pormenores e registro](https://adobe.ly/3NB6kuG) |
| [Comunidade Adobe Target](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940#M3096) | Quebra de Café de Perguntas e Respostas | Jim McTiernan responde suas perguntas sobre Adobe Target Recommendations, AB Testing e Personalização MVT na Comunidade Adobe Target <br>**Data:** 21 de abril de 2022 às 8 horas PDT<br>[Pormenores e registro](https://adobe.ly/3joCuvU%C2%A0) |
| [Estrutura da AEM e da CIF](https://adobe.ly/3O0uXl5) | AEM Gems | Integre a estrutura da AEM e da CIF para criar uma experiência rica e imersiva de comércio eletrônico <br>**Data:** 27 de abril de 2022 às 20:00 PDT / 17:00 CET / 20:30 IST<br>[Detalhes e registro](https://adobe.ly/3O0uXl5) |
| [Gems do AEM](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/overview.html?lang=en) | Webinário do Adobe Live | AEM atualizações do Gems para 2022 estão disponíveis! AEM Gems é uma série webinar de aprofundamentos técnicos na Adobe Experience Manager, entregue por especialistas em Adobe. <br>Para obter o Gems de AEM mais recente, consulte [Adobe Experience Manager as a Cloud Service: Revisão de 2021 e Perspectivas de 2022](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/aemcloudservice-2021-review-and-outlook.html?lang=en) e [Crie sites com mais rapidez com o AEM headless e o App Builder](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/build-sites-faster-with-headless-and-appbuilder.html?lang=en).<br>Visite essas notas de versão frequentemente ou assine o [Atualização prioritária de produto do Adobe](https://www.adobe.com/subscription/priority-product-update.html) para ficar no topo dos eventos AEM Gems e outros Experience League. |
| [Criadores de experiências - O intercâmbio de habilidades para o Adobe Workfront](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Webinário do Adobe Live | Adobe está feliz em anunciar a primeira edição de _Experience Manager - O Skill Exchange para Adobe Workfront_. <br>Esse evento gratuito de três horas de aprendizado digital é totalmente voltado para o Workfront. Você pode fazer perguntas a especialistas e colegas que conhecem melhor a gestão do trabalho. Seja você um novato no Workfront ou um especialista experiente, temos algo para todos.<br>**Data:** Quarta-feira, 13 de abril às 9:00 - 12:00 PDT. [Detalhes e registro](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true): O Adobe recomenda o registro, mesmo que você não possa participar, para que você tenha acesso garantido às gravações sob demanda. |
| [Adobe Workfront System Admin Essentials: Criar uma experiência ideal para o usuário](https://webinars.on24.com/adobe_workfront/AdminEssentialsUserExp?partnerref=field) | Webinário do Adobe Live | Junte-se a Mary Ann Erickson, gerente de sucesso do cliente da Adobe Workfront, e Steve Enos, analista de operações criativas do Liberty Joint Insurance para descobrir como projetar uma experiência ideal para o usuário. <br>**Data:** quarta-feira, 27 de abril. Hora: 20:00 PDT / 4:00 PM UK. <br>[Detalhes e registro](https://webinars.on24.com/adobe_workfront/AdminEssentialsUserExp?partnerref=field) |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=pt-BR) | Vídeo sob demanda | A [!DNL Developers Live] apresenta os mais recentes avanços tecnológicos e ferramentas de desenvolvedores que impulsionam o design, os fluxos de trabalho de criação de conteúdo, os serviços de documento e o gerenciamento de experiência do cliente em todos os setores. Assista o discurso de apresentação, conheça as APIs do Analytics, as camadas de dados do cliente, os projetos de código aberto do Adobe Developer e muito mais. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/system-status.png) [!DNL Adobe System Status] {#status}

O [!DNL Adobe System Status] fornece informações detalhadas, atualizações de status e notificações por email sobre eventos de interrupção e manutenção de produtos e serviços da Adobe. Confira em [status.adobe.com](https://status.adobe.com/pt-BR).

Para obter as informações mais recentes da versão, consulte as [notas de versão](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=pt-BR#status) do Status do sistema da Adobe.

## ![Ícone](/assets/ec_appicon_24.png) Experience Cloud — componentes e administração da interface central {#ecloud}

Os [componentes da interface central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=pt-BR) da Experience Cloud incluem recursos disponíveis na página inicial e no cabeçalho persistente do produto. Esses recursos incluem configurações de perfil do usuário, preferências e pesquisa. Você também encontra ajuda para o gerenciamento de usuários e produtos, atributos do cliente e públicos-alvo da Experience Cloud.

| Recurso | Descrição |
| ------- |-------|
| Pesquisa de linguagem natural | Obtenha respostas instantâneas para todas as suas perguntas de ajuda, por meio de uma única interface, por meio da Pesquisa unificada. Esse recurso está sempre disponível para você em todas as páginas do Experience Platform e Journey Optimizer. |

{style=&quot;table-layout:auto&quot;}

**Mais recursos de ajuda em [!DNL Experience Cloud Central UI Components] &amp; administração**

* [Notas de versão](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=pt-BR) para os Componentes de interface central da Experience Cloud
* [Gerenciamento de usuário e produto](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) na Experience Cloud (administração)
* [Notas de versão](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=pt-BR) do Places Service
* Documentação de produto para [Pessoas - Atributos do cliente e Biblioteca de público-alvo](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=pt-BR)
* [Pesquisa unificada por objetos e entidades](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Informações da versão mais recente e nova documentação para [!DNL Experience Platform] e [!UICONTROL SDK móvel]:

Data de lançamento: **30 de março de 2022**

* [Notas de versão da Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR)

### Novos tutoriais e cursos do [!DNL Experience Platform] {#tutorials-platform}

Novos tutoriais em vídeo, artigos e cursos publicados para [!DNL Experience Platform].

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Abril de 2022 | [Introdução ao Privacy Service no Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2021.1.prvsvc) | Curso | Saiba mais sobre as noções básicas do Adobe Experience Platform [!UICONTROL Privacy Service], incluindo como preparar seus dados para operações de privacidade e enviar solicitações de privacidade do cliente para o serviço. |
| Abril de 2022 | [API do servidor de rede de borda da Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/data-collection/server-api/overview.html) | Vídeo | Saiba mais sobre os benefícios do envio de dados para a Platform [!UICONTROL Rede Edge] usando uma API de servidor segura e autenticada. |
| Abril de 2022 | [Logs de auditoria](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-governance/audit-logs.html) | Vídeo | Saiba mais sobre como o recurso de logs de auditoria pode ajudar você a atender aos requisitos de conformidade e solucionar problemas de sua implementação do Adobe Experience Platform. |
| Abril de 2022 | [Preparação de dados para coleta de dados](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/data-prep.html) | Vídeo | Saiba como adicionar sua camada de dados a um novo armazenamento de dados em [!UICONTROL Coleta de dados]. Além disso, saiba como executar funções básicas de mapeamento usando o [!UICONTROL Preparação de dados para coleta de dados] recurso. |
| Abril de 2022 | [Considere mover tags de fornecedor do lado do cliente para o encaminhamento de eventos](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/consider-moving-tags.html) | Vídeo | Saiba como avaliar uma tag de fornecedor do lado do cliente para possivelmente movê-la para uma propriedade de encaminhamento de evento. |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Consulte [Notas de versão e logs de alteração](https://aep-sdks.gitbook.io/docs/release-notes) dos SDKs móveis da Adobe Experience Platform.

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **23 de março de 2022**

* Adobe Analytics [notas de versão](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=pt-BR)
* [Documentação de produto e tutoriais](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR) do Adobe Analytics

### AppMeasurement {#appm}

Versão de lançamento: **2.22.4**

* [AppMeasurement para notas de versão do JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=pt-BR)

### Novos tutoriais e cursos do [!DNL Analytics] {#tutorials-analytics}

Novos tutoriais em vídeo, artigos e cursos publicados no Adobe Analytics.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Abril de 2022 | [Filtrar seus dados com segmentação e datas personalizadas](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.filterdata) | Curso | Saiba como aplicar segmentos, criar segmentos personalizados e usar intervalos de datas para funcionar de forma mais inteligente na análise. |
| Abril de 2022 | [Configurar e administrar conjuntos de relatórios no Adobe Analytics](https://experienceleague.adobe.com/?recommended=Analytics-A-1-2021.1.administration) | Curso | Saiba como configurar itens de configuração gerais do conjunto de relatórios, configurar variáveis de tráfego e conversão, configurar canais de marketing e muito mais. |
| Abril de 2022 | [Contar histórias impactantes com dados](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/telling-impactful-stories-with-data.html?lang=en) | Vídeo | A narrativa de dados é onde arte e ciência se unem usando dados, visualização e narrativa. Ao contar uma história com dados de maneira eficaz, a Adobe Analytics pode se tornar mais acessível a um público maior e você pode aumentar o valor que você agrega à sua organização por meio de tomadas de decisão orientadas por dados. |
| Abril de 2022 | [Ganhe um assento à mesa](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/gaining-a-seat-at-the-table.html?lang=en) | Vídeo | Saiba mais sobre sua função de Administrador do Analytics e obtenha dicas sobre como obter a experiência que o ajuda a obter um assento na tabela de tomada de decisão da sua empresa. |
| Abril de 2022 | [Traduzir o idioma técnico da Adobe Analytics de forma não técnica](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/translating-adobe-analytics-technical-language.html?lang=en#) | Vídeo | Como especialista em Adobe Analytics de sua organização, você é fundamental para ajudar seus participantes a entender os detalhes técnicos e aproveitar ao máximo seu investimento em Adobe Analytics. |
| Abril de 2022 | [Segmentos rápidos no Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/quick-segments-in-analysis-workspace.html?lang=en) | Vídeo | _Segmentos rápidos_ O é uma experiência de segmentação simplificada diretamente na [!UICONTROL Workspace] tela. Saiba como criar segmentos instantâneos com até três regras sem precisar sair do fluxo de trabalho de análise. |
| Abril de 2022 | [Anotações no Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/annotations-in-analysis-workspace.html?lang=en) | Vídeo | Saiba como anotar uma data ou um intervalo de datas com problemas de dados conhecidos, feriados públicos e inicializações de campanha para informar melhor os usuários sobre por que eles estão vendo o que veem em gráficos de linha, tabelas e muito mais. |
| Abril de 2022 | [Trabalhar em várias funcionalidades](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/working-cross-functionally.html?lang=en) | Vídeo | Saiba mais com um campeão da Adobe Analytics sobre como trabalhar em várias funcionalidades da sua organização. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Data de lançamento: **23 de março de 2022**

* Customer Journey Analytics [notas de versão](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=pt-BR)
* [Documentação de produto e tutoriais](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=pt-BR) do Customer Journey Analytics

## ![Ícone](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Data de lançamento: **16 de março de 2022**

* [!DNL Streaming Media Analytics] [notas de versão](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=en)  (**nova localização**)
* [!DNL Streaming Media Analytics] [documentação e tutoriais do produto](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

### Novos tutoriais e cursos do Customer Journey Analytics {#tutorials-cja}

Novos tutoriais em vídeo, artigos e cursos publicados no Customer Journey Analytics.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Abril de 2022 | [Visão geral da configuração de Exibições de dados para o Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en) | Vídeo | Saiba mais sobre como configurar [!UICONTROL Visualizações de dados] para Customer Journey Analytics. [!UICONTROL Visualizações de dados] são semelhantes a [!UICONTROL Conjuntos de relatórios virtuais] no Adobe Analytics. Eles permitem configurar os dados recebidos para que sejam mais úteis para seus relatórios e análises. |
| Abril de 2022 | [Experiência de detalhes de conexões no CJA](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en) | Vídeo | Saiba como verificar o status dos conjuntos de dados da sua conexão e do processo de assimilação. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Correções e aprimoramentos no Audience Manager:

| Melhoria | Descrição |
| -----------| ---------- |  
| Validador para fontes de dados de destino pertencentes a outras empresas | O Audience Manager lançou uma melhoria para o [processo de integração de dados em lote](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=pt-BR). Para evitar a integração acidental de arquivos e dados em fontes de dados de destino pertencentes a outros parceiros, o Audience Manager adicionou um requisito de mapeamento entre a ID do parceiro (PID) e as fontes de dados (DPID) de propriedade de outros parceiros. <ul><li>Veja também o campo __DPID_TARGET_DATA_OWNER_ em [Requisitos de nome e tamanho de arquivo do Amazon S3 para arquivos de dados de entrada](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=pt-BR#name-elements).</li><li>Os consultores internos da Adobe e o atendimento ao cliente devem ler [Gerenciar o acesso de integração para dados secundários](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=pt-BR) para obter informações sobre o novo aprimoramento da exigência de mapeamento e sobre como solicitar um novo mapeamento.</li><li>_Não_ é necessário solicitar um mapeamento para os relacionamentos de compartilhamento de dados existentes. O mapeamento também _não_ é necessário ao integrar dados em fontes de dados de destino que pertencem ao seu PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Para obter recursos de autoajuda, consulte a [Documentação e tutoriais do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=pt-BR) na Experience League.

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

A Adobe recomenda visitar a página de [Roteiros e atualizações de versão do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para se manter atualizado sobre as informações de lançamento.

### Versões de produto do Experience Manager

* **Experience Manager as a Cloud Service**

   Assista ao [vídeo de visão geral da versão de março de 2022](https://video.tv.adobe.com/v/341465) para obter um resumo dos recursos adicionados à versão 2022.3.0 (março de 2022). <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [Vídeo Visão geral dos novos recursos da versão de janeiro de 2022](https://video.tv.adobe.com/v/340120).
   * [Vídeo Visão geral dos novos recursos da versão de dezembro de 2021](https://video.tv.adobe.com/v/339278).
   * [Vídeo Visão geral dos novos recursos da versão de outubro de 2021](https://video.tv.adobe.com/v/338253).
   * [Vídeo Visão geral dos novos recursos da versão de setembro de 2021](https://video.tv.adobe.com/v/337381).

* **Experience Manager Assets as a Cloud Service**

   _Novos recursos em Assets_

   * Experience Manager Dynamic Media agora oferece flexibilidade para [configurar uma conta alias](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=pt-BR) na interface do usuário, garantindo assim [!UICONTROL Dynamic Media] URLs e código de inserção do visualizador são atualizados. Essa atualização afeta positivamente a SEO para refletir as atualizações feitas no contexto de negócios, como rebranding.
   * Agora é possível usar a interface do Experience Manager Assets para:
      * Configure o [detecção de ativos duplicados](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-digital-assets.html?lang=en#detect-duplicate-assets) em um repositório.
      * Configurar [adição de marcas d&#39;água digitais](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/watermark-assets.html?lang=en) para imagens.
   * Os administradores agora podem configurar o serviço de email para downloads grandes. Isso permite que os usuários [ativem as notificações por email para downloads grandes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=en#enable-email-notifications-for-large-downloads) na interface do Experience Manager Assets. O usuário recebe uma notificação por email contendo o link de download da pasta zip arquivada após concluir o processo de download.
   * O recurso [Gerenciar publicação](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en) agora oferece uma interface aprimorada. Um usuário pode publicar ou cancelar a publicação de conteúdo de e para o destino selecionado, ou [Adicionar conteúdo](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#add-content) para a lista de publicação em todo o repositório DAM. Eles podem [Incluir configurações de pasta](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#include-folder-settings) para publicar o conteúdo das pastas selecionadas e aplicar filtros, e [agendar publicação](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#publish-assets-later) para uma data ou hora posterior.

      _Novos recursos no canal de pré-lançamento do Experience Manager Assets_

   * Você pode [classificar tags](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=en#use-tags-to-organize-assets) ao criar tags inteligentes e ao aplicar filtros de pesquisa usando o predicado tags .

* **Experience Manager Forms as a Cloud Service**

   _Novo no Forms_

   * **Comunicações - APIs de geração de documentos** — [APIs de geração de documentos](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=pt-BR) ajuda a combinar, reorganizar e validar documentos do PDF. Esse serviço permite gerar documentos de forma síncrona. As APIs permitem criar aplicativos para fazer o seguinte:

      * Montar documentos do PDF
      * Desmontar documentos do PDF
      * Converta e valide documentos compatíveis com PDF/A.
   * **Converter automaticamente PDF forms mais de 15 páginas em formulários adaptáveis** — Agora você pode usar o serviço automated forms conversion para converter PDF forms com até 40 páginas em formulários adaptáveis. O serviço agora oferece a opção de converter seções de formulários com mais de 15 páginas em fragmentos de formulário adaptáveis. Ajuda a melhorar a velocidade de renderização de formulários convertidos e facilita o carregamento de formulários grandes no editor de formulários adaptável.

   _Novo no canal de pré-lançamento do Forms_

   * **Use o XCI personalizado para gerar um Documento de Registro** — Agora você pode usar um arquivo XCI personalizado para definir várias propriedades de um Documento de registro. Substitui o XCI principal pelas alterações personalizadas.
   * **Usar CAPTCHA invisível em um formulário adaptável** — Você pode usar o CAPTCHA invisível para mostrar o desafio CAPTCHA somente se uma atividade suspeita for encontrada. Se não for encontrada nenhuma atividade suspeita, o desafio CAPTCHA não é apresentado.



* **Complemento CIF**

   _Novos recursos_

   * Beta - Experience Manager CIF Search Core Support Commerce LiveSearch.
   * SEO aprimorado para cenários de várias lojas - Os formatos de URL para PDP/PLP agora podem ser configurados em um nível de loja por meio das propriedades da Configuração da nuvem da CIF.
   * O seletor de produto suporta produtos preparados por meio da nova opção de filtro na interface do usuário. Essa capacidade permite que os profissionais de conteúdo preparem o gerenciamento de conteúdo do produto para lançamentos de produtos futuros.
   * Gerenciamento simplificado de configurações e tratamento de erros da CIF usando o nome da Configuração da nuvem da CIF em vez do URL do proxy de configuração.
   * Seleção manual da categoria para a lista de produtos e os componentes do carrossel. Essa capacidade permite que os profissionais de conteúdo usem esses componentes em páginas de conteúdo, fora da experiência de catálogo.

* **Experience Manager as a Cloud Service Foundation**

   _Novos recursos_

   * Para obter uma solução de problemas mais eficiente e eficaz de recursos personalizados em ambientes do Cloud, o Adobe lançou uma nova ferramenta para desenvolvedores: [o navegador do repositório](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developer-tools/repository-browser.html?lang=en). É um navegador de HTML leve, somente leitura, que pode ser inicializado no Console do desenvolvedor. Obtenha visibilidade sobre o repositório de conteúdo nas camadas de editor, autor e visualização e em todos os ambientes, incluindo produção, estágio e desenvolvimento. Navegue pela estrutura do conteúdo, visualize as propriedades e visualize e baixe binários.
   * As credenciais usadas para autenticar chamadas de API de servidor para servidor (por exemplo, para solicitações de API GraphQL) agora podem ser atualizadas antes da expiração em uma maneira de autoatendimento a partir do Console do desenvolvedor. Consulte a [documentação](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/generating-access-tokens-for-server-side-apis.html?lang=en#refresh-credentials) para obter mais informações.
   * As tarefas de manutenção de limpeza de versão e limpeza de log de auditoria, que não tinham sido anteriormente habilitadas, agora são habilitadas para novos ambientes. Consulte os valores associados na [Tarefa de manutenção](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/maintenance.html?lang=en) artigo 10. o
   * As ferramentas do Dispatcher SDK do Experience Manager as a Cloud Service agora suportam computadores Mac com o chip M1.

* **Cloud Manager**

   _Data de lançamento_

   A data de lançamento do Cloud Manager no Experience Manager as a Cloud Service 2022.02.0 foi 10 de fevereiro de 2022.
O próximo lançamento está planejado para 10 de março de 2022.

   _Novos recursos_

   * Novo acelerado [pipelines de configuração da camada da Web](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#web-tier-config-pipelines) foram introduzidos para implantar exclusivamente a configuração HTTPD/dispatcher.

      * Você deve estar AEM versão `2021.12.6151.20211217T120950Z` ou mais recentes e [aceitar o modo flexível das ferramentas do Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/content-delivery/disp-overview.html?lang=en#validation-debug) para usar esse recurso.
      * Esse recurso está planejado para implantação em uma abordagem em fases durante as duas semanas seguintes à versão 2022.02.0.
   * A experiência de página de aterrissagem do Cloud Manager foi atualizada para oferecer navegação aprimorada, fácil alternância entre exibições de grade/bloco e pop-ups para resumo rápido do programa.
   * Um novo limite de falha (`< D`) foi adicionado ao [métrica de classificação de confiabilidade](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/code-quality-testing.html?lang=en#understanding-code-quality-rules).

      * Clientes com problemas de qualidade graves que afetam a estabilidade do sistema, relacionados principalmente a índices inválidos e processos de fluxo de trabalho, não poderão implantar até que esses problemas sejam resolvidos.
   * A gravidade do BannedPath [regra de qualidade](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/code-quality-testing.html?lang=en#understanding-code-quality-rules) O foi alterado de bloqueador para crítico.
   * O assistente de pipeline informa o usuário quando uma atualização de ambiente do Experience Manager pode ser necessária antes de configurar um [pipeline de Configuração de camada da Web](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#web-tier-config-pipelines) associado a ela.


### Comunidade

* **Webinar de GEMs do Experience Manager**

   * Tópico: _Integre a estrutura da AEM e da CIF para criar uma experiência rica e imersiva de comércio eletrônico_
      * Data: quarta-feira, 27 de abril de 2022
      * Hora: 20:00 PDT / 17:00 CET / 20:30 IST
      * [Inscreva-se aqui](https://adobe.ly/3O0uXl5)
   * Adobe Summit 2022 | A lista completa de sessões e as gravações são [disponível aqui](https://adobe.ly/3rti6gF).

### Novos cursos e tutoriais do Experience Manager {#tutorials-aem}

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição | Produto |
| ------| ----- | ------ | ------ |-----|
| Abril de 2022 | [Geração de documentos usando a API de comunicação](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2022.3.formscs) | Curso | Mesclar dados com o modelo xdp chamando os endpoints HTTP do Forms CS. | AEM Forms |
| Abril de 2022 | [Montar PDF usando a operação invocar DDX](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-assembler/introduction.html?lang=en) | Vídeo | O Navegador de Repositório é uma ferramenta poderosa que fornece visibilidade sobre AEM armazenamento de dados subjacente, permitindo a fácil depuração AEM ambiente as a Cloud Service. O Navegador de Repositório é compatível com a inspeção de todos os recursos e propriedades de AEM em Produção, Estágio e Desenvolvimento, assim como com os serviços Autor, Publicação e Visualização. | AEM CS |
| Abril de 2022 | [Implementar a solução para salvar e recuperar instâncias de carta](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/store-retrieve-letters/introduction.html?lang=en) | Vídeo | Saiba como implementar usando o SPI para salvar e recuperar instâncias de carta de comunicação interativa. | AEM Forms |
| Abril de 2022 | [Criar e validar documentos PDF/A](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-assembler/pdfa-utilities.html?lang=en) | Vídeo | Saiba como criar e validar documentos PDF/A. PDF/A é uma versão padronizada ISO do Portable Document Format (PDF) especializada para uso no arquivamento e na preservação a longo prazo de documentos eletrônicos. | AEM Forms |
| Abril de 2022 | [Integrar o AEM Forms com o [!DNL ServiceNow] ](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/service-now.html?lang=en) | Vídeo | Crie e exiba o incidente no ServiceNow usando o Modelo de dados de formulário no AEM Forms. | AEM Forms |
| Abril de 2022 | [Visão geral dos ativos](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/overview.html) | Tutoriais | Adobe Experience Manager (AEM) [!DNL Assets] O é uma ferramenta de gerenciamento de ativos digitais no AEM Platform que permite que os usuários criem, gerenciem e compartilhem seus ativos digitais (imagens, vídeos, documentos e clipes de áudio) em um repositório baseado na Web. Este guia do usuário contém vídeos e tutoriais sobre os vários recursos e características do AEM Assets. | AEM Assets |
| Abril de 2022 | [Gerenciamento de permissões do Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/permissions-management.html) | Vídeo | Saiba como o gerenciamento de permissões do AEM Assets Essentials permite que as organizações controlem o acesso aos ativos, protejam sua marca e garantam a conformidade. | AEM Assets |
| Abril de 2022 | [Forms de metadados no Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/metadata-forms.html) | Vídeo | Saiba como o Assets Essentials Metadata Forms pode ser configurado rápida e facilmente para ajustar ativos. | AEM Assets |
| Abril de 2022 | [Trabalhar com rich text no Adobe Experience Manager Headless](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/rich-text.html) | Vídeo | Saiba como trabalhar com rich text no AEM Headless. O campo Multi-line text é um tipo de dados de Fragmentos de conteúdo que permite criar conteúdo rich text. | AEM Headless |
| Abril de 2022 | [Depuração de AEM as a Cloud Service com o Navegador de Repositório](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/repository-browser.html) | Vídeo | Saiba mais sobre o Navegador de Repositório, uma ferramenta poderosa que fornece visibilidade sobre o armazenamento de dados subjacente do AEM, permitindo a fácil depuração AEM ambiente as a Cloud Service. | AEM CS |
| Abril de 2022 | [Endereço IP de saída dedicado](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html) | Vídeo | Saiba como configurar e usar o endereço IP de saída dedicado, que permite que conexões de saída de AEM sejam originadas de um IP dedicado. | AEM CS |

{style=&quot;table-layout:auto&quot;}

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Informações sobre a versão do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Notas de versão do Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=pt-BR)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=pt-BR)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=pt-BR)
* [Notas de versão do Cumulative Fix Pack do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=pt-BR)
* [Notas de versão do Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=pt-BR)
* [Notas de versão do Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=pt-BR)
* [Notas de versão do aplicativo para desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=pt-BR)
* [Notas de versão do Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=pt-BR)
* [Notas de versão do Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=pt-BR)
* [Notas de versão do Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=pt-BR)

### Outros recursos de Ajuda do Experience Manager

* [Guias do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Guia do Usuário do Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR#previous-updates)
* [Versões anteriores da documentação do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Página inicial de ajuda do Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=pt-BR)
* [Documentação do Experience Manager: atualizações recentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=pt-BR#aem-as-a-cloud-service)

## ![Ícone](/assets/ec_appicon_24.png) Documentação XML para o Adobe Experience Manager {#xml-doc}

A Documentação XML do Adobe Experience Manager é um aplicativo implantado no AEM. É uma solução poderosa de gerenciamento de conteúdo de componentes (CCMS) de nível empresarial que permite o suporte ao DITA nativo no Adobe Experience Manager, permitindo que o AEM lide com a criação e a entrega de conteúdo baseado em DITA.

Saiba mais sobre a [Documentação XML para AEM](https://www.adobe.com/br/products/xml-documentation-for-experience-manager/features.html).

### Recursos adicionais

* [Documentação XML para o Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=pt-BR) - tutoriais na Experience League
* [Aprendizagem &amp; suporte da Documentação XML para o Adobe Experience Manager](https://helpx.adobe.com/br/support/xml-documentation-for-experience-manager.html) - documentação do produto

## ![Ícone](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Consulte os seguintes links para as notas de versão do Adobe Commerce:

* [Adobe Commerce e Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Infraestrutura em nuvem para Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Novos recursos do Adobe Commerce {#new-commerce}

Nova documentação e tutoriais do Adobe Commerce na Experience League.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Abril de 2022 | [Visão geral da Ferramenta de compatibilidade de atualização](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade/upgrade-compatibility-tool-overview.html) | Vídeo | Saiba mais sobre a Ferramenta de compatibilidade de atualização e como ela pode ajudá-lo a identificar rapidamente os erros e correções necessários para atualizar para uma versão mais recente do Adobe Commerce. |
| Abril de 2022 | [Usar a ferramenta de compatibilidade de atualização no PhpStorm](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade/uct-phpstorm.html) | Vídeo | A Ferramenta de compatibilidade de atualização (UCT) é uma ferramenta gratuita que analisa as incompatibilidades entre a versão atual e a versão de atualização do público alvo em apenas minutos. O Adobe fornece um plug-in PhpStorm para facilitar o uso da ferramenta. |
| Abril de 2022 | [Guia do Live Search](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/guide-overview.html) | Documentação do produto | A Live Search da Adobe Commerce oferece uma experiência de pesquisa rápida, superrelevante e intuitiva, e está disponível para Adobe Commerce sem custo adicional. |
| Abril de 2022 | [Guia do Recommendations do produto](https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/guide-overview.html) | Documentação do produto | Este guia destina-se aos administradores do Adobe Commerce. Ele inclui informações detalhadas sobre a instalação e integração do Product Recommendations, bem como a configuração e o gerenciamento dos serviços. |
| Abril de 2022 | [[!DNL Site-Wide Analysis Tool]](https://experienceleague.adobe.com/docs/commerce-operations/tools/site-wide-analysis-tool/intro.html?lang=en) | Documentação | Informações abrangentes sobre o [!DNL Site-Wide Analysis] Ferramenta, incluindo seus usos, o processo de instalação e obtenção de acesso. | Adobe Commerce |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/target.png) [!DNL Adobe Target] {#target}

Última atualização: **21 de março de 2022**

* Para obter informações de pré-lançamento, consulte [Pré-lançamento do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=pt-BR)
* Para obter informações atuais, consulte [Notas de versão do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produto do Campaign

Saiba mais sobre os recursos, as melhorias e as correções mais recentes na [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=pt-BR), [Campanha v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=pt-BR) e [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=pt-BR) notas de versão.

### Novos tutoriais e cursos do [!DNL Campaign] {#tutorials-campaign}

Novos tutoriais em vídeo e cursos publicados na Adobe Campaign.

| Publicado | Nome | Tipo | Descrição | Aplicativos |
| -----------| ---------- | ---------- | ---------- | ----|
| Abril de 2022 | [Melhore a entrega de email com conteúdo de Experience Manager](https://experienceleague.adobe.com/?recommended=Campaign-A-1-2022.v8.aemcontent) | Curso | Saiba como conectar o Adobe Campaign V8 com o Adobe Experience Manager (AEM) para permitir gerenciar modelos, ativos e formulários de delivery de email no Experience Manager. | Campaign v8, AEM |
| Abril de 2022 | [Trilha de auditoria](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/monitoring/audit-trail.html?lang=en) | Vídeo | Saiba como acessar os logs da Trilha de auditoria e quais configurações podem ser definidas. | Campaign v8 |

{style=&quot;table-layout:auto&quot;}

### Recursos de ajuda do Campaign

* Adobe Campaign v8: [Documentação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Guias de implementação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=pt-BR)
* Adobe Campaign Standard: [Documentação do Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=pt-BR) - [Planejamento de lançamento](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=pt-BR)
* Adobe Campaign Classic: [Documentação do Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=pt-BR)
* Painel de controle do Adobe Campaign: [Documentação](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - Vídeos explicativos do [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=pt-BR)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Com o Journey Optimizer, você pode gerenciar campanhas de canais agendados e momentos de um para um para milhões de clientes a partir de um único aplicativo, e toda a jornada é otimizada com decisões e insights inteligentes.

### Versões mais recentes do produto Journey Optimizer

Saiba mais sobre os recursos, melhorias e correções mais recentes nas [Notas de versão do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=pt-BR).

### Tutoriais e cursos do Journey Optimizer {#tutorials-ajo}

Tutoriais mais recentes do Journey Optimizer:

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Abril de 2022 | [Visão geral do Designer de mensagens](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/message-designer-overview.html?lang=en) | Vídeo | Entender os principais recursos e recursos do Adobe Journey Optimizer [!UICONTROL Designer de mensagens]. |
| Abril de 2022 | [Recursos de aplicativos para dispositivos móveis para desenvolvedores](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/mobile-capabilities-for-developers.html) | Vídeo | Entenda quais recursos de publicações de conteúdo para dispositivos móveis o Adobe Journey Optimizer oferece aos desenvolvedores. |
| Abril de 2022 | [Visão geral da Assets Essentials](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html?lang=en) | Vídeo | Obtenha uma visão geral sobre os recursos do Assets Essentials e como ele pode ser usado no Adobe Journey Optimizer. |
| Abril de 2022 | [Visão geral sobre a Tela da Jornada](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/overview-over-the-journey-canvas.html?lang=en) | Vídeo | Entenda os recursos e as funcionalidades da Tela do Journey. |
| Abril de 2022 | [Perfil e segmentação unificados](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/profiles-segments-subscriptions/unified-profile-and-segmentation-overview.html?lang=en) | Vídeo | Saiba como criar um perfil unificado e, em seguida, criar segmentos com base em atributos de perfil para personalizar as jornadas do cliente. |
| Abril de 2022 | [Recursos de publicações de conteúdo para dispositivos móveis para profissionais de marketing](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/mobile-capabilities.html) | Vídeo | Saiba que recursos para publicação de conteúdo para dispositivos móveis o Adobe Journey Optimizer oferece aos profissionais de marketing. |
| Abril de 2022 | [Criar ofertas personalizadas](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/create-personalized-offers.html) | Vídeo | Saiba como criar ofertas personalizadas no Offer Decisioning. As ofertas personalizadas têm regras de qualificação associadas a elas para ajudar você a mostrá-las apenas para clientes relevantes. |
| Abril de 2022 | [Criar tags](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/create-tags.html?lang=en) | Vídeo | Saiba como criar tags no Offer Decisioning. Tags são componentes opcionais de blocos de construção de ofertas. Elas podem ser usadas para organizar ofertas e agrupá-las em coleções dinâmicas. |
| Abril de 2022 | [Demonstração dos recursos de gerenciamento de decisões](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/demo-of-offer-decisioning.html?lang=en) | Vídeo | Saiba como as marcas podem usar os recursos de gerenciamento de decisões para definir e gerenciar suas ofertas, aplicar dados de clientes em tempo real e fornecer as experiências certas que os clientes esperam. |

{style=&quot;table-layout:auto&quot;}

### Mais recursos para o [!DNL Journey Optimizer]

* [Documentação do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=pt-BR)
* [Documentação do Gerenciamento de decisões](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Use o Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Últimas versões de produto do [!DNL Journey Orchestration]

Saiba mais sobre os recursos, melhorias e correções mais recentes nas Notas de versão do [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=pt-BR).

#### Mais recursos para o [!DNL Journey Orchestration]

* [Documentação do Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

O [!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes envolvendo-se em cada estágio de jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte a [!DNL Marketo Engage] [programação de lançamento](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=pt-BR) para obter as informações mais recentes sobre a programação de lançamento e notas de versão.

## ![Ícone](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

O Adobe [!DNL Workfront] é um aplicativo unificado de gerenciamento de trabalho para compartilhar ideias, criar conteúdos, gerenciar processos complexos e fazer o melhor trabalho.

Consulte a página [[!DNL Workfront] lançamentos](https://one.workfront.com/s/product-releases) para obter um resumo das informações mais recentes para todos os produtos.

## ![Ícone](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notas de versão para [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [Novos recursos no  [!DNL Advertising Cloud Search]](#adcloud-search)

<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

{style="table-layout:auto"}
-->

<!--
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

<!--
{style="table-layout:auto"}
-->

### Novos recursos no [!DNL Advertising Cloud Search] {#adcloud-search}

Última atualização: **11 de abril de 2022**

| Recurso | Descrição |
| ------- | ----------- |
| [!UICONTROL Campanhas]<br><br>[!UICONTROL Insights de publicidade] | (11 de abril; [!DNL Google Ads] contas) A Advertising Cloud Search transferiu todas as chamadas de API do antigo [!DNL Google AdWords API] o mais tardar [!DNL Google Ads API]. Mudar para o novo [!DNL Google Ads API] garante a continuidade com os recursos existentes e permite o acesso a [!DNL Google’s] mais recente [!DNL Ads] recursos.<br><br>Alguns recursos ainda não foram atualizados para a nova API e estão temporariamente indisponíveis:<ul><li>Extensões de localização:<ul>As extensões de localização não estão visíveis no [!UICONTROL Extensões] exibir.</li><li>Não é possível criar uma extensão.</li><li>Filtros em locais não funcionam.</li></li></ul><li>[!UICONTROL Insights de publicidade]: O [!UICONTROL Perda de Impressão] e [!UICONTROL Consulta beta de correspondência cruzada] as análises não estão disponíveis.</li></ul>Prevemos a restauração dos recursos de extensão de localização até o final de abril. Depois de determinar quando o [!UICONTROL Insights de publicidade] os módulos também podem ser restaurados, enviaremos uma atualização com a data estimada. |
| Integração com o Adobe Analytics | (7 de abril) No feed de dados que o Advertising Cloud envia para o [!DNL Analytics], dados para [!DNL Google Ads] e [!DNL Microsoft® Advertising] anúncios de pesquisa responsivos (RSAs) agora são classificados com o [!UICONTROL Tipo de anúncio responsivo] &quot;[!UICONTROL Anúncios de pesquisa responsivos].&quot; Anteriormente, os dados eram incluídos para a variável [!UICONTROL Tipo de anúncio responsivo] &quot;[!UICONTROL Anúncios de texto responsivos].&quot;<br><br>Além disso, a variável [!UICONTROL Título de anúncio responsivo] agora é preenchido com o primeiro título e o [!UICONTROL Descrição responsiva do anúncio] é preenchida com a primeira descrição. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Novos tutoriais e cursos publicados para a Adobe Document Cloud.

| Publicado | Nome | Tipo | Descrição | Aplicativo |
| -----------| ---------- | ---------- | ---------- | -----|
| Abril de 2022 | [Introdução ao Adobe Acrobat](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.1.acrobatgetstarted) | Curso | Saiba por que mais de 5 milhões de organizações em todo o mundo se voltam para o Acrobat para criar documentos digitais sem paralelo que impulsionam os negócios. Descubra novas maneiras de automatizar fluxos de trabalho de documentos manuais e criar experiências envolventes. | Adobe Acrobat |
| Abril de 2022 | [Tarefas avançadas no Adobe Acrobat](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.1.advancedtasks) | Curso | Leve suas habilidades do Acrobat ao próximo nível com técnicas avançadas para editar, trabalhar com formulários, otimizar e automatizar tarefas. Saiba como automatizar fluxos de trabalho manuais de documentos, proteger informações comerciais confidenciais e fornecer experiências excepcionais com seus arquivos PDF. | Adobe Acrobat |
| Abril de 2022 | [Modificação de um documento após o envio](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/modify-in-flight.html?lang=en) | Vídeo | Saiba como modificar um documento que já foi enviado para assinatura, como quando o documento errado é enviado por engano. | Adobe Acrobat Sign |
| Abril de 2022 | [Configurando a ordem de assinatura](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/setting-up-routing.html?lang=en) | Vídeo | Saiba como configurar a ordem de assinatura para vários signatários. Envie um documento em sequência e/ou em paralelo, ou a grupos específicos de indivíduos. | Adobe Acrobat Sign |
| Abril de 2022 | [Substituição de um assinante](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/replace-signer.html) | Vídeo | Saiba como substituir um assinante, como quando o email errado foi usado ao enviar um documento para assinatura. | Adobe Acrobat Sign |
| Abril de 2022 | [Acelere seu processo de vendas](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/acceleratesales.html) | Curso | Saiba como o Adobe Document Services pode integrar experiências de documentos em toda essa jornada para ajudar a acelerar as vendas. | Serviços do documento |
| Abril de 2022 | [Automatizar workflows legais](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/automatelegalworkflows.html) | Artigo | Saiba como gerenciar e executar com segurança termos de contrato, usando modelos predefinidos que mudam com base em um idioma aprovado. | Serviços do documento |
| Abril de 2022 | [Modernização da integração de funcionários](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/employeeonboarding.html) | Vídeo | Saiba como modernizar a integração de funcionários com as APIs do Adobe Document Services. | Serviços do documento |

{style=&quot;table-layout:auto&quot;}

Para obter ajuda sobre a Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem &amp; suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Adobe Creative Cloud para corporações {#creative-cloud}

Consulte [Tutoriais da Creative Cloud para corporações](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=pt-BR) para obter os tutoriais mais recentes.

## ![Ícone](/assets/experience-league.png) Gerenciamento de dados do cliente — Vozes {#voices}

[Gerencimanento de dados do cliente — Vozes](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) é o seu destino como técnico de gerenciamento de dados e líder e especialista de práticas de marketing. Essa coleção de tutoriais é o seu balcão central para ouvir outros usuários, inspirar-se e conhecer os desenvolvimentos na MarTech. Não é necessário fazer um registro. Clique e assista.

## ![Ícone](/assets/experience-league.png) Blueprints de experiência digital {#blueprints}

Os [Blueprints de experiência digital](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=pt-BR) são implementações replicáveis que permitem abordar estratégias e solucionar problemas comerciais estabelecidos de maneira rápida. Cada blueprint oferece uma série de artefatos que explicam o problema comercial de alto valor e fornecem arquiteturas, etapas de implementação, considerações técnicas e links para a documentação relevante.

[Topo](#events)
