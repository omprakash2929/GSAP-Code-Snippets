
# GSAP Snippets Extension

## Preview

![Alt Text](images/gsap-greensock-snippets.gif)



## ✨Features
This extension comes packed with snippets that cover the most popular GSAP methods and properties, helping you write GSAP code faster and more efficiently.

### Included Snippets:
#### Animation Methods:
- **gsap.to()**: Animate from the current state to the specified properties.
- **gsap.from()**: Animate from specific values to the current state.
- **gsap.fromTo()**: Animate between specific starting and ending values.
- **gsap.timeline()**: Create sequences of animations that play in order.
#### ScrollTrigger Methods:
- **ScrollTrigger.create()**: Set up scroll-based animations.
- **pin, scrub, markers**: Common properties for scroll-based animations.
#### Draggable:
- Quick setup for making elements draggable with GSAP.
#### Flip Plugin:
- Transform states and flip them with animations.

## Shortcut Examples:

The snippets are is inspired by [GreenSock's](https://greensock.com/) documentation.

### Basics Methods

| Snippet   | Description                                      |
| --------- | -------------------------------------------- |
| `gto`     | gsap.to(selector,{toVars})                   |
| `gsf`   | gsap.from(selector,{fromVars})                 |
| `gfromTo` | gsap.fromTo(selector, {fromVars}, {toVars}); |
| `gset`    | gsap.set(selector, {toVars});                |
| `gtl`     | Create gsap timeline                         |
| `gfromTo` | GSAP .fromTo() method                        |

### Defaults Properties

| Snippet    | Description                          |
| ---------- | -------------------------------- |
| `del`      | GSAP delay property: `delay:1`               |
| `sca`      | GSAP Scale property: `scale:1`  |
| `dur`     | GSAP Duration: `duration:1`                |
| `rep`   | GSAP Repeat property: `repeat:0.5` |
| `opa`   | GSAP Opacity property: `opacity:0.5` |
| `yo`   | GSAP yoyo property: `yoyo:true` |
| `rota`   | GSAP rotation property: `rotation:90` |
| `pau`   | GSAP paused property: `paused:true` |
| `onSt`   |GSAP onStart callback: `onStart:function()` |
| `tra`   | GSAP transform property: `transform:translate()` |
| `repea`   | GSAP  repeatDelay property: `repeatDelay:1` |
| `eas`   |SAP ease property: `ease:inOut` |
| `oncomp`   |GSAP onComplete callback: `onComplete:callback` |


### GSAP Special Methods

| Snippet  | Description                                                        |
| -------- | -------------------------------------------------------------- |
| `stagg`   | GSAP stagger property: `stagger:0.1`                         |
| `gskill` | GSAP killTweensOf() method: `gsap.killTweensOf:target` |

### GSAP Utils

| Snippet | Description                              |
| ------- | ------------------------------------ |
| `gsrand`   |GSAP utils random(): `gsap.utils.random(range,options)` |
| `gswrap`   |GSAP utils wrap(): `gsap.utils.wrap(range,input)` |

### GSAP ScrollTrigger

| Snippet | Purpose                                |
| ------- | -------------------------------------- |
| `gstscroll`   |Basic GSAP ScrollTrigger setup: `scrollTrigger: {trigger:element,start:top center, end:bottom center, scrub:true,markers:true}` |
| `scrollTr`   |GSAP scrollTrigger property:: `onComplete:callback` |
| `trigg`   |GSAP trigger property: `trigger:attribute` |
| `scroll`   |GSAP scroller property: `scroller:attribute` |
| `scru`   |GSAP scrub property: `scrub:1` |
| `mark`   |GSAP markers property: `markers:true` |

### Utility methods

| Snippet        | Purpose                  |
| -------------- | ------------------------ |
| `gprefix`      | gsap.utils.checkPrefix() |
| `gclamp`       | gsap.utils.clamp()       |
| `gdistribute`  | gsap.utils.distribute()  |
| `ginterpolate` | gsap.utils.interpolate() |
| `gclamp`       | gsap.utils.clamp()       |
| `gmapRange`    | gsap.utils.interpolate() |
| `gnormalize`   | gsap.utils.normalize()   |
| `gpipe`        | gsap.utils.pipe()        |
| `grandomnum`   | gsap.utils.random()      |
| `grandomarray` | gsap.utils.random([])    |
| `gselector`    | gsap.utils.selector()    |
| `gshuffle`     | gsap.utils.shuffle()     |
| `gsplitColor`  | gsap.utils.splitColor()  |
| `gtoArray`     | gsap.utils.toArray()     |
| `gunitize`     | gsap.utils.unitize()     |
| `gwrap`        | gsap.utils.gwrap()       |
| `gwrapYoyo`    | gsap.utils.wrapYoyo()    |


## Authors

- [@omprakash](https://github.com/omprakash2929)


## 🛠️ Requirements
- Visual Studio Code version 1.60.0 or higher.
- Basic understanding of GSAP is recommended to use the snippets effectively

## ⚙️ Extension Settings
This extension does not include any specific configuration settings. All snippets will be available automatically once installed. However, if you'd like to disable specific snippets, you can do so via VS Code's User Snippets settings.

## 🚧 Known Issues

- **Conflicting Shortcuts**: Some common snippet prefixes (like to or fr) may conflict with other snippet extensions or built-in VS Code IntelliSense.
- **CSS Support**: This extension currently focuses on JavaScript-based GSAP animations and doesn’t fully support CSS-only animations.
If you encounter any other issues, please feel free to report them in the issues section on GitHub.

## 🔧 Contributing
Contributions are welcome! If you have ideas for additional snippets, improvements, or bug fixes, feel free to submit a pull request or create an issue in the GitHub repository.

# 🎉 Conclusion
The **GSAP GreenSock Snippets** extension is the perfect tool for animators and developers looking to speed up their GSAP development workflow. With ready-made snippets for the most commonly used GSAP methods, you'll be animating faster and with fewer errors, whether you’re just getting started or you're a seasoned pro!
