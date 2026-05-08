---
user-guide-title: Journey Optimizer B2B Edition Documentation
user-guide-description: Learn about Adobe Journey Optimizer B2B Edition and how you can use it to orchestrate account and buying group journeys using built-in generative AI and industry-leading automation.
---

# Journey Optimizer B2B Edition User Guide {#user}

+ [Adobe Journey Optimizer B2B Edition Documentation](guide-overview.md)
+ [Release notes](./release-notes/release-notes.md)
+ Get started {#get-started}
    + [Journey Optimizer B2B Edition overview](about-journey-optimizer-b2b-edition.md)
    + Environment setup {#admin-setup}
       + [Setup checklist](./setup-ultimate.md)
       + [Namespaces and schemas](./data/namespaces-schemas.md)
       + [XDM field selection](./admin/xdm-field-management.md)
       + [Experience Events and fields](./admin/configure-aep-events.md)
       + [Branding domains](./start/branding-domains.md)
       + [Email tracking and delivery](./start/email-protocols.md)
       + [Email setup](./start/email-setup.md)
       + [Marketo Engage journey actions](./admin/marketo-actions-connect.md)
       + [User management](./admin/user-management.md)
    + [User onboarding](./start/get-started.md)
    + [Login and home page](home-page.md)
+ AI Assistant {#ai-assistant}
    + [Overview](./ai-assistant/ai-assistant-overview.md)
    + [Enable AI Assistant access](./ai-assistant/enable-ai-assistant-access.md)
    + [Question guidance](./ai-assistant/question-guidance.md)
    + [Use AI Assistant](./ai-assistant/use-ai-assistant.md)
    + [Generative AI for content](./ai-assistant/generative-ai-content.md)
    + Agents {#ai-agents}
       + [Audience Agent B2B](./agents/audience-agent-b2b.md)
       + [Journey Agent B2B](./agents/journey-agent.md)
       + [Sales Qualifier](./agents/sales-qualifier.md)
+ Journey management {#journeys}
    + [Account and person journeys](./journeys/journeys-overview.md)
    + [Create and publish a journey](./journeys/create-publish-journey.md)
    + [Journey re-entry](./journeys/journey-re-entry.md)
    + {hide-from-toc} [Journey nodes](./journeys/journey-nodes.md)
    + Journey nodes {#journey-nodes}
       + [Account audience](./journeys/account-audience-nodes.md)
       + [Person audience (Beta)](./journeys/person-audience-nodes.md)
       + [Take an action](./journeys/action-nodes.md)
       + [Listen for an event](./journeys/listen-for-event-nodes.md)
       + [Split and merge paths](./journeys/split-merge-paths-nodes.md)
       + [Variant split paths (Beta)](./journeys/variant-split-paths-nodes.md)
       + [Wait](./journeys/wait-nodes.md)
       + [External nodes](./journeys/external-nodes.md)
    + [Journey details](./journeys/journey-details.md)
+ Journey content {#journey-content}
    + [SMS channel](./content/sms-authoring.md)
    + [WhatsApp channel](./content/whatsapp-authoring.md)
    + Email channel {#email-channel}
       + [Add an email](./content/add-email.md)
       + [Send-time optimization](./content/email-send-time-optimization.md)
       + [Email authoring](./content/email-authoring.md)
       + [AI Assistant for email authoring](./content/ai-assistant-emails.md)
       + [GenStudio workflows](./content/genstudio-email-workflow.md)
       + [Dark mode for email design](./content/email-dark-mode.md)
       + [Governed templates](./content/email-authoring-governance.md)
       + [Sales alert email](./content/sales-alert-email.md)
       + [Email deduplication](./content/email-deduplication.md)
    + Web channel (Beta) {#web-channel}
      + [Overview](./content/web-experiences.md)
      + [Web experience design](./content/web-experience-design.md)
      + [Single-page applications](./content/web-single-page-applications.md)
    + [Custom personalization tokens](./content/personalization-my-tokens.md)
+ Audiences {#audiences}
    + [Experience Platform audiences](./audiences/account-audience-overview.md)
    + [Target external audiences](./audiences/target-external-audience.md)
    + [LinkedIn Account Matched audiences](./data/linkedin-account-matched-audiences.md)
    + [Default XDM fields](./admin/field-mapping.md)
+ Accounts {#accounts}
    + Buying groups {#buying-groups}
       + [Overview](./buying-groups/buying-groups-overview.md)
       + [Solution interests](./buying-groups/solution-interests.md)
       + [Role templates](./buying-groups/buying-groups-role-templates.md)
       + [Default and custom roles](./buying-groups/default-custom-roles.md)
       + [Role insights](./buying-groups/buying-group-role-insights.md)
       + Buying group scoring {#scoring}
          + [Engagement scores](./buying-groups/engagement-scores.md)
          + [Completeness scores](./buying-groups/completeness-scores.md)
       + [Buying group stages](./buying-groups/buying-group-stages.md)
       + [Create buying groups](./buying-groups/buying-groups-create.md)
       + [Export accounts](./audiences/account-list-export.md)
       + [Buying group filters in Marketo Engage](./buying-groups/marketo-engage-smart-list-buying-group-filters.md)
       + [In-CRM Insights](./buying-groups/incrm-insights.md)
    + Account lists {#account-lists}    
       + [Overview](./accounts/account-lists.md)
       + [Use in journeys and programs](./accounts/account-lists-journeys.md)
    + Sales experience {#sales-experience}
      + [Account details](./accounts/account-details.md)
      + [Buying group details](./buying-groups/buying-group-details.md)
      + [Person details](./accounts/person-details.md)
      + [CRM linking](./accounts/crm-linking.md)
+ Content management {#content-management}
   + Emails {#emails}
      + [Work with email content](./content/emails-list.md)
      + Preview and validation {#preview}
         + [Simulate content](./content/email-simulate-content.md)
         + [Test email rendering](./content/email-test-rendering.md)
         + [Spam report](./content/email-spam-report.md)
      + [Email collaboration](./content/email-collaboration-tools.md)
   + Assets {#assets}
      + [Overview](./content/assets-overview.md)
      + Internal assets {#internal-dam}
        + [Work with internal assets](./content/internal-image-assets.md)
        + [Edit images with Adobe Express](./content/image-edit-adobe-express.md)
      + [Experience Manager image assets](./content/aem-assets.md)
   + Templates {#templates}
      + [Content governance](./content/template-content-governance.md)
      + Email templates {#email-templates}
        + [Overview](./content/email-templates.md)
        + [Email template authoring](./content/email-template-authoring.md)
        + [Advanced HTML editing](./content/email-template-advanced-html.md)
        + [Convert image to template](./content/email-template-image-convert.md)
      + Landing page templates (Beta) {#landing-page-templates}
        + {hide-from-toc} [Overview](./content/landing-page-templates.md)
        + [Landing page template design](./content/landing-page-template-design.md)
   + Fragments {#visual-fragments}
      + [Overview](./content/fragments.md)
      + [Fragment authoring](./content/fragment-authoring.md)
   + Forms (Beta) {#forms}      
      + [Overview](./content/forms.md)
      + [Form design](./content/form-design.md)
   + Landing pages (Beta) {#landing-pages}
      + [Overview](./content/landing-pages.md)       
      + [Landing page design](./content/landing-page-design.md)
      + [AI Assistant for landing page content](./content/ai-assistant-landing-pages.md)
   + Content design tools {#content-design}
      + [Structure components](./content/structure-components.md)
      + [Content components](./content/content-components.md)
      + [Custom CSS](./content/design-custom-css.md)
   + Brands (Beta) {#brands}
      + [Overview](./content/brands-overview.md)
      + [Manage and create](./content/brands-manage-create.md)
      + [Generative AI models](./content/generative-ai-models.md)
   + [Brand themes](./content/brand-themes.md)
   + [Content evaluation](./content/content-evaluation.md)
   + [Conditional content](./content/conditional-content.md)
   + [Content accessibility](./content/accessible-content.md)
   + Personalization {#personalization}
      + [Overview](./content/personalization.md)
      + [Personalization syntax](./content/personalization-syntax.md)
      + [Helper functions list](./content/personalization-helper-functions.md)
+ Intelligent dashboards {#dashboards}
    + [Insights dashboard](./dashboards/intelligent-dashboard.md)
    + [Engagement dashboard](./dashboards/engagement-dashboard.md)
    + [Web engagement dashboard](./dashboards/web-engagement-dashboard.md)    
    + [Buying Groups dashboard](./dashboards/buying-groups-dashboard.md)
    + [Account Journeys dashboard](./dashboards/journeys-dashboard.md)
+ Administration {#admin}
    + [Governance](./admin/governance.md)
    + [Persona mapping](./admin/persona-mapping.md)
    + Configurations {#configurations}
       + [AEM Assets repositories](./admin/configure-aem-repositories.md)
       + [Intent data](./admin/intent-data.md)
       + [Engagement score weighting](./admin/engagement-score-weighting.md)
       + [External actions](./admin/configure-external-actions.md)
    + Channels {#channels}
       + [Email configurations](./admin/configure-channels-emails.md)
       + [SMS configurations](./admin/configure-channels-sms.md)
       + [WhatsApp configurations](./admin/configure-channels-whatsapp.md)
       + [Web channel configurations (Beta)](./admin/configure-channels-web.md)
       + [Landing page settings (Beta)](./admin/landing-page-settings.md)
       + {hide-from-toc} [Configure datastreams for event collection](./data/aep-event-collection.md)
