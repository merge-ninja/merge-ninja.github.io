{% include logo.html %}
{% comment %}
- [ ] Logo / Branding
  - [x] Markup: `_includes/logo.html`
  - [x] Placeholders (`icon.{png,svg}`, `tile{,-wide}.png`, `placeholder.com`)
  - [x] Styles
{% endcomment %}
{% include cta-signup.html %}
{% include cta-launch.html %}
{% comment %}
- [x] CTA: Install / Subscribe
  - [x] Data definition: `_data/campaigns.yml#launch`
  - [x] Markup: `_includes/cta-launch.html`
  - [x] Styles
  - [x] Server action
{% endcomment %}
{% include_relative README.md %}
{% include cta-newsletter.html %}
{% comment %}
- [x] CTA: Subscribe to Drip Campaign
  - [x] Data definition: `_data/campaigns.yml#newsletter`
  - [x] Markup: `_includes/cta-newsletter.html`
  - [x] Styles
  - [x] Server action
{% endcomment %}
