# VueLoaders

## Installation
To install this package, use npm:
```
npm install vueloaderspinners --save
```
## Usage
**Default example:**
```
<template>
  <div id="app">
    <Loader/>
  </div>
</template>

<script>

import Loader from 'vueloaderspinners'
export default {
  name: 'App',
  components: {
    Loader
  }
}
</script>
```
This will result to default loader:
<img src="https://media.giphy.com/media/WqcUT5i2efq2FSsBy9/giphy.gif" height="50" width="75"/>

## Options
You can change loader color and type options:
```
<Loader color="red" loaderType="default" />
```
<img src="https://media.giphy.com/media/ZZr0ELVUf3osXJuH3U/giphy.gif" height="50" width="75"/>


*set default loader's container width to height+4px, example: height = 24px; width: 28px;*
## Loaders
```
<Loader loaderType="infinity" />
```
<img src="https://media.giphy.com/media/kycTaRVtdXjgm7KVHs/giphy.gif" height="50" width="75"/>

```
<Loader loaderType="bubble" />
```
<img src="https://media.giphy.com/media/JsJpXcyFMZJwIp0NzI/giphy.gif" height="50" width="75"/>

```
<Loader loaderType="ball" />
```
<img src="https://media.giphy.com/media/S45tjIadGRXhRHLYuo/giphy.gif" height="50" width="75"/>

```
<Loader loaderType="bubble-spin" />
```
<img src="https://media.giphy.com/media/l0ohR5tmvnOfsmyPoT/giphy.gif" height="50" width="75"/>

```
<Loader loaderType="loading-text" />
```
<img src="https://media.giphy.com/media/H7wZEGWa77wKfVxvX8/giphy.gif" height="50" width="75"/>

```
<Loader loaderType="rain-drop" />
```
<img src="https://media.giphy.com/media/JtMYaVc2iSsv10nek6/giphy.gif" height="50" width="75"/>

```
<Loader loaderType="gears" />
```
<img src="https://media.giphy.com/media/WP397XsjEwrN8hoCIN/giphy.gif" height="50" width="75"/>
