# Mollitia - Prometheus Addon

<!-- TODO Badges -->

# Mollitia Prometheus

The `Mollitia` [Prometheus](https://prometheus.io/) addon adds metrics on every circuit and module so that you can monitor and analyze your applications.

## Documentation

## Installation

### With Node or any web UI Framework

``` bash
# Install mollitia
npm install mollitia --save
# Install the prometheus addon
npm install @mollitia/prometheus --save
```

``` javascript
// Javascript
const Mollitia = require('mollitia');
const { PrometheusAddon } = require('@mollitia/prometheus');

Mollitia.use(new PrometheusAddon());
```

``` typescript
// ES6 or TypeScript
import * as Mollitia from 'mollitia';
import { PrometheusAddon } from '@mollitia/prometheus';

Mollitia.use(new PrometheusAddon());
```

### With CDN

``` html
<!-- CDN -->
<script type="text/javascript" src="https://unpkg.com/mollitia"></script>
<script type="text/javascript" src="https://unpkg.com/@mollitia/prometheus"></script>
<script>
  window.Mollitia.use(new window.MollitiaPrometheus.PrometheusAddon());
</script>
```

## Features

<!-- TODO change links -->

- Works on Node and on browser (even **Internet Explorer 11**, wow).
- Adds metrics for each circuit and module created on your application.
- Allow labels to be added so that you can monitor easily.

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2021 © [Genesys](https://www.genesys.com/).