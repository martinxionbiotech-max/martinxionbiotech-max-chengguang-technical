<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "https://technical.chengguangenergy.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Battery Testing",
      "item": "https://technical.chengguangenergy.com/battery-testing/"
    }
  ]
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What does the CCA test measure?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "CCA measures cold starting power at -18°C according to SAE J537, and is the key spec for cold-climate starting."
      }
    },
    {
      "@type": "Question",
      "name": "What is Reserve Capacity?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Reserve Capacity measures how many minutes a battery can run without the alternator at a 25A load before dropping below the cutoff voltage."
      }
    },
    {
      "@type": "Question",
      "name": "What is C20 capacity?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "C20 capacity measures energy storage over a 20-hour discharge according to IEC 60095-1, useful for system sizing and deep-cycle applications."
      }
    },
    {
      "@type": "Question",
      "name": "What is charge acceptance?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Charge acceptance measures recharge speed at 14.0V per EN 50342-6, which matters for start-stop compatibility and fast recovery."
      }
    },
    {
      "@type": "Question",
      "name": "Are CCA ratings interchangeable between standards?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. A battery rated 500 CCA (SAE) may be roughly 550 (EN) or 400 (JIS) under other standards, so always check which standard is referenced."
      }
    }
  ]
}
</script>

# Battery Testing Methods

| Test | What It Measures | Key Standard | Why It Matters |
|------|-----------------|-------------|----------------|
| [CCA](cca.md) | Cold starting power at -18degC | SAE J537 | Cold climate starting |
| [Reserve Capacity](reserve-capacity.md) | Runtime without alternator at 25A | SAE J537 | Emergency power |
| [C20 Capacity](c20-capacity.md) | Energy storage over 20 hours | IEC 60095-1 | System sizing, deep cycle |
| [Charge Acceptance](charge-acceptance.md) | Recharge speed at 14.0V | EN 50342-6 | Start-stop compatibility |

!!! warning "CCA Standards Are Not Interchangeable"
    A battery rated 500 CCA (SAE) may be 550 (EN) or 400 (JIS). Always check which standard is referenced.

[Browse Battery Specifications](https://data.chengguangenergy.com/battery-models/)
