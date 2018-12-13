# css-media-queries

#### iPhone XR and XS max
```
/* 1792x828px at 326ppi */
@media only screen 
    and (device-width : 414px) 
    and (device-height : 896px) 
    and (-webkit-device-pixel-ratio : 2) {}
```
#### iPhone XS and iPhone X
```
/* 2436x1125px at 458ppi */
@media only screen 
    and (device-width : 375px) 
    and (device-height : 812px) 
    and (-webkit-device-pixel-ratio : 3) {}
```
#### iPhone XS Max
```
/* 2688x1242px at 458ppi */
@media only screen 
    and (device-width : 414px) 
    and (device-height : 896px) 
    and (-webkit-device-pixel-ratio : 3) {}
```
#### iPhone 4
```
@media only screen
    and (min-device-width : 320px)
    and (max-device-width : 480px)
    and (-webkit-min-device-pixel-ratio : 2) {}
```
#### iPhone 5
```
@media only screen
    and (min-device-width: 320px)
    and (max-device-height: 568px)
    and (-webkit-device-pixel-ratio: 2) {}
```
#### iPhone 6, 7, 8
```
@media only screen
    and (min-device-width: 375px)
    and (max-device-height: 667px)
    and (-webkit-device-pixel-ratio: 2) {}
```
#### iPhone 6+, 7+, 8+
```
@media only screen
    and (min-device-width: 414px)
    and (max-device-height: 736px)
    and (orientation : landscape)
    and (-webkit-device-pixel-ratio: 2) {}
```
#### Samsung Galaxy S5
```
@media only screen
    and (min-device-width: 360px)
    and (max-device-height: 640px)
    and (-webkit-device-pixel-ratio: 3) {}
```
#### iPads (portrait and landscape)
```
@media only screen
    and (min-device-width : 768px)
    and (max-device-width : 1024px) {}

```

## Looking for a specific orientation ?

### Portrait

#### iPads
```
@media only screen
    and (min-device-width : 768px)
    and (max-device-width : 1024px)
    and (orientation : portrait) {}
```
#### iPad 3
```
@media only screen
    and (min-device-width : 768px)
    and (max-device-width : 1024px)
    and (orientation : portrait)
    and (-webkit-min-device-pixel-ratio : 2) {}
```

### Landscape

#### iPads
```
@media only screen
    and (min-device-width : 768px)
    and (max-device-width : 1024px)
    and (orientation : landscape) {}
```
#### iPad 3
```
@media only screen
    and (min-device-width : 768px)
    and (max-device-width : 1024px)
    and (orientation : landscape)
    and (-webkit-min-device-pixel-ratio : 2) {}
```

