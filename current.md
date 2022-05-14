---
title: Notas de versão mais recentes
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação dos produtos e serviços para  [!DNL Experience Cloud] . Encontre ajuda e novos tutoriais sobre o [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: May 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: c3e59ee55c248878950ccf28a97b778dac69e31a
workflow-type: tm+mt
source-wordcount: '4977'
ht-degree: 50%

---

# Notas de versão da Adobe Experience Cloud - Maio de 2022

![Banner](assets/experience-cloud-banner-3.png)

Como um criador de experiências, o seu caminho para o sucesso começa com a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home). Encontre uma biblioteca ampla de documentação de instruções, tutoriais autoguiados, vídeos de instruções e cursos para todos os níveis e funções, uma comunidade online de usuários e suporte especializado quando precisar.

Está pronto para começar? [Conclua esse teste de 5 minutos](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp).

>[!NOTE]
>
>Para receber uma notificação por email mensal sobre atualizações nessa página, assine a [Atualização Prioritária de Produto da Adobe](https://www.adobe.com/subscription/priority-product-update.html). Verifique com frequência para ficar por dentro do que está acontecendo na Experience League.

Última atualização: **14 de maio de 2022**

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

Atualizado em **13 de maio de 2022**

| Evento | Tipo | Descrição |
| -----------|---------- | ----|
| [Adobe Analytics - Experience Makers - O Skill Exchange](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) | A troca de habilidades | Junte-se a nós neste evento digital gratuito de três horas focado totalmente no Adobe Analytics. Faça perguntas ao vivo de especialistas e colegas que conhecem melhor o Workspace.<br>18 de maio de 2022 a 1:30pm-4:15h EST<br> [Detalhes e inscrição](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) |
| [Adobe Campaign - Série de webinários de sucesso do cliente](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) | Peer2Peer: Aprimoramento das Jornadas do cliente via Adobe Campaign. | Junte-se a esta discussão ao vivo do Peer2Peer com Anja Starun, chefe de operações de envolvimento nas marcas Kayo, Binge e Flash da Streamotion. Saiba diretamente dela sobre as estratégias bem-sucedidas que sua equipe implementou para criar jornadas de clientes individualizadas usando o Adobe Campaign. <br>**Data:** 26 de maio às 15:00 EST <br>[Detalhes e registro](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) |
| [Notificações por push com o Journey Optimizer - Como configurar facilmente seu aplicativo móvel para push](https://www.youtube.com/watch?v=t36Xjhukmro) | Experience League LIVE  | Saiba mais sobre os casos de uso comuns para notificação por push com o Adobe Journey Optimizer e conheça os detalhes técnicos sobre como configurar um aplicativo para Push com o Adobe Experience Platform. <br>**Data:** 12 de maio de 2022 às 9:30 PDT<br>[Agendar eventos anteriores](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=pt-BR) |
| [Comunidade do Adobe Target](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940?profile.language=pt#M3096) | Sessão de Perguntas e respostas | Associe-se a Brent Kostak e Drew Burns da equipe de produtos do Adobe Target que podem responder suas perguntas da Adobe Target sobre públicos-alvo compartilhados, Real-Time CDP, dados primários, fluxos de trabalho de personalização completos e muito mais.<br>Assista ao recente [Webinar da personalização em tempo real](https://experienceleaguecommunities.adobe.com:443/t5/adobe-target-discussions/webinar-recording-4-28-22-real-time-personalization-with-adobe/td-p/449012) e apresentar as perguntas complementares aos peritos sobre a [Thread de café Break](https://adobe.ly/3MyiDHa) na Comunidade Adobe Target!<br>**Data:** 25 de maio de 2022 às 8 horas PDT<br>[Pormenores e registro](https://adobe.ly/3MyiDHa) |
| [Adobe [!DNL Developers Live]: Comércio](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=en) | Vídeos por demanda | _Adobe Developers Live: Comércio 2022_ reúne desenvolvedores e construtores de experiências com diversos antecedentes e um propósito singular - para criar experiências completas e incríveis. Esta conferência virtual de um dia apresenta atualizações importantes do Commerce e do Open Source Developer, sessões técnicas, oportunidades de rede da comunidade e muito mais. |
| [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | Vídeos por demanda | Saiba mais sobre a importância do seu roteiro do Marketo e como evitar um planejamento insatisfatório. Obtenha conselhos sobre como desbloquear o potencial dos Campos personalizados dos membros do programa, dicas e truques do Marketo Engage e muito mais na [!DNL Marketo] Skill Exchange de agosto de 2021, agora no Experience League. |
| [Adobe Summit 2022](https://business.adobe.com/summit/adobe-summit.html) | Sessões sob demanda | Aprenda com executivos da Adobe e com Ryan Reynolds, Rosalind Brewer (CEO da Walgreens Boots Alliance, Inc), John Donahoe (CEO da NIKE, Inc) e Gail J. McGovern (CEO da American Red Cross), que explicarão por que a experiência do cliente é a moeda da economia digital.<br>Explore [sessões sob demanda](https://business.adobe.com/summit/2022/sessions.html) do Adobe Summit 2022. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/system-status.png) [!DNL Adobe System Status] {#status}

O [!DNL Adobe System Status] fornece informações detalhadas, atualizações de status e notificações por email sobre eventos de interrupção e manutenção de produtos e serviços da Adobe. Confira em [status.adobe.com](https://status.adobe.com/pt).

Para obter as informações mais recentes da versão, consulte as [notas de versão](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=pt-BR#status) do Status do sistema da Adobe.

## ![Ícone](/assets/ec_appicon_24.png) Experience Cloud — componentes e administração da interface central {#ecloud}

Os [componentes da interface central](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=pt-BR) da Experience Cloud incluem recursos disponíveis na página inicial e no cabeçalho persistente do produto. Esses recursos incluem configurações de perfil do usuário, preferências e pesquisa. Você também encontra ajuda para o gerenciamento de usuários e produtos, atributos do cliente e públicos-alvo da Experience Cloud.

Não atualizado.

**Mais recursos de ajuda em [!DNL Experience Cloud Central UI Components] &amp; administração**

* [Notas de versão](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=pt-BR) para os Componentes de interface central da Experience Cloud
* [Gerenciamento de usuário e produto](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) na Experience Cloud (administração)
* [Notas de versão](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=pt-BR) do Places Service
* Documentação de produto para [Pessoas - Atributos do cliente e Biblioteca de público-alvo](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=pt-BR)
* [Pesquisa unificada por objetos e entidades](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=pt-BR)

## ![ícone](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Informações da última versão e nova documentação para a [!DNL Experience Platform] e o [!UICONTROL SDK móvel]:

Data de lançamento prevista: **25 de maio de 2022**

* [Notas de versão da Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR)

### Novos tutoriais e cursos da [!DNL Experience Platform] {#tutorials-platform}

Novos tutoriais em vídeo, artigos e cursos publicados para a [!DNL Experience Platform].

| Publicado | Nome | Tipo | Descrição | Aplicativo |
| -----------| ---------- | ---------- | ---------- |---------- |
| Maio de 2022 | [Insights de pré-compartilhamento da Correspondência de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-pre-share-insights.html) | Vídeo | Quando você decide sobre um parceiro estratégico com o qual compartilhar dados, é importante saber como os clientes são combinados, para que você saiba a utilidade desse compartilhamento de dados. Correspondência de segmentos permite que você veja a sobreposição com parceiros de dados potenciais antes de compartilhar quaisquer dados. | [!DNL Real-time Customer Data Platform] |
| Maio de 2022 | [Configuração da conexão de Correspondência de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-connection-setup.html?lang=en) | Vídeo | saiba como configurar a conexão entre você e um parceiro para compartilhar públicos. Após configurar esse recurso de Correspondência de segmentos , você poderá compartilhar dados entre si com seu parceiro de dados. | [!DNL Real-time Customer Data Platform] |
| Maio de 2022 | [Governança de dados de Correspondência de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-data-governance.html?lang=en) | Vídeo | Saiba como configurar e usar controles de governança de dados no Real-Time CDP para limitar quais conjuntos de dados (e, portanto, quais segmentos que usam esses conjuntos de dados) podem ser compartilhados com parceiros de dados. | [!DNL Real-time Customer Data Platform] |
| Maio de 2022 | [Fluxo de configuração da Correspondência de segmentos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-configuration-flow.html?lang=en) | Vídeo | Saiba mais sobre o processo de configuração de um [!UICONTROL Correspondência de segmentos] para um compartilhamento de dados. | [!DNL Real-time Customer Data Platform] |
| Maio de 2022 | [Conexão com destinos](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/connecting-to-destinations.html) | Vídeo | Antes de enviar dados para parceiros de destino a partir da CDP em tempo real, primeiro faça as conexões com esses parceiros. Este vídeo aborda esse processo, normalmente realizado por Administradores. | [!DNL Real-time Customer Data Platform] |
| Maio de 2022 | [Criar esquemas](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html) | Vídeo | Este vídeo mostra como criar esquemas no Adobe Experience Platform usando a classe Perfil individual XDM e vários grupos de campos. | Experience Platform |
| Maio de 2022 | [Analisar e visualizar insights de omnichchannel no Tableau usando o Serviço de query](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/analyze-and-visualize.html) | Vídeo | Saiba como usar o Serviço de query da Adobe Experience Platform com ferramentas de visualização de dados externas usando um exemplo de análise de churn. | Experience Platform |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Consulte [Notas de versão e logs de alteração](https://aep-sdks.gitbook.io/docs/release-notes) dos SDKs móveis da Adobe Experience Platform.

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **18 de maio de 2022**

* [Notas de versão](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=pt-BR) do Adobe Analytics 
* [Documentação de produto e tutoriais](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR) do Adobe Analytics

### AppMeasurement {#appm}

Versão de lançamento: **2.22.4**

* [AppMeasurement para notas de versão do JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=pt-BR)

### Novos tutoriais e cursos da [!DNL Analytics] {#tutorials-analytics}

Novos tutoriais em vídeo, artigos e cursos publicados para o Adobe Analytics.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Maio de 2022 | [Introdução ao Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/get-started-with-report-builder.html?lang=en) | Vídeo | Saiba mais sobre as noções básicas de uso do Report Builder, incluindo instalação, logon e solicitações de dados. |
| Maio de 2022 | [Navegar pela nova landing page](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/navigating-the-new-landing-page.html?lang=en) | Vídeo | Saiba como aproveitar ao máximo a nova página de aterrissagem do Analytics e seus recursos. |
| Maio de 2022 | [Próximo/Anterior e Resumo da página Painéis e relatórios da Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/next-previous-and-page-summary-workspace-panels-reports.html) | Vídeo | Consulte os dois novos tipos de painel em Analysis Workspace - Próximo/Anterior e Resumo da página. Isso faz com que o Workspace se pareça com alguns dos mais populares [!UICONTROL Reports &amp; Analytics] relatórios. |
| Maio de 2022 | [Atualizações da página de aterrissagem do Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-landing-page-updates.html?lang=en) | Vídeo | Saiba mais sobre algumas das grandes melhorias e adições da nova landing page. Recebemos seus comentários de clientes e tentamos incorporar os recursos mais importantes, como redimensionamento de colunas, novos tipos de colunas, links para relatórios em tempo real e de bot e muitos outros. |
| Maio de 2022 | [Você está fazendo as perguntas certas?](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/are-you-asking-the-right-questions.html) | Vídeo | Saiba como é mais valioso identificar e coletar os pontos de dados acionáveis do que registrar cada elemento possível. A identificação eficiente desses pontos de dados exige um plano básico e discussões criativas com as partes interessadas. |
| Maio de 2022 | [Use [!UICONTROL Report Builder] opções avançadas de entrega do Power BI](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/use-report-builder-advanced-delivery-options-for-power-bi.html?lang=en) | Vídeo | Saiba como configurar um agendamento avançado para enviar uma pasta de trabalho do Report Builder para o Power BI. |
| Maio de 2022 | [Agendar uma solicitação de Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/schedule-a-report-builder-request.html?lang=en) | Vídeo | Saiba como configurar um agendamento básico para uma pasta de trabalho do Report Builder. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Data de lançamento: **18 de maio de 2022**

* [Notas de versão](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=pt-BR) do Customer Journey Analytics 
* [Documentação de produto e tutoriais](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=pt-BR) do Customer Journey Analytics

## ![Ícone](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Última atualização: **23 de março de 2022**

* [!DNL Streaming Media Analytics][Notas de versão de ](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=pt-br)
* [Documentação do produto e tutoriais](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=pt-BR) do [!DNL Streaming Media Analytics]

<!-- ### New Customer Journey Analytics tutorials and courses {#tutorials-cja}

New video tutorials, articles, and courses published for Customer Journey Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2022|[Overview of configuring Data Views for Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en)|Video |Learn about configuring [!UICONTROL Data Views] for Customer Journey Analytics. [!UICONTROL Data Views] are similar to [!UICONTROL Virtual Report Suites] in Adobe Analytics. They allow you to configure the incoming data so that it can be most useful for your reporting and analysis. |
|April 2022|[Connections Details Experience in CJA](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en)|Video |Learn how to check the status of your connection’s datasets and of the ingestion process.|
-->

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Correções e aprimoramentos no Audience Manager:

| Melhoria | Descrição |
| -----------| ---------- |  
| Validador para fontes de dados de destino pertencentes a outras empresas | O Audience Manager lançou uma melhoria para o [processo de integração de dados em lote](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=pt-BR). Para evitar a integração acidental de arquivos e dados em fontes de dados de destino pertencentes a outros parceiros, o Audience Manager adicionou um requisito de mapeamento entre a ID do parceiro (PID) e as fontes de dados (DPID) de propriedade de outros parceiros. <ul><li>Veja também o campo __DPID_TARGET_DATA_OWNER_ em [Requisitos de nome e tamanho de arquivo do Amazon S3 para arquivos de dados de entrada](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=pt-BR#name-elements).</li><li>Os consultores internos da Adobe e o atendimento ao cliente devem ler [Gerenciar o acesso de integração para dados secundários](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=pt-BR) para obter informações sobre o novo aprimoramento da exigência de mapeamento e sobre como solicitar um novo mapeamento.</li><li>_Não_ é necessário solicitar um mapeamento para os relacionamentos de compartilhamento de dados existentes. O mapeamento também _não_ é necessário ao integrar dados em fontes de dados de destino que pertencem ao seu PID.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Para obter recursos de autoajuda, consulte a [Documentação e tutoriais do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=pt-BR) na Experience League.

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

Novos recursos, correções e atualizações no Experience Manager. A Adobe recomenda que os clientes com implantações no local implantem os patches mais recentes de forma a assegurar maior estabilidade, segurança e desempenho.

A Adobe recomenda visitar a página de [Atualizações e roteiros de versão do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para se manter atualizado sobre as informações de lançamento.

### Versões de produto do Experience Manager

* **Experience Manager as a Cloud Service**

   Observe a [Vídeo Visão geral da versão de abril de 2022](https://video.tv.adobe.com/v/342612?quality=12) para obter um resumo dos recursos adicionados na versão 2022.4.0 (abril de 2022). <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [Vídeo Visão geral da versão de março de 2022](https://video.tv.adobe.com/v/341465).
   * [Vídeo Visão geral da versão de janeiro de 2022](https://video.tv.adobe.com/v/340120).
   * [Vídeo Visão geral da versão de dezembro de 2021](https://video.tv.adobe.com/v/339278).
   * [Vídeo Visão geral da versão de outubro de 2021](https://video.tv.adobe.com/v/338253).
   * [Vídeo Visão geral da versão de setembro de 2021](https://video.tv.adobe.com/v/337381).

* **Experience Manager Sites as a Cloud Service**

   _Novo recurso_

   * Agora você pode definir tipos de dados de modelo de conteúdo como [traduzível](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/content-fragments/content-fragments-models.html?lang=en#properties) usar uma caixa de seleção no editor de modelo de conteúdo. Além disso, as regras e configurações de tradução do Experience Manager são atualizadas automaticamente.

   _Novo recurso no canal de pré-lançamento_

   * Publicar fragmentos de experiência na visualização - Para visualizar as experiências finais que seus visitantes podem ver, você pode publicar Fragmentos de experiência independentes no Serviço de visualização do Experience Manager as a Cloud Service.


* **Experience Manager Assets as a Cloud Service**

   _Novo recurso_

   * Agora você pode [classificar tags](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=pt-br#use-tags-to-organize-assets) na janela do seletor de tags em ordem crescente ou decrescente com base no nome da tag, data de criação ou data de modificação.

* **Experience Manager Forms as a Cloud Service**

   _Novos recursos_

   * **Comunicações - Suporte a APIs de manipulação de documentos no SDK as a Cloud Service do Forms** - [APIs de manipulação de documentos](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=pt-BR) ajuda a combinar, reorganizar e validar documentos do PDF. Agora você pode usar as Comunicações - APIs de geração de documentos em um ambiente de desenvolvimento local com a ajuda do SDK as a Cloud Service da Experience Manager Forms.
   * **Use o XCI personalizado para gerar um Documento de Registro** - Agora você pode [use um arquivo XCI personalizado para definir várias propriedades de um Documento de registro](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html?lang=en#use-a-custom-xci-file). Ele substitui o XCI principal pelas alterações personalizadas. Ele oferece mais controle sobre a geração de Documentos de registro, aumento da personalização e oportunidades de personalização.
   * **Usar CAPTCHA invisível em um formulário adaptável** - Você pode usar o [CAPTCHA invisível para mostrar o desafio CAPTCHA somente se houver atividade suspeita](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/add-components-to-an-adaptive-form/captcha-adaptive-forms.html?lang=en). Não sendo identificada nenhuma atividade suspeita, o desafio de CAPTCHA não é exibido. Ajuda a avaliar o preenchimento de formulários humanos sem os requisitos da caixa de seleção, reduzir os esforços de personalização e melhorar a experiência do usuário final.
   * **Configurações do Modelo de dados de formulário** - Agora você pode [reutilizar configurações do Modelo de dados de formulário em ambientes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/create-form-data-models.html?lang=en#runmode-specific-context-aware-config), simplificando as integrações de dados e reduzindo os custos de TI.

* **Experience Manager Screens as a Cloud Service**

   _Novo recurso_

   * Atribuição de canal em massa - Os usuários podem selecionar vários canais e atribuir a várias exibições ao mesmo tempo, em uma operação.

* **Experience Manager as a Cloud Service Foundation**

   _**Analisadores de build do SDK**_

   O plug-in Maven do Experience Manager as a Cloud Service SDK Build Analyzer detecta problemas em um projeto maven, incluindo dependências ausentes. Ela oferece aos desenvolvedores uma oportunidade de descobrir problemas durante o desenvolvimento local, bem antes de implantar em ambientes do Cloud com o Cloud Manager.

   Recentemente, foi adicionado um novo analisador:

   * content-packages-validation - valida para a sintaxe e a estrutura do conteúdo bem formadas para pacotes que são instalados durante a implantação.
   A Adobe recomenda que você atualize seu projeto maven com a versão mais recente do analisador ou inclua o analisador, se ainda não tiver feito isso. Consulte a [documentação da ](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=pt-BR) para obter mais informações.

* **Cloud Manager**

   _Novos recursos_

   * A página Ambientes tem uma coluna para exibir a versão do Experience Manager do ambiente.
   * A execução do pipeline agora exibe erros de nível superior da interface do usuário na tela de execução.
   * Execute novamente a Etapa de implantação de produção por meio da interface do usuário do Cloud Manager.
   * Reutilize a etapa de implantação de criação de imagens para executar novamente a implantação de produção.
   * Nova API para permitir a exclusão de autoatendimento da infraestrutura de rede.

* **Best Practices Analyzer**

   _Novos recursos_

   * Capacidade de detectar e relatar o uso de APIs não compatíveis do Asset Manager. Existem quatro APIs que não são mais suportadas no Experience Manager as a Cloud Service. Os clientes devem garantir que não estejam mais usando essas APIs e devem usar o novo método de upload de ativos.
   * Capacidade de detectar o uso de modelos de Fragmento de conteúdo. Os modelos de Fragmento de conteúdo não são mais compatíveis com a criação de novos fragmentos de conteúdo no Experience Manager as a Cloud Service. Os clientes devem criar modelos de fragmento de conteúdo para substituir os modelos de fragmento de conteúdo.
   * Capacidade de detectar ativos com mais de 100 descendentes no nó de metadados do ativo no repositório. O Adobe recomenda remover os nós de metadados de que você não precisa para melhorar o desempenho ao carregar pastas que consistem em tais ativos.
   * Capacidade de detectar e relatar o tipo de armazenamento de dados usado.
   * Padrão atualizado para o Portal de Formulários do Experience Manager.

### Comunidade

* **Webinar de GEMs Experience Manager gravados**

   * [_Integre a estrutura da AEM e da CIF para criar uma experiência rica e imersiva de comércio eletrônico_](https://adobe.ly/3jorz5r).

* Experience Manager as a Cloud Service [Atualização da versão 2022.4.0](https://adobe.ly/3LO0gOo).

### Novos cursos e tutoriais do Experience Manager {#tutorials-aem}

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição | Aplicativos |
| -----------| ---------- | ---------- | ---------- | ------|
| Maio de 2022 | [AEM atualização da versão 2021.4.0 do as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2021/2021-4-0.html?lang=en) | Vídeo | Saiba mais sobre a equipe de produtos AEM e conheça os recursos e as inovações da última versão do Adobe Experience Manager. | AEM Asset Essentials, Sites, Screens, Forms e Cloud Foundation |
| Maio de 2022 | [Cloud 5 AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-introduction.html) | Vídeos | Obtenha todas as informações úteis de que precisa sobre AEM as a Cloud Service em vídeos curtos de 5 minutos ou menos. Comece com a temporada 1. | AEM CS |
| Maio de 2022 | [Obter um token de logon para integrações](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-getting-login-token-integrations.html) | Vídeo | Um guia detalhado sobre como obter um token de login para integrações do Cloud Service e alguns casos de uso para isso. | AEM CS |
| Maio de 2022 | [Exibir vários documentos pdf em um carrossel](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/display-pdf-in-carousel.html?lang=en) | Vídeo | Saiba mais sobre o caso de uso comum para exibir vários documentos PDF para o usuário a ser revisado antes de enviar o formulário. | AEM Forms |
| Maio de 2022 | [Imagens com AEM headless](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/images.html) | Vídeo | Saiba mais sobre como desenvolver uma experiência rica e convincente AEM sem cabeçalho usando imagens e muito mais. | AEM Headless |
| Maio de 2022 | [Rich Text com AEM headless](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/localized-content.html) | Vídeo | Saiba como usar o campo Multi-line text , um tipo de dados de Fragmentos de conteúdo que permite aos autores criar conteúdo rich text. | AEM Cabeça |
| Maio de 2022 | [Endereço IP de saída dedicado](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html?lang=pt-br) | Vídeo | Aprenda a configurar e usar o endereço IP de saída dedicado, que permite que as conexões de saída do AEM sejam originárias de IP dedicado. | AEM CS |
| Maio de 2022 | [Implantação do código](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/deploy-code.html) | Vídeo | Saiba como implantar seu código na produção usando pipelines do Cloud Manager AEM as a Cloud Service. | AEM CS, Cloud Manager |
| Maio de 2022 | [Desative a execução do workflow de pós-processamento](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/asset-microservices-configure-and-use.html#disable-post-processing-workflow-execution) | Documentação | Saiba como criar um Modelo de fluxo de trabalho vazio na seção Fluxo de trabalho de início automático quando o pós-processamento não é necessário. | AEM CS |
| Maio de 2022 | [Marcas d&#39;água](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/watermarks.html?lang=en) | Vídeo | AEM recursos as a Cloud Service de marca d&#39;água permitem que representações de imagens personalizadas sejam marcadas d&#39;água usando qualquer imagem PNG. | AEM Assets |

{style=&quot;table-layout:auto&quot;}

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Informações sobre a versão do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=pt-BR)
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

* [Guias do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=pt-BR)
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

* [Notas de versão do Adobe Commerce e Magento Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Notas de versão do Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Ícone](/assets/target.png) [!DNL Adobe Target] {#target}

Última atualização: **9 de maio de 2022**

* Para obter informações de pré-lançamento, consulte [Pré-lançamento do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=pt-BR)
* Para obter informações atuais, consulte [Notas de versão do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=pt-BR)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produto do Campaign

Saiba mais sobre os recursos, as melhorias e as correções mais recentes na [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=pt-BR), [Campanha v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=pt-BR)e [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=pt-BR) notas de versão.

### Recursos de ajuda do Campaign

* Adobe Campaign v8: [Documentação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Guias de implementação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=pt-BR)
* Adobe Campaign Standard: [Documentação do Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=pt-BR) - [Planejamento de lançamento](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=pt-BR)
* Adobe Campaign Classic: [Documentação do Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=pt-BR)
* Painel de controle do Adobe Campaign: [Documentação](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=pt-BR)  - Vídeos explicativos do [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=pt-BR)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Com o Journey Optimizer, você pode gerenciar campanhas omnichannel programadas e momentos personalizados para milhões de clientes com um só aplicativo. E toda a jornada é otimizada com decisões e insights inteligentes.

### Versões mais recentes do produto Journey Optimizer

Saiba mais sobre os recursos, melhorias e correções mais recentes nas [Notas de versão do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=pt-BR).

### Tutoriais e cursos do Journey Optimizer {#tutorials-ajo}

Tutoriais mais recentes do Journey Optimizer:

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Maio de 2022 | [Criar regras de decisão](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-rules.html?lang=en) | Vídeo | Saiba como criar regras de decisões para a gestão de decisões. Regras ou _regras de decisão_ são um dos componentes básicos necessários das ofertas personalizadas. |
| Maio de 2022 | [Criar posicionamentos](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-placements.html) | Vídeo | Saiba como criar posicionamentos para a gestão de decisões. Inserções são um dos componentes básicos das ofertas. Uma inserção é a combinação de tipo de conteúdo e canal, como por exemplo, uma imagem em um email ou o código HTML em um site. |
| Maio de 2022 | [Criar decisões](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-decisions.html) | Vídeo | Saiba como criar decisões para a gestão de decisões. Uma decisão combina seus posicionamentos e coleções em uma única entidade, de modo que seja possível tomar a decisão de fornecer a oferta mais relevante ao cliente. |
| Maio de 2022 | [Fornecer ofertas com a API do hub de decisões](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/deliver-offers-with-the-decisions-api.html) | Vídeo | Saiba como fornecer ofertas com a API do hub de decisões. |
| Maio de 2022 | [Criar ofertas de fallback](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-fallback-offers.html) | Vídeo | Saiba como criar ofertas substitutas para a gestão de decisões. As ofertas de fallback são ofertas padrão exibidas para clientes que não se qualificam para nenhuma de suas ofertas personalizadas. |
| Maio de 2022 | [Criar coleções](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-collections.html?lang=en) | Vídeo | Saiba como criar coleções para a gestão de decisões. As coleções são usadas para gerenciar ofertas em grupos lógicos e são necessárias para criar atividades de gerenciamento de decisões |

{style=&quot;table-layout:auto&quot;}

### Mais recursos para o [!DNL Journey Optimizer]

* [Documentação do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=pt-BR)
* [Documentação do Gerenciamento de decisões](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Use o Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Últimas versões de produto do [!DNL Journey Orchestration]

Saiba mais sobre os recursos, melhorias e correções mais recentes nas Notas de versão do [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=pt-BR).

#### Mais recursos para o [!DNL Journey Orchestration]

* [Documentação do Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

O [!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes envolvendo-se em cada estágio de jornadas de compras complexas.

Eventos de vídeo recém-publicados no Experience League:

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Maio de 2022 | [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | Vídeos | Comece a aprender sobre seu roteiro do Marketo. Em seguida, descubra a importância de considerar sua instância do Marketo como um produto. Obtenha conselhos sobre como desbloquear o potencial dos Campos personalizados dos membros do programa, dicas e truques do Marketo Engage e muito mais, neste recém-publicado [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) desde agosto de 2021, agora no Experience League. |

{style=&quot;table-layout:auto&quot;}

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

### Novos recursos no [!DNL Advertising Cloud Search] {#adcloud-search}

Última atualização: **** 12 de maio de 2022 para versão de 14 de maio

| Recurso | Descrição |
| ------- | ----------- |
| [!UICONTROL Campanhas] | Os seguintes recursos beta estão disponíveis para todos os anunciantes:<ul><li>([!DNL Microsoft® Advertising] contas) Sincronização, visibilidade somente leitura e suporte a relatórios (incluindo dados de view-through) para suas campanhas de anúncios nativas existentes na [!DNL Microsoft® Audience Network], incluindo [!DNL Microsoft® Audience Ads].</li><li>([!DNL Google Ads] e [!DNL Microsoft® Advertising] contas) Capacidade de importar suas [!DNL Google Ads] campanhas e estrutura de campanha para [!DNL Microsoft® Advertising] from [!UICONTROL Pesquisar] > [!UICONTROL Ferramentas] > [!UICONTROL Importar Campanhas Beta].<br><br>Depois de importar campanhas, você pode verificar o status do seu trabalho de importação, revisar quaisquer logs de erro e editar, pausar ou excluir seu cronograma de importação.</li></ul> |
| [!UICONTROL Campanhas]<br><br>[!UICONTROL Portfolio] | ([!DNL Microsoft® Advertising] campanhas) As seguintes estratégias de lance estão disponíveis para todos os usuários:<ul><li>[!UICONTROL Compartilhamento de impressão do Target]: Você pode configurar campanhas com essa estratégia e, opcionalmente, definir um compartilhamento de impressões de direcionamento, uma posição de anúncio de destino e um custo máximo por clique. Cuidado: Esta opção ainda não é suportada em portfólios híbridos e não pode ser adicionada a portfólios padrão.</li><li>[!UICONTROL Maximizar cliques]: Você pode configurar campanhas com essa estratégia e, opcionalmente, definir uma meta de custo máximo por clique. Você pode incluir campanhas com essa estratégia em portfólios padrão ou híbridos. Para usar essa estratégia em um portfólio híbrido, o objetivo do portfólio deve incluir somente [!DNL Adobe] propriedades (métricas) e você deve habilitar o upload dos objetivos do Advertising Cloud Search para [!DNL Microsoft® Ads].</li></ul> |
| Integração com o Adobe Analytics | (7 de abril) No feed de dados que o Advertising Cloud envia para o [!DNL Analytics], dados para [!DNL Google Ads] os anúncios de pesquisa dinâmica estão disponíveis somente no nível do grupo de anúncios, a partir de 7 de maio de 2022. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Novos tutoriais e cursos publicados para a Adobe Document Cloud.

| Publicado | Nome | Tipo | Descrição | Aplicativo |
| -----------| ---------- | ---------- | ---------- |---------- |
| Maio de 2022 | [Compartilhamento de acesso à conta](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/share-account-access.html) | Vídeo | Saiba como configurar o acesso somente para visualização a transações na conta de outro usuário. | [!DNL Acrobat Sign] |
| Maio de 2022 | [Gerenciamento de modelos de documento](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/edit-a-template.html?lang=en) | Vídeo | Saiba como editar ou excluir um modelo na biblioteca. | [!DNL Acrobat Sign] |
| Maio de 2022 | [Crie seu primeiro fluxo no Microsoft® Power Automated](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/create-workflow-power-automate.html?lang=en) | Artigo | Saiba como criar seu primeiro fluxo no Microsoft® Power Automate usando o conector de Serviços Adobe PDF. | Document Services |
| Maio de 2022 | [Obtendo credenciais para o Microsoft® Power Automated](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/getting-credentials-power-automate.html?lang=en) | Artigo | Saiba como obter credenciais para começar a usar ou testar os Adobe PDF Services. Dependendo de você ser um usuário de avaliação ou um cliente existente, este tutorial percorre as etapas apropriadas para obter credenciais. | Serviços de documento |

{style=&quot;table-layout:auto&quot;}

Para obter ajuda sobre a Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem &amp; suporte da Document Cloud](https://helpx.adobe.com/br/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Adobe Creative Cloud para corporações {#creative-cloud}

Consulte [Tutoriais da Creative Cloud para corporações](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=pt-BR) para obter os tutoriais mais recentes.

## ![Ícone](/assets/experience-league.png) Gerenciamento de dados do cliente — Vozes {#voices}

[Gerencimanento de dados do cliente — Vozes](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=pt-BR) é o seu destino como técnico de gerenciamento de dados e líder e especialista de práticas de marketing. Essa coleção de tutoriais é o seu balcão central para ouvir outros usuários, inspirar-se e conhecer os desenvolvimentos na MarTech. Não é necessário fazer um registro. Clique e assista.

## ![Ícone](/assets/experience-league.png) Blueprints de experiência digital {#blueprints}

Os [Blueprints de experiência digital](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=pt-BR) são implementações replicáveis que permitem abordar estratégias e solucionar problemas comerciais estabelecidos de maneira rápida. Cada blueprint oferece uma série de artefatos que explicam o problema comercial de alto valor e fornecem arquiteturas, etapas de implementação, considerações técnicas e links para a documentação relevante.

[Topo](#events)
