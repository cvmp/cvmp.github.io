---
layout: cvmp-default
title: Sponsorship
excerpt: CVMP 2025 Sponsors
headline: Sponsorship
year: 2025
---

CVMP 2025 is proudly supported by leading organizations in academia and industry who share our vision of advancing visual media production technologies.

## Conference Sponsor

{% assign conference_sponsors = site.data.sponsor[page.year] | where: "level", "conference" %}
{% for sponsor in conference_sponsors %}
<div class="sponsor-section">
  <div class="sponsor-logo-large">
    <a href="{{ sponsor.url }}" target="_blank">
      <img src="{{ site.baseurl }}/{{ sponsor.image }}" alt="{{ sponsor.name }}" title="{{ sponsor.name }}" class="img-responsive">
    </a>
  </div>
</div>
{% endfor %}

## Gold Sponsors

{% assign gold_sponsors = site.data.sponsor[page.year] | where: "level", "gold" %}
{% if gold_sponsors.size > 0 %}
<div class="row">
{% for sponsor in gold_sponsors %}
  <div class="col-md-6 col-lg-4 sponsor-item">
    <div class="sponsor-logo">
      <a href="{{ sponsor.url }}" target="_blank">
        <img src="{{ site.baseurl }}/{{ sponsor.image }}" alt="{{ sponsor.name }}" title="{{ sponsor.name }}" class="img-responsive">
      </a>
    </div>
    <h4><a href="{{ sponsor.url }}" target="_blank">{{ sponsor.name }}</a></h4>
  </div>
{% endfor %}
</div>
{% else %}
<p><em>Gold sponsorship opportunities are available. Contact us for more information.</em></p>
{% endif %}

## Silver Sponsors

{% assign silver_sponsors = site.data.sponsor[page.year] | where: "level", "silver" %}
{% if silver_sponsors.size > 0 %}
<div class="row">
{% for sponsor in silver_sponsors %}
  <div class="col-md-4 col-lg-3 sponsor-item">
    <div class="sponsor-logo">
      <a href="{{ sponsor.url }}" target="_blank">
        <img src="{{ site.baseurl }}/{{ sponsor.image }}" alt="{{ sponsor.name }}" title="{{ sponsor.name }}" class="img-responsive">
      </a>
    </div>
    <h5><a href="{{ sponsor.url }}" target="_blank">{{ sponsor.name }}</a></h5>
  </div>
{% endfor %}
</div>
{% else %}
<p><em>Silver sponsorship opportunities are available. Contact us for more information.</em></p>
{% endif %}

## Bronze Sponsors

{% assign bronze_sponsors = site.data.sponsor[page.year] | where: "level", "bronze" %}
{% if bronze_sponsors.size > 0 %}
<div class="row">
{% for sponsor in bronze_sponsors %}
  <div class="col-md-3 col-lg-2 sponsor-item">
    <div class="sponsor-logo-small">
      <a href="{{ sponsor.url }}" target="_blank">
        <img src="{{ site.baseurl }}/{{ sponsor.image }}" alt="{{ sponsor.name }}" title="{{ sponsor.name }}" class="img-responsive">
      </a>
    </div>
    <h6><a href="{{ sponsor.url }}" target="_blank">{{ sponsor.name }}</a></h6>
  </div>
{% endfor %}
</div>
{% else %}
<p><em>Bronze sponsorship opportunities are available. Contact us for more information.</em></p>
{% endif %}

## Academic Partners

{% assign academic_sponsors = site.data.sponsor[page.year] | where: "level", "academic" %}
{% if academic_sponsors.size > 0 %}
<div class="row">
{% for sponsor in academic_sponsors %}
  <div class="col-md-4 col-lg-3 sponsor-item">
    <div class="sponsor-logo">
      <a href="{{ sponsor.url }}" target="_blank">
        <img src="{{ site.baseurl }}/{{ sponsor.image }}" alt="{{ sponsor.name }}" title="{{ sponsor.name }}" class="img-responsive">
      </a>
    </div>
    <h5><a href="{{ sponsor.url }}" target="_blank">{{ sponsor.name }}</a></h5>
  </div>
{% endfor %}
</div>
{% endif %}

---

## Become a Sponsor

CVMP provides an excellent platform for organizations to:

- **Connect with leading researchers** in computer vision, graphics, and AI
- **Showcase cutting-edge technologies** to academia and industry professionals
- **Recruit top talent** from Europe's premier visual media production community
- **Demonstrate thought leadership** in the creative industries

### Sponsorship Benefits

Our sponsorship packages offer various levels of visibility and engagement opportunities:

- **Conference Sponsor**: Premier branding, keynote opportunities, exhibition space
- **Gold Sponsors**: Prominent logo placement, networking reception presence, recruitment opportunities
- **Silver Sponsors**: Website visibility, program acknowledgment, booth space
- **Bronze Sponsors**: Logo recognition, program listing
- **Academic Partners**: Community recognition, student networking opportunities

### Contact Us

For sponsorship opportunities and customized packages, please contact;

- **Sara Coppola-Nicholson**: [sara.coppolanicholson@cookeoptics.com](mailto:sara.coppolanicholson@cookeoptics.com)
- **Da Chen**: [dc598@bath.ac.uk](mailto:dc598@bath.ac.uk)
- **General Inquiries**: [contact@cvmp-conference.org](mailto:contact@cvmp-conference.org)

<style>
.sponsor-section {
  margin: 30px 0;
  text-align: center;
}

.sponsor-logo-large img {
  max-height: 120px;
  width: auto;
}

.sponsor-logo img {
  max-height: 80px;
  width: auto;
}

.sponsor-logo-small img {
  max-height: 60px;
  width: auto;
}

.sponsor-item {
  margin-bottom: 30px;
  text-align: center;
}

.sponsor-item h4, .sponsor-item h5, .sponsor-item h6 {
  margin-top: 15px;
}
</style>