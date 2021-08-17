# omada-controller

![Version: 1.4.0](https://img.shields.io/badge/Version-1.4.0-informational?style=flat-square) ![AppVersion: auto](https://img.shields.io/badge/AppVersion-auto-informational?style=flat-square)

Omada enables the network administrators to monitor and manage all the Omada products in the network with a centralized management platform.

**Homepage:** <https://github.com/truechartsapps/tree/master/charts/incubator/omada-controller>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| truecharts | info@truecharts.org | https://truecharts.org |

## Source Code

* <https://github.com/mbentley/docker-omada-controller>
* <https://github.com/truechartsapps/tree/master/charts/omada-controller>

## Requirements

Kubernetes: `>=1.16.0-0`

| Repository | Name | Version |
|------------|------|---------|
| https://truecharts.org | common | 6.8.0 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| env | object | See below | environment variables. See [image docs](https://github.com/mbentley/docker-omada-controller) for more details. |
| env.TZ | string | `"UTC"` | Set the container timezone |
| image.pullPolicy | string | `"IfNotPresent"` | image pull policy |
| image.repository | string | `"mbentley/omada-controller"` | image repository |
| image.tag | string | `"4.4"` | image tag |
| persistence | object | See values.yaml | Configure persistence settings for the chart under this key. |
| service | object | See values.yaml | Configures service settings for the chart. |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)