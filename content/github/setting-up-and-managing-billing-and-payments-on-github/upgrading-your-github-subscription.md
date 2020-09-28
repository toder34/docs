---
title: Upgrading your GitHub subscription
intro: 'You can upgrade the subscription for any type of {{ site.data.variables.product.product_name }} account at any time.'
redirect_from:
  - /articles/upgrading-your-personal-account-s-billing-plan/
  - /articles/upgrading-your-personal-account/
  - /articles/upgrading-your-personal-account-from-free-to-a-paid-account/
  - /articles/upgrading-your-personal-account-from-free-to-paid-with-a-credit-card/
  - /articles/upgrading-your-personal-account-from-free-to-paid-with-paypal/
  - /articles/500-error-while-upgrading/
  - /articles/upgrading-your-organization-s-billing-plan/
  - /articles/changing-your-organization-billing-plan/
  - /articles/upgrading-your-organization-account-from-free-to-paid-with-a-credit-card/
  - /articles/upgrading-your-organization-account-from-free-to-paid-with-paypal/
  - /articles/upgrading-your-organization-account/
  - /articles/switching-from-per-repository-to-per-user-pricing/
  - /articles/adding-seats-to-your-organization/
  - /articles/upgrading-your-github-billing-plan/
  - /articles/upgrading-your-github-subscription
versions:
  free-pro-team: '*'
---

### Upgrading your personal account's subscription

You can upgrade your personal account from {{ site.data.variables.product.prodname_free_user }} to {{ site.data.variables.product.prodname_pro }} to get advanced code review tools on private repositories. {{ site.data.reusables.gated-features.more-info }}

{{ site.data.reusables.user_settings.access_settings }}
{{ site.data.reusables.user_settings.billing }}
{{ site.data.reusables.user_settings.subscriptions-tab }}
4. Next to "{{ site.data.variables.product.prodname_free_user }}", click **Upgrade**.
  ![Upgrade button](/assets/images/help/billing/settings_billing_user_upgrade.png)
{{ site.data.reusables.dotcom_billing.choose-monthly-or-yearly-billing }}
{{ site.data.reusables.dotcom_billing.show-plan-details }}
{{ site.data.reusables.dotcom_billing.enter-payment-info }}
{{ site.data.reusables.dotcom_billing.finish_upgrade }}

### Upgrading your organization's subscription

You can upgrade your organization from {{ site.data.variables.product.prodname_free_team }} for an organization to {{ site.data.variables.product.prodname_team }} to access advanced collaboration and management tools for teams, or upgrade your organization to {{ site.data.variables.product.prodname_ghe_cloud }} for additional security, compliance, and deployment controls. {{ site.data.reusables.gated-features.more-info-org-products }}

{{ site.data.reusables.dotcom_billing.org-billing-perms }}

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.org_settings }}
{{ site.data.reusables.organizations.billing }}
{{ site.data.reusables.user_settings.subscriptions-tab }}
{{ site.data.reusables.dotcom_billing.upgrade_org }}
{{ site.data.reusables.dotcom_billing.choose_org_plan }}
{{ site.data.reusables.dotcom_billing.choose-monthly-or-yearly-billing }}
{{ site.data.reusables.dotcom_billing.show-plan-details }}
{{ site.data.reusables.dotcom_billing.enter-payment-info }}
{{ site.data.reusables.dotcom_billing.owned_by_business }}
{{ site.data.reusables.dotcom_billing.finish_upgrade }}

#### Next steps for organizations using {{ site.data.variables.product.prodname_ghe_cloud }}

If you upgraded your organization to {{ site.data.variables.product.prodname_ghe_cloud }}, you can set up identity and access management for your organization. For more information, see "[Managing SAML single sign-on for your organization](/articles/managing-saml-single-sign-on-for-your-organization)."

If you'd like to use an enterprise account with {{ site.data.variables.product.prodname_ghe_cloud }}, contact {{ site.data.variables.contact.contact_enterprise_sales }}. For more information, see "[About enterprise accounts](/articles/about-enterprise-accounts)."

### Adding seats to your organization

If you'd like additional users to have access to your {{ site.data.variables.product.prodname_team }} organization's private repositories, you can purchase more seats anytime.

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.org_settings }}
{{ site.data.reusables.organizations.billing }}
{{ site.data.reusables.user_settings.subscriptions-tab }}
{{ site.data.reusables.dotcom_billing.add-seats }}
{{ site.data.reusables.dotcom_billing.number-of-seats }}
{{ site.data.reusables.dotcom_billing.confirm-add-seats }}

### Switching your organization from per-repository to per-user pricing

{{ site.data.reusables.dotcom_billing.switch-legacy-billing }} For more information, see "[About per-user pricing](/articles/about-per-user-pricing)."

{{ site.data.reusables.profile.access_profile }}
{{ site.data.reusables.profile.access_org }}
{{ site.data.reusables.organizations.org_settings }}
{{ site.data.reusables.organizations.billing }}
5. To the right of your plan name, use the **Edit** drop-down menu, and select **Edit plan**.
  ![Edit drop-down menu](/assets/images/help/billing/per-user-upgrade-button.png)
6. To the right of "Advanced tools for teams", click **Upgrade now**.
  ![Upgrade now button](/assets/images/help/billing/per-user-upgrade-now-button.png)
{{ site.data.reusables.dotcom_billing.choose_org_plan }}
{{ site.data.reusables.dotcom_billing.choose-monthly-or-yearly-billing }}
{{ site.data.reusables.dotcom_billing.owned_by_business }}
{{ site.data.reusables.dotcom_billing.finish_upgrade }}

### Troubleshooting a 500 error when upgrading

{{ site.data.reusables.dotcom_billing.500-error }}

### Further reading

- "[{{ site.data.variables.product.prodname_dotcom }}'s products](/articles/github-s-products)"
- "[How does upgrading or downgrading affect the billing process?](/articles/how-does-upgrading-or-downgrading-affect-the-billing-process)"
- "[About billing on {{ site.data.variables.product.prodname_dotcom }}](/articles/about-billing-on-github)."