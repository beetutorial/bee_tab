# Bee_CustomTabBoard

## usage 


```
self.window.rootViewController = [[BeeCustomTabBoard alloc] initWithBundleName:@"finiance_tab"];
```


## 示例配置文件

```
{
    "tab1s": "ddd",
    "tab_bg": {
        "name": "tab_bg.png",
        "frame": {
            "l": 0,
            "t": 0,
            "w": 320,
            "h": 49
        }
    },
    "resourceBundleName": "CustomTabBar.bundle",
    "bglightImageName": "tab_light.png",
    "btns": [
             {
             "controllerName": "CatelogBoard",
             "default": "tab_zx.png",
             "heighlighted": "tab_zx_h.png",
             "selected": "tab_zx_h.png",
             "indicatorImage": "indicator.png"
             },
             {
             "controllerName": "TestBoard",
             "default": "tab_xg.png",
             "heighlighted": "tab_xg_h.png",
             "selected": "tab_xg_h.png",
             "indicatorImage": "indicator.png"
             },
             {
             "controllerName": "TestBoard",
             "default": "tab_hq.png",
             "heighlighted": "tab_hq_h.png",
             "selected": "tab_hq_h.png",
             "indicatorImage": "indicator.png"
             },
             {
             "controllerName": "TestBoard",
             "default": "tab_sz.png",
             "heighlighted": "tab_sz_h.png",
             "selected": "tab_sz_h.png",
             "indicatorImage": "indicator.png"
             }
             ]
}
```


## 欢迎fork和反馈

在issue提问或邮件shiren1118@126.com