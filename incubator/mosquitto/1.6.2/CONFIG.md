# mosquitto

![Version: 1.6.1](https://img.shields.io/badge/Version-1.6.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: auto](https://img.shields.io/badge/AppVersion-auto-informational?style=flat-square)

Eclipse Mosquitto - An open source MQTT broker

**Homepage:** <https://github.com/truecharts/apps/tree/master/charts/incubator/mosquitto>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| TrueCharts | info@truecharts.org | truecharts.org |

## Source Code

* <https://github.com/eclipse/mosquitto>

## Requirements

Kubernetes: `>=1.16.0-0`

| Repository | Name | Version |
|------------|------|---------|
| https://truecharts.org/ | common | 6.8.0 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| auth.enabled | bool | `false` | By enabling this, `allow_anonymous` gets set to `false` in the mosquitto config. |
| image.pullPolicy | string | `"IfNotPresent"` | image pull policy |
| image.repository | string | `"eclipse-mosquitto"` | image repository |
| image.tag | string | `"2.0.11"` | image tag |
| persistence.configinc | object | See values.yaml | Configure a persistent volume to place *.conf mosquitto-config-files in. When enabled, this gets set as `include_dir` in the mosquitto config. |
| persistence.data | object | See values.yaml | Configure a persistent volume to place mosquitto data in. When enabled, this enables `persistence` and `persistence_location` in the mosquitto config. |
| service | object | See values.yaml | Configures service settings for the chart. Normally this does not need to be modified. |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)