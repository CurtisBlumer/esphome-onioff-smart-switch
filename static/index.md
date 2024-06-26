# About

The ONiOFF smart switch has an ESP8625 and can be flashed to ESPHome with a small amount of soldering.

There are project templates for a generic switch, a light, and a fan.

This is mostly just to make it easier for me to reconfigure the ones I have. I'll add more documentation later.

# Installation

You can use the button below to install the pre-built firmware directly to your device via USB from the browser.

## Switch

The relay is configured as a switch that does not come back on after power loss.

<esp-web-install-button manifest="./onioff-switch-manifest.json"></esp-web-install-button>

## Light

The relay is configured as a light that always comes back on after power loss.

<esp-web-install-button manifest="./onioff-switch-light-manifest.json"></esp-web-install-button>

## Fan

The relay is configured as a fan that does not come back on after power loss.

<esp-web-install-button manifest="./onioff-switch-fan-manifest.json"></esp-web-install-button>

<script type="module" src="https://unpkg.com/esp-web-tools@9/dist/web/install-button.js?module"></script>
