# PostHog MaxMind Plugin

Enrich your PostHog events with GeoIP data from MaxMind.

## Installation

### npm

```shell
npm i posthog-maxmind-plugin
```

### yarn

```shell
yarn add posthog-maxmind-plugin
```

## PostHog Configuration

> **Note:** Plugins are currently only available on [self-hosted PostHog instances](posthog.com/docs/features/plugins).

1. Visit the _Plugins_ page in PostHog ('Settings' -> 'Project Plugins')
1. Click '+ Install new plugin' and use the path to your local module installation to add the plugin
  - Installing from GitHub URL does not work for plugins written in TypeScript
1. [Sign up](https://dev.maxmind.com/geoip/geoip2/geolite2/) to MaxMind
1. Download the GeoLite2 City (or the paid GeoIP City) database
1. Upload the `.mmdb` file in the archive via the plugin interface
1. Enable the plugin and watch your events come in with the enriched data!


