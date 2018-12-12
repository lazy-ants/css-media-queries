# css-media-queries
The list of CSS media queries used to target devices

### iPhone XR
```
/* 1792x828px at 326ppi */
@media only screen 
    and (device-width : 414px) 
    and (device-height : 896px) 
    and (-webkit-device-pixel-ratio : 2) {}
```

### iPhone XS
```
/* 2436x1125px at 458ppi */
@media only screen 
    and (device-width : 375px) 
    and (device-height : 812px) 
    and (-webkit-device-pixel-ratio : 3) {}
```
### iPhone XS Max
```
/* 2688x1242px at 458ppi */
@media only screen 
    and (device-width : 414px) 
    and (device-height : 896px) 
    and (-webkit-device-pixel-ratio : 3) {}
```

___
## Looking for a specific orientation ?

### Portrait

_Add the following rule:_
```
    and (orientation : portrait)
```

### Landscape

_Add the following rule:_
```
    and (orientation : landscape)
```
