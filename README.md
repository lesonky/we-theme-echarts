# An echarts theme from WE Design

# How to use this theme

## with npm
```
npm install @njshaoshao/we-theme-charts
```

## with yarn
```
y add @njshaoshao/we-theme-charts
```

## global use
```
import echarts from 'echarts';

// import theme one by one
// import webar from '@njshaoshao/we-theme-echarts/webar'
// import weline from '@njshaoshao/we-theme-echarts/weline'

// import all themes
import { webar, weline } from '@njshaoshao/we-theme-echarts';

echarts.registerTheme('webar', webar);
echarts.registerTheme('weline', weline);

// then can use in init function with theme name
echarts.init(initDom, 'weline')
echarts.init(initDom, 'webar')
```

## use in init function
```
import echarts from 'echarts';

// import theme one by one
// import webar from '@njshaoshao/we-theme-echarts/webar'
// import weline from '@njshaoshao/we-theme-echarts/weline'

import { webar, weline } from '@njshaoshao/we-theme-echarts';

echarts.init(initDom, weline)
echarts.init(initDom, webar)
```
