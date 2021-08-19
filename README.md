# RuchiJS
It's a javascript library for our utilities &amp; we're making it better day by day. 

# Instalation
1. Using node package manager:
    ```shell
    npm i ruchijs
    ```
2. Using yarn
    ```shell
    yarn add ruchijs
    ```

## Then
```javascript
// You can import simply the Ruchi object or one by one ->
import Ruchi, { logger } from 'ruchijs';

// Simple logger
logger('Ruchi Rocked🤘');

// Getting viewport's height & width
const {x: height, y: width} = Ruchi.getViewportSizes();
```
