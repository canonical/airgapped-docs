---
myst:
  html_meta:
    "description": "Learn about key airgapped concepts and product-specific airgapped documentation at Canonical, including Landscape, Ubuntu Pro, Juju, and MAAS."
---

# Airgapped documentation at Canonical

Airgapped environments are offline from the public internet, either through strict network controls or full physical isolation. Many organizations use them to meet security, compliance, or operational requirements. Working in these environments requires different workflows for installing, updating, and operating software.

Canonical provides tools and guidance to support deploying and maintaining Ubuntu and other Canonical products in airgapped environments. This documentation set explains key concepts, types of airgaps, and considerations for planning airgapped deployments. It also links to product-specific guides for working without direct internet access.

This documentation is intended for administrators, security teams, and engineers who manage systems in restricted or fully disconnected networks.

---

## In this documentation

````{grid} 1

```{grid-item-card} [About air-gapped environments](about)

**Key concepts**: Understand key concepts about air-gapping
```

```{grid-item-card} [Air-gapped documentation for Canonical products](products)

**Product documentation** Links to airgapped documentation for specific products
```

````

```{toctree}
:hidden:
:maxdepth: 2

Home <self>
about
Product-specific documentation <products>
