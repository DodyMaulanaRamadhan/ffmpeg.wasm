import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Installation

:::note
ffmpeg.wasm only supports running in browser, see [FAQ](/docs/faq) for more
details
:::

## Package Managers

Install ffmpeg.wasm using package managers like npm and yarn:

<Tabs>
<TabItem value="npm" label="npm" default>

```bash
npm install @ffmpeg/ffmpeg @ffmpeg/util
```

</TabItem>
<TabItem value="yarn" label="yarn">

```bash
yarn add @ffmpeg/ffmpeg @ffmpeg/util
```

</TabItem>
</Tabs>

:::info
As ffmpeg.wasm spawns a web worker, you cannot import ffmpeg.wasm from CDN like
unpkg. It is recommended to download it and self-hosted most of the time.
:::
