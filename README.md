# VueHelper

 ![logo](./src/images/logo.jpg)

## Notes

- 版本更新详情请浏览[releases](https://github.com/OYsun/vscode-VueHelper/releases)
- 关于文件配置问题,请务必看这里：https://github.com/OYsun/vscode-VueHelper/issues/1

## feature
- （1） may be the best vue code snippets plug-ins in Vscode, not only includes the vue2 all api, also contains vue-router 2 and vuex 2 code 

- （2） Each snippet has a detailed description, mainly to facilitate learning, because when learning to forget the use of an api, often to consult the document will be a waste of time, so I will increase the description of each code snippet, description of the basis are derived from official documents 
    - [vue](http://cn.vuejs.org/) | [vue-router](https://router.vuejs.org/zh-cn/) |  [vuex](https://vuex.vuejs.org/zh-cn/)
![zh](./src/images/description.gif)



## snippets

- The code standard style base on [JavaScript Standard Style](https://github.com/feross/standard/blob/master/RULES.md#javascript-standard-style) 

- In vue and vue-router, vuex general `$` are the beginning of the vm api,In the vscode code snippet prepared by the `$` is a variable, when you enter $ is no role。So for all "$" please enter `vm` 

![$](./src/images/$.gif)

- Tips for the way Many plug-ins is to use shorthand，for example, the router object method, enter `rtb->` will prompt `router.beforeEach()`,This is convenient, but need to force you to remember, not friendly.So what I've taken is that when you type `router`, it lists all the properties and methods of the router object 

![snippets](./src/images/snippet.gif)

### Vue code snippets

![vue](./src/images/VueSnippets.gif)


### vue-router code snippets

![vue-router](./src/images/VueRouterSnippets.gif)


### vuex code snippets

![vuex](./src/images/VuexSnippets.gif)


## Installation

* [vscode Extensions Marketplace](https://marketplace.visualstudio.com/items?itemName=oysun.vuehelper)
```javascript
ext install VueHelper
```

## Contributing
This is an open source project open to anyone. Contributions are extremely welcome :[github](https://github.com/OYsun/vscode-VueHelper) 

## Release Notes

### More versions of the information, please click [here](https://github.com/OYsun/vscode-VueHelper/releases) 


