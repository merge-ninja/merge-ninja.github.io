{% include logo.html %}
{% comment %}
- [ ] Logo / Branding
  - [x] Markup: `_includes/logo.html`
  - [x] Placeholders (`icon.{png,svg}`, `tile{,-wide}.png`)
  - [ ] Styles
{% endcomment %}
{% include cta-launch.html %}
{% comment %}
- [ ] CTA: Install / Subscribe
  - [ ] Data definition: `_data/campaigns.yml#launch`
  - [x] Markup: `_includes/cta{,-launch}.html`
  - [ ] Styles
  - [ ] Server action
{% endcomment %}
{% include_relative README.md %}
{% include cta-newsletter.html %}
{% comment %}
- [ ] CTA: Subscribe to Drip Campaign
  - [x] Data definition: `_data/campaigns.yml#newsletter`
  - [x] Markup: `_includes/cta.html`
  - [ ] Styles
  - [ ] Server action
{% endcomment %}
