# api documentation for  [gsap (v1.19.1)](http://greensock.com/gsap/)  [![npm package](https://img.shields.io/npm/v/npmdoc-gsap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gsap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gsap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gsap)
#### Think of GSAP as the Swiss Army Knife of animation...but better. It animates anything JavaScript can touch (CSS properties, canvas library objects, SVG, generic objects, whatever) and it solves countless browser inconsistencies, all with blazing speed (up

[![NPM](https://nodei.co/npm/gsap.png?downloads=true)](https://www.npmjs.com/package/gsap)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gsap/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gsap_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gsap/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gsap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gsap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "http://greensock.com/forums/"
    },
    "dependencies": {},
    "description": "Think of GSAP as the Swiss Army Knife of animation...but better. It animates anything JavaScript can touch (CSS properties, canvas library objects, SVG, generic objects, whatever) and it solves countless browser inconsistencies, all with blazing speed (up",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "480d320c662337c2663f836baf45e91ea024b553",
        "tarball": "https://registry.npmjs.org/gsap/-/gsap-1.19.1.tgz"
    },
    "filename": "TweenMax.min.js",
    "gitHead": "66b182b6f47c69d566ab4d77fdce490b6e626012",
    "homepage": "http://greensock.com/gsap/",
    "keywords": [
        "animation",
        "TweenLite",
        "TweenMax",
        "TimelineLite",
        "TimelineMax",
        "GSAP",
        "GreenSock",
        "easing",
        "EasePack",
        "CustomEase",
        "jQuery",
        "jquery.gsap.js",
        "Bezier",
        "SVG",
        "3D",
        "2D",
        "transform",
        "tweening"
    ],
    "license": "Standard 'no charge' license: http://greensock.com/standard-license. Club GreenSock members get more: http://greensock.com/licensing/. Why GreenSock doesn't employ an MIT license: http://greensock.com/why-license/",
    "main": "./TweenMax.js",
    "maintainers": [
        {
            "name": "greensock",
            "email": "info@greensock.com"
        }
    ],
    "name": "gsap",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/greensock/GreenSock-JS.git"
    },
    "scripts": {},
    "version": "1.19.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gsap](#apidoc.module.gsap)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BackIn (overshoot)](#apidoc.element.gsap.BackIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BackInOut (overshoot)](#apidoc.element.gsap.BackInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BackOut (overshoot)](#apidoc.element.gsap.BackOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BezierPlugin ()](#apidoc.element.gsap.BezierPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BounceIn ()](#apidoc.element.gsap.BounceIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BounceInOut ()](#apidoc.element.gsap.BounceInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BounceOut ()](#apidoc.element.gsap.BounceOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CSSPlugin ()](#apidoc.element.gsap.CSSPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CSSRulePlugin ()](#apidoc.element.gsap.CSSRulePlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CircIn ()](#apidoc.element.gsap.CircIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CircInOut ()](#apidoc.element.gsap.CircInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CircOut ()](#apidoc.element.gsap.CircOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ColorPropsPlugin ()](#apidoc.element.gsap.ColorPropsPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Cubic ()](#apidoc.element.gsap.Cubic)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Ease (func, extraParams, type, power)](#apidoc.element.gsap.Ease)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ElasticIn (amplitude, period)](#apidoc.element.gsap.ElasticIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ElasticInOut (amplitude, period)](#apidoc.element.gsap.ElasticInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ElasticOut (amplitude, period)](#apidoc.element.gsap.ElasticOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ExpoIn ()](#apidoc.element.gsap.ExpoIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ExpoInOut ()](#apidoc.element.gsap.ExpoInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ExpoOut ()](#apidoc.element.gsap.ExpoOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Linear ()](#apidoc.element.gsap.Linear)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Power0 ()](#apidoc.element.gsap.Power0)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Power1 ()](#apidoc.element.gsap.Power1)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Power2 ()](#apidoc.element.gsap.Power2)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Power3 ()](#apidoc.element.gsap.Power3)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Power4 ()](#apidoc.element.gsap.Power4)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Quad ()](#apidoc.element.gsap.Quad)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Quart ()](#apidoc.element.gsap.Quart)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Quint ()](#apidoc.element.gsap.Quint)
1.  [function <span class="apidocSignatureSpan">gsap.</span>RoughEase (vars)](#apidoc.element.gsap.RoughEase)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SineIn ()](#apidoc.element.gsap.SineIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SineInOut ()](#apidoc.element.gsap.SineInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SineOut ()](#apidoc.element.gsap.SineOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SlowMo (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SteppedEase (steps)](#apidoc.element.gsap.SteppedEase)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Strong ()](#apidoc.element.gsap.Strong)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TimelineLite (vars)](#apidoc.element.gsap.TimelineLite)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TimelineMax (vars)](#apidoc.element.gsap.TimelineMax)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TweenLite (target, duration, vars)](#apidoc.element.gsap.TweenLite)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TweenMax (target, duration, vars)](#apidoc.element.gsap.TweenMax)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TweenPlugin (props, priority)](#apidoc.element.gsap.TweenPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>allFrom (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.allFrom)
1.  [function <span class="apidocSignatureSpan">gsap.</span>allFromTo (targets, duration, fromVars, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.allFromTo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>allTo (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.allTo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>delayedCall (delay, callback, params, scope, useFrames)](#apidoc.element.gsap.delayedCall)
1.  [function <span class="apidocSignatureSpan">gsap.</span>from (target, duration, vars)](#apidoc.element.gsap.from)
1.  [function <span class="apidocSignatureSpan">gsap.</span>fromTo (target, duration, fromVars, toVars)](#apidoc.element.gsap.fromTo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>getAllTweens (includeTimelines)](#apidoc.element.gsap.getAllTweens)
1.  [function <span class="apidocSignatureSpan">gsap.</span>getTweensOf (target, onlyActive)](#apidoc.element.gsap.getTweensOf)
1.  [function <span class="apidocSignatureSpan">gsap.</span>globalTimeScale (value)](#apidoc.element.gsap.globalTimeScale)
1.  [function <span class="apidocSignatureSpan">gsap.</span>isTweening (target)](#apidoc.element.gsap.isTweening)
1.  [function <span class="apidocSignatureSpan">gsap.</span>killAll (complete, tweens, delayedCalls, timelines)](#apidoc.element.gsap.killAll)
1.  [function <span class="apidocSignatureSpan">gsap.</span>killChildTweensOf (parent, complete)](#apidoc.element.gsap.killChildTweensOf)
1.  [function <span class="apidocSignatureSpan">gsap.</span>killDelayedCallsTo (target, onlyActive, vars)](#apidoc.element.gsap.killDelayedCallsTo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>killTweensOf (target, onlyActive, vars)](#apidoc.element.gsap.killTweensOf)
1.  [function <span class="apidocSignatureSpan">gsap.</span>lagSmoothing (threshold, adjustedLag)](#apidoc.element.gsap.lagSmoothing)
1.  [function <span class="apidocSignatureSpan">gsap.</span>pauseAll (tweens, delayedCalls, timelines)](#apidoc.element.gsap.pauseAll)
1.  [function <span class="apidocSignatureSpan">gsap.</span>render ()](#apidoc.element.gsap.render)
1.  [function <span class="apidocSignatureSpan">gsap.</span>resumeAll (tweens, delayedCalls, timelines)](#apidoc.element.gsap.resumeAll)
1.  [function <span class="apidocSignatureSpan">gsap.</span>set (target, vars)](#apidoc.element.gsap.set)
1.  [function <span class="apidocSignatureSpan">gsap.</span>staggerFrom (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.staggerFrom)
1.  [function <span class="apidocSignatureSpan">gsap.</span>staggerFromTo (targets, duration, fromVars, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.staggerFromTo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>staggerTo (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.staggerTo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>to (target, duration, vars)](#apidoc.element.gsap.to)
1.  object <span class="apidocSignatureSpan">gsap.</span>Back
1.  object <span class="apidocSignatureSpan">gsap.</span>BackIn.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>BackInOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>BackOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>BezierPlugin.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>Bounce
1.  object <span class="apidocSignatureSpan">gsap.</span>BounceIn.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>BounceInOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>BounceOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>CSSPlugin._internals
1.  object <span class="apidocSignatureSpan">gsap.</span>CSSPlugin._internals.CSSPropTween.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>CSSPlugin.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>CSSRulePlugin.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>Circ
1.  object <span class="apidocSignatureSpan">gsap.</span>CircIn.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>CircInOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>CircOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>ColorPropsPlugin.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>Ease.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>EaseLookup
1.  object <span class="apidocSignatureSpan">gsap.</span>Elastic
1.  object <span class="apidocSignatureSpan">gsap.</span>ElasticIn.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>ElasticInOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>ElasticOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>Expo
1.  object <span class="apidocSignatureSpan">gsap.</span>ExpoIn.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>ExpoInOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>ExpoOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>RoughEase.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>Sine
1.  object <span class="apidocSignatureSpan">gsap.</span>SineIn.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>SineInOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>SineOut.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>SlowMo.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>SteppedEase.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TimelineLite._internals
1.  object <span class="apidocSignatureSpan">gsap.</span>TimelineLite.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TimelineMax.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._internals
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.attr.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.directionalRotation.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.easel.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.endArray.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.modifiers.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.raphael.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.roundProps.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite._plugins.text.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenLite.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>TweenPlugin.prototype
1.  object <span class="apidocSignatureSpan">gsap.</span>ticker
1.  string <span class="apidocSignatureSpan">gsap.</span>version

#### [module gsap.BackIn](#apidoc.module.gsap.BackIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BackIn (overshoot)](#apidoc.element.gsap.BackIn.BackIn)

#### [module gsap.BackIn.prototype](#apidoc.module.gsap.BackIn.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>config (overshoot)](#apidoc.element.gsap.BackIn.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>constructor (overshoot)](#apidoc.element.gsap.BackIn.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.BackIn.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>_params

#### [module gsap.BackInOut](#apidoc.module.gsap.BackInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BackInOut (overshoot)](#apidoc.element.gsap.BackInOut.BackInOut)

#### [module gsap.BackInOut.prototype](#apidoc.module.gsap.BackInOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>config (overshoot)](#apidoc.element.gsap.BackInOut.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>constructor (overshoot)](#apidoc.element.gsap.BackInOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BackInOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>_params

#### [module gsap.BackOut](#apidoc.module.gsap.BackOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BackOut (overshoot)](#apidoc.element.gsap.BackOut.BackOut)

#### [module gsap.BackOut.prototype](#apidoc.module.gsap.BackOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>config (overshoot)](#apidoc.element.gsap.BackOut.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>constructor (overshoot)](#apidoc.element.gsap.BackOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BackOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>_params

#### [module gsap.BezierPlugin](#apidoc.module.gsap.BezierPlugin)
1.  boolean <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>_autoCSS
1.  [function <span class="apidocSignatureSpan">gsap.</span>BezierPlugin ()](#apidoc.element.gsap.BezierPlugin.BezierPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>_cssRegister ()](#apidoc.element.gsap.BezierPlugin._cssRegister)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>bezierThrough (values, curviness, quadratic, basic, correlate, prepend)](#apidoc.element.gsap.BezierPlugin.bezierThrough)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>cubicToQuadratic (a, b, c, d)](#apidoc.element.gsap.BezierPlugin.cubicToQuadratic)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>quadraticToCubic (a, b, c)](#apidoc.element.gsap.BezierPlugin.quadraticToCubic)
1.  number <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>API
1.  string <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>version

#### [module gsap.BezierPlugin.prototype](#apidoc.module.gsap.BezierPlugin.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.BezierPlugin.prototype._kill)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_mod (lookup)](#apidoc.element.gsap.BezierPlugin.prototype._mod)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_onInitTween (target, vars, tween)](#apidoc.element.gsap.BezierPlugin.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>constructor ()](#apidoc.element.gsap.BezierPlugin.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.BezierPlugin.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_propName

#### [module gsap.BounceIn](#apidoc.module.gsap.BounceIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BounceIn ()](#apidoc.element.gsap.BounceIn.BounceIn)

#### [module gsap.BounceIn.prototype](#apidoc.module.gsap.BounceIn.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.BounceIn.prototype.</span>constructor ()](#apidoc.element.gsap.BounceIn.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.BounceIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.BounceIn.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.BounceIn.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.BounceIn.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.BounceIn.prototype.</span>_params

#### [module gsap.BounceInOut](#apidoc.module.gsap.BounceInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BounceInOut ()](#apidoc.element.gsap.BounceInOut.BounceInOut)

#### [module gsap.BounceInOut.prototype](#apidoc.module.gsap.BounceInOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.BounceInOut.prototype.</span>constructor ()](#apidoc.element.gsap.BounceInOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.BounceInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BounceInOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.BounceInOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.BounceInOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.BounceInOut.prototype.</span>_params

#### [module gsap.BounceOut](#apidoc.module.gsap.BounceOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>BounceOut ()](#apidoc.element.gsap.BounceOut.BounceOut)

#### [module gsap.BounceOut.prototype](#apidoc.module.gsap.BounceOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.BounceOut.prototype.</span>constructor ()](#apidoc.element.gsap.BounceOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.BounceOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BounceOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.BounceOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.BounceOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.BounceOut.prototype.</span>_params

#### [module gsap.CSSPlugin](#apidoc.module.gsap.CSSPlugin)
1.  boolean <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>defaultSmoothOrigin
1.  boolean <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>useSVGTransformAttr
1.  [function <span class="apidocSignatureSpan">gsap.</span>CSSPlugin ()](#apidoc.element.gsap.CSSPlugin.CSSPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>cascadeTo (target, duration, vars)](#apidoc.element.gsap.CSSPlugin.cascadeTo)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>colorStringFilter (a)](#apidoc.element.gsap.CSSPlugin.colorStringFilter)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>getStyle (t, p, cs, calc, dflt)](#apidoc.element.gsap.CSSPlugin.getStyle)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>parseColor (v, toHSL)](#apidoc.element.gsap.CSSPlugin.parseColor)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>parseComplex (t, p, b, e, clrs, dflt, pt, pr, plugin, setRatio)](#apidoc.element.gsap.CSSPlugin.parseComplex)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>registerSpecialProp (name, onInitTween, priority)](#apidoc.element.gsap.CSSPlugin.registerSpecialProp)
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>API
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>defaultTransformPerspective
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>_internals
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>suffixMap
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>defaultSkewType
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>version

#### [module gsap.CSSPlugin._internals](#apidoc.module.gsap.CSSPlugin._internals)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>CSSPropTween (t, p, s, c, next, type, n, r, pr, b, e)](#apidoc.element.gsap.CSSPlugin._internals.CSSPropTween)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>Transform ()](#apidoc.element.gsap.CSSPlugin._internals.Transform)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_parseToProxy (t, vars, cssp, pt, plugin, shallow)](#apidoc.element.gsap.CSSPlugin._internals._parseToProxy)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_registerComplexSpecialProp (p, options, defaults)](#apidoc.element.gsap.CSSPlugin._internals._registerComplexSpecialProp)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_registerPluginProp (p)](#apidoc.element.gsap.CSSPlugin._internals._registerPluginProp)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_setPluginRatio (v)](#apidoc.element.gsap.CSSPlugin._internals._setPluginRatio)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>calculateOffset (t, p, cs)](#apidoc.element.gsap.CSSPlugin._internals.calculateOffset)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>convertToPixels (t, p, v, sfx, recurse)](#apidoc.element.gsap.CSSPlugin._internals.convertToPixels)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>getTransform (t, cs, rec, parse)](#apidoc.element.gsap.CSSPlugin._internals.getTransform)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>set3DTransformRatio (v)](#apidoc.element.gsap.CSSPlugin._internals.set3DTransformRatio)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>setTransformRatio (v)](#apidoc.element.gsap.CSSPlugin._internals.setTransformRatio)
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_specialProps

#### [module gsap.CSSPlugin._internals.CSSPropTween.prototype](#apidoc.module.gsap.CSSPlugin._internals.CSSPropTween.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>appendXtra (pfx, s, c, sfx, r, pad)](#apidoc.element.gsap.CSSPlugin._internals.CSSPropTween.prototype.appendXtra)
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>l
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>pr
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn1
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn2
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn3
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn4
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn5
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn6
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn7
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xn8
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>_next
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>_prev
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>data
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>plugin
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>rxp
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>setRatio
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xfirst
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs0
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs1
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs2
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs3
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs4
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs5
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs6
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs7
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>xs8

#### [module gsap.CSSPlugin.prototype](#apidoc.module.gsap.CSSPlugin.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_addLazySet (t, p, v)](#apidoc.element.gsap.CSSPlugin.prototype._addLazySet)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_enableTransforms (threeD)](#apidoc.element.gsap.CSSPlugin.prototype._enableTransforms)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.CSSPlugin.prototype._kill)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_linkCSSP (pt, next, prev, remove)](#apidoc.element.gsap.CSSPlugin.prototype._linkCSSP)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_mod (lookup)](#apidoc.element.gsap.CSSPlugin.prototype._mod)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_onInitTween (target, vars, tween, index)](#apidoc.element.gsap.CSSPlugin.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>constructor ()](#apidoc.element.gsap.CSSPlugin.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>parse (target, vars, pt, plugin)](#apidoc.element.gsap.CSSPlugin.prototype.parse)
1.  [function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.CSSPlugin.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_firstPT
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_lastParsedTransform
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_super
1.  object <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_transform
1.  string <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_propName

#### [module gsap.CSSRulePlugin](#apidoc.module.gsap.CSSRulePlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CSSRulePlugin ()](#apidoc.element.gsap.CSSRulePlugin.CSSRulePlugin)
1.  [function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.</span>getRule (selector)](#apidoc.element.gsap.CSSRulePlugin.getRule)
1.  number <span class="apidocSignatureSpan">gsap.CSSRulePlugin.</span>API
1.  string <span class="apidocSignatureSpan">gsap.CSSRulePlugin.</span>version

#### [module gsap.CSSRulePlugin.prototype](#apidoc.module.gsap.CSSRulePlugin.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.CSSRulePlugin.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>constructor ()](#apidoc.element.gsap.CSSRulePlugin.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.CSSRulePlugin.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>_propName

#### [module gsap.CircIn](#apidoc.module.gsap.CircIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CircIn ()](#apidoc.element.gsap.CircIn.CircIn)

#### [module gsap.CircIn.prototype](#apidoc.module.gsap.CircIn.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.CircIn.prototype.</span>constructor ()](#apidoc.element.gsap.CircIn.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.CircIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.CircIn.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.CircIn.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.CircIn.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.CircIn.prototype.</span>_params

#### [module gsap.CircInOut](#apidoc.module.gsap.CircInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CircInOut ()](#apidoc.element.gsap.CircInOut.CircInOut)

#### [module gsap.CircInOut.prototype](#apidoc.module.gsap.CircInOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.CircInOut.prototype.</span>constructor ()](#apidoc.element.gsap.CircInOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.CircInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.CircInOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.CircInOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.CircInOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.CircInOut.prototype.</span>_params

#### [module gsap.CircOut](#apidoc.module.gsap.CircOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>CircOut ()](#apidoc.element.gsap.CircOut.CircOut)

#### [module gsap.CircOut.prototype](#apidoc.module.gsap.CircOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.CircOut.prototype.</span>constructor ()](#apidoc.element.gsap.CircOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.CircOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.CircOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.CircOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.CircOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.CircOut.prototype.</span>_params

#### [module gsap.ColorPropsPlugin](#apidoc.module.gsap.ColorPropsPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ColorPropsPlugin ()](#apidoc.element.gsap.ColorPropsPlugin.ColorPropsPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.</span>colorStringFilter (a)](#apidoc.element.gsap.ColorPropsPlugin.colorStringFilter)
1.  [function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.</span>parseColor (v, toHSL)](#apidoc.element.gsap.ColorPropsPlugin.parseColor)
1.  number <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.</span>API
1.  string <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.</span>version

#### [module gsap.ColorPropsPlugin.prototype](#apidoc.module.gsap.ColorPropsPlugin.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.ColorPropsPlugin.prototype._kill)
1.  [function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.ColorPropsPlugin.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>constructor ()](#apidoc.element.gsap.ColorPropsPlugin.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.ColorPropsPlugin.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_firstNumPT
1.  object <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_propName

#### [module gsap.Ease](#apidoc.module.gsap.Ease)
1.  [function <span class="apidocSignatureSpan">gsap.</span>Ease (func, extraParams, type, power)](#apidoc.element.gsap.Ease.Ease)
1.  [function <span class="apidocSignatureSpan">gsap.Ease.</span>register (ease, names, types, create)](#apidoc.element.gsap.Ease.register)
1.  object <span class="apidocSignatureSpan">gsap.Ease.</span>map

#### [module gsap.Ease.prototype](#apidoc.module.gsap.Ease.prototype)
1.  boolean <span class="apidocSignatureSpan">gsap.Ease.prototype.</span>_calcEnd
1.  [function <span class="apidocSignatureSpan">gsap.Ease.prototype.</span>getRatio (p)](#apidoc.element.gsap.Ease.prototype.getRatio)

#### [module gsap.EaseLookup](#apidoc.module.gsap.EaseLookup)
1.  [function <span class="apidocSignatureSpan">gsap.EaseLookup.</span>find (s)](#apidoc.element.gsap.EaseLookup.find)

#### [module gsap.ElasticIn](#apidoc.module.gsap.ElasticIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ElasticIn (amplitude, period)](#apidoc.element.gsap.ElasticIn.ElasticIn)

#### [module gsap.ElasticIn.prototype](#apidoc.module.gsap.ElasticIn.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>config (amplitude, period)](#apidoc.element.gsap.ElasticIn.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>constructor (amplitude, period)](#apidoc.element.gsap.ElasticIn.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.ElasticIn.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>_params

#### [module gsap.ElasticInOut](#apidoc.module.gsap.ElasticInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ElasticInOut (amplitude, period)](#apidoc.element.gsap.ElasticInOut.ElasticInOut)

#### [module gsap.ElasticInOut.prototype](#apidoc.module.gsap.ElasticInOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>config (amplitude, period)](#apidoc.element.gsap.ElasticInOut.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>constructor (amplitude, period)](#apidoc.element.gsap.ElasticInOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ElasticInOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>_params

#### [module gsap.ElasticOut](#apidoc.module.gsap.ElasticOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ElasticOut (amplitude, period)](#apidoc.element.gsap.ElasticOut.ElasticOut)

#### [module gsap.ElasticOut.prototype](#apidoc.module.gsap.ElasticOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>config (amplitude, period)](#apidoc.element.gsap.ElasticOut.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>constructor (amplitude, period)](#apidoc.element.gsap.ElasticOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ElasticOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>_params

#### [module gsap.ExpoIn](#apidoc.module.gsap.ExpoIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ExpoIn ()](#apidoc.element.gsap.ExpoIn.ExpoIn)

#### [module gsap.ExpoIn.prototype](#apidoc.module.gsap.ExpoIn.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.ExpoIn.prototype.</span>constructor ()](#apidoc.element.gsap.ExpoIn.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.ExpoIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.ExpoIn.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.ExpoIn.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.ExpoIn.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.ExpoIn.prototype.</span>_params

#### [module gsap.ExpoInOut](#apidoc.module.gsap.ExpoInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ExpoInOut ()](#apidoc.element.gsap.ExpoInOut.ExpoInOut)

#### [module gsap.ExpoInOut.prototype](#apidoc.module.gsap.ExpoInOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.ExpoInOut.prototype.</span>constructor ()](#apidoc.element.gsap.ExpoInOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.ExpoInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ExpoInOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.ExpoInOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.ExpoInOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.ExpoInOut.prototype.</span>_params

#### [module gsap.ExpoOut](#apidoc.module.gsap.ExpoOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>ExpoOut ()](#apidoc.element.gsap.ExpoOut.ExpoOut)

#### [module gsap.ExpoOut.prototype](#apidoc.module.gsap.ExpoOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.ExpoOut.prototype.</span>constructor ()](#apidoc.element.gsap.ExpoOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.ExpoOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ExpoOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.ExpoOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.ExpoOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.ExpoOut.prototype.</span>_params

#### [module gsap.RoughEase](#apidoc.module.gsap.RoughEase)
1.  [function <span class="apidocSignatureSpan">gsap.</span>RoughEase (vars)](#apidoc.element.gsap.RoughEase.RoughEase)
1.  object <span class="apidocSignatureSpan">gsap.RoughEase.</span>ease

#### [module gsap.RoughEase.prototype](#apidoc.module.gsap.RoughEase.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>config (vars)](#apidoc.element.gsap.RoughEase.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>constructor (vars)](#apidoc.element.gsap.RoughEase.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>getRatio (p)](#apidoc.element.gsap.RoughEase.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>_params

#### [module gsap.SineIn](#apidoc.module.gsap.SineIn)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SineIn ()](#apidoc.element.gsap.SineIn.SineIn)

#### [module gsap.SineIn.prototype](#apidoc.module.gsap.SineIn.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.SineIn.prototype.</span>constructor ()](#apidoc.element.gsap.SineIn.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.SineIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.SineIn.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.SineIn.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.SineIn.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.SineIn.prototype.</span>_params

#### [module gsap.SineInOut](#apidoc.module.gsap.SineInOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SineInOut ()](#apidoc.element.gsap.SineInOut.SineInOut)

#### [module gsap.SineInOut.prototype](#apidoc.module.gsap.SineInOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.SineInOut.prototype.</span>constructor ()](#apidoc.element.gsap.SineInOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.SineInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.SineInOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.SineInOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.SineInOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.SineInOut.prototype.</span>_params

#### [module gsap.SineOut](#apidoc.module.gsap.SineOut)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SineOut ()](#apidoc.element.gsap.SineOut.SineOut)

#### [module gsap.SineOut.prototype](#apidoc.module.gsap.SineOut.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.SineOut.prototype.</span>constructor ()](#apidoc.element.gsap.SineOut.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.SineOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.SineOut.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.SineOut.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.SineOut.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.SineOut.prototype.</span>_params

#### [module gsap.SlowMo](#apidoc.module.gsap.SlowMo)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SlowMo (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.SlowMo)
1.  [function <span class="apidocSignatureSpan">gsap.SlowMo.</span>config (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.config)
1.  object <span class="apidocSignatureSpan">gsap.SlowMo.</span>ease

#### [module gsap.SlowMo.prototype](#apidoc.module.gsap.SlowMo.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>config (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>constructor (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>getRatio (p)](#apidoc.element.gsap.SlowMo.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>_params

#### [module gsap.SteppedEase](#apidoc.module.gsap.SteppedEase)
1.  [function <span class="apidocSignatureSpan">gsap.</span>SteppedEase (steps)](#apidoc.element.gsap.SteppedEase.SteppedEase)
1.  [function <span class="apidocSignatureSpan">gsap.SteppedEase.</span>config (steps)](#apidoc.element.gsap.SteppedEase.config)
1.  object <span class="apidocSignatureSpan">gsap.SteppedEase.</span>ease

#### [module gsap.SteppedEase.prototype](#apidoc.module.gsap.SteppedEase.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>config (steps)](#apidoc.element.gsap.SteppedEase.prototype.config)
1.  [function <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>constructor (steps)](#apidoc.element.gsap.SteppedEase.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>getRatio (p)](#apidoc.element.gsap.SteppedEase.prototype.getRatio)
1.  number <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>_power
1.  number <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>_type
1.  object <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>_params

#### [module gsap.TimelineLite](#apidoc.module.gsap.TimelineLite)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TimelineLite (vars)](#apidoc.element.gsap.TimelineLite.TimelineLite)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.</span>exportRoot (vars, ignoreDelayedCalls)](#apidoc.element.gsap.TimelineLite.exportRoot)
1.  object <span class="apidocSignatureSpan">gsap.TimelineLite.</span>_internals
1.  string <span class="apidocSignatureSpan">gsap.TimelineLite.</span>version

#### [module gsap.TimelineLite._internals](#apidoc.module.gsap.TimelineLite._internals)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite._internals.</span>pauseCallback ()](#apidoc.element.gsap.TimelineLite._internals.pauseCallback)

#### [module gsap.TimelineLite.prototype](#apidoc.module.gsap.TimelineLite.prototype)
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_active
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_forcingPlayhead
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_gc
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_hasPause
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_reversed
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>autoRemoveChildren
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>smoothChildTiming
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_contains (tween)](#apidoc.element.gsap.TimelineLite.prototype._contains)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_enabled (enabled, ignoreTimeline)](#apidoc.element.gsap.TimelineLite.prototype._enabled)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_hasPausedChild ()](#apidoc.element.gsap.TimelineLite.prototype._hasPausedChild)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_kill (vars, target)](#apidoc.element.gsap.TimelineLite.prototype._kill)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_parseTimeOrLabel (timeOrLabel, offsetOrLabel, appendIfAbsent, ignore)](#apidoc.element.gsap.TimelineLite.prototype._parseTimeOrLabel)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_remove (tween, skipDisable)](#apidoc.element.gsap.TimelineLite.prototype._remove)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>add (value, position, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.add)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>addLabel (label, position)](#apidoc.element.gsap.TimelineLite.prototype.addLabel)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>addPause (position, callback, params, scope)](#apidoc.element.gsap.TimelineLite.prototype.addPause)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>append (value, offsetOrLabel)](#apidoc.element.gsap.TimelineLite.prototype.append)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>appendMultiple (tweens, offsetOrLabel, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.appendMultiple)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>call (callback, params, scope, position)](#apidoc.element.gsap.TimelineLite.prototype.call)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>clear (labels)](#apidoc.element.gsap.TimelineLite.prototype.clear)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>constructor (vars)](#apidoc.element.gsap.TimelineLite.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>duration (value)](#apidoc.element.gsap.TimelineLite.prototype.duration)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>from (target, duration, vars, position)](#apidoc.element.gsap.TimelineLite.prototype.from)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>fromTo (target, duration, fromVars, toVars, position)](#apidoc.element.gsap.TimelineLite.prototype.fromTo)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>getChildren (nested, tweens, timelines, ignoreBeforeTime)](#apidoc.element.gsap.TimelineLite.prototype.getChildren)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>getLabelTime (label)](#apidoc.element.gsap.TimelineLite.prototype.getLabelTime)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>getTweensOf (target, nested)](#apidoc.element.gsap.TimelineLite.prototype.getTweensOf)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>gotoAndPlay (position, suppressEvents)](#apidoc.element.gsap.TimelineLite.prototype.gotoAndPlay)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>gotoAndStop (position, suppressEvents)](#apidoc.element.gsap.TimelineLite.prototype.gotoAndStop)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>insert (value, position, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.insert)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>insertMultiple (value, position, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.insertMultiple)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>invalidate ()](#apidoc.element.gsap.TimelineLite.prototype.invalidate)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>paused (value)](#apidoc.element.gsap.TimelineLite.prototype.paused)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>rawTime (wrapRepeats)](#apidoc.element.gsap.TimelineLite.prototype.rawTime)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>recent ()](#apidoc.element.gsap.TimelineLite.prototype.recent)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>remove (value)](#apidoc.element.gsap.TimelineLite.prototype.remove)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>removeLabel (label)](#apidoc.element.gsap.TimelineLite.prototype.removeLabel)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>render (time, suppressEvents, force)](#apidoc.element.gsap.TimelineLite.prototype.render)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>seek (position, suppressEvents)](#apidoc.element.gsap.TimelineLite.prototype.seek)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>set (target, vars, position)](#apidoc.element.gsap.TimelineLite.prototype.set)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>shiftChildren (amount, adjustLabels, ignoreBeforeTime)](#apidoc.element.gsap.TimelineLite.prototype.shiftChildren)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>staggerFrom (targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.TimelineLite.prototype.staggerFrom)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>staggerFromTo (targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.TimelineLite.prototype.staggerFromTo)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>staggerTo (targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.TimelineLite.prototype.staggerTo)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>stop ()](#apidoc.element.gsap.TimelineLite.prototype.stop)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>to (target, duration, vars, position)](#apidoc.element.gsap.TimelineLite.prototype.to)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>totalDuration (value)](#apidoc.element.gsap.TimelineLite.prototype.totalDuration)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>totalTime (time, suppressEvents, uncapped)](#apidoc.element.gsap.TimelineLite.prototype.totalTime)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>usesFrames ()](#apidoc.element.gsap.TimelineLite.prototype.usesFrames)
1.  number <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_delay
1.  number <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_duration
1.  number <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_startTime
1.  number <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_timeScale
1.  number <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_totalDuration
1.  object <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_next
1.  object <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_prev
1.  object <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_timeline
1.  object <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>timeline
1.  object <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>vars

#### [module gsap.TimelineMax](#apidoc.module.gsap.TimelineMax)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TimelineMax (vars)](#apidoc.element.gsap.TimelineMax.TimelineMax)
1.  string <span class="apidocSignatureSpan">gsap.TimelineMax.</span>version

#### [module gsap.TimelineMax.prototype](#apidoc.module.gsap.TimelineMax.prototype)
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_active
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_gc
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_reversed
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_sortChildren
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>autoRemoveChildren
1.  boolean <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>smoothChildTiming
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>addCallback (callback, position, params, scope)](#apidoc.element.gsap.TimelineMax.prototype.addCallback)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>constructor (vars)](#apidoc.element.gsap.TimelineMax.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>currentLabel (value)](#apidoc.element.gsap.TimelineMax.prototype.currentLabel)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getActive (nested, tweens, timelines)](#apidoc.element.gsap.TimelineMax.prototype.getActive)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getLabelAfter (time)](#apidoc.element.gsap.TimelineMax.prototype.getLabelAfter)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getLabelBefore (time)](#apidoc.element.gsap.TimelineMax.prototype.getLabelBefore)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getLabelsArray ()](#apidoc.element.gsap.TimelineMax.prototype.getLabelsArray)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>invalidate ()](#apidoc.element.gsap.TimelineMax.prototype.invalidate)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>progress (value, suppressEvents)](#apidoc.element.gsap.TimelineMax.prototype.progress)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>removeCallback (callback, position)](#apidoc.element.gsap.TimelineMax.prototype.removeCallback)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>removePause (position)](#apidoc.element.gsap.TimelineMax.prototype.removePause)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>render (time, suppressEvents, force)](#apidoc.element.gsap.TimelineMax.prototype.render)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>repeat (value)](#apidoc.element.gsap.TimelineMax.prototype.repeat)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>repeatDelay (value)](#apidoc.element.gsap.TimelineMax.prototype.repeatDelay)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>time (value, suppressEvents)](#apidoc.element.gsap.TimelineMax.prototype.time)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>totalDuration (value)](#apidoc.element.gsap.TimelineMax.prototype.totalDuration)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>totalProgress (value, suppressEvents)](#apidoc.element.gsap.TimelineMax.prototype.totalProgress)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>tweenFromTo (fromPosition, toPosition, vars)](#apidoc.element.gsap.TimelineMax.prototype.tweenFromTo)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>tweenTo (position, vars)](#apidoc.element.gsap.TimelineMax.prototype.tweenTo)
1.  [function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>yoyo (value)](#apidoc.element.gsap.TimelineMax.prototype.yoyo)
1.  number <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_delay
1.  number <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_duration
1.  number <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_startTime
1.  number <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_timeScale
1.  number <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_totalDuration
1.  object <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_labels
1.  object <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_next
1.  object <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_prev
1.  object <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>_timeline
1.  object <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>timeline
1.  object <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>vars

#### [module gsap.TweenLite](#apidoc.module.gsap.TweenLite)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TweenLite (target, duration, vars)](#apidoc.element.gsap.TweenLite.TweenLite)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>_onPluginEvent (type, tween)](#apidoc.element.gsap.TweenLite._onPluginEvent)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>defaultStringFilter (a)](#apidoc.element.gsap.TweenLite.defaultStringFilter)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>delayedCall (delay, callback, params, scope, useFrames)](#apidoc.element.gsap.TweenLite.delayedCall)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>from (target, duration, vars)](#apidoc.element.gsap.TweenLite.from)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>fromTo (target, duration, fromVars, toVars)](#apidoc.element.gsap.TweenLite.fromTo)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>getTweensOf (target, onlyActive)](#apidoc.element.gsap.TweenLite.getTweensOf)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>killDelayedCallsTo (target, onlyActive, vars)](#apidoc.element.gsap.TweenLite.killDelayedCallsTo)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>killTweensOf (target, onlyActive, vars)](#apidoc.element.gsap.TweenLite.killTweensOf)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>lagSmoothing (threshold, adjustedLag)](#apidoc.element.gsap.TweenLite.lagSmoothing)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>render ()](#apidoc.element.gsap.TweenLite.render)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>selector (e)](#apidoc.element.gsap.TweenLite.selector)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>set (target, vars)](#apidoc.element.gsap.TweenLite.set)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.</span>to (target, duration, vars)](#apidoc.element.gsap.TweenLite.to)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite.</span>autoSleep
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.</span>_internals
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.</span>_plugins
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.</span>defaultEase
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.</span>ticker
1.  string <span class="apidocSignatureSpan">gsap.TweenLite.</span>defaultOverwrite
1.  string <span class="apidocSignatureSpan">gsap.TweenLite.</span>version

#### [module gsap.TweenLite._internals](#apidoc.module.gsap.TweenLite._internals)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>blobDif (start, end, filter, pt)](#apidoc.element.gsap.TweenLite._internals.blobDif)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>isArray (obj)](#apidoc.element.gsap.TweenLite._internals.isArray)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>isSelector (v)](#apidoc.element.gsap.TweenLite._internals.isSelector)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>lazyRender ()](#apidoc.element.gsap.TweenLite._internals.lazyRender)
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>lazyTweens
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>reservedProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>tweenLookup

#### [module gsap.TweenLite._plugins](#apidoc.module.gsap.TweenLite._plugins)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>attr ()](#apidoc.element.gsap.TweenLite._plugins.attr)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>bezier ()](#apidoc.element.gsap.TweenLite._plugins.bezier)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>colorProps ()](#apidoc.element.gsap.TweenLite._plugins.colorProps)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>css ()](#apidoc.element.gsap.TweenLite._plugins.css)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>cssRule ()](#apidoc.element.gsap.TweenLite._plugins.cssRule)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>directionalRotation ()](#apidoc.element.gsap.TweenLite._plugins.directionalRotation)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>easel ()](#apidoc.element.gsap.TweenLite._plugins.easel)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>endArray ()](#apidoc.element.gsap.TweenLite._plugins.endArray)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>modifiers ()](#apidoc.element.gsap.TweenLite._plugins.modifiers)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>raphael ()](#apidoc.element.gsap.TweenLite._plugins.raphael)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>roundProps ()](#apidoc.element.gsap.TweenLite._plugins.roundProps)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>text ()](#apidoc.element.gsap.TweenLite._plugins.text)

#### [module gsap.TweenLite._plugins.attr.prototype](#apidoc.module.gsap.TweenLite._plugins.attr.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.attr.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.attr.prototype.constructor)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>_propName

#### [module gsap.TweenLite._plugins.directionalRotation.prototype](#apidoc.module.gsap.TweenLite._plugins.directionalRotation.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>setRatio (ratio)](#apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>_propName

#### [module gsap.TweenLite._plugins.easel.prototype](#apidoc.module.gsap.TweenLite._plugins.easel.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.easel.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.easel.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>setRatio (v)](#apidoc.element.gsap.TweenLite._plugins.easel.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>_propName

#### [module gsap.TweenLite._plugins.endArray.prototype](#apidoc.module.gsap.TweenLite._plugins.endArray.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_mod (lookup)](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype._mod)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>setRatio (ratio)](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_propName

#### [module gsap.TweenLite._plugins.modifiers.prototype](#apidoc.module.gsap.TweenLite._plugins.modifiers.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_add (target, p, s, c, mod)](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._add)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_onInitAllProps ()](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._onInitAllProps)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype.constructor)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_propName

#### [module gsap.TweenLite._plugins.raphael.prototype](#apidoc.module.gsap.TweenLite._plugins.raphael.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_parseTransform (t, v)](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype._parseTransform)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>setRatio (v)](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_propName

#### [module gsap.TweenLite._plugins.roundProps.prototype](#apidoc.module.gsap.TweenLite._plugins.roundProps.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_add (target, p, s, c)](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._add)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_onInitAllProps ()](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._onInitAllProps)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype.constructor)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_propName

#### [module gsap.TweenLite._plugins.text.prototype](#apidoc.module.gsap.TweenLite._plugins.text.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.text.prototype._onInitTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.text.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>setRatio (ratio)](#apidoc.element.gsap.TweenLite._plugins.text.prototype.setRatio)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_priority
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_overwriteProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_super
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_delimiter
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_newClass
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_oldClass
1.  string <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_propName

#### [module gsap.TweenLite.prototype](#apidoc.module.gsap.TweenLite.prototype)
1.  boolean <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_active
1.  boolean <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_gc
1.  boolean <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_lazy
1.  boolean <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_notifyPluginsOfEnabled
1.  boolean <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_reversed
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_enabled (enabled, ignoreTimeline)](#apidoc.element.gsap.TweenLite.prototype._enabled)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_init ()](#apidoc.element.gsap.TweenLite.prototype._init)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_initProps (target, propLookup, siblings, overwrittenProps, index)](#apidoc.element.gsap.TweenLite.prototype._initProps)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_kill (vars, target, overwritingTween)](#apidoc.element.gsap.TweenLite.prototype._kill)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>constructor (target, duration, vars)](#apidoc.element.gsap.TweenLite.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>invalidate ()](#apidoc.element.gsap.TweenLite.prototype.invalidate)
1.  [function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>render (time, suppressEvents, force)](#apidoc.element.gsap.TweenLite.prototype.render)
1.  number <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_delay
1.  number <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_duration
1.  number <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_timeScale
1.  number <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_totalDuration
1.  number <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>ratio
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_ease
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_firstPT
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_overwrittenProps
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_startAt
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_targets
1.  object <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>vars

#### [module gsap.TweenPlugin](#apidoc.module.gsap.TweenPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.</span>TweenPlugin (props, priority)](#apidoc.element.gsap.TweenPlugin.TweenPlugin)
1.  [function <span class="apidocSignatureSpan">gsap.TweenPlugin.</span>activate (plugins)](#apidoc.element.gsap.TweenPlugin.activate)
1.  number <span class="apidocSignatureSpan">gsap.TweenPlugin.</span>API
1.  string <span class="apidocSignatureSpan">gsap.TweenPlugin.</span>version

#### [module gsap.TweenPlugin.prototype](#apidoc.module.gsap.TweenPlugin.prototype)
1.  [function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_addTween (target, prop, start, end, overwriteProp, mod, funcParam, stringFilter, index)](#apidoc.element.gsap.TweenPlugin.prototype._addTween)
1.  [function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.TweenPlugin.prototype._kill)
1.  [function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_mod (lookup)](#apidoc.element.gsap.TweenPlugin.prototype._mod)
1.  [function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_roundProps (lookup)](#apidoc.element.gsap.TweenPlugin.prototype._roundProps)
1.  [function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.TweenPlugin.prototype.setRatio)
1.  object <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_firstPT

#### [module gsap.ticker](#apidoc.module.gsap.ticker)
1.  [function <span class="apidocSignatureSpan">gsap.ticker.</span>fps (value)](#apidoc.element.gsap.ticker.fps)
1.  [function <span class="apidocSignatureSpan">gsap.ticker.</span>lagSmoothing (threshold, adjustedLag)](#apidoc.element.gsap.ticker.lagSmoothing)
1.  [function <span class="apidocSignatureSpan">gsap.ticker.</span>sleep ()](#apidoc.element.gsap.ticker.sleep)
1.  [function <span class="apidocSignatureSpan">gsap.ticker.</span>tick ()](#apidoc.element.gsap.ticker.tick)
1.  [function <span class="apidocSignatureSpan">gsap.ticker.</span>useRAF (value)](#apidoc.element.gsap.ticker.useRAF)
1.  [function <span class="apidocSignatureSpan">gsap.ticker.</span>wake (seamless)](#apidoc.element.gsap.ticker.wake)
1.  number <span class="apidocSignatureSpan">gsap.ticker.</span>frame
1.  number <span class="apidocSignatureSpan">gsap.ticker.</span>time
1.  object <span class="apidocSignatureSpan">gsap.ticker.</span>_eventTarget
1.  object <span class="apidocSignatureSpan">gsap.ticker.</span>_listeners



# <a name="apidoc.module.gsap"></a>[module gsap](#apidoc.module.gsap)

#### <a name="apidoc.element.gsap.BackIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>BackIn (overshoot)](#apidoc.element.gsap.BackIn)
- description and source-code
```javascript
BackIn = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BackInOut (overshoot)](#apidoc.element.gsap.BackInOut)
- description and source-code
```javascript
BackInOut = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BackOut (overshoot)](#apidoc.element.gsap.BackOut)
- description and source-code
```javascript
BackOut = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BezierPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>BezierPlugin ()](#apidoc.element.gsap.BezierPlugin)
- description and source-code
```javascript
BezierPlugin = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BounceIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>BounceIn ()](#apidoc.element.gsap.BounceIn)
- description and source-code
```javascript
BounceIn = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BounceInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BounceInOut ()](#apidoc.element.gsap.BounceInOut)
- description and source-code
```javascript
BounceInOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BounceOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BounceOut ()](#apidoc.element.gsap.BounceOut)
- description and source-code
```javascript
BounceOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>CSSPlugin ()](#apidoc.element.gsap.CSSPlugin)
- description and source-code
```javascript
CSSPlugin = function () {
				TweenPlugin.call(this, "css");
				this._overwriteProps.length = 0;
				this.setRatio = CSSPlugin.prototype.setRatio; //speed optimization (avoid prototype lookup on this "hot" method)
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSRulePlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>CSSRulePlugin ()](#apidoc.element.gsap.CSSRulePlugin)
- description and source-code
```javascript
CSSRulePlugin = function () {
				TweenPlugin.call(this, "cssRule");
				this._overwriteProps.length = 0;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CircIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>CircIn ()](#apidoc.element.gsap.CircIn)
- description and source-code
```javascript
CircIn = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CircInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>CircInOut ()](#apidoc.element.gsap.CircInOut)
- description and source-code
```javascript
CircInOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CircOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>CircOut ()](#apidoc.element.gsap.CircOut)
- description and source-code
```javascript
CircOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ColorPropsPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>ColorPropsPlugin ()](#apidoc.element.gsap.ColorPropsPlugin)
- description and source-code
```javascript
ColorPropsPlugin = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Cubic"></a>[function <span class="apidocSignatureSpan">gsap.</span>Cubic ()](#apidoc.element.gsap.Cubic)
- description and source-code
```javascript
Cubic = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Ease"></a>[function <span class="apidocSignatureSpan">gsap.</span>Ease (func, extraParams, type, power)](#apidoc.element.gsap.Ease)
- description and source-code
```javascript
Ease = function (func, extraParams, type, power) {
				this._func = func;
				this._type = type || 0;
				this._power = power || 0;
				this._params = extraParams ? _baseParams.concat(extraParams) : _baseParams;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>ElasticIn (amplitude, period)](#apidoc.element.gsap.ElasticIn)
- description and source-code
```javascript
ElasticIn = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ElasticInOut (amplitude, period)](#apidoc.element.gsap.ElasticInOut)
- description and source-code
```javascript
ElasticInOut = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ElasticOut (amplitude, period)](#apidoc.element.gsap.ElasticOut)
- description and source-code
```javascript
ElasticOut = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ExpoIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>ExpoIn ()](#apidoc.element.gsap.ExpoIn)
- description and source-code
```javascript
ExpoIn = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ExpoInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ExpoInOut ()](#apidoc.element.gsap.ExpoInOut)
- description and source-code
```javascript
ExpoInOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ExpoOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ExpoOut ()](#apidoc.element.gsap.ExpoOut)
- description and source-code
```javascript
ExpoOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Linear"></a>[function <span class="apidocSignatureSpan">gsap.</span>Linear ()](#apidoc.element.gsap.Linear)
- description and source-code
```javascript
Linear = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Power0"></a>[function <span class="apidocSignatureSpan">gsap.</span>Power0 ()](#apidoc.element.gsap.Power0)
- description and source-code
```javascript
Power0 = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Power1"></a>[function <span class="apidocSignatureSpan">gsap.</span>Power1 ()](#apidoc.element.gsap.Power1)
- description and source-code
```javascript
Power1 = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Power2"></a>[function <span class="apidocSignatureSpan">gsap.</span>Power2 ()](#apidoc.element.gsap.Power2)
- description and source-code
```javascript
Power2 = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Power3"></a>[function <span class="apidocSignatureSpan">gsap.</span>Power3 ()](#apidoc.element.gsap.Power3)
- description and source-code
```javascript
Power3 = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Power4"></a>[function <span class="apidocSignatureSpan">gsap.</span>Power4 ()](#apidoc.element.gsap.Power4)
- description and source-code
```javascript
Power4 = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Quad"></a>[function <span class="apidocSignatureSpan">gsap.</span>Quad ()](#apidoc.element.gsap.Quad)
- description and source-code
```javascript
Quad = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Quart"></a>[function <span class="apidocSignatureSpan">gsap.</span>Quart ()](#apidoc.element.gsap.Quart)
- description and source-code
```javascript
Quart = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Quint"></a>[function <span class="apidocSignatureSpan">gsap.</span>Quint ()](#apidoc.element.gsap.Quint)
- description and source-code
```javascript
Quint = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.RoughEase"></a>[function <span class="apidocSignatureSpan">gsap.</span>RoughEase (vars)](#apidoc.element.gsap.RoughEase)
- description and source-code
```javascript
RoughEase = function (vars) {
			vars = vars || {};
			var taper = vars.taper || "none",
				a = [],
				cnt = 0,
				points = (vars.points || 20) | 0,
				i = points,
				randomize = (vars.randomize !== false),
				clamp = (vars.clamp === true),
				template = (vars.template instanceof Ease) ? vars.template : null,
				strength = (typeof(vars.strength) === "number") ? vars.strength * 0.4 : 0.4,
				x, y, bump, invX, obj, pnt;
			while (--i > -1) {
				x = randomize ? Math.random() : (1 / points) * i;
				y = template ? template.getRatio(x) : x;
				if (taper === "none") {
					bump = strength;
				} else if (taper === "out") {
					invX = 1 - x;
					bump = invX * invX * strength;
				} else if (taper === "in") {
					bump = x * x * strength;
				} else if (x < 0.5) {  //"both" (start)
					invX = x * 2;
					bump = invX * invX * 0.5 * strength;
				} else {				//"both" (end)
					invX = (1 - x) * 2;
					bump = invX * invX * 0.5 * strength;
				}
				if (randomize) {
					y += (Math.random() * bump) - (bump * 0.5);
				} else if (i % 2) {
					y += bump * 0.5;
				} else {
					y -= bump * 0.5;
				}
				if (clamp) {
					if (y > 1) {
						y = 1;
					} else if (y < 0) {
						y = 0;
					}
				}
				a[cnt++] = {x:x, y:y};
			}
			a.sort(function(a, b) {
				return a.x - b.x;
			});

			pnt = new EasePoint(1, 1, null);
			i = points;
			while (--i > -1) {
				obj = a[i];
				pnt = new EasePoint(obj.x, obj.y, pnt);
			}

			this._prev = new EasePoint(0, 0, (pnt.t !== 0) ? pnt : pnt.next);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SineIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>SineIn ()](#apidoc.element.gsap.SineIn)
- description and source-code
```javascript
SineIn = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SineInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>SineInOut ()](#apidoc.element.gsap.SineInOut)
- description and source-code
```javascript
SineInOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SineOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>SineOut ()](#apidoc.element.gsap.SineOut)
- description and source-code
```javascript
SineOut = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SlowMo"></a>[function <span class="apidocSignatureSpan">gsap.</span>SlowMo (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo)
- description and source-code
```javascript
SlowMo = function (linearRatio, power, yoyoMode) {
				power = (power || power === 0) ? power : 0.7;
				if (linearRatio == null) {
					linearRatio = 0.7;
				} else if (linearRatio > 1) {
					linearRatio = 1;
				}
				this._p = (linearRatio !== 1) ? power : 0;
				this._p1 = (1 - linearRatio) / 2;
				this._p2 = linearRatio;
				this._p3 = this._p1 + this._p2;
				this._calcEnd = (yoyoMode === true);
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SteppedEase"></a>[function <span class="apidocSignatureSpan">gsap.</span>SteppedEase (steps)](#apidoc.element.gsap.SteppedEase)
- description and source-code
```javascript
SteppedEase = function (steps) {
				steps = steps || 1;
				this._p1 = 1 / steps;
				this._p2 = steps + 1;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Strong"></a>[function <span class="apidocSignatureSpan">gsap.</span>Strong ()](#apidoc.element.gsap.Strong)
- description and source-code
```javascript
Strong = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite"></a>[function <span class="apidocSignatureSpan">gsap.</span>TimelineLite (vars)](#apidoc.element.gsap.TimelineLite)
- description and source-code
```javascript
TimelineLite = function (vars) {
				SimpleTimeline.call(this, vars);
				this._labels = {};
				this.autoRemoveChildren = (this.vars.autoRemoveChildren === true);
				this.smoothChildTiming = (this.vars.smoothChildTiming === true);
				this._sortChildren = true;
				this._onUpdate = this.vars.onUpdate;
				var v = this.vars,
					val, p;
				for (p in v) {
					val = v[p];
					if (_isArray(val)) if (val.join("").indexOf("{self}") !== -1) {
						v[p] = this._swapSelfInParams(val);
					}
				}
				if (_isArray(v.tweens)) {
					this.add(v.tweens, 0, v.align, v.stagger);
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax"></a>[function <span class="apidocSignatureSpan">gsap.</span>TimelineMax (vars)](#apidoc.element.gsap.TimelineMax)
- description and source-code
```javascript
TimelineMax = function (vars) {
				TimelineLite.call(this, vars);
				this._repeat = this.vars.repeat || 0;
				this._repeatDelay = this.vars.repeatDelay || 0;
				this._cycle = 0;
				this._yoyo = (this.vars.yoyo === true);
				this._dirty = true;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite"></a>[function <span class="apidocSignatureSpan">gsap.</span>TweenLite (target, duration, vars)](#apidoc.element.gsap.TweenLite)
- description and source-code
```javascript
TweenLite = function (target, duration, vars) {
				Animation.call(this, duration, vars);
				this.render = TweenLite.prototype.render; //speed optimization (avoid prototype lookup on this "hot" method)

				if (target == null) {
					throw "Cannot tween a null target.";
				}

				this.target = target = (typeof(target) !== "string") ? target : TweenLite.selector(target) || target;

				var isSelector = (target.jquery || (target.length && target !== window && target[0] && (target[0] === window || (target[0].nodeType
 && target[0].style && !target.nodeType)))),
					overwrite = this.vars.overwrite,
					i, targ, targets;

				this._overwrite = overwrite = (overwrite == null) ? _overwriteLookup[TweenLite.defaultOverwrite] : (typeof(overwrite) === "number
") ? overwrite >> 0 : _overwriteLookup[overwrite];

				if ((isSelector || target instanceof Array || (target.push && _isArray(target))) && typeof(target[0]) !== "number") {
					this._targets = targets = _slice(target);  //don't use Array.prototype.slice.call(target, 0) because that doesn't work in IE8
 with a NodeList that's returned by querySelectorAll()
					this._propLookup = [];
					this._siblings = [];
					for (i = 0; i < targets.length; i++) {
						targ = targets[i];
						if (!targ) {
							targets.splice(i--, 1);
							continue;
						} else if (typeof(targ) === "string") {
							targ = targets[i--] = TweenLite.selector(targ); //in case it's an array of strings
							if (typeof(targ) === "string") {
								targets.splice(i+1, 1); //to avoid an endless loop (can't imagine why the selector would return a string, but just in case
)
							}
							continue;
						} else if (targ.length && targ !== window && targ[0] && (targ[0] === window || (targ[0].nodeType && targ[0].style && !targ
.nodeType))) { //in case the user is passing in an array of selector objects (like jQuery objects), we need to check one more level
 and pull things out if necessary. Also note that <select> elements pass all the criteria regarding length and the first child having
 style, so we must also check to ensure the target isn't an HTML node itself.
							targets.splice(i--, 1);
							this._targets = targets = targets.concat(_slice(targ));
							continue;
						}
						this._siblings[i] = _register(targ, this, false);
						if (overwrite === 1) if (this._siblings[i].length > 1) {
							_applyOverwrite(targ, this, null, 1, this._siblings[i]);
						}
					}

				} else {
					this._propLookup = {};
					this._siblings = _register(target, this, false);
					if (overwrite === 1) if (this._siblings.length > 1) {
						_applyOverwrite(target, this, null, 1, this._siblings);
					}
				}
				if (this.vars.immediateRender || (duration === 0 && this._delay === 0 && this.vars.immediateRender !== false)) {
					this._time = -_tinyNum; //forces a render without having to set the render() "force" parameter to true because we want to allow
 lazying by default (using the "force" parameter always forces an immediate full render)
					this.render(Math.min(0, -this._delay)); //in case delay is negative
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenMax"></a>[function <span class="apidocSignatureSpan">gsap.</span>TweenMax (target, duration, vars)](#apidoc.element.gsap.TweenMax)
- description and source-code
```javascript
TweenMax = function (target, duration, vars) {
				TweenLite.call(this, target, duration, vars);
				this._cycle = 0;
				this._yoyo = (this.vars.yoyo === true);
				this._repeat = this.vars.repeat || 0;
				this._repeatDelay = this.vars.repeatDelay || 0;
				this._dirty = true; //ensures that if there is any repeat, the totalDuration will get recalculated to accurately report it.
				this.render = TweenMax.prototype.render; //speed optimization (avoid prototype lookup on this "hot" method)
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>TweenPlugin (props, priority)](#apidoc.element.gsap.TweenPlugin)
- description and source-code
```javascript
TweenPlugin = function (props, priority) {
					this._overwriteProps = (props || "").split(",");
					this._propName = this._overwriteProps[0];
					this._priority = priority || 0;
					this._super = TweenPlugin.prototype;
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.allFrom"></a>[function <span class="apidocSignatureSpan">gsap.</span>allFrom (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.allFrom)
- description and source-code
```javascript
allFrom = function (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.runBackwards = true;
			vars.immediateRender = (vars.immediateRender != false);
			return TweenMax.staggerTo(targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.allFromTo"></a>[function <span class="apidocSignatureSpan">gsap.</span>allFromTo (targets, duration, fromVars, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.allFromTo)
- description and source-code
```javascript
allFromTo = function (targets, duration, fromVars, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return TweenMax.staggerTo(targets, duration, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.allTo"></a>[function <span class="apidocSignatureSpan">gsap.</span>allTo (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.allTo)
- description and source-code
```javascript
allTo = function (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			stagger = stagger || 0;
			var delay = 0,
				a = [],
				finalComplete = function() {
					if (vars.onComplete) {
						vars.onComplete.apply(vars.onCompleteScope || this, arguments);
					}
					onCompleteAll.apply(onCompleteAllScope || vars.callbackScope || this, onCompleteAllParams || _blankArray);
				},
				cycle = vars.cycle,
				fromCycle = (vars.startAt && vars.startAt.cycle),
				l, copy, i, p;
			if (!_isArray(targets)) {
				if (typeof(targets) === "string") {
					targets = TweenLite.selector(targets) || targets;
				}
				if (_isSelector(targets)) {
					targets = _slice(targets);
				}
			}
			targets = targets || [];
			if (stagger < 0) {
				targets = _slice(targets);
				targets.reverse();
				stagger *= -1;
			}
			l = targets.length - 1;
			for (i = 0; i <= l; i++) {
				copy = {};
				for (p in vars) {
					copy[p] = vars[p];
				}
				if (cycle) {
					_applyCycle(copy, targets, i);
					if (copy.duration != null) {
						duration = copy.duration;
						delete copy.duration;
					}
				}
				if (fromCycle) {
					fromCycle = copy.startAt = {};
					for (p in vars.startAt) {
						fromCycle[p] = vars.startAt[p];
					}
					_applyCycle(copy.startAt, targets, i);
				}
				copy.delay = delay + (copy.delay || 0);
				if (i === l && onCompleteAll) {
					copy.onComplete = finalComplete;
				}
				a[i] = new TweenMax(targets[i], duration, copy);
				delay += stagger;
			}
			return a;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.delayedCall"></a>[function <span class="apidocSignatureSpan">gsap.</span>delayedCall (delay, callback, params, scope, useFrames)](#apidoc.element.gsap.delayedCall)
- description and source-code
```javascript
delayedCall = function (delay, callback, params, scope, useFrames) {
			return new TweenMax(callback, 0, {delay:delay, onComplete:callback, onCompleteParams:params, callbackScope:scope, onReverseComplete
:callback, onReverseCompleteParams:params, immediateRender:false, useFrames:useFrames, overwrite:0});
		}
```
- example usage
```shell
...
		p.staggerFromTo = function(targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope
) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return this.staggerTo(targets, duration, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		};

		p.call = function(callback, params, scope, position) {
			return this.add( TweenLite.delayedCall(0, callback, params, scope), position);
		};

		p.set = function(target, vars, position) {
			position = this._parseTimeOrLabel(position, 0, true);
			if (vars.immediateRender == null) {
				vars.immediateRender = (position === this._time && !this._paused);
			}
...
```

#### <a name="apidoc.element.gsap.from"></a>[function <span class="apidocSignatureSpan">gsap.</span>from (target, duration, vars)](#apidoc.element.gsap.from)
- description and source-code
```javascript
from = function (target, duration, vars) {
			vars.runBackwards = true;
			vars.immediateRender = (vars.immediateRender != false);
			return new TweenMax(target, duration, vars);
		}
```
- example usage
```shell
...

		p.to = function(target, duration, vars, position) {
			var Engine = (vars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( new Engine(target, duration, vars), position) : this.set(target, vars, position);
		};

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
			var Engine = (toVars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( Engine.fromTo(target, duration, fromVars, toVars), position) : this.set(target, toVars, position);
		};
...
```

#### <a name="apidoc.element.gsap.fromTo"></a>[function <span class="apidocSignatureSpan">gsap.</span>fromTo (target, duration, fromVars, toVars)](#apidoc.element.gsap.fromTo)
- description and source-code
```javascript
fromTo = function (target, duration, fromVars, toVars) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return new TweenMax(target, duration, toVars);
		}
```
- example usage
```shell
...

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
			var Engine = (toVars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( Engine.fromTo(target, duration, fromVars, toVars), position) : this.set(target, toVars, position);
		};

		p.staggerTo = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			var tl = new TimelineLite({onComplete:onCompleteAll, onCompleteParams:onCompleteAllParams, callbackScope:onCompleteAllScope,
smoothChildTiming:this.smoothChildTiming}),
				cycle = vars.cycle,
				copy, i;
			if (typeof(targets) === "string") {
...
```

#### <a name="apidoc.element.gsap.getAllTweens"></a>[function <span class="apidocSignatureSpan">gsap.</span>getAllTweens (includeTimelines)](#apidoc.element.gsap.getAllTweens)
- description and source-code
```javascript
getAllTweens = function (includeTimelines) {
				return _getChildrenOf(Animation._rootTimeline, includeTimelines).concat( _getChildrenOf(Animation._rootFramesTimeline, includeTimelines
) );
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.getTweensOf"></a>[function <span class="apidocSignatureSpan">gsap.</span>getTweensOf (target, onlyActive)](#apidoc.element.gsap.getTweensOf)
- description and source-code
```javascript
getTweensOf = function (target, onlyActive) {
			if (target == null) { return []; }
			target = (typeof(target) !== "string") ? target : TweenLite.selector(target) || target;
			var i, a, j, t;
			if ((_isArray(target) || _isSelector(target)) && typeof(target[0]) !== "number") {
				i = target.length;
				a = [];
				while (--i > -1) {
					a = a.concat(TweenLite.getTweensOf(target[i], onlyActive));
				}
				i = a.length;
				//now get rid of any duplicates (tweens of arrays of objects could cause duplicates)
				while (--i > -1) {
					t = a[i];
					j = i;
					while (--j > -1) {
						if (t === a[j]) {
							a.splice(i, 1);
						}
					}
				}
			} else {
				a = _register(target).concat();
				i = a.length;
				while (--i > -1) {
					if (a[i]._gc || (onlyActive && !a[i].isActive())) {
						a.splice(i, 1);
					}
				}
			}
			return a;
		}
```
- example usage
```shell
...
			var disabled = this._gc,
				a = [],
				cnt = 0,
				tweens, i;
			if (disabled) {
				this._enabled(true, true); //getTweensOf() filters out disabled tweens, and we have to mark them as _gc = true when the timeline
 completes in order to allow clean garbage collection, so temporarily re-enable the timeline here.
			}
			tweens = TweenLite.getTweensOf(target);
			i = tweens.length;
			while (--i > -1) {
				if (tweens[i].timeline === this || (nested && this._contains(tweens[i]))) {
					a[cnt++] = tweens[i];
				}
			}
			if (disabled) {
...
```

#### <a name="apidoc.element.gsap.globalTimeScale"></a>[function <span class="apidocSignatureSpan">gsap.</span>globalTimeScale (value)](#apidoc.element.gsap.globalTimeScale)
- description and source-code
```javascript
globalTimeScale = function (value) {
			var tl = Animation._rootTimeline,
				t = TweenLite.ticker.time;
			if (!arguments.length) {
				return tl._timeScale;
			}
			value = value || _tinyNum; //can't allow zero because it'll throw the math off
			tl._startTime = t - ((t - tl._startTime) * tl._timeScale / value);
			tl = Animation._rootFramesTimeline;
			t = TweenLite.ticker.frame;
			tl._startTime = t - ((t - tl._startTime) * tl._timeScale / value);
			tl._timeScale = Animation._rootTimeline._timeScale = value;
			return value;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.isTweening"></a>[function <span class="apidocSignatureSpan">gsap.</span>isTweening (target)](#apidoc.element.gsap.isTweening)
- description and source-code
```javascript
isTweening = function (target) {
			return (TweenLite.getTweensOf(target, true).length > 0);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.killAll"></a>[function <span class="apidocSignatureSpan">gsap.</span>killAll (complete, tweens, delayedCalls, timelines)](#apidoc.element.gsap.killAll)
- description and source-code
```javascript
killAll = function (complete, tweens, delayedCalls, timelines) {
			if (tweens == null) {
				tweens = true;
			}
			if (delayedCalls == null) {
				delayedCalls = true;
			}
			var a = getAllTweens((timelines != false)),
				l = a.length,
				allTrue = (tweens && delayedCalls && timelines),
				isDC, tween, i;
			for (i = 0; i < l; i++) {
				tween = a[i];
				if (allTrue || (tween instanceof SimpleTimeline) || ((isDC = (tween.target === tween.vars.onComplete)) && delayedCalls) || (
tweens && !isDC)) {
					if (complete) {
						tween.totalTime(tween._reversed ? 0 : tween.totalDuration());
					} else {
						tween._enabled(false, false);
					}
				}
			}
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.killChildTweensOf"></a>[function <span class="apidocSignatureSpan">gsap.</span>killChildTweensOf (parent, complete)](#apidoc.element.gsap.killChildTweensOf)
- description and source-code
```javascript
killChildTweensOf = function (parent, complete) {
			if (parent == null) {
				return;
			}
			var tl = TweenLiteInternals.tweenLookup,
				a, curParent, p, i, l;
			if (typeof(parent) === "string") {
				parent = TweenLite.selector(parent) || parent;
			}
			if (_isSelector(parent)) {
				parent = _slice(parent);
			}
			if (_isArray(parent)) {
				i = parent.length;
				while (--i > -1) {
					TweenMax.killChildTweensOf(parent[i], complete);
				}
				return;
			}
			a = [];
			for (p in tl) {
				curParent = tl[p].target.parentNode;
				while (curParent) {
					if (curParent === parent) {
						a = a.concat(tl[p].tweens);
					}
					curParent = curParent.parentNode;
				}
			}
			l = a.length;
			for (i = 0; i < l; i++) {
				if (complete) {
					a[i].totalTime(a[i].totalDuration());
				}
				a[i]._enabled(false, false);
			}
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.killDelayedCallsTo"></a>[function <span class="apidocSignatureSpan">gsap.</span>killDelayedCallsTo (target, onlyActive, vars)](#apidoc.element.gsap.killDelayedCallsTo)
- description and source-code
```javascript
killDelayedCallsTo = function (target, onlyActive, vars) {
			if (typeof(onlyActive) === "object") {
				vars = onlyActive; //for backwards compatibility (before "onlyActive" parameter was inserted)
				onlyActive = false;
			}
			var a = TweenLite.getTweensOf(target, onlyActive),
				i = a.length;
			while (--i > -1) {
				a[i]._kill(vars, target);
			}
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.killTweensOf"></a>[function <span class="apidocSignatureSpan">gsap.</span>killTweensOf (target, onlyActive, vars)](#apidoc.element.gsap.killTweensOf)
- description and source-code
```javascript
killTweensOf = function (target, onlyActive, vars) {
			if (typeof(onlyActive) === "object") {
				vars = onlyActive; //for backwards compatibility (before "onlyActive" parameter was inserted)
				onlyActive = false;
			}
			var a = TweenLite.getTweensOf(target, onlyActive),
				i = a.length;
			while (--i > -1) {
				a[i]._kill(vars, target);
			}
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.lagSmoothing"></a>[function <span class="apidocSignatureSpan">gsap.</span>lagSmoothing (threshold, adjustedLag)](#apidoc.element.gsap.lagSmoothing)
- description and source-code
```javascript
lagSmoothing = function (threshold, adjustedLag) {
			_ticker.lagSmoothing(threshold, adjustedLag);
		}
```
- example usage
```shell
...

		TweenLite.version = "1.19.1";
		TweenLite.defaultEase = p._ease = new Ease(null, null, 1, 1);
		TweenLite.defaultOverwrite = "auto";
		TweenLite.ticker = _ticker;
		TweenLite.autoSleep = 120;
		TweenLite.lagSmoothing = function(threshold, adjustedLag) {
			_ticker.lagSmoothing(threshold, adjustedLag);
		};

		TweenLite.selector = window.$ || window.jQuery || function(e) {
			var selector = window.$ || window.jQuery;
			if (selector) {
				TweenLite.selector = selector;
				return selector(e);
...
```

#### <a name="apidoc.element.gsap.pauseAll"></a>[function <span class="apidocSignatureSpan">gsap.</span>pauseAll (tweens, delayedCalls, timelines)](#apidoc.element.gsap.pauseAll)
- description and source-code
```javascript
pauseAll = function (tweens, delayedCalls, timelines) {
			_changePause(true, tweens, delayedCalls, timelines);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.render"></a>[function <span class="apidocSignatureSpan">gsap.</span>render ()](#apidoc.element.gsap.render)
- description and source-code
```javascript
render = function () {
				var i, a, p;
				if (_lazyTweens.length) { //if code is run outside of the requestAnimationFrame loop, there may be tweens queued AFTER the engine
 refreshed, so we need to ensure any pending renders occur before we refresh again.
					_lazyRender();
				}
				_rootTimeline.render((_ticker.time - _rootTimeline._startTime) * _rootTimeline._timeScale, false, false);
				_rootFramesTimeline.render((_ticker.frame - _rootFramesTimeline._startTime) * _rootFramesTimeline._timeScale, false, false);
				if (_lazyTweens.length) {
					_lazyRender();
				}
				if (_ticker.frame >= _nextGCFrame) { //dump garbage every 120 frames or whatever the user sets TweenLite.autoSleep to
					_nextGCFrame = _ticker.frame + (parseInt(TweenLite.autoSleep, 10) || 120);
					for (p in _tweenLookup) {
						a = _tweenLookup[p].tweens;
						i = a.length;
						while (--i > -1) {
							if (a[i]._gc) {
								a.splice(i, 1);
							}
						}
						if (a.length === 0) {
							delete _tweenLookup[p];
						}
					}
					//if there are no more tweens in the root timelines, or if they're all paused, make the _timer sleep to reduce load on the
CPU slightly
					p = _rootTimeline._first;
					if (!p || p._paused) if (TweenLite.autoSleep && !_rootFramesTimeline._first && _ticker._listeners.tick.length === 1) {
						while (p && p._paused) {
							p = p._next;
						}
						if (!p) {
							_ticker.sleep();
						}
					}
				}
			}
```
- example usage
```shell
...
					if (curTime !== this._time || (this._paused && !prevPaused)) { //in case a tween pauses or seeks the timeline when rendering
, like inside of an onUpdate/onComplete
						break;
					} else if (tween._active || (tween._startTime <= curTime && !tween._paused && !tween._gc)) {
						if (pauseTween === tween) {
							this.pause();
						}
						if (!tween._reversed) {
							tween.render((time - tween._startTime) * tween._timeScale, suppressEvents, force);
						} else {
							tween.render(((!tween._dirty) ? tween._totalDuration : tween.totalDuration()) - ((time - tween._startTime) * tween._timeScale
), suppressEvents, force);
						}
					}
					tween = next;
				}
			} else {
...
```

#### <a name="apidoc.element.gsap.resumeAll"></a>[function <span class="apidocSignatureSpan">gsap.</span>resumeAll (tweens, delayedCalls, timelines)](#apidoc.element.gsap.resumeAll)
- description and source-code
```javascript
resumeAll = function (tweens, delayedCalls, timelines) {
			_changePause(false, tweens, delayedCalls, timelines);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.set"></a>[function <span class="apidocSignatureSpan">gsap.</span>set (target, vars)](#apidoc.element.gsap.set)
- description and source-code
```javascript
set = function (target, vars) {
			return new TweenMax(target, 0, vars);
		}
```
- example usage
```shell
...
			}
			return time * scale;
		}
		*/

		p.to = function(target, duration, vars, position) {
			var Engine = (vars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( new Engine(target, duration, vars), position) : this.set(target, vars, position);
		};

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
...
```

#### <a name="apidoc.element.gsap.staggerFrom"></a>[function <span class="apidocSignatureSpan">gsap.</span>staggerFrom (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.staggerFrom)
- description and source-code
```javascript
staggerFrom = function (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.runBackwards = true;
			vars.immediateRender = (vars.immediateRender != false);
			return TweenMax.staggerTo(targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.staggerFromTo"></a>[function <span class="apidocSignatureSpan">gsap.</span>staggerFromTo (targets, duration, fromVars, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.staggerFromTo)
- description and source-code
```javascript
staggerFromTo = function (targets, duration, fromVars, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return TweenMax.staggerTo(targets, duration, toVars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.staggerTo"></a>[function <span class="apidocSignatureSpan">gsap.</span>staggerTo (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.staggerTo)
- description and source-code
```javascript
staggerTo = function (targets, duration, vars, stagger, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			stagger = stagger || 0;
			var delay = 0,
				a = [],
				finalComplete = function() {
					if (vars.onComplete) {
						vars.onComplete.apply(vars.onCompleteScope || this, arguments);
					}
					onCompleteAll.apply(onCompleteAllScope || vars.callbackScope || this, onCompleteAllParams || _blankArray);
				},
				cycle = vars.cycle,
				fromCycle = (vars.startAt && vars.startAt.cycle),
				l, copy, i, p;
			if (!_isArray(targets)) {
				if (typeof(targets) === "string") {
					targets = TweenLite.selector(targets) || targets;
				}
				if (_isSelector(targets)) {
					targets = _slice(targets);
				}
			}
			targets = targets || [];
			if (stagger < 0) {
				targets = _slice(targets);
				targets.reverse();
				stagger *= -1;
			}
			l = targets.length - 1;
			for (i = 0; i <= l; i++) {
				copy = {};
				for (p in vars) {
					copy[p] = vars[p];
				}
				if (cycle) {
					_applyCycle(copy, targets, i);
					if (copy.duration != null) {
						duration = copy.duration;
						delete copy.duration;
					}
				}
				if (fromCycle) {
					fromCycle = copy.startAt = {};
					for (p in vars.startAt) {
						fromCycle[p] = vars.startAt[p];
					}
					_applyCycle(copy.startAt, targets, i);
				}
				copy.delay = delay + (copy.delay || 0);
				if (i === l && onCompleteAll) {
					copy.onComplete = finalComplete;
				}
				a[i] = new TweenMax(targets[i], duration, copy);
				delay += stagger;
			}
			return a;
		}
```
- example usage
```shell
...
			}
			return this.add(tl, position);
		};

		p.staggerFrom = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.immediateRender = (vars.immediateRender != false);
			vars.runBackwards = true;
			return this.staggerTo(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		};

		p.staggerFromTo = function(targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope
) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return this.staggerTo(targets, duration, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		};
...
```

#### <a name="apidoc.element.gsap.to"></a>[function <span class="apidocSignatureSpan">gsap.</span>to (target, duration, vars)](#apidoc.element.gsap.to)
- description and source-code
```javascript
to = function (target, duration, vars) {
			return new TweenMax(target, duration, vars);
		}
```
- example usage
```shell
...
				if (cycle) {
					_applyCycle(copy, targets, i);
					if (copy.duration != null) {
						duration = copy.duration;
						delete copy.duration;
					}
				}
				tl.to(targets[i], duration, copy, i * stagger);
			}
			return this.add(tl, position);
		};

		p.staggerFrom = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.immediateRender = (vars.immediateRender != false);
			vars.runBackwards = true;
...
```



# <a name="apidoc.module.gsap.BackIn"></a>[module gsap.BackIn](#apidoc.module.gsap.BackIn)

#### <a name="apidoc.element.gsap.BackIn.BackIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>BackIn (overshoot)](#apidoc.element.gsap.BackIn.BackIn)
- description and source-code
```javascript
BackIn = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BackIn.prototype"></a>[module gsap.BackIn.prototype](#apidoc.module.gsap.BackIn.prototype)

#### <a name="apidoc.element.gsap.BackIn.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>config (overshoot)](#apidoc.element.gsap.BackIn.prototype.config)
- description and source-code
```javascript
config = function (overshoot) {
					return new C(overshoot);
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackIn.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>constructor (overshoot)](#apidoc.element.gsap.BackIn.prototype.constructor)
- description and source-code
```javascript
constructor = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackIn.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.BackIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.BackIn.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
					return p * p * ((this._p1 + 1) * p - this._p1);
				}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.BackInOut"></a>[module gsap.BackInOut](#apidoc.module.gsap.BackInOut)

#### <a name="apidoc.element.gsap.BackInOut.BackInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BackInOut (overshoot)](#apidoc.element.gsap.BackInOut.BackInOut)
- description and source-code
```javascript
BackInOut = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BackInOut.prototype"></a>[module gsap.BackInOut.prototype](#apidoc.module.gsap.BackInOut.prototype)

#### <a name="apidoc.element.gsap.BackInOut.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>config (overshoot)](#apidoc.element.gsap.BackInOut.prototype.config)
- description and source-code
```javascript
config = function (overshoot) {
					return new C(overshoot);
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackInOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>constructor (overshoot)](#apidoc.element.gsap.BackInOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackInOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.BackInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BackInOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
					return ((p *= 2) < 1) ? 0.5 * p * p * ((this._p2 + 1) * p - this._p2) : 0.5 * ((p -= 2) * p * ((this._p2 + 1) * p + this._p2
) + 2);
				}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.BackOut"></a>[module gsap.BackOut](#apidoc.module.gsap.BackOut)

#### <a name="apidoc.element.gsap.BackOut.BackOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BackOut (overshoot)](#apidoc.element.gsap.BackOut.BackOut)
- description and source-code
```javascript
BackOut = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BackOut.prototype"></a>[module gsap.BackOut.prototype](#apidoc.module.gsap.BackOut.prototype)

#### <a name="apidoc.element.gsap.BackOut.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>config (overshoot)](#apidoc.element.gsap.BackOut.prototype.config)
- description and source-code
```javascript
config = function (overshoot) {
					return new C(overshoot);
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>constructor (overshoot)](#apidoc.element.gsap.BackOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (overshoot) {
						this._p1 = (overshoot || overshoot === 0) ? overshoot : 1.70158;
						this._p2 = this._p1 * 1.525;
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BackOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.BackOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BackOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
					return ((p = p - 1) * p * ((this._p1 + 1) * p + this._p1) + 1);
				}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.BezierPlugin"></a>[module gsap.BezierPlugin](#apidoc.module.gsap.BezierPlugin)

#### <a name="apidoc.element.gsap.BezierPlugin.BezierPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>BezierPlugin ()](#apidoc.element.gsap.BezierPlugin.BezierPlugin)
- description and source-code
```javascript
BezierPlugin = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BezierPlugin._cssRegister"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>_cssRegister ()](#apidoc.element.gsap.BezierPlugin._cssRegister)
- description and source-code
```javascript
_cssRegister = function () {
			var CSSPlugin = _globals.CSSPlugin;
			if (!CSSPlugin) {
				return;
			}
			var _internals = CSSPlugin._internals,
				_parseToProxy = _internals._parseToProxy,
				_setPluginRatio = _internals._setPluginRatio,
				CSSPropTween = _internals.CSSPropTween;
			_internals._registerComplexSpecialProp("bezier", {parser:function(t, e, prop, cssp, pt, plugin) {
				if (e instanceof Array) {
					e = {values:e};
				}
				plugin = new BezierPlugin();
				var values = e.values,
					l = values.length - 1,
					pluginValues = [],
					v = {},
					i, p, data;
				if (l < 0) {
					return pt;
				}
				for (i = 0; i <= l; i++) {
					data = _parseToProxy(t, values[i], cssp, pt, plugin, (l !== i));
					pluginValues[i] = data.end;
				}
				for (p in e) {
					v[p] = e[p]; //duplicate the vars object because we need to alter some things which would cause problems if the user plans
to reuse the same vars object for another tween.
				}
				v.values = pluginValues;
				pt = new CSSPropTween(t, "bezier", 0, 0, data.pt, 2);
				pt.data = data;
				pt.plugin = plugin;
				pt.setRatio = _setPluginRatio;
				if (v.autoRotate === 0) {
					v.autoRotate = true;
				}
				if (v.autoRotate && !(v.autoRotate instanceof Array)) {
					i = (v.autoRotate === true) ? 0 : Number(v.autoRotate);
					v.autoRotate = (data.end.left != null) ? [["left","top","rotation",i,false]] : (data.end.x != null) ? [["x","y","rotation",
i,false]] : false;
				}
				if (v.autoRotate) {
					if (!cssp._transform) {
						cssp._enableTransforms(false);
					}
					data.autoRotate = cssp._target._gsTransform;
					data.proxy.rotation = data.autoRotate.rotation || 0;
					cssp._overwriteProps.push("rotation");
				}
				plugin._onInitTween(data.proxy, v, cssp._tween);
				return pt;
			}});
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BezierPlugin.bezierThrough"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>bezierThrough (values, curviness, quadratic, basic, correlate, prepend)](#apidoc.element.gsap.BezierPlugin.bezierThrough)
- description and source-code
```javascript
bezierThrough = function (values, curviness, quadratic, basic, correlate, prepend) {
				var obj = {},
					props = [],
					first = prepend || values[0],
					i, p, a, j, r, l, seamless, last;
				correlate = (typeof(correlate) === "string") ? ","+correlate+"," : _correlate;
				if (curviness == null) {
					curviness = 1;
				}
				for (p in values[0]) {
					props.push(p);
				}
				//check to see if the last and first values are identical (well, within 0.05). If so, make seamless by appending the second
element to the very end of the values array and the 2nd-to-last element to the very beginning (we'll remove those segments later
)
				if (values.length > 1) {
					last = values[values.length - 1];
					seamless = true;
					i = props.length;
					while (--i > -1) {
						p = props[i];
						if (Math.abs(first[p] - last[p]) > 0.05) { //build in a tolerance of +/-0.05 to accommodate rounding errors.
							seamless = false;
							break;
						}
					}
					if (seamless) {
						values = values.concat(); //duplicate the array to avoid contaminating the original which the user may be reusing for other
 tweens
						if (prepend) {
							values.unshift(prepend);
						}
						values.push(values[1]);
						prepend = values[values.length - 3];
					}
				}
				_r1.length = _r2.length = _r3.length = 0;
				i = props.length;
				while (--i > -1) {
					p = props[i];
					_corProps[p] = (correlate.indexOf(","+p+",") !== -1);
					obj[p] = _parseAnchors(values, p, _corProps[p], prepend);
				}
				i = _r1.length;
				while (--i > -1) {
					_r1[i] = Math.sqrt(_r1[i]);
					_r2[i] = Math.sqrt(_r2[i]);
				}
				if (!basic) {
					i = props.length;
					while (--i > -1) {
						if (_corProps[p]) {
							a = obj[props[i]];
							l = a.length - 1;
							for (j = 0; j < l; j++) {
								r = (a[j+1].da / _r2[j] + a[j].da / _r1[j]) || 0;
								_r3[j] = (_r3[j] || 0) + r * r;
							}
						}
					}
					i = _r3.length;
					while (--i > -1) {
						_r3[i] = Math.sqrt(_r3[i]);
					}
				}
				i = props.length;
				j = quadratic ? 4 : 1;
				while (--i > -1) {
					p = props[i];
					a = obj[p];
					_calculateControlPoints(a, curviness, quadratic, basic, _corProps[p]); //this method requires that _parseAnchors() and _setSegmentRatios
() ran first so that _r1, _r2, and _r3 values are populated for all properties
					if (seamless) {
						a.splice(0, j);
						a.splice(a.length - j, j);
					}
				}
				return obj;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BezierPlugin.cubicToQuadratic"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>cubicToQuadratic (a, b, c, d)](#apidoc.element.gsap.BezierPlugin.cubicToQuadratic)
- description and source-code
```javascript
cubicToQuadratic = function (a, b, c, d) {
				var q1 = {a:a},
					q2 = {},
					q3 = {},
					q4 = {c:d},
					mab = (a + b) / 2,
					mbc = (b + c) / 2,
					mcd = (c + d) / 2,
					mabc = (mab + mbc) / 2,
					mbcd = (mbc + mcd) / 2,
					m8 = (mbcd - mabc) / 8;
				q1.b = mab + (a - mab) / 4;
				q2.b = mabc + m8;
				q1.c = q2.a = (q1.b + q2.b) / 2;
				q2.c = q3.a = (mabc + mbcd) / 2;
				q3.b = mbcd - m8;
				q4.b = mcd + (d - mcd) / 4;
				q3.c = q4.a = (q3.b + q4.b) / 2;
				return [q1, q2, q3, q4];
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BezierPlugin.quadraticToCubic"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.</span>quadraticToCubic (a, b, c)](#apidoc.element.gsap.BezierPlugin.quadraticToCubic)
- description and source-code
```javascript
quadraticToCubic = function (a, b, c) {
			return new Segment(a, (2 * b + a) / 3, (2 * b + c) / 3, c);
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BezierPlugin.prototype"></a>[module gsap.BezierPlugin.prototype](#apidoc.module.gsap.BezierPlugin.prototype)

#### <a name="apidoc.element.gsap.BezierPlugin.prototype._kill"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.BezierPlugin.prototype._kill)
- description and source-code
```javascript
_kill = function (lookup) {
			var a = this._props,
				p, i;
			for (p in this._beziers) {
				if (p in lookup) {
					delete this._beziers[p];
					delete this._func[p];
					i = a.length;
					while (--i > -1) {
						if (a[i] === p) {
							a.splice(i, 1);
						}
					}
				}
			}
			a = this._autoRotate;
			if (a) {
				i = a.length;
				while (--i > -1) {
					if (lookup[a[i][2]]) {
						a.splice(i, 1);
					}
				}
			}
			return this._super._kill.call(this, lookup);
		}
```
- example usage
```shell
...
			if (!vars && !target) {
				return this._enabled(false, false);
			}
			var tweens = (!target) ? this.getChildren(true, true, false) : this.getTweensOf(target),
				i = tweens.length,
				changed = false;
			while (--i > -1) {
				if (tweens[i]._kill(vars, target)) {
					changed = true;
				}
			}
			return changed;
		};

		p.clear = function(labels) {
...
```

#### <a name="apidoc.element.gsap.BezierPlugin.prototype._mod"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_mod (lookup)](#apidoc.element.gsap.BezierPlugin.prototype._mod)
- description and source-code
```javascript
_mod = function (lookup) {
			var op = this._overwriteProps,
				i = op.length,
				val;
			while (--i > -1) {
				val = lookup[op[i]];
				if (val && typeof(val) === "function") {
					this._mod[op[i]] = val;
				}
			}
		}
```
- example usage
```shell
...
			i = rp.length;
			while (--i > -1) {
				prop = rp[i];
				pt = tween._firstPT;
				while (pt) {
					next = pt._next; //record here, because it may get removed
					if (pt.pg) {
						pt.t._mod(lookup);
					} else if (pt.n === prop) {
						if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
							_roundLinkedList(pt.t._firstPT);
						} else {
							this._add(pt.t, prop, pt.s, pt.c);
							//remove from linked list
							if (next) {
...
```

#### <a name="apidoc.element.gsap.BezierPlugin.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>_onInitTween (target, vars, tween)](#apidoc.element.gsap.BezierPlugin.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, vars, tween) {
						this._target = target;
						if (vars instanceof Array) {
							vars = {values:vars};
						}
						this._func = {};
						this._mod = {};
						this._props = [];
						this._timeRes = (vars.timeResolution == null) ? 6 : parseInt(vars.timeResolution, 10);
						var values = vars.values || [],
							first = {},
							second = values[0],
							autoRotate = vars.autoRotate || tween.vars.orientToBezier,
							p, isFunc, i, j, prepend;

						this._autoRotate = autoRotate ? (autoRotate instanceof Array) ? autoRotate : [["x","y","rotation",((autoRotate === true) ?
0 : Number(autoRotate) || 0)]] : null;
						for (p in second) {
							this._props.push(p);
						}

						i = this._props.length;
						while (--i > -1) {
							p = this._props[i];

							this._overwriteProps.push(p);
							isFunc = this._func[p] = (typeof(target[p]) === "function");
							first[p] = (!isFunc) ? parseFloat(target[p]) : target[ ((p.indexOf("set") || typeof(target["get" + p.substr(3)]) !== "function
") ? p : "get" + p.substr(3)) ]();
							if (!prepend) if (first[p] !== values[0][p]) {
								prepend = first;
							}
						}
						this._beziers = (vars.type !== "cubic" && vars.type !== "quadratic" && vars.type !== "soft") ? bezierThrough(values, isNaN
(vars.curviness) ? 1 : vars.curviness, false, (vars.type === "thruBasic"), vars.correlate, prepend) : _parseBezierData(values, vars
.type, first);
						this._segCount = this._beziers[p].length;

						if (this._timeRes) {
							var ld = _parseLengthData(this._beziers, this._timeRes);
							this._length = ld.length;
							this._lengths = ld.lengths;
							this._segments = ld.segments;
							this._l1 = this._li = this._s1 = this._si = 0;
							this._l2 = this._lengths[0];
							this._curSeg = this._segments[0];
							this._s2 = this._curSeg[0];
							this._prec = 1 / this._curSeg.length;
						}

						if ((autoRotate = this._autoRotate)) {
							this._initialRotations = [];
							if (!(autoRotate[0] instanceof Array)) {
								this._autoRotate = autoRotate = [autoRotate];
							}
							i = autoRotate.length;
							while (--i > -1) {
								for (j = 0; j < 3; j++) {
									p = autoRotate[i][j];
									this._func[p] = (typeof(target[p]) === "function") ? target[ ((p.indexOf("set") || typeof(target["get" + p.substr(3)]) !== "
function") ? p : "get" + p.substr(3)) ] : false;
								}
								p = autoRotate[i][2];
								this._initialRotations[i] = (this._func[p] ? this._func[p].call(this._target) : this._target[p]) || 0;
								this._overwriteProps.push(p);
							}
						}
						this._startRatio = tween.vars.runBackwards ? 1 : 0; //we determine the starting ratio when the tween inits which is always
 0 unless the tween has runBackwards:true (indicating it's a from() tween) in which case it's 1.
						return true;
					}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.BezierPlugin.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>constructor ()](#apidoc.element.gsap.BezierPlugin.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BezierPlugin.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.BezierPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.BezierPlugin.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (v) {
						var segments = this._segCount,
							func = this._func,
							target = this._target,
							notStart = (v !== this._startRatio),
							curIndex, inv, i, p, b, t, val, l, lengths, curSeg;
						if (!this._timeRes) {
							curIndex = (v < 0) ? 0 : (v >= 1) ? segments - 1 : (segments * v) >> 0;
							t = (v - (curIndex * (1 / segments))) * segments;
						} else {
							lengths = this._lengths;
							curSeg = this._curSeg;
							v *= this._length;
							i = this._li;
							//find the appropriate segment (if the currently cached one isn't correct)
							if (v > this._l2 && i < segments - 1) {
								l = segments - 1;
								while (i < l && (this._l2 = lengths[++i]) <= v) {	}
								this._l1 = lengths[i-1];
								this._li = i;
								this._curSeg = curSeg = this._segments[i];
								this._s2 = curSeg[(this._s1 = this._si = 0)];
							} else if (v < this._l1 && i > 0) {
								while (i > 0 && (this._l1 = lengths[--i]) >= v) { }
								if (i === 0 && v < this._l1) {
									this._l1 = 0;
								} else {
									i++;
								}
								this._l2 = lengths[i];
								this._li = i;
								this._curSeg = curSeg = this._segments[i];
								this._s1 = curSeg[(this._si = curSeg.length - 1) - 1] || 0;
								this._s2 = curSeg[this._si];
							}
							curIndex = i;
							//now find the appropriate sub-segment (we split it into the number of pieces that was defined by "precision" and measured
 each one)
							v -= this._l1;
							i = this._si;
							if (v > this._s2 && i < curSeg.length - 1) {
								l = curSeg.length - 1;
								while (i < l && (this._s2 = curSeg[++i]) <= v) {	}
								this._s1 = curSeg[i-1];
								this._si = i;
							} else if (v < this._s1 && i > 0) {
								while (i > 0 && (this._s1 = curSeg[--i]) >= v) {	}
								if (i === 0 && v < this._s1) {
									this._s1 = 0;
								} else {
									i++;
								}
								this._s2 = curSeg[i];
								this._si = i;
							}
							t = ((i + (v - this._s1) / (this._s2 - this._s1)) * this._prec) || 0;
						}
						inv = 1 - t;

						i = this._props.length;
						while (--i > -1) {
							p = this._props[i];
							b = this._beziers[p][curIndex];
							val = (t * t * b.da + 3 * inv * (t * b.ca + inv * b.ba)) * t + b.a;
							if (this._mod[p]) {
								val = this._mod[p](val, target);
							}
							if (func[p]) {
								target[p](val);
							} else {
								target[p] = val;
							}
						}

						if (this._autoRotate) {
							var ar = this._autoRotate,
								b2, x1, y1, x2, y2, add, conv;
							i = ar.length;
							while (--i > -1) {
								p = ar[i][2];
								add = ar[i][3] || 0;
								conv = (ar[i][4] === true) ? 1 : _RAD2DEG;
								b = this._beziers[ar[i][0]];
								b2 = this._beziers[ar[i][1]];

								if (b && b2) { //in case one of the properties got overwritten.
									b = b[curIndex];
									b2 = b2[curIndex];

									x1 = b.a + (b.b - b.a) * t;
									x2 = b.b + (b.c - b.b) * t;
									x1 += (x2 - x1) * t;
									x2 += ((b.c + (b.d - b.c) * t) - x2) * t;

									y1 = b2.a + (b2.b - b2.a) * t;
									y2 = b2.b + (b2.c - b2.b) * t;
									y1 += (y2 - y1) * t;
									y2 += ((b2.c + (b2.d - b2.c) * t) - y2) * t;

									val = notStart ? Math.atan2(y2 - y1, x2 - x1) * conv + add : this._initialRotations[i];

									if (this._mod[p]) {
										val = this._mod[p](val, target); //for modProps
									}

									if (func[p]) {
										target[p](val);
									} else {
										target[p] = val;
									}
								}
							}
						}
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BounceIn"></a>[module gsap.BounceIn](#apidoc.module.gsap.BounceIn)

#### <a name="apidoc.element.gsap.BounceIn.BounceIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>BounceIn ()](#apidoc.element.gsap.BounceIn.BounceIn)
- description and source-code
```javascript
BounceIn = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BounceIn.prototype"></a>[module gsap.BounceIn.prototype](#apidoc.module.gsap.BounceIn.prototype)

#### <a name="apidoc.element.gsap.BounceIn.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.BounceIn.prototype.</span>constructor ()](#apidoc.element.gsap.BounceIn.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BounceIn.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.BounceIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.BounceIn.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				if ((p = 1 - p) < 1 / 2.75) {
					return 1 - (7.5625 * p * p);
				} else if (p < 2 / 2.75) {
					return 1 - (7.5625 * (p -= 1.5 / 2.75) * p + 0.75);
				} else if (p < 2.5 / 2.75) {
					return 1 - (7.5625 * (p -= 2.25 / 2.75) * p + 0.9375);
				}
				return 1 - (7.5625 * (p -= 2.625 / 2.75) * p + 0.984375);
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.BounceInOut"></a>[module gsap.BounceInOut](#apidoc.module.gsap.BounceInOut)

#### <a name="apidoc.element.gsap.BounceInOut.BounceInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BounceInOut ()](#apidoc.element.gsap.BounceInOut.BounceInOut)
- description and source-code
```javascript
BounceInOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BounceInOut.prototype"></a>[module gsap.BounceInOut.prototype](#apidoc.module.gsap.BounceInOut.prototype)

#### <a name="apidoc.element.gsap.BounceInOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.BounceInOut.prototype.</span>constructor ()](#apidoc.element.gsap.BounceInOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BounceInOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.BounceInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BounceInOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				var invert = (p < 0.5);
				if (invert) {
					p = 1 - (p * 2);
				} else {
					p = (p * 2) - 1;
				}
				if (p < 1 / 2.75) {
					p = 7.5625 * p * p;
				} else if (p < 2 / 2.75) {
					p = 7.5625 * (p -= 1.5 / 2.75) * p + 0.75;
				} else if (p < 2.5 / 2.75) {
					p = 7.5625 * (p -= 2.25 / 2.75) * p + 0.9375;
				} else {
					p = 7.5625 * (p -= 2.625 / 2.75) * p + 0.984375;
				}
				return invert ? (1 - p) * 0.5 : p * 0.5 + 0.5;
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.BounceOut"></a>[module gsap.BounceOut](#apidoc.module.gsap.BounceOut)

#### <a name="apidoc.element.gsap.BounceOut.BounceOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>BounceOut ()](#apidoc.element.gsap.BounceOut.BounceOut)
- description and source-code
```javascript
BounceOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.BounceOut.prototype"></a>[module gsap.BounceOut.prototype](#apidoc.module.gsap.BounceOut.prototype)

#### <a name="apidoc.element.gsap.BounceOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.BounceOut.prototype.</span>constructor ()](#apidoc.element.gsap.BounceOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.BounceOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.BounceOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.BounceOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				if (p < 1 / 2.75) {
					return 7.5625 * p * p;
				} else if (p < 2 / 2.75) {
					return 7.5625 * (p -= 1.5 / 2.75) * p + 0.75;
				} else if (p < 2.5 / 2.75) {
					return 7.5625 * (p -= 2.25 / 2.75) * p + 0.9375;
				}
				return 7.5625 * (p -= 2.625 / 2.75) * p + 0.984375;
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.CSSPlugin"></a>[module gsap.CSSPlugin](#apidoc.module.gsap.CSSPlugin)

#### <a name="apidoc.element.gsap.CSSPlugin.CSSPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>CSSPlugin ()](#apidoc.element.gsap.CSSPlugin.CSSPlugin)
- description and source-code
```javascript
CSSPlugin = function () {
				TweenPlugin.call(this, "css");
				this._overwriteProps.length = 0;
				this.setRatio = CSSPlugin.prototype.setRatio; //speed optimization (avoid prototype lookup on this "hot" method)
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.cascadeTo"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>cascadeTo (target, duration, vars)](#apidoc.element.gsap.CSSPlugin.cascadeTo)
- description and source-code
```javascript
cascadeTo = function (target, duration, vars) {
			var tween = TweenLite.to(target, duration, vars),
				results = [tween],
				b = [],
				e = [],
				targets = [],
				_reservedProps = TweenLite._internals.reservedProps,
				i, difs, p, from;
			target = tween._targets || tween.target;
			_getChildStyles(target, b, targets);
			tween.render(duration, true, true);
			_getChildStyles(target, e);
			tween.render(0, true, true);
			tween._enabled(true);
			i = targets.length;
			while (--i > -1) {
				difs = _cssDif(targets[i], b[i], e[i]);
				if (difs.firstMPT) {
					difs = difs.difs;
					for (p in vars) {
						if (_reservedProps[p]) {
							difs[p] = vars[p];
						}
					}
					from = {};
					for (p in difs) {
						from[p] = b[i][p];
					}
					results.push(TweenLite.fromTo(targets[i], duration, from, difs));
				}
			}
			return results;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.colorStringFilter"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>colorStringFilter (a)](#apidoc.element.gsap.CSSPlugin.colorStringFilter)
- description and source-code
```javascript
colorStringFilter = function (a) {
			var combined = a[0] + a[1],
				toHSL;
			if (_colorExp.test(combined)) {
				toHSL = (combined.indexOf("hsl(") !== -1 || combined.indexOf("hsla(") !== -1);
				a[0] = _formatColors(a[0], toHSL);
				a[1] = _formatColors(a[1], toHSL);
			}
			_colorExp.lastIndex = 0;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.getStyle"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>getStyle (t, p, cs, calc, dflt)](#apidoc.element.gsap.CSSPlugin.getStyle)
- description and source-code
```javascript
getStyle = function (t, p, cs, calc, dflt) {
				var rv;
				if (!_supportsOpacity) if (p === "opacity") { //several versions of IE don't use the standard "opacity" property - they use
things like filter:alpha(opacity=50), so we parse that here.
					return _getIEOpacity(t);
				}
				if (!calc && t.style[p]) {
					rv = t.style[p];
				} else if ((cs = cs || _getComputedStyle(t))) {
					rv = cs[p] || cs.getPropertyValue(p) || cs.getPropertyValue(p.replace(_capsExp, "-$1").toLowerCase());
				} else if (t.currentStyle) {
					rv = t.currentStyle[p];
				}
				return (dflt != null && (!rv || rv === "none" || rv === "auto" || rv === "auto auto")) ? dflt : rv;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.parseColor"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>parseColor (v, toHSL)](#apidoc.element.gsap.CSSPlugin.parseColor)
- description and source-code
```javascript
parseColor = function (v, toHSL) {
				var a, r, g, b, h, s, l, max, min, d, wasHSL;
				if (!v) {
					a = _colorLookup.black;
				} else if (typeof(v) === "number") {
					a = [v >> 16, (v >> 8) & 255, v & 255];
				} else {
					if (v.charAt(v.length - 1) === ",") { //sometimes a trailing comma is included and we should chop it off (typically from a
comma-delimited list of values like a textShadow:"2px 2px 2px blue, 5px 5px 5px rgb(255,0,0)" - in this example "blue," has a trailing
 comma. We could strip it out inside parseComplex() but we'd need to do it to the beginning and ending values plus it wouldn't provide
 protection from other potential scenarios like if the user passes in a similar value.
						v = v.substr(0, v.length - 1);
					}
					if (_colorLookup[v]) {
						a = _colorLookup[v];
					} else if (v.charAt(0) === "#") {
						if (v.length === 4) { //for shorthand like #9F0
							r = v.charAt(1);
							g = v.charAt(2);
							b = v.charAt(3);
							v = "#" + r + r + g + g + b + b;
						}
						v = parseInt(v.substr(1), 16);
						a = [v >> 16, (v >> 8) & 255, v & 255];
					} else if (v.substr(0, 3) === "hsl") {
						a = wasHSL = v.match(_numExp);
						if (!toHSL) {
							h = (Number(a[0]) % 360) / 360;
							s = Number(a[1]) / 100;
							l = Number(a[2]) / 100;
							g = (l <= 0.5) ? l * (s + 1) : l + s - l * s;
							r = l * 2 - g;
							if (a.length > 3) {
								a[3] = Number(v[3]);
							}
							a[0] = _hue(h + 1 / 3, r, g);
							a[1] = _hue(h, r, g);
							a[2] = _hue(h - 1 / 3, r, g);
						} else if (v.indexOf("=") !== -1) { //if relative values are found, just return the raw strings with the relative prefixes
 in place.
							return v.match(_relNumExp);
						}
					} else {
						a = v.match(_numExp) || _colorLookup.transparent;
					}
					a[0] = Number(a[0]);
					a[1] = Number(a[1]);
					a[2] = Number(a[2]);
					if (a.length > 3) {
						a[3] = Number(a[3]);
					}
				}
				if (toHSL && !wasHSL) {
					r = a[0] / 255;
					g = a[1] / 255;
					b = a[2] / 255;
					max = Math.max(r, g, b);
					min = Math.min(r, g, b);
					l = (max + min) / 2;
					if (max === min) {
						h = s = 0;
					} else {
						d = max - min;
						s = l > 0.5 ? d / (2 - max - min) : d / (max + min);
						h = (max === r) ? (g - b) / d + (g < b ? 6 : 0) : (max === g) ? (b - r) / d + 2 : (r - g) / d + 4;
						h *= 60;
					}
					a[0] = (h + 0.5) | 0;
					a[1] = (s * 100 + 0.5) | 0;
					a[2] = (l * 100 + 0.5) | 0;
				}
				return a;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.parseComplex"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>parseComplex (t, p, b, e, clrs, dflt, pt, pr, plugin, setRatio)](#apidoc.element.gsap.CSSPlugin.parseComplex)
- description and source-code
```javascript
parseComplex = function (t, p, b, e, clrs, dflt, pt, pr, plugin, setRatio) {
				//DEBUG: _log("parseComplex: "+p+", b: "+b+", e: "+e);
				b = b || dflt || "";
				if (typeof(e) === "function") {
					e = e(_index, _target);
				}
				pt = new CSSPropTween(t, p, 0, 0, pt, (setRatio ? 2 : 1), null, false, pr, b, e);
				e += ""; //ensures it's a string
				if (clrs && _colorExp.test(e + b)) { //if colors are found, normalize the formatting to rgba() or hsla().
					e = [b, e];
					CSSPlugin.colorStringFilter(e);
					b = e[0];
					e = e[1];
				}
				var ba = b.split(", ").join(",").split(" "), //beginning array
					ea = e.split(", ").join(",").split(" "), //ending array
					l = ba.length,
					autoRound = (_autoRound !== false),
					i, xi, ni, bv, ev, bnums, enums, bn, hasAlpha, temp, cv, str, useHSL;
				if (e.indexOf(",") !== -1 || b.indexOf(",") !== -1) {
					ba = ba.join(" ").replace(_commasOutsideParenExp, ", ").split(" ");
					ea = ea.join(" ").replace(_commasOutsideParenExp, ", ").split(" ");
					l = ba.length;
				}
				if (l !== ea.length) {
					//DEBUG: _log("mismatched formatting detected on " + p + " (" + b + " vs " + e + ")");
					ba = (dflt || "").split(" ");
					l = ba.length;
				}
				pt.plugin = plugin;
				pt.setRatio = setRatio;
				_colorExp.lastIndex = 0;
				for (i = 0; i < l; i++) {
					bv = ba[i];
					ev = ea[i];
					bn = parseFloat(bv);
					//if the value begins with a number (most common). It's fine if it has a suffix like px
					if (bn || bn === 0) {
						pt.appendXtra("", bn, _parseChange(ev, bn), ev.replace(_relNumExp, ""), (autoRound && ev.indexOf("px") !== -1), true);

					//if the value is a color
					} else if (clrs && _colorExp.test(bv)) {
						str = ev.indexOf(")") + 1;
						str = ")" + (str ? ev.substr(str) : ""); //if there's a comma or ) at the end, retain it.
						useHSL = (ev.indexOf("hsl") !== -1 && _supportsOpacity);
						bv = _parseColor(bv, useHSL);
						ev = _parseColor(ev, useHSL);
						hasAlpha = (bv.length + ev.length > 6);
						if (hasAlpha && !_supportsOpacity && ev[3] === 0) { //older versions of IE don't support rgba(), so if the destination alpha
 is 0, just use "transparent" for the end color
							pt["xs" + pt.l] += pt.l ? " transparent" : "transparent";
							pt.e = pt.e.split(ea[i]).join("transparent");
						} else {
							if (!_supportsOpacity) { //old versions of IE don't support rgba().
								hasAlpha = false;
							}
							if (useHSL) {
								pt.appendXtra((hasAlpha ? "hsla(" : "hsl("), bv[0], _parseChange(ev[0], bv[0]), ",", false, true)
									.appendXtra("", bv[1], _parseChange(ev[1], bv[1]), "%,", false)
									.appendXtra("", bv[2], _parseChange(ev[2], bv[2]), (hasAlpha ? "%," : "%" + str), false);
							} else {
								pt.appendXtra((hasAlpha ? "rgba(" : "rgb("), bv[0], ev[0] - bv[0], ",", true, true)
									.appendXtra("", bv[1], ev[1] - bv[1], ",", true)
									.appendXtra("", bv[2], ev[2] - bv[2], (hasAlpha ? "," : str), true);
							}

							if (hasAlpha) {
								bv = (bv.length < 4) ? 1 : bv[3];
								pt.appendXtra("", bv, ((ev.length < 4) ? 1 : ev[3]) - bv, str, false);
							}
						}
						_colorExp.lastIndex = 0; //otherwise the test() on the RegExp could move the lastIndex and taint future results.

					} else {
						bnums = bv.match(_numExp); //gets each group of numbers in the beginning value string and drops them into an array

						//if no number is found, treat it as a non-tweening value and just append the string to the current xs.
						if (!bnums) {
							pt["xs" + pt.l] += (pt.l || pt["xs" + pt.l]) ? " " + ev : ev;

						//loop through all the numbers that are found and construct the extra values on the pt.
						} else {
							enums = ev.match(_relNumExp); //get each group of numbers in the end value string and drop them into an array. We allow relative
 values too, like +=50 or -=.5
							if (!enums || enums.length !== bnums.length) {
								//DEBUG: _log("mismatched formatting detected on " + p + " (" + b + " vs " + e + ")");
								return pt;
							}
							ni = 0;
							for (xi = 0 ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.registerSpecialProp"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.</span>registerSpecialProp (name, onInitTween, priority)](#apidoc.element.gsap.CSSPlugin.registerSpecialProp)
- description and source-code
```javascript
registerSpecialProp = function (name, onInitTween, priority) {
			_registerComplexSpecialProp(name, {parser:function(t, e, p, cssp, pt, plugin, vars) {
				var rv = new CSSPropTween(t, p, 0, 0, pt, 2, p, false, priority);
				rv.plugin = plugin;
				rv.setRatio = onInitTween(t, e, cssp._tween, p);
				return rv;
			}, priority:priority});
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CSSPlugin._internals"></a>[module gsap.CSSPlugin._internals](#apidoc.module.gsap.CSSPlugin._internals)

#### <a name="apidoc.element.gsap.CSSPlugin._internals.CSSPropTween"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>CSSPropTween (t, p, s, c, next, type, n, r, pr, b, e)](#apidoc.element.gsap.CSSPlugin._internals.CSSPropTween)
- description and source-code
```javascript
CSSPropTween = function (t, p, s, c, next, type, n, r, pr, b, e) {
				this.t = t; //target
				this.p = p; //property
				this.s = s; //starting value
				this.c = c; //change value
				this.n = n || p; //name that this CSSPropTween should be associated to (usually the same as p, but not always - n is what overwriting
 looks at)
				if (!(t instanceof CSSPropTween)) {
					_overwriteProps.push(this.n);
				}
				this.r = r; //round (boolean)
				this.type = type || 0; //0 = normal tween, -1 = non-tweening (in which case xs0 will be applied to the target's property, like
 tp.t[tp.p] = tp.xs0), 1 = complex-value SpecialProp, 2 = custom setRatio() that does all the work
				if (pr) {
					this.pr = pr;
					_hasPriority = true;
				}
				this.b = (b === undefined) ? s : b;
				this.e = (e === undefined) ? s + c : e;
				if (next) {
					this._next = next;
					next._prev = this;
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals.Transform"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>Transform ()](#apidoc.element.gsap.CSSPlugin._internals.Transform)
- description and source-code
```javascript
Transform = function () {
				this.perspective = parseFloat(CSSPlugin.defaultTransformPerspective) || 0;
				this.force3D = (CSSPlugin.defaultForce3D === false || !_supports3D) ? false : CSSPlugin.defaultForce3D || "auto";
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals._parseToProxy"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_parseToProxy (t, vars, cssp, pt, plugin, shallow)](#apidoc.element.gsap.CSSPlugin._internals._parseToProxy)
- description and source-code
```javascript
_parseToProxy = function (t, vars, cssp, pt, plugin, shallow) {
				var bpt = pt,
					start = {},
					end = {},
					transform = cssp._transform,
					oldForce = _forcePT,
					i, p, xp, mpt, firstPT;
				cssp._transform = null;
				_forcePT = vars;
				pt = firstPT = cssp.parse(t, vars, pt, plugin);
				_forcePT = oldForce;
				//break off from the linked list so the new ones are isolated.
				if (shallow) {
					cssp._transform = transform;
					if (bpt) {
						bpt._prev = null;
						if (bpt._prev) {
							bpt._prev._next = null;
						}
					}
				}
				while (pt && pt !== bpt) {
					if (pt.type <= 1) {
						p = pt.p;
						end[p] = pt.s + pt.c;
						start[p] = pt.s;
						if (!shallow) {
							mpt = new MiniPropTween(pt, "s", p, mpt, pt.r);
							pt.c = 0;
						}
						if (pt.type === 1) {
							i = pt.l;
							while (--i > 0) {
								xp = "xn" + i;
								p = pt.p + "_" + xp;
								end[p] = pt.data[xp];
								start[p] = pt[xp];
								if (!shallow) {
									mpt = new MiniPropTween(pt, xp, p, mpt, pt.rxp[xp]);
								}
							}
						}
					}
					pt = pt._next;
				}
				return {proxy:start, end:end, firstMPT:mpt, pt:firstPT};
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals._registerComplexSpecialProp"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_registerComplexSpecialProp (p, options, defaults)](#apidoc.element.gsap.CSSPlugin._internals._registerComplexSpecialProp)
- description and source-code
```javascript
_registerComplexSpecialProp = function (p, options, defaults) {
				if (typeof(options) !== "object") {
					options = {parser:defaults}; //to make backwards compatible with older versions of BezierPlugin and ThrowPropsPlugin
				}
				var a = p.split(","),
					d = options.defaultValue,
					i, temp;
				defaults = defaults || [d];
				for (i = 0; i < a.length; i++) {
					options.prefix = (i === 0 && options.prefix);
					options.defaultValue = defaults[i] || d;
					temp = new SpecialProp(a[i], options);
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals._registerPluginProp"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_registerPluginProp (p)](#apidoc.element.gsap.CSSPlugin._internals._registerPluginProp)
- description and source-code
```javascript
_registerPluginProp = function (p) {
				if (!_specialProps[p]) {
					var pluginName = p.charAt(0).toUpperCase() + p.substr(1) + "Plugin";
					_registerComplexSpecialProp(p, {parser:function(t, e, p, cssp, pt, plugin, vars) {
						var pluginClass = _globals.com.greensock.plugins[pluginName];
						if (!pluginClass) {
							_log("Error: " + pluginName + " js file not loaded.");
							return pt;
						}
						pluginClass._cssRegister();
						return _specialProps[p].parse(t, e, p, cssp, pt, plugin, vars);
					}});
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals._setPluginRatio"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>_setPluginRatio (v)](#apidoc.element.gsap.CSSPlugin._internals._setPluginRatio)
- description and source-code
```javascript
_setPluginRatio = function (v) {
				this.plugin.setRatio(v);
				var d = this.data,
					proxy = d.proxy,
					mpt = d.firstMPT,
					min = 0.000001,
					val, pt, i, str, p;
				while (mpt) {
					val = proxy[mpt.v];
					if (mpt.r) {
						val = Math.round(val);
					} else if (val < min && val > -min) {
						val = 0;
					}
					mpt.t[mpt.p] = val;
					mpt = mpt._next;
				}
				if (d.autoRotate) {
					d.autoRotate.rotation = d.mod ? d.mod(proxy.rotation, this.t) : proxy.rotation; //special case for ModifyPlugin to hook into
 an auto-rotating bezier
				}
				//at the end, we must set the CSSPropTween's "e" (end) value dynamically here because that's what is used in the final setRatio
() method. Same for "b" at the beginning.
				if (v === 1 || v === 0) {
					mpt = d.firstMPT;
					p = (v === 1) ? "e" : "b";
					while (mpt) {
						pt = mpt.t;
						if (!pt.type) {
							pt[p] = pt.s + pt.xs0;
						} else if (pt.type === 1) {
							str = pt.xs0 + pt.s + pt.xs1;
							for (i = 1; i < pt.l; i++) {
								str += pt["xn"+i] + pt["xs"+(i+1)];
							}
							pt[p] = str;
						}
						mpt = mpt._next;
					}
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals.calculateOffset"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>calculateOffset (t, p, cs)](#apidoc.element.gsap.CSSPlugin._internals.calculateOffset)
- description and source-code
```javascript
calculateOffset = function (t, p, cs) { //for figuring out "top" or "left" in px when it's "auto". We need to factor in margin with the offsetLeft
/offsetTop
				if (_getStyle(t, "position", cs) !== "absolute") { return 0; }
				var dim = ((p === "left") ? "Left" : "Top"),
					v = _getStyle(t, "margin" + dim, cs);
				return t["offset" + dim] - (_convertToPixels(t, p, parseFloat(v), v.replace(_suffixExp, "")) || 0);
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals.convertToPixels"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>convertToPixels (t, p, v, sfx, recurse)](#apidoc.element.gsap.CSSPlugin._internals.convertToPixels)
- description and source-code
```javascript
convertToPixels = function (t, p, v, sfx, recurse) {
				if (sfx === "px" || !sfx) { return v; }
				if (sfx === "auto" || !v) { return 0; }
				var horiz = _horizExp.test(p),
					node = t,
					style = _tempDiv.style,
					neg = (v < 0),
					precise = (v === 1),
					pix, cache, time;
				if (neg) {
					v = -v;
				}
				if (precise) {
					v *= 100;
				}
				if (sfx === "%" && p.indexOf("border") !== -1) {
					pix = (v / 100) * (horiz ? t.clientWidth : t.clientHeight);
				} else {
					style.cssText = "border:0 solid red;position:" + _getStyle(t, "position") + ";line-height:0;";
					if (sfx === "%" || !node.appendChild || sfx.charAt(0) === "v" || sfx === "rem") {
						node = t.parentNode || _doc.body;
						cache = node._gsCache;
						time = TweenLite.ticker.frame;
						if (cache && horiz && cache.time === time) { //performance optimization: we record the width of elements along with the ticker
 frame so that we can quickly get it again on the same tick (seems relatively safe to assume it wouldn't change on the same tick
)
							return cache.width * v / 100;
						}
						style[(horiz ? "width" : "height")] = v + sfx;
					} else {
						style[(horiz ? "borderLeftWidth" : "borderTopWidth")] = v + sfx;
					}
					node.appendChild(_tempDiv);
					pix = parseFloat(_tempDiv[(horiz ? "offsetWidth" : "offsetHeight")]);
					node.removeChild(_tempDiv);
					if (horiz && sfx === "%" && CSSPlugin.cacheWidths !== false) {
						cache = node._gsCache = node._gsCache || {};
						cache.time = time;
						cache.width = pix / v * 100;
					}
					if (pix === 0 && !recurse) {
						pix = _convertToPixels(t, p, v, sfx, true);
					}
				}
				if (precise) {
					pix /= 100;
				}
				return neg ? -pix : pix;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals.getTransform"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>getTransform (t, cs, rec, parse)](#apidoc.element.gsap.CSSPlugin._internals.getTransform)
- description and source-code
```javascript
getTransform = function (t, cs, rec, parse) {
				if (t._gsTransform && rec && !parse) {
					return t._gsTransform; //if the element already has a _gsTransform, use that. Note: some browsers don't accurately return the
 calculated style for the transform (particularly for SVG), so it's almost always safest to just use the values we've already applied
 rather than re-parsing things.
				}
				var tm = rec ? t._gsTransform || new Transform() : new Transform(),
					invX = (tm.scaleX < 0), //in order to interpret things properly, we need to know if the user applied a negative scaleX previously
 so that we can adjust the rotation and skewX accordingly. Otherwise, if we always interpret a flipped matrix as affecting scaleY
 and the user only wants to tween the scaleX on multiple sequential tweens, it would keep the negative scaleY without that being
 the user's intent.
					min = 0.00002,
					rnd = 100000,
					zOrigin = _supports3D ? parseFloat(_getStyle(t, _transformOriginProp, cs, false, "0 0 0").split(" ")[2]) || tm.zOrigin  ||
0 : 0,
					defaultTransformPerspective = parseFloat(CSSPlugin.defaultTransformPerspective) || 0,
					m, i, scaleX, scaleY, rotation, skewX;

				tm.svg = !!(t.getCTM && _isSVG(t));
				if (tm.svg) {
					_parseSVGOrigin(t, _getStyle(t, _transformOriginProp, cs, false, "50% 50%") + "", tm, t.getAttribute("data-svg-origin"));
					_useSVGTransformAttr = CSSPlugin.useSVGTransformAttr || _forceSVGTransformAttr;
				}
				m = _getMatrix(t);
				if (m !== _identity2DMatrix) {

					if (m.length === 16) {
						//we'll only look at these position-related 6 variables first because if x/y/z all match, it's relatively safe to assume we
 don't need to re-parse everything which risks losing important rotational information (like rotationX:180 plus rotationY:180 would
 look the same as rotation:180 - there's no way to know for sure which direction was taken based solely on the matrix3d() values
)
						var a11 = m[0], a21 = m[1], a31 = m[2], a41 = m[3],
							a12 = m[4], a22 = m[5], a32 = m[6], a42 = m[7],
							a13 = m[8], a23 = m[9], a33 = m[10],
							a14 = m[12], a24 = m[13], a34 = m[14],
							a43 = m[11],
							angle = Math.atan2(a32, a33),
							t1, t2, t3, t4, cos, sin;

						//we manually compensate for non-zero z component of transformOrigin to work around bugs in Safari
						if (tm.zOrigin) {
							a34 = -tm.zOrigin;
							a14 = a13*a34-m[12];
							a24 = a23*a34-m[13];
							a34 = a33*a34+tm.zOrigin-m[14];
						}
						tm.rotationX = angle * _RAD2DEG;
						//rotationX
						if (angle) {
							cos = Math.cos(-angle);
							sin = Math.sin(-angle);
							t1 = a12*cos+a13*sin;
							t2 = a22*cos+a23*sin;
							t3 = a32*cos+a33*sin;
							a13 = a12*-sin+a13*cos;
							a23 = a22*-sin+a23*cos;
							a33 = a32*-sin+a33*cos;
							a43 = a42*-sin+a43*cos;
							a12 = t1;
							a22 = t2;
							a32 = t3;
						}
						//rotationY
						angle = Math.atan2(-a31, a33);
						tm.rotationY = angle * _RAD2DEG;
						if (angle) {
							cos = Math.cos(-angle);
							sin = Math.sin(-angle);
							t1 = a11*cos-a13*sin;
							t2 = a21*cos-a23*sin;
							t3 = a31*cos-a33*sin;
							a23 = a21*sin+a23*cos;
							a33 = a31*sin+a33*cos;
							a43 = a41*sin+a43*cos;
							a11 = t1;
							a21 = t2;
							a31 = t3;
						}
						//rotationZ
						angle = Math.atan2(a21, a11);
						tm.rotation = angle * _RAD2DEG;
						if (angle) {
							cos = Math.cos(-angle);
							sin = Math.sin(-angle);
							a11 = a11*cos+a12*sin;
							t2 = a21*cos+a22*sin;
							a22 = a21*-sin+a22*cos;
							a32 = a31*-sin+a32*cos;
							a21 = t2;
						}

						if (tm.rotationX && Math.abs(tm.rotationX) + Math.abs(tm.rotation) > 359.9) { //when rotationY is set, it will often be parsed
 as 180 degrees different than it should be, and rotationX and rotation both being 180 (it looks the same), so we adjust for that
 here.
							tm.rotationX = tm.rotation = 0;
							tm.rotationY = 180 - tm.rotationY;
						}

						tm.scaleX = ((Math.sqrt(a11 * a11 + a21 * a21) * rnd + 0.5) | 0) / rnd;
						tm.scaleY = ((Math.sqrt(a22 * a ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals.set3DTransformRatio"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>set3DTransformRatio (v)](#apidoc.element.gsap.CSSPlugin._internals.set3DTransformRatio)
- description and source-code
```javascript
set3DTransformRatio = function (v) {
				var t = this.data, //refers to the element's _gsTransform object
					style = this.t.style,
					angle = t.rotation,
					rotationX = t.rotationX,
					rotationY = t.rotationY,
					sx = t.scaleX,
					sy = t.scaleY,
					sz = t.scaleZ,
					x = t.x,
					y = t.y,
					z = t.z,
					isSVG = t.svg,
					perspective = t.perspective,
					force3D = t.force3D,
					skewY = t.skewY,
					skewX = t.skewX,
					t1,	a11, a12, a13, a21, a22, a23, a31, a32, a33, a41, a42, a43,
					zOrigin, min, cos, sin, t2, transform, comma, zero, skew, rnd;
				if (skewY) { //for performance reasons, we combine all skewing into the skewX and rotation values. Remember, a skewY of 10 degrees
 looks the same as a rotation of 10 degrees plus a skewX of 10 degrees.
					skewX += skewY;
					angle += skewY;
				}

				//check to see if we should render as 2D (and SVGs must use 2D when _useSVGTransformAttr is true)
				if (((((v === 1 || v === 0) && force3D === "auto" && (this.tween._totalTime === this.tween._totalDuration || !this.tween._totalTime
)) || !force3D) && !z && !perspective && !rotationY && !rotationX && sz === 1) || (_useSVGTransformAttr && isSVG) || !_supports3D
) { //on the final render (which could be 0 for a from tween), if there are no 3D aspects, render in 2D to free up memory and improve
 performance especially on mobile devices. Check the tween's totalTime/totalDuration too in order to make sure it doesn't happen
 between repeats if it's a repeating tween.

					//2D
					if (angle || skewX || isSVG) {
						angle *= _DEG2RAD;
						skew = skewX * _DEG2RAD;
						rnd = 100000;
						a11 = Math.cos(angle) * sx;
						a21 = Math.sin(angle) * sx;
						a12 = Math.sin(angle - skew) * -sy;
						a22 = Math.cos(angle - skew) * sy;
						if (skew && t.skewType === "simple") { //by default, we compensate skewing on the other axis to make it look more natural,
but you can set the skewType to "simple" to use the uncompensated skewing that CSS does
							t1 = Math.tan(skew - skewY * _DEG2RAD);
							t1 = Math.sqrt(1 + t1 * t1);
							a12 *= t1;
							a22 *= t1;
							if (skewY) {
								t1 = Math.tan(skewY * _DEG2RAD);
								t1 = Math.sqrt(1 + t1 * t1);
								a11 *= t1;
								a21 *= t1;
							}
						}
						if (isSVG) {
							x += t.xOrigin - (t.xOrigin * a11 + t.yOrigin * a12) + t.xOffset;
							y += t.yOrigin - (t.xOrigin * a21 + t.yOrigin * a22) + t.yOffset;
							if (_useSVGTransformAttr && (t.xPercent || t.yPercent)) { //The SVG spec doesn't support percentage-based translation in
the "transform" attribute, so we merge it into the matrix to simulate it.
								min = this.t.getBBox();
								x += t.xPercent * 0.01 * min.width;
								y += t.yPercent * 0.01 * min.height;
							}
							min = 0.000001;
							if (x < min) if (x > -min) {
								x = 0;
							}
							if (y < min) if (y > -min) {
								y = 0;
							}
						}
						transform = (((a11 * rnd) | 0) / rnd) + "," + (((a21 * rnd) | 0) / rnd) + "," + (((a12 * rnd) | 0) / rnd) + "," + (((a22 *
rnd) | 0) / rnd) + "," + x + "," + y + ")";
						if (isSVG && _useSVGTransformAttr) {
							this.t.setAttribute("transform", "matrix(" + transform);
						} else {
							//some browsers have a hard time with very small values like 2.4492935982947064e-16 (notice the "e-" towards the end) and
 would render the object slightly off. So we round to 5 decimal places.
							style[_transformProp] = ((t.xPercent || t.yPercent) ? "translate(" + t.xPercent + "%," + t.yPercent + "%) matrix(" : "matrix
(") + transform;
						}
					} else {
						style[_transformProp] = ((t.xPercent || t.yPercent) ? "translate(" + t.xPercent + "%," + t.yPercent + "%) matrix(" : "matrix
(") + sx + ",0,0," + sy + "," + x + "," + y + ")";
					}
					return;

				}
				if (_isFirefox) { //Firefox has a bug (at least in v25) that causes it to render the transparent part of 32-bit PNG images as
 black when displayed inside an iframe and the 3D scale is very small and doesn't change sufficiently enough between renders (like
 if you use a Power4.easeInOut to scale from 0 to 1 whe ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin._internals.setTransformRatio"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.</span>setTransformRatio (v)](#apidoc.element.gsap.CSSPlugin._internals.setTransformRatio)
- description and source-code
```javascript
setTransformRatio = function (v) {
				var t = this.data, //refers to the element's _gsTransform object
					style = this.t.style,
					angle = t.rotation,
					rotationX = t.rotationX,
					rotationY = t.rotationY,
					sx = t.scaleX,
					sy = t.scaleY,
					sz = t.scaleZ,
					x = t.x,
					y = t.y,
					z = t.z,
					isSVG = t.svg,
					perspective = t.perspective,
					force3D = t.force3D,
					skewY = t.skewY,
					skewX = t.skewX,
					t1,	a11, a12, a13, a21, a22, a23, a31, a32, a33, a41, a42, a43,
					zOrigin, min, cos, sin, t2, transform, comma, zero, skew, rnd;
				if (skewY) { //for performance reasons, we combine all skewing into the skewX and rotation values. Remember, a skewY of 10 degrees
 looks the same as a rotation of 10 degrees plus a skewX of 10 degrees.
					skewX += skewY;
					angle += skewY;
				}

				//check to see if we should render as 2D (and SVGs must use 2D when _useSVGTransformAttr is true)
				if (((((v === 1 || v === 0) && force3D === "auto" && (this.tween._totalTime === this.tween._totalDuration || !this.tween._totalTime
)) || !force3D) && !z && !perspective && !rotationY && !rotationX && sz === 1) || (_useSVGTransformAttr && isSVG) || !_supports3D
) { //on the final render (which could be 0 for a from tween), if there are no 3D aspects, render in 2D to free up memory and improve
 performance especially on mobile devices. Check the tween's totalTime/totalDuration too in order to make sure it doesn't happen
 between repeats if it's a repeating tween.

					//2D
					if (angle || skewX || isSVG) {
						angle *= _DEG2RAD;
						skew = skewX * _DEG2RAD;
						rnd = 100000;
						a11 = Math.cos(angle) * sx;
						a21 = Math.sin(angle) * sx;
						a12 = Math.sin(angle - skew) * -sy;
						a22 = Math.cos(angle - skew) * sy;
						if (skew && t.skewType === "simple") { //by default, we compensate skewing on the other axis to make it look more natural,
but you can set the skewType to "simple" to use the uncompensated skewing that CSS does
							t1 = Math.tan(skew - skewY * _DEG2RAD);
							t1 = Math.sqrt(1 + t1 * t1);
							a12 *= t1;
							a22 *= t1;
							if (skewY) {
								t1 = Math.tan(skewY * _DEG2RAD);
								t1 = Math.sqrt(1 + t1 * t1);
								a11 *= t1;
								a21 *= t1;
							}
						}
						if (isSVG) {
							x += t.xOrigin - (t.xOrigin * a11 + t.yOrigin * a12) + t.xOffset;
							y += t.yOrigin - (t.xOrigin * a21 + t.yOrigin * a22) + t.yOffset;
							if (_useSVGTransformAttr && (t.xPercent || t.yPercent)) { //The SVG spec doesn't support percentage-based translation in
the "transform" attribute, so we merge it into the matrix to simulate it.
								min = this.t.getBBox();
								x += t.xPercent * 0.01 * min.width;
								y += t.yPercent * 0.01 * min.height;
							}
							min = 0.000001;
							if (x < min) if (x > -min) {
								x = 0;
							}
							if (y < min) if (y > -min) {
								y = 0;
							}
						}
						transform = (((a11 * rnd) | 0) / rnd) + "," + (((a21 * rnd) | 0) / rnd) + "," + (((a12 * rnd) | 0) / rnd) + "," + (((a22 *
rnd) | 0) / rnd) + "," + x + "," + y + ")";
						if (isSVG && _useSVGTransformAttr) {
							this.t.setAttribute("transform", "matrix(" + transform);
						} else {
							//some browsers have a hard time with very small values like 2.4492935982947064e-16 (notice the "e-" towards the end) and
 would render the object slightly off. So we round to 5 decimal places.
							style[_transformProp] = ((t.xPercent || t.yPercent) ? "translate(" + t.xPercent + "%," + t.yPercent + "%) matrix(" : "matrix
(") + transform;
						}
					} else {
						style[_transformProp] = ((t.xPercent || t.yPercent) ? "translate(" + t.xPercent + "%," + t.yPercent + "%) matrix(" : "matrix
(") + sx + ",0,0," + sy + "," + x + "," + y + ")";
					}
					return;

				}
				if (_isFirefox) { //Firefox has a bug (at least in v25) that causes it to render the transparent part of 32-bit PNG images as
 black when displayed inside an iframe and the 3D scale is very small and doesn't change sufficiently enough between renders (like
 if you use a Power4.easeInOut to scale from 0 to 1 whe ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CSSPlugin._internals.CSSPropTween.prototype"></a>[module gsap.CSSPlugin._internals.CSSPropTween.prototype](#apidoc.module.gsap.CSSPlugin._internals.CSSPropTween.prototype)

#### <a name="apidoc.element.gsap.CSSPlugin._internals.CSSPropTween.prototype.appendXtra"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin._internals.CSSPropTween.prototype.</span>appendXtra (pfx, s, c, sfx, r, pad)](#apidoc.element.gsap.CSSPlugin._internals.CSSPropTween.prototype.appendXtra)
- description and source-code
```javascript
appendXtra = function (pfx, s, c, sfx, r, pad) {
			var pt = this,
				l = pt.l;
			pt["xs" + l] += (pad && (l || pt["xs" + l])) ? " " + pfx : pfx || "";
			if (!c) if (l !== 0 && !pt.plugin) { //typically we'll combine non-changing values right into the xs to optimize performance,
but we don't combine them when there's a plugin that will be tweening the values because it may depend on the values being split
 apart, like for a bezier, if a value doesn't change between the first and second iteration but then it does on the 3rd, we'll run
 into trouble because there's no xn slot for that value!
				pt["xs" + l] += s + (sfx || "");
				return pt;
			}
			pt.l++;
			pt.type = pt.setRatio ? 2 : 1;
			pt["xs" + pt.l] = sfx || "";
			if (l > 0) {
				pt.data["xn" + l] = s + c;
				pt.rxp["xn" + l] = r; //round extra property (we need to tap into this in the _parseToProxy() method)
				pt["xn" + l] = s;
				if (!pt.plugin) {
					pt.xfirst = new CSSPropTween(pt, "xn" + l, s, c, pt.xfirst || pt, 0, pt.n, r, pt.pr);
					pt.xfirst.xs0 = 0; //just to ensure that the property stays numeric which helps modern browsers speed up processing. Remember
, in the setRatio() method, we do pt.t[pt.p] = val + pt.xs0 so if pt.xs0 is "" (the default), it'll cast the end value as a string
. When a property is a number sometimes and a string sometimes, it prevents the compiler from locking in the data type, slowing
things down slightly.
				}
				return pt;
			}
			pt.data = {s:s + c};
			pt.rxp = {};
			pt.s = s;
			pt.c = c;
			pt.r = r;
			return pt;
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CSSPlugin.prototype"></a>[module gsap.CSSPlugin.prototype](#apidoc.module.gsap.CSSPlugin.prototype)

#### <a name="apidoc.element.gsap.CSSPlugin.prototype._addLazySet"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_addLazySet (t, p, v)](#apidoc.element.gsap.CSSPlugin.prototype._addLazySet)
- description and source-code
```javascript
_addLazySet = function (t, p, v) {
			var pt = this._firstPT = new CSSPropTween(t, p, 0, 0, this._firstPT, 2);
			pt.e = v;
			pt.setRatio = lazySet;
			pt.data = this;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype._enableTransforms"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_enableTransforms (threeD)](#apidoc.element.gsap.CSSPlugin.prototype._enableTransforms)
- description and source-code
```javascript
_enableTransforms = function (threeD) {
			this._transform = this._transform || _getTransform(this._target, _cs, true); //ensures that the element has a _gsTransform property
 with the appropriate values.
			this._transformType = (!(this._transform.svg && _useSVGTransformAttr) && (threeD || this._transformType === 3)) ? 3 : 2;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype._kill"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.CSSPlugin.prototype._kill)
- description and source-code
```javascript
_kill = function (lookup) {
			var copy = lookup,
				pt, p, xfirst;
			if (lookup.autoAlpha || lookup.alpha) {
				copy = {};
				for (p in lookup) { //copy the lookup so that we're not changing the original which may be passed elsewhere.
					copy[p] = lookup[p];
				}
				copy.opacity = 1;
				if (copy.autoAlpha) {
					copy.visibility = 1;
				}
			}
			if (lookup.className && (pt = this._classNamePT)) { //for className tweens, we need to kill any associated CSSPropTweens too;
a linked list starts at the className's "xfirst".
				xfirst = pt.xfirst;
				if (xfirst && xfirst._prev) {
					this._linkCSSP(xfirst._prev, pt._next, xfirst._prev._prev); //break off the prev
				} else if (xfirst === this._firstPT) {
					this._firstPT = pt._next;
				}
				if (pt._next) {
					this._linkCSSP(pt._next, pt._next._next, xfirst._prev);
				}
				this._classNamePT = null;
			}
			pt = this._firstPT;
			while (pt) {
				if (pt.plugin && pt.plugin !== p && pt.plugin._kill) { //for plugins that are registered with CSSPlugin, we should notify them
 of the kill.
					pt.plugin._kill(lookup);
					p = pt.plugin;
				}
				pt = pt._next;
			}
			return TweenPlugin.prototype._kill.call(this, copy);
		}
```
- example usage
```shell
...
			if (!vars && !target) {
				return this._enabled(false, false);
			}
			var tweens = (!target) ? this.getChildren(true, true, false) : this.getTweensOf(target),
				i = tweens.length,
				changed = false;
			while (--i > -1) {
				if (tweens[i]._kill(vars, target)) {
					changed = true;
				}
			}
			return changed;
		};

		p.clear = function(labels) {
...
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype._linkCSSP"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_linkCSSP (pt, next, prev, remove)](#apidoc.element.gsap.CSSPlugin.prototype._linkCSSP)
- description and source-code
```javascript
_linkCSSP = function (pt, next, prev, remove) {
			if (pt) {
				if (next) {
					next._prev = pt;
				}
				if (pt._next) {
					pt._next._prev = pt._prev;
				}
				if (pt._prev) {
					pt._prev._next = pt._next;
				} else if (this._firstPT === pt) {
					this._firstPT = pt._next;
					remove = true; //just to prevent resetting this._firstPT 5 lines down in case pt._next is null. (optimized for speed)
				}
				if (prev) {
					prev._next = pt;
				} else if (!remove && this._firstPT === null) {
					this._firstPT = pt;
				}
				pt._next = next;
				pt._prev = prev;
			}
			return pt;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype._mod"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_mod (lookup)](#apidoc.element.gsap.CSSPlugin.prototype._mod)
- description and source-code
```javascript
_mod = function (lookup) {
			var pt = this._firstPT;
			while (pt) {
				if (typeof(lookup[pt.p]) === "function" && lookup[pt.p] === Math.round) { //only gets called by RoundPropsPlugin (ModifyPlugin
 manages all the rendering internally for CSSPlugin properties that need modification). Remember, we handle rounding a bit differently
 in this plugin for performance reasons, leveraging "r" as an indicator that the value should be rounded internally..
					pt.r = 1;
				}
				pt = pt._next;
			}
		}
```
- example usage
```shell
...
			i = rp.length;
			while (--i > -1) {
				prop = rp[i];
				pt = tween._firstPT;
				while (pt) {
					next = pt._next; //record here, because it may get removed
					if (pt.pg) {
						pt.t._mod(lookup);
					} else if (pt.n === prop) {
						if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
							_roundLinkedList(pt.t._firstPT);
						} else {
							this._add(pt.t, prop, pt.s, pt.c);
							//remove from linked list
							if (next) {
...
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>_onInitTween (target, vars, tween, index)](#apidoc.element.gsap.CSSPlugin.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, vars, tween, index) {
			if (!target.nodeType) { //css is only for dom elements
				return false;
			}
			this._target = _target = target;
			this._tween = tween;
			this._vars = vars;
			_index = index;
			_autoRound = vars.autoRound;
			_hasPriority = false;
			_suffixMap = vars.suffixMap || CSSPlugin.suffixMap;
			_cs = _getComputedStyle(target, "");
			_overwriteProps = this._overwriteProps;
			var style = target.style,
				v, pt, pt2, first, last, next, zIndex, tpt, threeD;
			if (_reqSafariFix) if (style.zIndex === "") {
				v = _getStyle(target, "zIndex", _cs);
				if (v === "auto" || v === "") {
					//corrects a bug in [non-Android] Safari that prevents it from repainting elements in their new positions if they don't have
 a zIndex set. We also can't just apply this inside _parseTransform() because anything that's moved in any way (like using "left
" or "top" instead of transforms like "x" and "y") can be affected, so it is best to ensure that anything that's tweening has a
z-index. Setting "WebkitPerspective" to a non-zero value worked too except that on iOS Safari things would flicker randomly. Plus
 zIndex is less memory-intensive.
					this._addLazySet(style, "zIndex", 0);
				}
			}

			if (typeof(vars) === "string") {
				first = style.cssText;
				v = _getAllStyles(target, _cs);
				style.cssText = first + ";" + vars;
				v = _cssDif(target, v, _getAllStyles(target)).difs;
				if (!_supportsOpacity && _opacityValExp.test(vars)) {
					v.opacity = parseFloat( RegExp.$1 );
				}
				vars = v;
				style.cssText = first;
			}

			if (vars.className) { //className tweens will combine any differences they find in the css with the vars that are passed in,
so {className:"myClass", scale:0.5, left:20} would work.
				this._firstPT = pt = _specialProps.className.parse(target, vars.className, "className", this, null, null, vars);
			} else {
				this._firstPT = pt = this.parse(target, vars, null);
			}

			if (this._transformType) {
				threeD = (this._transformType === 3);
				if (!_transformProp) {
					style.zoom = 1; //helps correct an IE issue.
				} else if (_isSafari) {
					_reqSafariFix = true;
					//if zIndex isn't set, iOS Safari doesn't repaint things correctly sometimes (seemingly at random).
					if (style.zIndex === "") {
						zIndex = _getStyle(target, "zIndex", _cs);
						if (zIndex === "auto" || zIndex === "") {
							this._addLazySet(style, "zIndex", 0);
						}
					}
					//Setting WebkitBackfaceVisibility corrects 3 bugs:
					// 1) [non-Android] Safari skips rendering changes to "top" and "left" that are made on the same frame/render as a transform
 update.
					// 2) iOS Safari sometimes neglects to repaint elements in their new positions. Setting "WebkitPerspective" to a non-zero value
 worked too except that on iOS Safari things would flicker randomly.
					// 3) Safari sometimes displayed odd artifacts when tweening the transform (or WebkitTransform) property, like ghosts of the
 edges of the element remained. Definitely a browser bug.
					//Note: we allow the user to override the auto-setting by defining WebkitBackfaceVisibility in the vars of the tween.
					if (_isSafariLT6) {
						this._addLazySet(style, "WebkitBackfaceVisibility", this._vars.WebkitBackfaceVisibility || (threeD ? "visible" : "hidden"));
					}
				}
				pt2 = pt;
				while (pt2 && pt2._next) {
					pt2 = pt2._next;
				}
				tpt = new CSSPropTween(target, "transform", 0, 0, null, 2);
				this._linkCSSP(tpt, null, pt2);
				tpt.setRatio = _transformProp ? _setTransformRatio : _setIETransformRatio;
				tpt.data = this._transform || _getTransform(target, _cs, true);
				tpt.tween = tween;
				tpt.pr = -1; //ensures that the transforms get applied after the components are updated.
				_overwriteProps.pop(); //we don't want to force the overwrite of all "transform" tweens of the target - we only care about individual
 transform properties like scaleX, rotation, etc. The CSSPropTween constructor automatically adds the property to _overwriteProps
 which is why we need to pop() here.
			}

			if (_has ...
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>constructor ()](#apidoc.element.gsap.CSSPlugin.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
				TweenPlugin.call(this, "css");
				this._overwriteProps.length = 0;
				this.setRatio = CSSPlugin.prototype.setRatio; //speed optimization (avoid prototype lookup on this "hot" method)
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype.parse"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>parse (target, vars, pt, plugin)](#apidoc.element.gsap.CSSPlugin.prototype.parse)
- description and source-code
```javascript
parse = function (target, vars, pt, plugin) {
			var style = target.style,
				p, sp, bn, en, bs, es, bsfx, esfx, isStr, rel;
			for (p in vars) {
				es = vars[p]; //ending value string
				if (typeof(es) === "function") {
					es = es(_index, _target);
				}
				sp = _specialProps[p]; //SpecialProp lookup.
				if (sp) {
					pt = sp.parse(target, es, p, this, pt, plugin, vars);

				} else {
					bs = _getStyle(target, p, _cs) + "";
					isStr = (typeof(es) === "string");
					if (p === "color" || p === "fill" || p === "stroke" || p.indexOf("Color") !== -1 || (isStr && _rgbhslExp.test(es))) { //Opera
 uses background: to define color sometimes in addition to backgroundColor:
						if (!isStr) {
							es = _parseColor(es);
							es = ((es.length > 3) ? "rgba(" : "rgb(") + es.join(",") + ")";
						}
						pt = _parseComplex(style, p, bs, es, true, "transparent", pt, 0, plugin);

					} else if (isStr && _complexExp.test(es)) {
						pt = _parseComplex(style, p, bs, es, true, null, pt, 0, plugin);

					} else {
						bn = parseFloat(bs);
						bsfx = (bn || bn === 0) ? bs.substr((bn + "").length) : ""; //remember, bs could be non-numeric like "normal" for fontWeight
, so we should default to a blank suffix in that case.

						if (bs === "" || bs === "auto") {
							if (p === "width" || p === "height") {
								bn = _getDimension(target, p, _cs);
								bsfx = "px";
							} else if (p === "left" || p === "top") {
								bn = _calculateOffset(target, p, _cs);
								bsfx = "px";
							} else {
								bn = (p !== "opacity") ? 0 : 1;
								bsfx = "";
							}
						}

						rel = (isStr && es.charAt(1) === "=");
						if (rel) {
							en = parseInt(es.charAt(0) + "1", 10);
							es = es.substr(2);
							en *= parseFloat(es);
							esfx = es.replace(_suffixExp, "");
						} else {
							en = parseFloat(es);
							esfx = isStr ? es.replace(_suffixExp, "") : "";
						}

						if (esfx === "") {
							esfx = (p in _suffixMap) ? _suffixMap[p] : bsfx; //populate the end suffix, prioritizing the map, then if none is found,
use the beginning suffix.
						}

						es = (en || en === 0) ? (rel ? en + bn : en) + esfx : vars[p]; //ensures that any += or -= prefixes are taken care of. Record
 the end value before normalizing the suffix because we always want to end the tween on exactly what they intended even if it doesn
't match the beginning value's suffix.

						//if the beginning/ending suffixes don't match, normalize them...
						if (bsfx !== esfx) if (esfx !== "") if (en || en === 0) if (bn) { //note: if the beginning value (bn) is 0, we don't need
to convert units!
							bn = _convertToPixels(target, p, bn, bsfx);
							if (esfx === "%") {
								bn /= _convertToPixels(target, p, 100, "%") / 100;
								if (vars.strictUnits !== true) { //some browsers report only "px" values instead of allowing "%" with getComputedStyle(),
so we assume that if we're tweening to a %, we should start there too unless strictUnits:true is defined. This approach is particularly
 useful for responsive designs that use from() tweens.
									bs = bn + "%";
								}

							} else if (esfx === "em" || esfx === "rem" || esfx === "vw" || esfx === "vh") {
								bn /= _convertToPixels(target, p, 1, esfx);

							//otherwise convert to pixels.
							} else if (esfx !== "px") {
								en = _convertToPixels(target, p, en, esfx);
								esfx = "px"; //we don't use bsfx after this, so we don't need to set it to px too.
							}
							if (rel) if (en || en === 0) {
								es = (en + bn) + esfx; //the changes we made affect relative calculations, so adjust the end value here.
							}
						}

						if (rel) {
							en += bn;
						}

						if ((bn || bn === 0) && (en || en === 0)) { //faster than isNaN(). Also, previously we required en !== bn but that doesn't
 really gain much performance and it prevents _parseToProxy() from working properly if beginning and ending values match but need
 to get tweened by an external plugin anyway. For example, a bezier tween where the target starts at left:0 and has these points
: [{left:50},{le ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSPlugin.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.CSSPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.CSSPlugin.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (v) {
			var pt = this._firstPT,
				min = 0.000001,
				val, str, i;
			//at the end of the tween, we set the values to exactly what we received in order to make sure non-tweening values (like "position
" or "float" or whatever) are set and so that if the beginning/ending suffixes (units) didn't match and we normalized to px, the
 value that the user passed in is used here. We check to see if the tween is at its beginning in case it's a from() tween in which
 case the ratio will actually go from 1 to 0 over the course of the tween (backwards).
			if (v === 1 && (this._tween._time === this._tween._duration || this._tween._time === 0)) {
				while (pt) {
					if (pt.type !== 2) {
						if (pt.r && pt.type !== -1) {
							val = Math.round(pt.s + pt.c);
							if (!pt.type) {
								pt.t[pt.p] = val + pt.xs0;
							} else if (pt.type === 1) { //complex value (one that typically has multiple numbers inside a string, like "rect(5px,10px
,20px,25px)"
								i = pt.l;
								str = pt.xs0 + val + pt.xs1;
								for (i = 1; i < pt.l; i++) {
									str += pt["xn"+i] + pt["xs"+(i+1)];
								}
								pt.t[pt.p] = str;
							}
						} else {
							pt.t[pt.p] = pt.e;
						}
					} else {
						pt.setRatio(v);
					}
					pt = pt._next;
				}

			} else if (v || !(this._tween._time === this._tween._duration || this._tween._time === 0) || this._tween._rawPrevTime === -0.
000001) {
				while (pt) {
					val = pt.c * v + pt.s;
					if (pt.r) {
						val = Math.round(val);
					} else if (val < min) if (val > -min) {
						val = 0;
					}
					if (!pt.type) {
						pt.t[pt.p] = val + pt.xs0;
					} else if (pt.type === 1) { //complex value (one that typically has multiple numbers inside a string, like "rect(5px,10px,20px
,25px)"
						i = pt.l;
						if (i === 2) {
							pt.t[pt.p] = pt.xs0 + val + pt.xs1 + pt.xn1 + pt.xs2;
						} else if (i === 3) {
							pt.t[pt.p] = pt.xs0 + val + pt.xs1 + pt.xn1 + pt.xs2 + pt.xn2 + pt.xs3;
						} else if (i === 4) {
							pt.t[pt.p] = pt.xs0 + val + pt.xs1 + pt.xn1 + pt.xs2 + pt.xn2 + pt.xs3 + pt.xn3 + pt.xs4;
						} else if (i === 5) {
							pt.t[pt.p] = pt.xs0 + val + pt.xs1 + pt.xn1 + pt.xs2 + pt.xn2 + pt.xs3 + pt.xn3 + pt.xs4 + pt.xn4 + pt.xs5;
						} else {
							str = pt.xs0 + val + pt.xs1;
							for (i = 1; i < pt.l; i++) {
								str += pt["xn"+i] + pt["xs"+(i+1)];
							}
							pt.t[pt.p] = str;
						}

					} else if (pt.type === -1) { //non-tweening value
						pt.t[pt.p] = pt.xs0;

					} else if (pt.setRatio) { //custom setRatio() for things like SpecialProps, external plugins, etc.
						pt.setRatio(v);
					}
					pt = pt._next;
				}

			//if the tween is reversed all the way back to the beginning, we need to restore the original values which may have different
 units (like % instead of px or em or whatever).
			} else {
				while (pt) {
					if (pt.type !== 2) {
						pt.t[pt.p] = pt.b;
					} else {
						pt.setRatio(v);
					}
					pt = pt._next;
				}
			}
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CSSRulePlugin"></a>[module gsap.CSSRulePlugin](#apidoc.module.gsap.CSSRulePlugin)

#### <a name="apidoc.element.gsap.CSSRulePlugin.CSSRulePlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>CSSRulePlugin ()](#apidoc.element.gsap.CSSRulePlugin.CSSRulePlugin)
- description and source-code
```javascript
CSSRulePlugin = function () {
				TweenPlugin.call(this, "cssRule");
				this._overwriteProps.length = 0;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSRulePlugin.getRule"></a>[function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.</span>getRule (selector)](#apidoc.element.gsap.CSSRulePlugin.getRule)
- description and source-code
```javascript
getRule = function (selector) {
			var ruleProp = _doc.all ? 'rules' : 'cssRules',
				ss = _doc.styleSheets,
				i = ss.length,
				pseudo = (selector.charAt(0) === ":"),
				j, curSS, cs, a;
			selector = (pseudo ? "" : ",") + selector.toLowerCase() + ","; //note: old versions of IE report tag name selectors as upper
case, so we just change everything to lowercase.
			if (pseudo) {
				a = [];
			}
			while (--i > -1) {
				//Firefox may throw insecure operation errors when css is loaded from other domains, so try/catch.
				try {
					curSS = ss[i][ruleProp];
					if (!curSS) {
						continue;
					}
					j = curSS.length;
				} catch (e) {
					console.log(e);
					continue;
				}
				while (--j > -1) {
					cs = curSS[j];
					if (cs.selectorText && ("," + cs.selectorText.split("::").join(":").toLowerCase() + ",").indexOf(selector) !== -1) { //note
: IE adds an extra ":" to pseudo selectors, so .myClass:after becomes .myClass::after, so we need to strip the extra one out.
						if (pseudo) {
							a.push(cs.style);
						} else {
							return cs.style;
						}
					}
				}
			}
			return a;
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CSSRulePlugin.prototype"></a>[module gsap.CSSRulePlugin.prototype](#apidoc.module.gsap.CSSRulePlugin.prototype)

#### <a name="apidoc.element.gsap.CSSRulePlugin.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.CSSRulePlugin.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween) {
			if (target.cssText === undefined) {
				return false;
			}
			var div = target._gsProxy = target._gsProxy || _doc.createElement("div");
			this._ss = target;
			this._proxy = div.style;
			div.style.cssText = target.cssText;
			CSSPlugin.prototype._onInitTween.call(this, div, value, tween); //we just offload all the work to the regular CSSPlugin and then
 copy the cssText back over to the rule in the setRatio() method. This allows us to have all of the updates to CSSPlugin automatically
 flow through to CSSRulePlugin instead of having to maintain both
			return true;
		}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.CSSRulePlugin.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>constructor ()](#apidoc.element.gsap.CSSRulePlugin.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
				TweenPlugin.call(this, "cssRule");
				this._overwriteProps.length = 0;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CSSRulePlugin.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.CSSRulePlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.CSSRulePlugin.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (v) {
			_superSetRatio.call(this, v);
			this._ss.cssText = this._proxy.cssText;
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CircIn"></a>[module gsap.CircIn](#apidoc.module.gsap.CircIn)

#### <a name="apidoc.element.gsap.CircIn.CircIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>CircIn ()](#apidoc.element.gsap.CircIn.CircIn)
- description and source-code
```javascript
CircIn = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CircIn.prototype"></a>[module gsap.CircIn.prototype](#apidoc.module.gsap.CircIn.prototype)

#### <a name="apidoc.element.gsap.CircIn.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.CircIn.prototype.</span>constructor ()](#apidoc.element.gsap.CircIn.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CircIn.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.CircIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.CircIn.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return -(Math.sqrt(1 - (p * p)) - 1);
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.CircInOut"></a>[module gsap.CircInOut](#apidoc.module.gsap.CircInOut)

#### <a name="apidoc.element.gsap.CircInOut.CircInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>CircInOut ()](#apidoc.element.gsap.CircInOut.CircInOut)
- description and source-code
```javascript
CircInOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CircInOut.prototype"></a>[module gsap.CircInOut.prototype](#apidoc.module.gsap.CircInOut.prototype)

#### <a name="apidoc.element.gsap.CircInOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.CircInOut.prototype.</span>constructor ()](#apidoc.element.gsap.CircInOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CircInOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.CircInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.CircInOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return ((p*=2) < 1) ? -0.5 * (Math.sqrt(1 - p * p) - 1) : 0.5 * (Math.sqrt(1 - (p -= 2) * p) + 1);
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.CircOut"></a>[module gsap.CircOut](#apidoc.module.gsap.CircOut)

#### <a name="apidoc.element.gsap.CircOut.CircOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>CircOut ()](#apidoc.element.gsap.CircOut.CircOut)
- description and source-code
```javascript
CircOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.CircOut.prototype"></a>[module gsap.CircOut.prototype](#apidoc.module.gsap.CircOut.prototype)

#### <a name="apidoc.element.gsap.CircOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.CircOut.prototype.</span>constructor ()](#apidoc.element.gsap.CircOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.CircOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.CircOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.CircOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return Math.sqrt(1 - (p = p - 1) * p);
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.ColorPropsPlugin"></a>[module gsap.ColorPropsPlugin](#apidoc.module.gsap.ColorPropsPlugin)

#### <a name="apidoc.element.gsap.ColorPropsPlugin.ColorPropsPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>ColorPropsPlugin ()](#apidoc.element.gsap.ColorPropsPlugin.ColorPropsPlugin)
- description and source-code
```javascript
ColorPropsPlugin = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ColorPropsPlugin.colorStringFilter"></a>[function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.</span>colorStringFilter (a)](#apidoc.element.gsap.ColorPropsPlugin.colorStringFilter)
- description and source-code
```javascript
colorStringFilter = function (a) {
		var combined = a[0] + a[1],
			toHSL;
		_colorExp.lastIndex = 0;
		if (_colorExp.test(combined)) {
			toHSL = (combined.indexOf("hsl(") !== -1 || combined.indexOf("hsla(") !== -1);
			a[0] = _formatColors(a[0], toHSL);
			a[1] = _formatColors(a[1], toHSL);
		}
	}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ColorPropsPlugin.parseColor"></a>[function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.</span>parseColor (v, toHSL)](#apidoc.element.gsap.ColorPropsPlugin.parseColor)
- description and source-code
```javascript
parseColor = function (v, toHSL) {
			var a, r, g, b, h, s, l, max, min, d, wasHSL;
			if (!v) {
				a = _colorLookup.black;
			} else if (typeof(v) === "number") {
				a = [v >> 16, (v >> 8) & 255, v & 255];
			} else {
				if (v.charAt(v.length - 1) === ",") { //sometimes a trailing comma is included and we should chop it off (typically from a comma
-delimited list of values like a textShadow:"2px 2px 2px blue, 5px 5px 5px rgb(255,0,0)" - in this example "blue," has a trailing
 comma. We could strip it out inside parseComplex() but we'd need to do it to the beginning and ending values plus it wouldn't provide
 protection from other potential scenarios like if the user passes in a similar value.
					v = v.substr(0, v.length - 1);
				}
				if (_colorLookup[v]) {
					a = _colorLookup[v];
				} else if (v.charAt(0) === "#") {
					if (v.length === 4) { //for shorthand like #9F0
						r = v.charAt(1);
						g = v.charAt(2);
						b = v.charAt(3);
						v = "#" + r + r + g + g + b + b;
					}
					v = parseInt(v.substr(1), 16);
					a = [v >> 16, (v >> 8) & 255, v & 255];
				} else if (v.substr(0, 3) === "hsl") {
					a = wasHSL = v.match(_numExp);
					if (!toHSL) {
						h = (Number(a[0]) % 360) / 360;
						s = Number(a[1]) / 100;
						l = Number(a[2]) / 100;
						g = (l <= 0.5) ? l * (s + 1) : l + s - l * s;
						r = l * 2 - g;
						if (a.length > 3) {
							a[3] = Number(v[3]);
						}
						a[0] = _hue(h + 1 / 3, r, g);
						a[1] = _hue(h, r, g);
						a[2] = _hue(h - 1 / 3, r, g);
					} else if (v.indexOf("=") !== -1) { //if relative values are found, just return the raw strings with the relative prefixes
in place.
						return v.match(_relNumExp);
					}
				} else {
					a = v.match(_numExp) || _colorLookup.transparent;
				}
				a[0] = Number(a[0]);
				a[1] = Number(a[1]);
				a[2] = Number(a[2]);
				if (a.length > 3) {
					a[3] = Number(a[3]);
				}
			}
			if (toHSL && !wasHSL) {
				r = a[0] / 255;
				g = a[1] / 255;
				b = a[2] / 255;
				max = Math.max(r, g, b);
				min = Math.min(r, g, b);
				l = (max + min) / 2;
				if (max === min) {
					h = s = 0;
				} else {
					d = max - min;
					s = l > 0.5 ? d / (2 - max - min) : d / (max + min);
					h = (max === r) ? (g - b) / d + (g < b ? 6 : 0) : (max === g) ? (b - r) / d + 2 : (r - g) / d + 4;
					h *= 60;
				}
				a[0] = (h + 0.5) | 0;
				a[1] = (s * 100 + 0.5) | 0;
				a[2] = (l * 100 + 0.5) | 0;
			}
			return a;
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ColorPropsPlugin.prototype"></a>[module gsap.ColorPropsPlugin.prototype](#apidoc.module.gsap.ColorPropsPlugin.prototype)

#### <a name="apidoc.element.gsap.ColorPropsPlugin.prototype._kill"></a>[function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.ColorPropsPlugin.prototype._kill)
- description and source-code
```javascript
_kill = function (lookup) {
		var pt = this._firstNumPT,
			prev;
		while (pt) {
			if (pt.p in lookup) {
				if (pt === p._firstNumPT) {
					this._firstNumPT = pt._next;
				}
				if (prev) {
					prev._next = pt._next;
				}
			} else {
				prev = pt;
			}
			pt = pt._next;
		}
		return this._super._kill(lookup);
	}
```
- example usage
```shell
...
			if (!vars && !target) {
				return this._enabled(false, false);
			}
			var tweens = (!target) ? this.getChildren(true, true, false) : this.getTweensOf(target),
				i = tweens.length,
				changed = false;
			while (--i > -1) {
				if (tweens[i]._kill(vars, target)) {
					changed = true;
				}
			}
			return changed;
		};

		p.clear = function(labels) {
...
```

#### <a name="apidoc.element.gsap.ColorPropsPlugin.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.ColorPropsPlugin.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween, index) {
				var p, proxy, pt, val;
				this._target = target;
				this._proxy = proxy = ((value.format + "").toUpperCase() === "NUMBER") ? {} : 0;
				for (p in value) {
					if (p !== "format") {
						if (proxy) {
							this._firstNumPT = pt = {_next:this._firstNumPT, t:target, p:p, f:(typeof(target[p]) === "function")};
							proxy[p] = "rgb(" + _parseColor(!pt.f ? target[p] : target[ ((p.indexOf("set") || typeof(target["get" + p.substr(3)]) !== "
function") ? p : "get" + p.substr(3)) ]()).join(",") + ")";
							val = value[p];
							if (typeof(val) === "function") {
								val = val(index, target);
							}
							this._addTween(proxy, p, "get", ((typeof(val) === "number") ? "rgb(" + _parseColor(val, false).join(",") + ")" : val), p,
null, null, _colorStringFilter);
						} else {
							this._addTween(target, p, "get", value[p], p, null, null, _colorStringFilter, index);
						}

					}
				}
				return true;
			}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.ColorPropsPlugin.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>constructor ()](#apidoc.element.gsap.ColorPropsPlugin.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ColorPropsPlugin.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.ColorPropsPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.ColorPropsPlugin.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (v) {
				var pt = this._firstNumPT,
					val;
				this._super.setRatio.call(this, v);
				while (pt) {
					val = _parseColor(this._proxy[pt.p], false);
					val = val[0] << 16 | val[1] << 8 | val[2];
					if (pt.f) {
						this._target[pt.p](val);
					} else {
						this._target[pt.p] = val;
					}
					pt = pt._next;
				}
			}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.Ease"></a>[module gsap.Ease](#apidoc.module.gsap.Ease)

#### <a name="apidoc.element.gsap.Ease.Ease"></a>[function <span class="apidocSignatureSpan">gsap.</span>Ease (func, extraParams, type, power)](#apidoc.element.gsap.Ease.Ease)
- description and source-code
```javascript
Ease = function (func, extraParams, type, power) {
				this._func = func;
				this._type = type || 0;
				this._power = power || 0;
				this._params = extraParams ? _baseParams.concat(extraParams) : _baseParams;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.Ease.register"></a>[function <span class="apidocSignatureSpan">gsap.Ease.</span>register (ease, names, types, create)](#apidoc.element.gsap.Ease.register)
- description and source-code
```javascript
register = function (ease, names, types, create) {
				var na = names.split(","),
					i = na.length,
					ta = (types || "easeIn,easeOut,easeInOut").split(","),
					e, name, j, type;
				while (--i > -1) {
					name = na[i];
					e = create ? _class("easing."+name, null, true) : gs.easing[name] || {};
					j = ta.length;
					while (--j > -1) {
						type = ta[j];
						_easeMap[name + "." + type] = _easeMap[type + name] = e[type] = ease.getRatio ? ease : ease[type] || new ease();
					}
				}
			}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.Ease.prototype"></a>[module gsap.Ease.prototype](#apidoc.module.gsap.Ease.prototype)

#### <a name="apidoc.element.gsap.Ease.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.Ease.prototype.</span>getRatio (p)](#apidoc.element.gsap.Ease.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
			if (this._func) {
				this._params[0] = p;
				return this._func.apply(null, this._params);
			}
			var t = this._type,
				pw = this._power,
				r = (t === 1) ? 1 - p : (t === 2) ? p : (p < 0.5) ? p * 2 : (1 - p) * 2;
			if (pw === 1) {
				r *= r;
			} else if (pw === 2) {
				r *= r * r;
			} else if (pw === 3) {
				r *= r * r * r;
			} else if (pw === 4) {
				r *= r * r * r * r;
			}
			return (t === 1) ? 1 - r : (t === 2) ? r : (p < 0.5) ? r / 2 : 1 - (r / 2);
		}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.EaseLookup"></a>[module gsap.EaseLookup](#apidoc.module.gsap.EaseLookup)

#### <a name="apidoc.element.gsap.EaseLookup.find"></a>[function <span class="apidocSignatureSpan">gsap.EaseLookup.</span>find (s)](#apidoc.element.gsap.EaseLookup.find)
- description and source-code
```javascript
find = function (s) {
					return Ease.map[s];
				}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ElasticIn"></a>[module gsap.ElasticIn](#apidoc.module.gsap.ElasticIn)

#### <a name="apidoc.element.gsap.ElasticIn.ElasticIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>ElasticIn (amplitude, period)](#apidoc.element.gsap.ElasticIn.ElasticIn)
- description and source-code
```javascript
ElasticIn = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ElasticIn.prototype"></a>[module gsap.ElasticIn.prototype](#apidoc.module.gsap.ElasticIn.prototype)

#### <a name="apidoc.element.gsap.ElasticIn.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>config (amplitude, period)](#apidoc.element.gsap.ElasticIn.prototype.config)
- description and source-code
```javascript
config = function (amplitude, period) {
				return new C(amplitude, period);
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticIn.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>constructor (amplitude, period)](#apidoc.element.gsap.ElasticIn.prototype.constructor)
- description and source-code
```javascript
constructor = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticIn.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.ElasticIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.ElasticIn.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return -(this._p1 * Math.pow(2, 10 * (p -= 1)) * Math.sin( (p - this._p3) * this._p2 ));
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.ElasticInOut"></a>[module gsap.ElasticInOut](#apidoc.module.gsap.ElasticInOut)

#### <a name="apidoc.element.gsap.ElasticInOut.ElasticInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ElasticInOut (amplitude, period)](#apidoc.element.gsap.ElasticInOut.ElasticInOut)
- description and source-code
```javascript
ElasticInOut = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ElasticInOut.prototype"></a>[module gsap.ElasticInOut.prototype](#apidoc.module.gsap.ElasticInOut.prototype)

#### <a name="apidoc.element.gsap.ElasticInOut.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>config (amplitude, period)](#apidoc.element.gsap.ElasticInOut.prototype.config)
- description and source-code
```javascript
config = function (amplitude, period) {
				return new C(amplitude, period);
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticInOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>constructor (amplitude, period)](#apidoc.element.gsap.ElasticInOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticInOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.ElasticInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ElasticInOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return ((p *= 2) < 1) ? -0.5 * (this._p1 * Math.pow(2, 10 * (p -= 1)) * Math.sin( (p - this._p3) * this._p2)) : this._p1 * Math
.pow(2, -10 *(p -= 1)) * Math.sin( (p - this._p3) * this._p2 ) * 0.5 + 1;
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.ElasticOut"></a>[module gsap.ElasticOut](#apidoc.module.gsap.ElasticOut)

#### <a name="apidoc.element.gsap.ElasticOut.ElasticOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ElasticOut (amplitude, period)](#apidoc.element.gsap.ElasticOut.ElasticOut)
- description and source-code
```javascript
ElasticOut = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ElasticOut.prototype"></a>[module gsap.ElasticOut.prototype](#apidoc.module.gsap.ElasticOut.prototype)

#### <a name="apidoc.element.gsap.ElasticOut.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>config (amplitude, period)](#apidoc.element.gsap.ElasticOut.prototype.config)
- description and source-code
```javascript
config = function (amplitude, period) {
				return new C(amplitude, period);
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>constructor (amplitude, period)](#apidoc.element.gsap.ElasticOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (amplitude, period) {
					this._p1 = (amplitude >= 1) ? amplitude : 1; //note: if amplitude is < 1, we simply adjust the period for a more natural feel
. Otherwise the math doesn't work right and the curve starts at 1.
					this._p2 = (period || def) / (amplitude < 1 ? amplitude : 1);
					this._p3 = this._p2 / _2PI * (Math.asin(1 / this._p1) || 0);
					this._p2 = _2PI / this._p2; //precalculate to optimize
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ElasticOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.ElasticOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ElasticOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return this._p1 * Math.pow(2, -10 * p) * Math.sin( (p - this._p3) * this._p2 ) + 1;
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.ExpoIn"></a>[module gsap.ExpoIn](#apidoc.module.gsap.ExpoIn)

#### <a name="apidoc.element.gsap.ExpoIn.ExpoIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>ExpoIn ()](#apidoc.element.gsap.ExpoIn.ExpoIn)
- description and source-code
```javascript
ExpoIn = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ExpoIn.prototype"></a>[module gsap.ExpoIn.prototype](#apidoc.module.gsap.ExpoIn.prototype)

#### <a name="apidoc.element.gsap.ExpoIn.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.ExpoIn.prototype.</span>constructor ()](#apidoc.element.gsap.ExpoIn.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ExpoIn.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.ExpoIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.ExpoIn.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return Math.pow(2, 10 * (p - 1)) - 0.001;
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.ExpoInOut"></a>[module gsap.ExpoInOut](#apidoc.module.gsap.ExpoInOut)

#### <a name="apidoc.element.gsap.ExpoInOut.ExpoInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ExpoInOut ()](#apidoc.element.gsap.ExpoInOut.ExpoInOut)
- description and source-code
```javascript
ExpoInOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ExpoInOut.prototype"></a>[module gsap.ExpoInOut.prototype](#apidoc.module.gsap.ExpoInOut.prototype)

#### <a name="apidoc.element.gsap.ExpoInOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.ExpoInOut.prototype.</span>constructor ()](#apidoc.element.gsap.ExpoInOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ExpoInOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.ExpoInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ExpoInOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return ((p *= 2) < 1) ? 0.5 * Math.pow(2, 10 * (p - 1)) : 0.5 * (2 - Math.pow(2, -10 * (p - 1)));
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.ExpoOut"></a>[module gsap.ExpoOut](#apidoc.module.gsap.ExpoOut)

#### <a name="apidoc.element.gsap.ExpoOut.ExpoOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>ExpoOut ()](#apidoc.element.gsap.ExpoOut.ExpoOut)
- description and source-code
```javascript
ExpoOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ExpoOut.prototype"></a>[module gsap.ExpoOut.prototype](#apidoc.module.gsap.ExpoOut.prototype)

#### <a name="apidoc.element.gsap.ExpoOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.ExpoOut.prototype.</span>constructor ()](#apidoc.element.gsap.ExpoOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.ExpoOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.ExpoOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.ExpoOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return 1 - Math.pow(2, -10 * p);
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.RoughEase"></a>[module gsap.RoughEase](#apidoc.module.gsap.RoughEase)

#### <a name="apidoc.element.gsap.RoughEase.RoughEase"></a>[function <span class="apidocSignatureSpan">gsap.</span>RoughEase (vars)](#apidoc.element.gsap.RoughEase.RoughEase)
- description and source-code
```javascript
RoughEase = function (vars) {
			vars = vars || {};
			var taper = vars.taper || "none",
				a = [],
				cnt = 0,
				points = (vars.points || 20) | 0,
				i = points,
				randomize = (vars.randomize !== false),
				clamp = (vars.clamp === true),
				template = (vars.template instanceof Ease) ? vars.template : null,
				strength = (typeof(vars.strength) === "number") ? vars.strength * 0.4 : 0.4,
				x, y, bump, invX, obj, pnt;
			while (--i > -1) {
				x = randomize ? Math.random() : (1 / points) * i;
				y = template ? template.getRatio(x) : x;
				if (taper === "none") {
					bump = strength;
				} else if (taper === "out") {
					invX = 1 - x;
					bump = invX * invX * strength;
				} else if (taper === "in") {
					bump = x * x * strength;
				} else if (x < 0.5) {  //"both" (start)
					invX = x * 2;
					bump = invX * invX * 0.5 * strength;
				} else {				//"both" (end)
					invX = (1 - x) * 2;
					bump = invX * invX * 0.5 * strength;
				}
				if (randomize) {
					y += (Math.random() * bump) - (bump * 0.5);
				} else if (i % 2) {
					y += bump * 0.5;
				} else {
					y -= bump * 0.5;
				}
				if (clamp) {
					if (y > 1) {
						y = 1;
					} else if (y < 0) {
						y = 0;
					}
				}
				a[cnt++] = {x:x, y:y};
			}
			a.sort(function(a, b) {
				return a.x - b.x;
			});

			pnt = new EasePoint(1, 1, null);
			i = points;
			while (--i > -1) {
				obj = a[i];
				pnt = new EasePoint(obj.x, obj.y, pnt);
			}

			this._prev = new EasePoint(0, 0, (pnt.t !== 0) ? pnt : pnt.next);
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.RoughEase.prototype"></a>[module gsap.RoughEase.prototype](#apidoc.module.gsap.RoughEase.prototype)

#### <a name="apidoc.element.gsap.RoughEase.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>config (vars)](#apidoc.element.gsap.RoughEase.prototype.config)
- description and source-code
```javascript
config = function (vars) {
			return new RoughEase(vars);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.RoughEase.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>constructor (vars)](#apidoc.element.gsap.RoughEase.prototype.constructor)
- description and source-code
```javascript
constructor = function (vars) {
			vars = vars || {};
			var taper = vars.taper || "none",
				a = [],
				cnt = 0,
				points = (vars.points || 20) | 0,
				i = points,
				randomize = (vars.randomize !== false),
				clamp = (vars.clamp === true),
				template = (vars.template instanceof Ease) ? vars.template : null,
				strength = (typeof(vars.strength) === "number") ? vars.strength * 0.4 : 0.4,
				x, y, bump, invX, obj, pnt;
			while (--i > -1) {
				x = randomize ? Math.random() : (1 / points) * i;
				y = template ? template.getRatio(x) : x;
				if (taper === "none") {
					bump = strength;
				} else if (taper === "out") {
					invX = 1 - x;
					bump = invX * invX * strength;
				} else if (taper === "in") {
					bump = x * x * strength;
				} else if (x < 0.5) {  //"both" (start)
					invX = x * 2;
					bump = invX * invX * 0.5 * strength;
				} else {				//"both" (end)
					invX = (1 - x) * 2;
					bump = invX * invX * 0.5 * strength;
				}
				if (randomize) {
					y += (Math.random() * bump) - (bump * 0.5);
				} else if (i % 2) {
					y += bump * 0.5;
				} else {
					y -= bump * 0.5;
				}
				if (clamp) {
					if (y > 1) {
						y = 1;
					} else if (y < 0) {
						y = 0;
					}
				}
				a[cnt++] = {x:x, y:y};
			}
			a.sort(function(a, b) {
				return a.x - b.x;
			});

			pnt = new EasePoint(1, 1, null);
			i = points;
			while (--i > -1) {
				obj = a[i];
				pnt = new EasePoint(obj.x, obj.y, pnt);
			}

			this._prev = new EasePoint(0, 0, (pnt.t !== 0) ? pnt : pnt.next);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.RoughEase.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.RoughEase.prototype.</span>getRatio (p)](#apidoc.element.gsap.RoughEase.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
			var pnt = this._prev;
			if (p > pnt.t) {
				while (pnt.next && p >= pnt.t) {
					pnt = pnt.next;
				}
				pnt = pnt.prev;
			} else {
				while (pnt.prev && p <= pnt.t) {
					pnt = pnt.prev;
				}
			}
			this._prev = pnt;
			return (pnt.v + ((p - pnt.t) / pnt.gap) * pnt.c);
		}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.SineIn"></a>[module gsap.SineIn](#apidoc.module.gsap.SineIn)

#### <a name="apidoc.element.gsap.SineIn.SineIn"></a>[function <span class="apidocSignatureSpan">gsap.</span>SineIn ()](#apidoc.element.gsap.SineIn.SineIn)
- description and source-code
```javascript
SineIn = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.SineIn.prototype"></a>[module gsap.SineIn.prototype](#apidoc.module.gsap.SineIn.prototype)

#### <a name="apidoc.element.gsap.SineIn.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.SineIn.prototype.</span>constructor ()](#apidoc.element.gsap.SineIn.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SineIn.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.SineIn.prototype.</span>getRatio (p)](#apidoc.element.gsap.SineIn.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return -Math.cos(p * _HALF_PI) + 1;
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.SineInOut"></a>[module gsap.SineInOut](#apidoc.module.gsap.SineInOut)

#### <a name="apidoc.element.gsap.SineInOut.SineInOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>SineInOut ()](#apidoc.element.gsap.SineInOut.SineInOut)
- description and source-code
```javascript
SineInOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.SineInOut.prototype"></a>[module gsap.SineInOut.prototype](#apidoc.module.gsap.SineInOut.prototype)

#### <a name="apidoc.element.gsap.SineInOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.SineInOut.prototype.</span>constructor ()](#apidoc.element.gsap.SineInOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SineInOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.SineInOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.SineInOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return -0.5 * (Math.cos(Math.PI * p) - 1);
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.SineOut"></a>[module gsap.SineOut](#apidoc.module.gsap.SineOut)

#### <a name="apidoc.element.gsap.SineOut.SineOut"></a>[function <span class="apidocSignatureSpan">gsap.</span>SineOut ()](#apidoc.element.gsap.SineOut.SineOut)
- description and source-code
```javascript
SineOut = function (){}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.SineOut.prototype"></a>[module gsap.SineOut.prototype](#apidoc.module.gsap.SineOut.prototype)

#### <a name="apidoc.element.gsap.SineOut.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.SineOut.prototype.</span>constructor ()](#apidoc.element.gsap.SineOut.prototype.constructor)
- description and source-code
```javascript
constructor = function (){}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SineOut.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.SineOut.prototype.</span>getRatio (p)](#apidoc.element.gsap.SineOut.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
				return Math.sin(p * _HALF_PI);
			}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.SlowMo"></a>[module gsap.SlowMo](#apidoc.module.gsap.SlowMo)

#### <a name="apidoc.element.gsap.SlowMo.SlowMo"></a>[function <span class="apidocSignatureSpan">gsap.</span>SlowMo (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.SlowMo)
- description and source-code
```javascript
SlowMo = function (linearRatio, power, yoyoMode) {
				power = (power || power === 0) ? power : 0.7;
				if (linearRatio == null) {
					linearRatio = 0.7;
				} else if (linearRatio > 1) {
					linearRatio = 1;
				}
				this._p = (linearRatio !== 1) ? power : 0;
				this._p1 = (1 - linearRatio) / 2;
				this._p2 = linearRatio;
				this._p3 = this._p1 + this._p2;
				this._calcEnd = (yoyoMode === true);
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SlowMo.config"></a>[function <span class="apidocSignatureSpan">gsap.SlowMo.</span>config (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.config)
- description and source-code
```javascript
config = function (linearRatio, power, yoyoMode) {
			return new SlowMo(linearRatio, power, yoyoMode);
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.SlowMo.prototype"></a>[module gsap.SlowMo.prototype](#apidoc.module.gsap.SlowMo.prototype)

#### <a name="apidoc.element.gsap.SlowMo.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>config (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.prototype.config)
- description and source-code
```javascript
config = function (linearRatio, power, yoyoMode) {
			return new SlowMo(linearRatio, power, yoyoMode);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SlowMo.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>constructor (linearRatio, power, yoyoMode)](#apidoc.element.gsap.SlowMo.prototype.constructor)
- description and source-code
```javascript
constructor = function (linearRatio, power, yoyoMode) {
				power = (power || power === 0) ? power : 0.7;
				if (linearRatio == null) {
					linearRatio = 0.7;
				} else if (linearRatio > 1) {
					linearRatio = 1;
				}
				this._p = (linearRatio !== 1) ? power : 0;
				this._p1 = (1 - linearRatio) / 2;
				this._p2 = linearRatio;
				this._p3 = this._p1 + this._p2;
				this._calcEnd = (yoyoMode === true);
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SlowMo.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.SlowMo.prototype.</span>getRatio (p)](#apidoc.element.gsap.SlowMo.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
			var r = p + (0.5 - p) * this._p;
			if (p < this._p1) {
				return this._calcEnd ? 1 - ((p = 1 - (p / this._p1)) * p) : r - ((p = 1 - (p / this._p1)) * p * p * p * r);
			} else if (p > this._p3) {
				return this._calcEnd ? 1 - (p = (p - this._p3) / this._p1) * p : r + ((p - r) * (p = (p - this._p3) / this._p1) * p * p * p);
			}
			return this._calcEnd ? 1 : r;
		}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.SteppedEase"></a>[module gsap.SteppedEase](#apidoc.module.gsap.SteppedEase)

#### <a name="apidoc.element.gsap.SteppedEase.SteppedEase"></a>[function <span class="apidocSignatureSpan">gsap.</span>SteppedEase (steps)](#apidoc.element.gsap.SteppedEase.SteppedEase)
- description and source-code
```javascript
SteppedEase = function (steps) {
				steps = steps || 1;
				this._p1 = 1 / steps;
				this._p2 = steps + 1;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SteppedEase.config"></a>[function <span class="apidocSignatureSpan">gsap.SteppedEase.</span>config (steps)](#apidoc.element.gsap.SteppedEase.config)
- description and source-code
```javascript
config = function (steps) {
			return new SteppedEase(steps);
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.SteppedEase.prototype"></a>[module gsap.SteppedEase.prototype](#apidoc.module.gsap.SteppedEase.prototype)

#### <a name="apidoc.element.gsap.SteppedEase.prototype.config"></a>[function <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>config (steps)](#apidoc.element.gsap.SteppedEase.prototype.config)
- description and source-code
```javascript
config = function (steps) {
			return new SteppedEase(steps);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SteppedEase.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>constructor (steps)](#apidoc.element.gsap.SteppedEase.prototype.constructor)
- description and source-code
```javascript
constructor = function (steps) {
				steps = steps || 1;
				this._p1 = 1 / steps;
				this._p2 = steps + 1;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.SteppedEase.prototype.getRatio"></a>[function <span class="apidocSignatureSpan">gsap.SteppedEase.prototype.</span>getRatio (p)](#apidoc.element.gsap.SteppedEase.prototype.getRatio)
- description and source-code
```javascript
getRatio = function (p) {
			if (p < 0) {
				p = 0;
			} else if (p >= 1) {
				p = 0.999999999;
			}
			return ((this._p2 * p) >> 0) * this._p1;
		}
```
- example usage
```shell
...
		p.render = function(time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
...
```



# <a name="apidoc.module.gsap.TimelineLite"></a>[module gsap.TimelineLite](#apidoc.module.gsap.TimelineLite)

#### <a name="apidoc.element.gsap.TimelineLite.TimelineLite"></a>[function <span class="apidocSignatureSpan">gsap.</span>TimelineLite (vars)](#apidoc.element.gsap.TimelineLite.TimelineLite)
- description and source-code
```javascript
TimelineLite = function (vars) {
				SimpleTimeline.call(this, vars);
				this._labels = {};
				this.autoRemoveChildren = (this.vars.autoRemoveChildren === true);
				this.smoothChildTiming = (this.vars.smoothChildTiming === true);
				this._sortChildren = true;
				this._onUpdate = this.vars.onUpdate;
				var v = this.vars,
					val, p;
				for (p in v) {
					val = v[p];
					if (_isArray(val)) if (val.join("").indexOf("{self}") !== -1) {
						v[p] = this._swapSelfInParams(val);
					}
				}
				if (_isArray(v.tweens)) {
					this.add(v.tweens, 0, v.align, v.stagger);
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.exportRoot"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.</span>exportRoot (vars, ignoreDelayedCalls)](#apidoc.element.gsap.TimelineLite.exportRoot)
- description and source-code
```javascript
exportRoot = function (vars, ignoreDelayedCalls) {
			vars = vars || {};
			if (vars.smoothChildTiming == null) {
				vars.smoothChildTiming = true;
			}
			var tl = new TimelineLite(vars),
				root = tl._timeline,
				tween, next;
			if (ignoreDelayedCalls == null) {
				ignoreDelayedCalls = true;
			}
			root._remove(tl, true);
			tl._startTime = 0;
			tl._rawPrevTime = tl._time = tl._totalTime = root._time;
			tween = root._first;
			while (tween) {
				next = tween._next;
				if (!ignoreDelayedCalls || !(tween instanceof TweenLite && tween.target === tween.vars.onComplete)) {
					tl.add(tween, tween._startTime - tween._delay);
				}
				tween = next;
			}
			root.add(tl, 0);
			return tl;
		}
```
- example usage
```shell
...
					if (time > totalDuration && !uncapped) {
						time = totalDuration;
					}
					this._startTime = (this._paused ? this._pauseTime : tl._time) - ((!this._reversed ? time : totalDuration - time) / this._timeScale
);
					if (!tl._dirty) { //for performance improvement. If the parent's cache is already dirty, it already took care of marking the
 ancestors as dirty too, so skip the function call here.
						this._uncache(false);
					}
					//in case any of the ancestor timelines had completed but should now be enabled, we should reset their totalTime() which will
 also ensure that they're lined up properly and enabled. Skip for animations that are on the root (wasteful). Example: a TimelineLite
.exportRoot() is performed when there's a paused tween on the root, the export will not complete until that tween is unpaused, but
 imagine a child gets restarted later, after all [unpaused] tweens have completed. The startTime of that child would get pushed
out, but one of the ancestors may have completed.
					if (tl._timeline) {
						while (tl._timeline) {
							if (tl._timeline._time !== (tl._startTime + tl._totalTime) / tl._timeScale) {
								tl.totalTime(tl._totalTime, true);
							}
							tl = tl._timeline;
						}
...
```



# <a name="apidoc.module.gsap.TimelineLite._internals"></a>[module gsap.TimelineLite._internals](#apidoc.module.gsap.TimelineLite._internals)

#### <a name="apidoc.element.gsap.TimelineLite._internals.pauseCallback"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite._internals.</span>pauseCallback ()](#apidoc.element.gsap.TimelineLite._internals.pauseCallback)
- description and source-code
```javascript
pauseCallback = function () {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TimelineLite.prototype"></a>[module gsap.TimelineLite.prototype](#apidoc.module.gsap.TimelineLite.prototype)

#### <a name="apidoc.element.gsap.TimelineLite.prototype._contains"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_contains (tween)](#apidoc.element.gsap.TimelineLite.prototype._contains)
- description and source-code
```javascript
_contains = function (tween) {
			var tl = tween.timeline;
			while (tl) {
				if (tl === this) {
					return true;
				}
				tl = tl.timeline;
			}
			return false;
		}
```
- example usage
```shell
...
				tweens, i;
			if (disabled) {
				this._enabled(true, true); //getTweensOf() filters out disabled tweens, and we have to mark them as _gc = true when the timeline
 completes in order to allow clean garbage collection, so temporarily re-enable the timeline here.
			}
			tweens = TweenLite.getTweensOf(target);
			i = tweens.length;
			while (--i > -1) {
				if (tweens[i].timeline === this || (nested && this._contains(tweens[i]))) {
					a[cnt++] = tweens[i];
				}
			}
			if (disabled) {
				this._enabled(false, true);
			}
			return a;
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype._enabled"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_enabled (enabled, ignoreTimeline)](#apidoc.element.gsap.TimelineLite.prototype._enabled)
- description and source-code
```javascript
_enabled = function (enabled, ignoreTimeline) {
			if (enabled === this._gc) {
				var tween = this._first;
				while (tween) {
					tween._enabled(enabled, true);
					tween = tween._next;
				}
			}
			return SimpleTimeline.prototype._enabled.call(this, enabled, ignoreTimeline);
		}
```
- example usage
```shell
...
				//in case any of the ancestors had completed but should now be enabled...
				tl = this;
				beforeRawTime = (tl.rawTime() > value._startTime); //if the tween is placed on the timeline so that it starts BEFORE the current
 rawTime, we should align the playhead (move the timeline). This is because sometimes users will create a timeline, let it finish
, and much later append a tween and expect it to run instead of jumping to its end state. While technically one could argue that
 it should jump to its end state, that's not what users intuitively expect.
				while (tl._timeline) {
					if (beforeRawTime && tl._timeline.smoothChildTiming) {
						tl.totalTime(tl._totalTime, true); //moves the timeline (shifts its startTime) if necessary, and also enables it.
					} else if (tl._gc) {
						tl._enabled(true, false);
					}
					tl = tl._timeline;
				}
			}

			return this;
		};
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype._hasPausedChild"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_hasPausedChild ()](#apidoc.element.gsap.TimelineLite.prototype._hasPausedChild)
- description and source-code
```javascript
_hasPausedChild = function () {
			var tween = this._first;
			while (tween) {
				if (tween._paused || ((tween instanceof TimelineLite) && tween._hasPausedChild())) {
					return true;
				}
				tween = tween._next;
			}
			return false;
		}
```
- example usage
```shell
...
				prevTime = this._time,
				prevStart = this._startTime,
				prevTimeScale = this._timeScale,
				prevPaused = this._paused,
				tween, isComplete, next, callback, internalForce, pauseTween, curTime;
			if (time >= totalDur - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = totalDur;
				if (!this._reversed) if (!this._hasPausedChild()) {
					isComplete = true;
					callback = "onComplete";
					internalForce = !!this._timeline.autoRemoveChildren; //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
					if (this._duration === 0) if ((time <= 0 && time >= -0.0000001) || this._rawPrevTime < 0 || this._rawPrevTime === _tinyNum)
if (this._rawPrevTime !== time && this._first) {
						internalForce = true;
						if (this._rawPrevTime > _tinyNum) {
							callback = "onReverseComplete";
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype._kill"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_kill (vars, target)](#apidoc.element.gsap.TimelineLite.prototype._kill)
- description and source-code
```javascript
_kill = function (vars, target) {
			if (!vars && !target) {
				return this._enabled(false, false);
			}
			var tweens = (!target) ? this.getChildren(true, true, false) : this.getTweensOf(target),
				i = tweens.length,
				changed = false;
			while (--i > -1) {
				if (tweens[i]._kill(vars, target)) {
					changed = true;
				}
			}
			return changed;
		}
```
- example usage
```shell
...
			if (!vars && !target) {
				return this._enabled(false, false);
			}
			var tweens = (!target) ? this.getChildren(true, true, false) : this.getTweensOf(target),
				i = tweens.length,
				changed = false;
			while (--i > -1) {
				if (tweens[i]._kill(vars, target)) {
					changed = true;
				}
			}
			return changed;
		};

		p.clear = function(labels) {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype._parseTimeOrLabel"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_parseTimeOrLabel (timeOrLabel, offsetOrLabel, appendIfAbsent, ignore)](#apidoc.element.gsap.TimelineLite.prototype._parseTimeOrLabel)
- description and source-code
```javascript
_parseTimeOrLabel = function (timeOrLabel, offsetOrLabel, appendIfAbsent, ignore) {
			var i;
			//if we're about to add a tween/timeline (or an array of them) that's already a child of this timeline, we should remove it first
 so that it doesn't contaminate the duration().
			if (ignore instanceof Animation && ignore.timeline === this) {
				this.remove(ignore);
			} else if (ignore && ((ignore instanceof Array) || (ignore.push && _isArray(ignore)))) {
				i = ignore.length;
				while (--i > -1) {
					if (ignore[i] instanceof Animation && ignore[i].timeline === this) {
						this.remove(ignore[i]);
					}
				}
			}
			if (typeof(offsetOrLabel) === "string") {
				return this._parseTimeOrLabel(offsetOrLabel, (appendIfAbsent && typeof(timeOrLabel) === "number" && this._labels[offsetOrLabel
] == null) ? timeOrLabel - this.duration() : 0, appendIfAbsent);
			}
			offsetOrLabel = offsetOrLabel || 0;
			if (typeof(timeOrLabel) === "string" && (isNaN(timeOrLabel) || this._labels[timeOrLabel] != null)) { //if the string is a number
 like "1", check to see if there's a label with that name, otherwise interpret it as a number (absolute value).
				i = timeOrLabel.indexOf("=");
				if (i === -1) {
					if (this._labels[timeOrLabel] == null) {
						return appendIfAbsent ? (this._labels[timeOrLabel] = this.duration() + offsetOrLabel) : offsetOrLabel;
					}
					return this._labels[timeOrLabel] + offsetOrLabel;
				}
				offsetOrLabel = parseInt(timeOrLabel.charAt(i-1) + "1", 10) * Number(timeOrLabel.substr(i+1));
				timeOrLabel = (i > 1) ? this._parseTimeOrLabel(timeOrLabel.substr(0, i-1), 0, appendIfAbsent) : this.duration();
			} else if (timeOrLabel == null) {
				timeOrLabel = this.duration();
			}
			return Number(timeOrLabel) + offsetOrLabel;
		}
```
- example usage
```shell
...
		};

		p.call = function(callback, params, scope, position) {
			return this.add( TweenLite.delayedCall(0, callback, params, scope), position);
		};

		p.set = function(target, vars, position) {
			position = this._parseTimeOrLabel(position, 0, true);
			if (vars.immediateRender == null) {
				vars.immediateRender = (position === this._time && !this._paused);
			}
			return this.add( new TweenLite(target, 0, vars), position);
		};

		TimelineLite.exportRoot = function(vars, ignoreDelayedCalls) {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype._remove"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>_remove (tween, skipDisable)](#apidoc.element.gsap.TimelineLite.prototype._remove)
- description and source-code
```javascript
_remove = function (tween, skipDisable) {
			SimpleTimeline.prototype._remove.call(this, tween, skipDisable);
			var last = this._last;
			if (!last) {
				this._time = this._totalTime = this._duration = this._totalDuration = 0;
			} else if (this._time > this.duration()) {
				this._time = this._duration;
				this._totalTime = this._totalDuration;
			}
			return this;
		}
```
- example usage
```shell
...
			}
			var tl = new TimelineLite(vars),
				root = tl._timeline,
				tween, next;
			if (ignoreDelayedCalls == null) {
				ignoreDelayedCalls = true;
			}
			root._remove(tl, true);
			tl._startTime = 0;
			tl._rawPrevTime = tl._time = tl._totalTime = root._time;
			tween = root._first;
			while (tween) {
				next = tween._next;
				if (!ignoreDelayedCalls || !(tween instanceof TweenLite && tween.target === tween.vars.onComplete)) {
					tl.add(tween, tween._startTime - tween._delay);
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.add"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>add (value, position, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.add)
- description and source-code
```javascript
add = function (value, position, align, stagger) {
			var curTime, l, i, child, tl, beforeRawTime;
			if (typeof(position) !== "number") {
				position = this._parseTimeOrLabel(position, 0, true, value);
			}
			if (!(value instanceof Animation)) {
				if ((value instanceof Array) || (value && value.push && _isArray(value))) {
					align = align || "normal";
					stagger = stagger || 0;
					curTime = position;
					l = value.length;
					for (i = 0; i < l; i++) {
						if (_isArray(child = value[i])) {
							child = new TimelineLite({tweens:child});
						}
						this.add(child, curTime);
						if (typeof(child) !== "string" && typeof(child) !== "function") {
							if (align === "sequence") {
								curTime = child._startTime + (child.totalDuration() / child._timeScale);
							} else if (align === "start") {
								child._startTime -= child.delay();
							}
						}
						curTime += stagger;
					}
					return this._uncache(true);
				} else if (typeof(value) === "string") {
					return this.addLabel(value, position);
				} else if (typeof(value) === "function") {
					value = TweenLite.delayedCall(0, value);
				} else {
					throw("Cannot add " + value + " into the timeline; it is not a tween, timeline, function, or string.");
				}
			}

			SimpleTimeline.prototype.add.call(this, value, position);

			//if the timeline has already ended but the inserted tween/timeline extends the duration, we should enable this timeline again
 so that it renders properly. We should also align the playhead with the parent timeline's when appropriate.
			if (this._gc || this._time === this._duration) if (!this._paused) if (this._duration < this.duration()) {
				//in case any of the ancestors had completed but should now be enabled...
				tl = this;
				beforeRawTime = (tl.rawTime() > value._startTime); //if the tween is placed on the timeline so that it starts BEFORE the current
 rawTime, we should align the playhead (move the timeline). This is because sometimes users will create a timeline, let it finish
, and much later append a tween and expect it to run instead of jumping to its end state. While technically one could argue that
 it should jump to its end state, that's not what users intuitively expect.
				while (tl._timeline) {
					if (beforeRawTime && tl._timeline.smoothChildTiming) {
						tl.totalTime(tl._totalTime, true); //moves the timeline (shifts its startTime) if necessary, and also enables it.
					} else if (tl._gc) {
						tl._enabled(true, false);
					}
					tl = tl._timeline;
				}
			}

			return this;
		}
```
- example usage
```shell
...
				for (p in v) {
					val = v[p];
					if (_isArray(val)) if (val.join("").indexOf("{self}") !== -1) {
						v[p] = this._swapSelfInParams(val);
					}
				}
				if (_isArray(v.tweens)) {
					this.add(v.tweens, 0, v.align, v.stagger);
				}
			},
			_tinyNum = 0.0000000001,
			TweenLiteInternals = TweenLite._internals,
			_internals = TimelineLite._internals = {},
			_isSelector = TweenLiteInternals.isSelector,
			_isArray = TweenLiteInternals.isArray,
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.addLabel"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>addLabel (label, position)](#apidoc.element.gsap.TimelineLite.prototype.addLabel)
- description and source-code
```javascript
addLabel = function (label, position) {
			this._labels[label] = this._parseTimeOrLabel(position);
			return this;
		}
```
- example usage
```shell
...
								child._startTime -= child.delay();
							}
						}
						curTime += stagger;
					}
					return this._uncache(true);
				} else if (typeof(value) === "string") {
					return this.addLabel(value, position);
				} else if (typeof(value) === "function") {
					value = TweenLite.delayedCall(0, value);
				} else {
					throw("Cannot add " + value + " into the timeline; it is not a tween, timeline, function, or string.");
				}
			}
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.addPause"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>addPause (position, callback, params, scope)](#apidoc.element.gsap.TimelineLite.prototype.addPause)
- description and source-code
```javascript
addPause = function (position, callback, params, scope) {
			var t = TweenLite.delayedCall(0, _pauseCallback, params, scope || this);
			t.vars.onComplete = t.vars.onReverseComplete = callback;
			t.data = "isPause";
			this._hasPause = true;
			return this.add(t, position);
		}
```
- example usage
```shell
...
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
						time = 0;
					}
					if (prevRawPrevTime < 0 || (time <= 0 && time >= -0.0000001) || (prevRawPrevTime === _tinyNum && this.data !== "isPause"))
if (prevRawPrevTime !== time) { //note: when this.data is "isPause", it's a callback added by addPause() on a timeline that we should
 not be triggered when LEAVING its exact start time. In other words, tl.addPause(1).play(1) shouldn't pause.
						force = true;
						if (prevRawPrevTime > _tinyNum) {
							callback = "onReverseComplete";
						}
					}
					this._rawPrevTime = rawPrevTime = (!suppressEvents || time || prevRawPrevTime === time) ? time : _tinyNum; //when the playhead
 arrives at EXACTLY time 0 (right on top) of a zero-duration tween, we need to discern if events are suppressed so that when the
 playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callback would be triggered
 in this render. Basically, the callback should fire either when the playhead ARRIVES or LEAVES this exact spot, not both. Imagine
 doing a timeline.seek(0) and there's a callback that sits at 0. Since events are suppressed on that seek() by default, nothing
will fire, but when the playhead moves off of that position, the callback should fire. This behavior is what people intuitively
expect. We set the _rawPrevTime to be a precise tiny number to indicate this scenario rather than using another property/variable
 which would increase memory usage. This technique is less readable, but more efficient.
				}
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.append"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>append (value, offsetOrLabel)](#apidoc.element.gsap.TimelineLite.prototype.append)
- description and source-code
```javascript
append = function (value, offsetOrLabel) {
			return this.add(value, this._parseTimeOrLabel(null, offsetOrLabel, true, value));
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.appendMultiple"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>appendMultiple (tweens, offsetOrLabel, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.appendMultiple)
- description and source-code
```javascript
appendMultiple = function (tweens, offsetOrLabel, align, stagger) {
			return this.add(tweens, this._parseTimeOrLabel(null, offsetOrLabel, true, tweens), align, stagger);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.call"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>call (callback, params, scope, position)](#apidoc.element.gsap.TimelineLite.prototype.call)
- description and source-code
```javascript
call = function (callback, params, scope, position) {
			return this.add( TweenLite.delayedCall(0, callback, params, scope), position);
		}
```
- example usage
```shell
...
(_gsScope._gsQueue || (_gsScope._gsQueue = [])).push( function() {

	"use strict";

	_gsScope._gsDefine("TimelineLite", ["core.Animation","core.SimpleTimeline","TweenLite"], function(Animation, SimpleTimeline, TweenLite
) {

		var TimelineLite = function(vars) {
				SimpleTimeline.call(this, vars);
				this._labels = {};
				this.autoRemoveChildren = (this.vars.autoRemoveChildren === true);
				this.smoothChildTiming = (this.vars.smoothChildTiming === true);
				this._sortChildren = true;
				this._onUpdate = this.vars.onUpdate;
				var v = this.vars,
					val, p;
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.clear"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>clear (labels)](#apidoc.element.gsap.TimelineLite.prototype.clear)
- description and source-code
```javascript
clear = function (labels) {
			var tweens = this.getChildren(false, true, true),
				i = tweens.length;
			this._time = this._totalTime = 0;
			while (--i > -1) {
				tweens[i]._enabled(false, false);
			}
			if (labels !== false) {
				this._labels = {};
			}
			return this._uncache(true);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>constructor (vars)](#apidoc.element.gsap.TimelineLite.prototype.constructor)
- description and source-code
```javascript
constructor = function (vars) {
				SimpleTimeline.call(this, vars);
				this._labels = {};
				this.autoRemoveChildren = (this.vars.autoRemoveChildren === true);
				this.smoothChildTiming = (this.vars.smoothChildTiming === true);
				this._sortChildren = true;
				this._onUpdate = this.vars.onUpdate;
				var v = this.vars,
					val, p;
				for (p in v) {
					val = v[p];
					if (_isArray(val)) if (val.join("").indexOf("{self}") !== -1) {
						v[p] = this._swapSelfInParams(val);
					}
				}
				if (_isArray(v.tweens)) {
					this.add(v.tweens, 0, v.align, v.stagger);
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.duration"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>duration (value)](#apidoc.element.gsap.TimelineLite.prototype.duration)
- description and source-code
```javascript
duration = function (value) {
			if (!arguments.length) {
				if (this._dirty) {
					this.totalDuration(); //just triggers recalculation
				}
				return this._duration;
			}
			if (this.duration() !== 0 && value !== 0) {
				this.timeScale(this._duration / value);
			}
			return this;
		}
```
- example usage
```shell
...
					throw("Cannot add " + value + " into the timeline; it is not a tween, timeline, function, or string.");
				}
			}

			SimpleTimeline.prototype.add.call(this, value, position);

			//if the timeline has already ended but the inserted tween/timeline extends the duration, we should enable this timeline again
 so that it renders properly. We should also align the playhead with the parent timeline's when appropriate.
			if (this._gc || this._time === this._duration) if (!this._paused) if (this._duration < this.duration()) {
				//in case any of the ancestors had completed but should now be enabled...
				tl = this;
				beforeRawTime = (tl.rawTime() > value._startTime); //if the tween is placed on the timeline so that it starts BEFORE the current
 rawTime, we should align the playhead (move the timeline). This is because sometimes users will create a timeline, let it finish
, and much later append a tween and expect it to run instead of jumping to its end state. While technically one could argue that
 it should jump to its end state, that's not what users intuitively expect.
				while (tl._timeline) {
					if (beforeRawTime && tl._timeline.smoothChildTiming) {
						tl.totalTime(tl._totalTime, true); //moves the timeline (shifts its startTime) if necessary, and also enables it.
					} else if (tl._gc) {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.from"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>from (target, duration, vars, position)](#apidoc.element.gsap.TimelineLite.prototype.from)
- description and source-code
```javascript
from = function (target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		}
```
- example usage
```shell
...

		p.to = function(target, duration, vars, position) {
			var Engine = (vars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( new Engine(target, duration, vars), position) : this.set(target, vars, position);
		};

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
			var Engine = (toVars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( Engine.fromTo(target, duration, fromVars, toVars), position) : this.set(target, toVars, position);
		};
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.fromTo"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>fromTo (target, duration, fromVars, toVars, position)](#apidoc.element.gsap.TimelineLite.prototype.fromTo)
- description and source-code
```javascript
fromTo = function (target, duration, fromVars, toVars, position) {
			var Engine = (toVars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( Engine.fromTo(target, duration, fromVars, toVars), position) : this.set(target, toVars, position);
		}
```
- example usage
```shell
...

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
			var Engine = (toVars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( Engine.fromTo(target, duration, fromVars, toVars), position) : this.set(target, toVars, position);
		};

		p.staggerTo = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			var tl = new TimelineLite({onComplete:onCompleteAll, onCompleteParams:onCompleteAllParams, callbackScope:onCompleteAllScope,
smoothChildTiming:this.smoothChildTiming}),
				cycle = vars.cycle,
				copy, i;
			if (typeof(targets) === "string") {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.getChildren"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>getChildren (nested, tweens, timelines, ignoreBeforeTime)](#apidoc.element.gsap.TimelineLite.prototype.getChildren)
- description and source-code
```javascript
getChildren = function (nested, tweens, timelines, ignoreBeforeTime) {
			ignoreBeforeTime = ignoreBeforeTime || -9999999999;
			var a = [],
				tween = this._first,
				cnt = 0;
			while (tween) {
				if (tween._startTime < ignoreBeforeTime) {
					//do nothing
				} else if (tween instanceof TweenLite) {
					if (tweens !== false) {
						a[cnt++] = tween;
					}
				} else {
					if (timelines !== false) {
						a[cnt++] = tween;
					}
					if (nested !== false) {
						a = a.concat(tween.getChildren(true, tweens, timelines));
						cnt = a.length;
					}
				}
				tween = tween._next;
			}
			return a;
		}
```
- example usage
```shell
...
						a[cnt++] = tween;
					}
				} else {
					if (timelines !== false) {
						a[cnt++] = tween;
					}
					if (nested !== false) {
						a = a.concat(tween.getChildren(true, tweens, timelines));
						cnt = a.length;
					}
				}
				tween = tween._next;
			}
			return a;
		};
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.getLabelTime"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>getLabelTime (label)](#apidoc.element.gsap.TimelineLite.prototype.getLabelTime)
- description and source-code
```javascript
getLabelTime = function (label) {
			return (this._labels[label] != null) ? this._labels[label] : -1;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.getTweensOf"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>getTweensOf (target, nested)](#apidoc.element.gsap.TimelineLite.prototype.getTweensOf)
- description and source-code
```javascript
getTweensOf = function (target, nested) {
			var disabled = this._gc,
				a = [],
				cnt = 0,
				tweens, i;
			if (disabled) {
				this._enabled(true, true); //getTweensOf() filters out disabled tweens, and we have to mark them as _gc = true when the timeline
 completes in order to allow clean garbage collection, so temporarily re-enable the timeline here.
			}
			tweens = TweenLite.getTweensOf(target);
			i = tweens.length;
			while (--i > -1) {
				if (tweens[i].timeline === this || (nested && this._contains(tweens[i]))) {
					a[cnt++] = tweens[i];
				}
			}
			if (disabled) {
				this._enabled(false, true);
			}
			return a;
		}
```
- example usage
```shell
...
			var disabled = this._gc,
				a = [],
				cnt = 0,
				tweens, i;
			if (disabled) {
				this._enabled(true, true); //getTweensOf() filters out disabled tweens, and we have to mark them as _gc = true when the timeline
 completes in order to allow clean garbage collection, so temporarily re-enable the timeline here.
			}
			tweens = TweenLite.getTweensOf(target);
			i = tweens.length;
			while (--i > -1) {
				if (tweens[i].timeline === this || (nested && this._contains(tweens[i]))) {
					a[cnt++] = tweens[i];
				}
			}
			if (disabled) {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.gotoAndPlay"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>gotoAndPlay (position, suppressEvents)](#apidoc.element.gsap.TimelineLite.prototype.gotoAndPlay)
- description and source-code
```javascript
gotoAndPlay = function (position, suppressEvents) {
			return this.play(position, suppressEvents);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.gotoAndStop"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>gotoAndStop (position, suppressEvents)](#apidoc.element.gsap.TimelineLite.prototype.gotoAndStop)
- description and source-code
```javascript
gotoAndStop = function (position, suppressEvents) {
			return this.pause(position, suppressEvents);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.insert"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>insert (value, position, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.insert)
- description and source-code
```javascript
insert = function (value, position, align, stagger) {
			return this.add(value, position || 0, align, stagger);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.insertMultiple"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>insertMultiple (value, position, align, stagger)](#apidoc.element.gsap.TimelineLite.prototype.insertMultiple)
- description and source-code
```javascript
insertMultiple = function (value, position, align, stagger) {
			return this.add(value, position || 0, align, stagger);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.invalidate"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>invalidate ()](#apidoc.element.gsap.TimelineLite.prototype.invalidate)
- description and source-code
```javascript
invalidate = function () {
			var tween = this._first;
			while (tween) {
				tween.invalidate();
				tween = tween._next;
			}
			return Animation.prototype.invalidate.call(this);;
		}
```
- example usage
```shell
...
			}
			return this._uncache(true);
		};

		p.invalidate = function() {
			var tween = this._first;
			while (tween) {
				tween.invalidate();
				tween = tween._next;
			}
			return Animation.prototype.invalidate.call(this);;
		};

		p._enabled = function(enabled, ignoreTimeline) {
			if (enabled === this._gc) {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.paused"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>paused (value)](#apidoc.element.gsap.TimelineLite.prototype.paused)
- description and source-code
```javascript
paused = function (value) {
			if (!value) { //if there's a pause directly at the spot from where we're unpausing, skip it.
				var tween = this._first,
					time = this._time;
				while (tween) {
					if (tween._startTime === time && tween.data === "isPause") {
						tween._rawPrevTime = 0; //remember, _rawPrevTime is how zero-duration tweens/callbacks sense directionality and determine
whether or not to fire. If _rawPrevTime is the same as _startTime on the next render, it won't fire.
					}
					tween = tween._next;
				}
			}
			return Animation.prototype.paused.apply(this, arguments);
		}
```
- example usage
```shell
...
		};

		p.seek = function(position, suppressEvents) {
			return this.totalTime((typeof(position) === "number") ? position : this._parseTimeOrLabel(position), (suppressEvents !== false
));
		};

		p.stop = function() {
			return this.paused(true);
		};

		p.gotoAndPlay = function(position, suppressEvents) {
			return this.play(position, suppressEvents);
		};

		p.gotoAndStop = function(position, suppressEvents) {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.rawTime"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>rawTime (wrapRepeats)](#apidoc.element.gsap.TimelineLite.prototype.rawTime)
- description and source-code
```javascript
rawTime = function (wrapRepeats) {
			return (wrapRepeats && (this._paused || (this._repeat && this.time() > 0 && this.totalProgress() < 1))) ? this._totalTime % (
this._duration + this._repeatDelay) : this._paused ? this._totalTime : (this._timeline.rawTime(wrapRepeats) - this._startTime) *
this._timeScale;
		}
```
- example usage
```shell
...

			SimpleTimeline.prototype.add.call(this, value, position);

			//if the timeline has already ended but the inserted tween/timeline extends the duration, we should enable this timeline again
 so that it renders properly. We should also align the playhead with the parent timeline's when appropriate.
			if (this._gc || this._time === this._duration) if (!this._paused) if (this._duration < this.duration()) {
				//in case any of the ancestors had completed but should now be enabled...
				tl = this;
				beforeRawTime = (tl.rawTime() > value._startTime); //if the tween is placed on the timeline so that it starts BEFORE the current
 rawTime, we should align the playhead (move the timeline). This is because sometimes users will create a timeline, let it finish
, and much later append a tween and expect it to run instead of jumping to its end state. While technically one could argue that
 it should jump to its end state, that's not what users intuitively expect.
				while (tl._timeline) {
					if (beforeRawTime && tl._timeline.smoothChildTiming) {
						tl.totalTime(tl._totalTime, true); //moves the timeline (shifts its startTime) if necessary, and also enables it.
					} else if (tl._gc) {
						tl._enabled(true, false);
					}
					tl = tl._timeline;
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.recent"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>recent ()](#apidoc.element.gsap.TimelineLite.prototype.recent)
- description and source-code
```javascript
recent = function () {
			return this._recent;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.remove"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>remove (value)](#apidoc.element.gsap.TimelineLite.prototype.remove)
- description and source-code
```javascript
remove = function (value) {
			if (value instanceof Animation) {
				this._remove(value, false);
				var tl = value._timeline = value.vars.useFrames ? Animation._rootFramesTimeline : Animation._rootTimeline; //now that it's removed
, default it to the root timeline so that if it gets played again, it doesn't jump back into this timeline.
				value._startTime = (value._paused ? value._pauseTime : tl._time) - ((!value._reversed ? value._totalTime : value.totalDuration
() - value._totalTime) / value._timeScale); //ensure that if it gets played again, the timing is correct.
				return this;
			} else if (value instanceof Array || (value && value.push && _isArray(value))) {
				var i = value.length;
				while (--i > -1) {
					this.remove(value[i]);
				}
				return this;
			} else if (typeof(value) === "string") {
				return this.removeLabel(value);
			}
			return this.kill(null, value);
		}
```
- example usage
```shell
...
				this._remove(value, false);
				var tl = value._timeline = value.vars.useFrames ? Animation._rootFramesTimeline : Animation._rootTimeline; //now that it's removed
, default it to the root timeline so that if it gets played again, it doesn't jump back into this timeline.
				value._startTime = (value._paused ? value._pauseTime : tl._time) - ((!value._reversed ? value._totalTime : value.totalDuration
() - value._totalTime) / value._timeScale); //ensure that if it gets played again, the timing is correct.
				return this;
			} else if (value instanceof Array || (value && value.push && _isArray(value))) {
				var i = value.length;
				while (--i > -1) {
					this.remove(value[i]);
				}
				return this;
			} else if (typeof(value) === "string") {
				return this.removeLabel(value);
			}
			return this.kill(null, value);
		};
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.removeLabel"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>removeLabel (label)](#apidoc.element.gsap.TimelineLite.prototype.removeLabel)
- description and source-code
```javascript
removeLabel = function (label) {
			delete this._labels[label];
			return this;
		}
```
- example usage
```shell
...
			} else if (value instanceof Array || (value && value.push && _isArray(value))) {
				var i = value.length;
				while (--i > -1) {
					this.remove(value[i]);
				}
				return this;
			} else if (typeof(value) === "string") {
				return this.removeLabel(value);
			}
			return this.kill(null, value);
		};

		p._remove = function(tween, skipDisable) {
			SimpleTimeline.prototype._remove.call(this, tween, skipDisable);
			var last = this._last;
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.render"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>render (time, suppressEvents, force)](#apidoc.element.gsap.TimelineLite.prototype.render)
- description and source-code
```javascript
render = function (time, suppressEvents, force) {
			if (this._gc) {
				this._enabled(true, false);
			}
			var totalDur = (!this._dirty) ? this._totalDuration : this.totalDuration(),
				prevTime = this._time,
				prevStart = this._startTime,
				prevTimeScale = this._timeScale,
				prevPaused = this._paused,
				tween, isComplete, next, callback, internalForce, pauseTween, curTime;
			if (time >= totalDur - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = totalDur;
				if (!this._reversed) if (!this._hasPausedChild()) {
					isComplete = true;
					callback = "onComplete";
					internalForce = !!this._timeline.autoRemoveChildren; //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
					if (this._duration === 0) if ((time <= 0 && time >= -0.0000001) || this._rawPrevTime < 0 || this._rawPrevTime === _tinyNum)
if (this._rawPrevTime !== time && this._first) {
						internalForce = true;
						if (this._rawPrevTime > _tinyNum) {
							callback = "onReverseComplete";
						}
					}
				}
				this._rawPrevTime = (this._duration || !suppressEvents || time || this._rawPrevTime === time) ? time : _tinyNum; //when the
playhead arrives at EXACTLY time 0 (right on top) of a zero-duration timeline or tween, we need to discern if events are suppressed
 so that when the playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callback
 would be triggered in this render. Basically, the callback should fire either when the playhead ARRIVES or LEAVES this exact spot
, not both. Imagine doing a timeline.seek(0) and there's a callback that sits at 0. Since events are suppressed on that seek() by
 default, nothing will fire, but when the playhead moves off of that position, the callback should fire. This behavior is what people
 intuitively expect. We set the _rawPrevTime to be a precise tiny number to indicate this scenario rather than using another property
/variable which would increase memory usage. This technique is less readable, but more efficient.
				time = totalDur + 0.0001; //to avoid occasional floating point rounding errors - sometimes child tweens/timelines were not being
 fully completed (their progress might be 0.999999999999998 instead of 1 because when _time - tween._startTime is performed, floating
 point errors would return a value that was SLIGHTLY off). Try (999999999999.7 - 999999999999) * 1 = 0.699951171875 instead of 0
.7.

			} else if (time < 0.0000001) { //to work around occasional floating point math artifacts, round super small values to 0.
				this._totalTime = this._time = 0;
				if (prevTime !== 0 || (this._duration === 0 && this._rawPrevTime !== _tinyNum && (this._rawPrevTime > 0 || (time < 0 && this
._rawPrevTime >= 0)))) {
					callback = "onReverseComplete";
					isComplete = this._reversed;
				}
				if (time < 0) {
					this._active = false;
					if (this._timeline.autoRemoveChildren && this._reversed) { //ensures proper GC if a timeline is resumed after it's finished
 reversing.
						internalForce = isComplete = true;
						callback = "onReverseComplete";
					} else if (this._rawPrevTime >= 0 && this._first) { //when going back beyond the start, force a render so that zero-duration
 tweens that sit at the very beginning render their start values properly. Otherwise, if the parent timeline's playhead lands exactly
 at this timeline's startTime, and then moves backwards, the zero-duration tweens at the beginning would still be at their end state
.
						internalForce = true;
					}
					this._rawPrevTime = time;
				} else {
					this._rawPrevTime = (this._duration || !suppressEvents || time || this._rawPrevTime === time) ? time : _tinyNum; //when the
 playhead arrives at EXACTLY time 0 (right on top) of a zero-duration timeline or tween, we need to discern if events are suppressed
 so that when the playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callbac ...
```
- example usage
```shell
...
					if (curTime !== this._time || (this._paused && !prevPaused)) { //in case a tween pauses or seeks the timeline when rendering
, like inside of an onUpdate/onComplete
						break;
					} else if (tween._active || (tween._startTime <= curTime && !tween._paused && !tween._gc)) {
						if (pauseTween === tween) {
							this.pause();
						}
						if (!tween._reversed) {
							tween.render((time - tween._startTime) * tween._timeScale, suppressEvents, force);
						} else {
							tween.render(((!tween._dirty) ? tween._totalDuration : tween.totalDuration()) - ((time - tween._startTime) * tween._timeScale
), suppressEvents, force);
						}
					}
					tween = next;
				}
			} else {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.seek"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>seek (position, suppressEvents)](#apidoc.element.gsap.TimelineLite.prototype.seek)
- description and source-code
```javascript
seek = function (position, suppressEvents) {
			return this.totalTime((typeof(position) === "number") ? position : this._parseTimeOrLabel(position), (suppressEvents !== false
));
		}
```
- example usage
```shell
...
					if (this._duration === 0) if ((time <= 0 && time >= -0.0000001) || this._rawPrevTime < 0 || this._rawPrevTime === _tinyNum)
if (this._rawPrevTime !== time && this._first) {
						internalForce = true;
						if (this._rawPrevTime > _tinyNum) {
							callback = "onReverseComplete";
						}
					}
				}
				this._rawPrevTime = (this._duration || !suppressEvents || time || this._rawPrevTime === time) ? time : _tinyNum; //when the
playhead arrives at EXACTLY time 0 (right on top) of a zero-duration timeline or tween, we need to discern if events are suppressed
 so that when the playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callback
 would be triggered in this render. Basically, the callback should fire either when the playhead ARRIVES or LEAVES this exact spot
, not both. Imagine doing a timeline.seek(0) and there's a callback that sits at 0. Since events are suppressed on that seek() by
 default, nothing will fire, but when the playhead moves off of that position, the callback should fire. This behavior is what people
 intuitively expect. We set the _rawPrevTime to be a precise tiny number to indicate this scenario rather than using another property
/variable which would increase memory usage. This technique is less readable, but more efficient.
				time = totalDur + 0.0001; //to avoid occasional floating point rounding errors - sometimes child tweens/timelines were not being
 fully completed (their progress might be 0.999999999999998 instead of 1 because when _time - tween._startTime is performed, floating
 point errors would return a value that was SLIGHTLY off). Try (999999999999.7 - 999999999999) * 1 = 0.699951171875 instead of 0
.7.

			} else if (time < 0.0000001) { //to work around occasional floating point math artifacts, round super small values to 0.
				this._totalTime = this._time = 0;
				if (prevTime !== 0 || (this._duration === 0 && this._rawPrevTime !== _tinyNum && (this._rawPrevTime > 0 || (time < 0 && this
._rawPrevTime >= 0)))) {
					callback = "onReverseComplete";
					isComplete = this._reversed;
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.set"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>set (target, vars, position)](#apidoc.element.gsap.TimelineLite.prototype.set)
- description and source-code
```javascript
set = function (target, vars, position) {
			position = this._parseTimeOrLabel(position, 0, true);
			if (vars.immediateRender == null) {
				vars.immediateRender = (position === this._time && !this._paused);
			}
			return this.add( new TweenLite(target, 0, vars), position);
		}
```
- example usage
```shell
...
			}
			return time * scale;
		}
		*/

		p.to = function(target, duration, vars, position) {
			var Engine = (vars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( new Engine(target, duration, vars), position) : this.set(target, vars, position);
		};

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.shiftChildren"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>shiftChildren (amount, adjustLabels, ignoreBeforeTime)](#apidoc.element.gsap.TimelineLite.prototype.shiftChildren)
- description and source-code
```javascript
shiftChildren = function (amount, adjustLabels, ignoreBeforeTime) {
			ignoreBeforeTime = ignoreBeforeTime || 0;
			var tween = this._first,
				labels = this._labels,
				p;
			while (tween) {
				if (tween._startTime >= ignoreBeforeTime) {
					tween._startTime += amount;
				}
				tween = tween._next;
			}
			if (adjustLabels) {
				for (p in labels) {
					if (labels[p] >= ignoreBeforeTime) {
						labels[p] += amount;
					}
				}
			}
			return this._uncache(true);
		}
```
- example usage
```shell
...
							prevStart = tween._startTime;
						}
						if (tween._startTime < 0 && !tween._paused) { //children aren't allowed to have negative startTimes unless smoothChildTiming
 is true, so adjust here if one is found.
							max -= tween._startTime;
							if (this._timeline.smoothChildTiming) {
								this._startTime += tween._startTime / this._timeScale;
							}
							this.shiftChildren(-tween._startTime, false, -9999999999);
							prevStart = 0;
						}
						end = tween._startTime + (tween._totalDuration / tween._timeScale);
						if (end > max) {
							max = end;
						}
						tween = prev;
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.staggerFrom"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>staggerFrom (targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.TimelineLite.prototype.staggerFrom)
- description and source-code
```javascript
staggerFrom = function (targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.immediateRender = (vars.immediateRender != false);
			vars.runBackwards = true;
			return this.staggerTo(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.staggerFromTo"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>staggerFromTo (targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.TimelineLite.prototype.staggerFromTo)
- description and source-code
```javascript
staggerFromTo = function (targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return this.staggerTo(targets, duration, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.staggerTo"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>staggerTo (targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope)](#apidoc.element.gsap.TimelineLite.prototype.staggerTo)
- description and source-code
```javascript
staggerTo = function (targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			var tl = new TimelineLite({onComplete:onCompleteAll, onCompleteParams:onCompleteAllParams, callbackScope:onCompleteAllScope,
smoothChildTiming:this.smoothChildTiming}),
				cycle = vars.cycle,
				copy, i;
			if (typeof(targets) === "string") {
				targets = TweenLite.selector(targets) || targets;
			}
			targets = targets || [];
			if (_isSelector(targets)) { //senses if the targets object is a selector. If it is, we should translate it into an array.
				targets = _slice(targets);
			}
			stagger = stagger || 0;
			if (stagger < 0) {
				targets = _slice(targets);
				targets.reverse();
				stagger *= -1;
			}
			for (i = 0; i < targets.length; i++) {
				copy = _copy(vars);
				if (copy.startAt) {
					copy.startAt = _copy(copy.startAt);
					if (copy.startAt.cycle) {
						_applyCycle(copy.startAt, targets, i);
					}
				}
				if (cycle) {
					_applyCycle(copy, targets, i);
					if (copy.duration != null) {
						duration = copy.duration;
						delete copy.duration;
					}
				}
				tl.to(targets[i], duration, copy, i * stagger);
			}
			return this.add(tl, position);
		}
```
- example usage
```shell
...
			}
			return this.add(tl, position);
		};

		p.staggerFrom = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.immediateRender = (vars.immediateRender != false);
			vars.runBackwards = true;
			return this.staggerTo(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		};

		p.staggerFromTo = function(targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope
) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return this.staggerTo(targets, duration, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		};
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.stop"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>stop ()](#apidoc.element.gsap.TimelineLite.prototype.stop)
- description and source-code
```javascript
stop = function () {
			return this.paused(true);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.to"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>to (target, duration, vars, position)](#apidoc.element.gsap.TimelineLite.prototype.to)
- description and source-code
```javascript
to = function (target, duration, vars, position) {
			var Engine = (vars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( new Engine(target, duration, vars), position) : this.set(target, vars, position);
		}
```
- example usage
```shell
...
				if (cycle) {
					_applyCycle(copy, targets, i);
					if (copy.duration != null) {
						duration = copy.duration;
						delete copy.duration;
					}
				}
				tl.to(targets[i], duration, copy, i * stagger);
			}
			return this.add(tl, position);
		};

		p.staggerFrom = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.immediateRender = (vars.immediateRender != false);
			vars.runBackwards = true;
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.totalDuration"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>totalDuration (value)](#apidoc.element.gsap.TimelineLite.prototype.totalDuration)
- description and source-code
```javascript
totalDuration = function (value) {
			if (!arguments.length) {
				if (this._dirty) {
					var max = 0,
						tween = this._last,
						prevStart = 999999999999,
						prev, end;
					while (tween) {
						prev = tween._prev; //record it here in case the tween changes position in the sequence...
						if (tween._dirty) {
							tween.totalDuration(); //could change the tween._startTime, so make sure the tween's cache is clean before analyzing it.
						}
						if (tween._startTime > prevStart && this._sortChildren && !tween._paused) { //in case one of the tweens shifted out of order
, it needs to be re-inserted into the correct position in the sequence
							this.add(tween, tween._startTime - tween._delay);
						} else {
							prevStart = tween._startTime;
						}
						if (tween._startTime < 0 && !tween._paused) { //children aren't allowed to have negative startTimes unless smoothChildTiming
 is true, so adjust here if one is found.
							max -= tween._startTime;
							if (this._timeline.smoothChildTiming) {
								this._startTime += tween._startTime / this._timeScale;
							}
							this.shiftChildren(-tween._startTime, false, -9999999999);
							prevStart = 0;
						}
						end = tween._startTime + (tween._totalDuration / tween._timeScale);
						if (end > max) {
							max = end;
						}
						tween = prev;
					}
					this._duration = this._totalDuration = max;
					this._dirty = false;
				}
				return this._totalDuration;
			}
			return (value && this.totalDuration()) ? this.timeScale(this._totalDuration / value) : this;
		}
```
- example usage
```shell
...
					for (i = 0; i < l; i++) {
						if (_isArray(child = value[i])) {
							child = new TimelineLite({tweens:child});
						}
						this.add(child, curTime);
						if (typeof(child) !== "string" && typeof(child) !== "function") {
							if (align === "sequence") {
								curTime = child._startTime + (child.totalDuration() / child._timeScale);
							} else if (align === "start") {
								child._startTime -= child.delay();
							}
						}
						curTime += stagger;
					}
					return this._uncache(true);
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.totalTime"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>totalTime (time, suppressEvents, uncapped)](#apidoc.element.gsap.TimelineLite.prototype.totalTime)
- description and source-code
```javascript
totalTime = function (time, suppressEvents, uncapped) {
			this._forcingPlayhead = true;
			var val = Animation.prototype.totalTime.apply(this, arguments);
			this._forcingPlayhead = false;
			return val;
		}
```
- example usage
```shell
...
			//if the timeline has already ended but the inserted tween/timeline extends the duration, we should enable this timeline again
 so that it renders properly. We should also align the playhead with the parent timeline's when appropriate.
			if (this._gc || this._time === this._duration) if (!this._paused) if (this._duration < this.duration()) {
				//in case any of the ancestors had completed but should now be enabled...
				tl = this;
				beforeRawTime = (tl.rawTime() > value._startTime); //if the tween is placed on the timeline so that it starts BEFORE the current
 rawTime, we should align the playhead (move the timeline). This is because sometimes users will create a timeline, let it finish
, and much later append a tween and expect it to run instead of jumping to its end state. While technically one could argue that
 it should jump to its end state, that's not what users intuitively expect.
				while (tl._timeline) {
					if (beforeRawTime && tl._timeline.smoothChildTiming) {
						tl.totalTime(tl._totalTime, true); //moves the timeline (shifts its startTime) if necessary, and also enables it.
					} else if (tl._gc) {
						tl._enabled(true, false);
					}
					tl = tl._timeline;
				}
			}
...
```

#### <a name="apidoc.element.gsap.TimelineLite.prototype.usesFrames"></a>[function <span class="apidocSignatureSpan">gsap.TimelineLite.prototype.</span>usesFrames ()](#apidoc.element.gsap.TimelineLite.prototype.usesFrames)
- description and source-code
```javascript
usesFrames = function () {
			var tl = this._timeline;
			while (tl._timeline) {
				tl = tl._timeline;
			}
			return (tl === Animation._rootFramesTimeline);
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TimelineMax"></a>[module gsap.TimelineMax](#apidoc.module.gsap.TimelineMax)

#### <a name="apidoc.element.gsap.TimelineMax.TimelineMax"></a>[function <span class="apidocSignatureSpan">gsap.</span>TimelineMax (vars)](#apidoc.element.gsap.TimelineMax.TimelineMax)
- description and source-code
```javascript
TimelineMax = function (vars) {
				TimelineLite.call(this, vars);
				this._repeat = this.vars.repeat || 0;
				this._repeatDelay = this.vars.repeatDelay || 0;
				this._cycle = 0;
				this._yoyo = (this.vars.yoyo === true);
				this._dirty = true;
			}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TimelineMax.prototype"></a>[module gsap.TimelineMax.prototype](#apidoc.module.gsap.TimelineMax.prototype)

#### <a name="apidoc.element.gsap.TimelineMax.prototype.addCallback"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>addCallback (callback, position, params, scope)](#apidoc.element.gsap.TimelineMax.prototype.addCallback)
- description and source-code
```javascript
addCallback = function (callback, position, params, scope) {
			return this.add( TweenLite.delayedCall(0, callback, params, scope), position);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>constructor (vars)](#apidoc.element.gsap.TimelineMax.prototype.constructor)
- description and source-code
```javascript
constructor = function (vars) {
				TimelineLite.call(this, vars);
				this._repeat = this.vars.repeat || 0;
				this._repeatDelay = this.vars.repeatDelay || 0;
				this._cycle = 0;
				this._yoyo = (this.vars.yoyo === true);
				this._dirty = true;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.currentLabel"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>currentLabel (value)](#apidoc.element.gsap.TimelineMax.prototype.currentLabel)
- description and source-code
```javascript
currentLabel = function (value) {
			if (!arguments.length) {
				return this.getLabelBefore(this._time + 0.00000001);
			}
			return this.seek(value, true);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.getActive"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getActive (nested, tweens, timelines)](#apidoc.element.gsap.TimelineMax.prototype.getActive)
- description and source-code
```javascript
getActive = function (nested, tweens, timelines) {
			if (nested == null) {
				nested = true;
			}
			if (tweens == null) {
				tweens = true;
			}
			if (timelines == null) {
				timelines = false;
			}
			var a = [],
				all = this.getChildren(nested, tweens, timelines),
				cnt = 0,
				l = all.length,
				i, tween;
			for (i = 0; i < l; i++) {
				tween = all[i];
				if (tween.isActive()) {
					a[cnt++] = tween;
				}
			}
			return a;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.getLabelAfter"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getLabelAfter (time)](#apidoc.element.gsap.TimelineMax.prototype.getLabelAfter)
- description and source-code
```javascript
getLabelAfter = function (time) {
			if (!time) if (time !== 0) { //faster than isNan()
				time = this._time;
			}
			var labels = this.getLabelsArray(),
				l = labels.length,
				i;
			for (i = 0; i < l; i++) {
				if (labels[i].time > time) {
					return labels[i].name;
				}
			}
			return null;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.getLabelBefore"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getLabelBefore (time)](#apidoc.element.gsap.TimelineMax.prototype.getLabelBefore)
- description and source-code
```javascript
getLabelBefore = function (time) {
			if (time == null) {
				time = this._time;
			}
			var labels = this.getLabelsArray(),
				i = labels.length;
			while (--i > -1) {
				if (labels[i].time < time) {
					return labels[i].name;
				}
			}
			return null;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.getLabelsArray"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>getLabelsArray ()](#apidoc.element.gsap.TimelineMax.prototype.getLabelsArray)
- description and source-code
```javascript
getLabelsArray = function () {
			var a = [],
				cnt = 0,
				p;
			for (p in this._labels) {
				a[cnt++] = {time:this._labels[p], name:p};
			}
			a.sort(function(a,b) {
				return a.time - b.time;
			});
			return a;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.invalidate"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>invalidate ()](#apidoc.element.gsap.TimelineMax.prototype.invalidate)
- description and source-code
```javascript
invalidate = function () {
			this._locked = false; //unlock and set cycle in case invalidate() is called from inside an onRepeat
			return TimelineLite.prototype.invalidate.call(this);
		}
```
- example usage
```shell
...
			}
			return this._uncache(true);
		};

		p.invalidate = function() {
			var tween = this._first;
			while (tween) {
				tween.invalidate();
				tween = tween._next;
			}
			return Animation.prototype.invalidate.call(this);;
		};

		p._enabled = function(enabled, ignoreTimeline) {
			if (enabled === this._gc) {
...
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.progress"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>progress (value, suppressEvents)](#apidoc.element.gsap.TimelineMax.prototype.progress)
- description and source-code
```javascript
progress = function (value, suppressEvents) {
			return (!arguments.length) ? this._time / this.duration() : this.totalTime( this.duration() * ((this._yoyo && (this._cycle &
1) !== 0) ? 1 - value : value) + (this._cycle * (this._duration + this._repeatDelay)), suppressEvents);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.removeCallback"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>removeCallback (callback, position)](#apidoc.element.gsap.TimelineMax.prototype.removeCallback)
- description and source-code
```javascript
removeCallback = function (callback, position) {
			if (callback) {
				if (position == null) {
					this._kill(null, callback);
				} else {
					var a = this.getTweensOf(callback, false),
						i = a.length,
						time = this._parseTimeOrLabel(position);
					while (--i > -1) {
						if (a[i]._startTime === time) {
							a[i]._enabled(false, false);
						}
					}
				}
			}
			return this;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.removePause"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>removePause (position)](#apidoc.element.gsap.TimelineMax.prototype.removePause)
- description and source-code
```javascript
removePause = function (position) {
			return this.removeCallback(TimelineLite._internals.pauseCallback, position);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.render"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>render (time, suppressEvents, force)](#apidoc.element.gsap.TimelineMax.prototype.render)
- description and source-code
```javascript
render = function (time, suppressEvents, force) {
			if (this._gc) {
				this._enabled(true, false);
			}
			var totalDur = (!this._dirty) ? this._totalDuration : this.totalDuration(),
				dur = this._duration,
				prevTime = this._time,
				prevTotalTime = this._totalTime,
				prevStart = this._startTime,
				prevTimeScale = this._timeScale,
				prevRawPrevTime = this._rawPrevTime,
				prevPaused = this._paused,
				prevCycle = this._cycle,
				tween, isComplete, next, callback, internalForce, cycleDuration, pauseTween, curTime;
			if (time >= totalDur - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				if (!this._locked) {
					this._totalTime = totalDur;
					this._cycle = this._repeat;
				}
				if (!this._reversed) if (!this._hasPausedChild()) {
					isComplete = true;
					callback = "onComplete";
					internalForce = !!this._timeline.autoRemoveChildren; //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
					if (this._duration === 0) if ((time <= 0 && time >= -0.0000001) || prevRawPrevTime < 0 || prevRawPrevTime === _tinyNum) if (
prevRawPrevTime !== time && this._first) {
						internalForce = true;
						if (prevRawPrevTime > _tinyNum) {
							callback = "onReverseComplete";
						}
					}
				}
				this._rawPrevTime = (this._duration || !suppressEvents || time || this._rawPrevTime === time) ? time : _tinyNum; //when the
playhead arrives at EXACTLY time 0 (right on top) of a zero-duration timeline or tween, we need to discern if events are suppressed
 so that when the playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callback
 would be triggered in this render. Basically, the callback should fire either when the playhead ARRIVES or LEAVES this exact spot
, not both. Imagine doing a timeline.seek(0) and there's a callback that sits at 0. Since events are suppressed on that seek() by
 default, nothing will fire, but when the playhead moves off of that position, the callback should fire. This behavior is what people
 intuitively expect. We set the _rawPrevTime to be a precise tiny number to indicate this scenario rather than using another property
/variable which would increase memory usage. This technique is less readable, but more efficient.
				if (this._yoyo && (this._cycle & 1) !== 0) {
					this._time = time = 0;
				} else {
					this._time = dur;
					time = dur + 0.0001; //to avoid occasional floating point rounding errors - sometimes child tweens/timelines were not being
 fully completed (their progress might be 0.999999999999998 instead of 1 because when _time - tween._startTime is performed, floating
 point errors would return a value that was SLIGHTLY off). Try (999999999999.7 - 999999999999) * 1 = 0.699951171875 instead of 0
.7. We cannot do less then 0.0001 because the same issue can occur when the duration is extremely large like 999999999999 in which
 case adding 0.00000001, for example, causes it to act like nothing was added.
				}
				
			} else if (time < 0.0000001) { //to work around occasional floating point math artifacts, round super small values to 0.
				if (!this._locked) {
					this._totalTime = this._cycle = 0;
				}
				this._time = 0;
				if (prevTime !== 0 || (dur === 0 && prevRawPrevTime !== _tinyNum && (prevRawPrevTime > 0 || (time < 0 && prevRawPrevTime >=
0)) && !this._locked)) { //edge case for checking time < 0 && prevRawPrevTime >= 0: a zero-duration fromTo() tween inside a zero
-duration timeline (yeah, very rare)
					callback = "onReverseComplete";
					isComplete = this._reversed;
				}
				if (time < 0) {
					this._active = false;
					if (this._timeline.autoRemoveChildren && this._reversed) {
						internalForce = isComplete = true;
						callback = "onReverseComplete";
					} else if (prevRawPrevTime >= 0 && this._first) { //when going back beyond the start, force a render so that zero-duration
tweens that sit at the very beginning render their start values properly. Otherwise, if the parent tim ...
```
- example usage
```shell
...
					if (curTime !== this._time || (this._paused && !prevPaused)) { //in case a tween pauses or seeks the timeline when rendering
, like inside of an onUpdate/onComplete
						break;
					} else if (tween._active || (tween._startTime <= curTime && !tween._paused && !tween._gc)) {
						if (pauseTween === tween) {
							this.pause();
						}
						if (!tween._reversed) {
							tween.render((time - tween._startTime) * tween._timeScale, suppressEvents, force);
						} else {
							tween.render(((!tween._dirty) ? tween._totalDuration : tween.totalDuration()) - ((time - tween._startTime) * tween._timeScale
), suppressEvents, force);
						}
					}
					tween = next;
				}
			} else {
...
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.repeat"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>repeat (value)](#apidoc.element.gsap.TimelineMax.prototype.repeat)
- description and source-code
```javascript
repeat = function (value) {
			if (!arguments.length) {
				return this._repeat;
			}
			this._repeat = value;
			return this._uncache(true);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.repeatDelay"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>repeatDelay (value)](#apidoc.element.gsap.TimelineMax.prototype.repeatDelay)
- description and source-code
```javascript
repeatDelay = function (value) {
			if (!arguments.length) {
				return this._repeatDelay;
			}
			this._repeatDelay = value;
			return this._uncache(true);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.time"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>time (value, suppressEvents)](#apidoc.element.gsap.TimelineMax.prototype.time)
- description and source-code
```javascript
time = function (value, suppressEvents) {
			if (!arguments.length) {
				return this._time;
			}
			if (this._dirty) {
				this.totalDuration();
			}
			if (value > this._duration) {
				value = this._duration;
			}
			if (this._yoyo && (this._cycle & 1) !== 0) {
				value = (this._duration - value) + (this._cycle * (this._duration + this._repeatDelay));
			} else if (this._repeat !== 0) {
				value += this._cycle * (this._duration + this._repeatDelay);
			}
			return this.totalTime(value, suppressEvents);
		}
```
- example usage
```shell
...
			while (tl._timeline) {
				tl = tl._timeline;
			}
			return (tl === Animation._rootFramesTimeline);
		};

		p.rawTime = function(wrapRepeats) {
			return (wrapRepeats && (this._paused || (this._repeat && this.time() > 0 && this.totalProgress() < 1))) ? this._totalTime % (
this._duration + this._repeatDelay) : this._paused ? this._totalTime : (this._timeline.rawTime(wrapRepeats) - this._startTime) *
this._timeScale;
		};

		return TimelineLite;

	}, true);
...
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.totalDuration"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>totalDuration (value)](#apidoc.element.gsap.TimelineMax.prototype.totalDuration)
- description and source-code
```javascript
totalDuration = function (value) {
			if (!arguments.length) {
				if (this._dirty) {
					TimelineLite.prototype.totalDuration.call(this); //just forces refresh
					//Instead of Infinity, we use 999999999999 so that we can accommodate reverses.
					this._totalDuration = (this._repeat === -1) ? 999999999999 : this._duration * (this._repeat + 1) + (this._repeatDelay * this
._repeat);
				}
				return this._totalDuration;
			}
			return (this._repeat === -1 || !value) ? this : this.timeScale( this.totalDuration() / value );
		}
```
- example usage
```shell
...
					for (i = 0; i < l; i++) {
						if (_isArray(child = value[i])) {
							child = new TimelineLite({tweens:child});
						}
						this.add(child, curTime);
						if (typeof(child) !== "string" && typeof(child) !== "function") {
							if (align === "sequence") {
								curTime = child._startTime + (child.totalDuration() / child._timeScale);
							} else if (align === "start") {
								child._startTime -= child.delay();
							}
						}
						curTime += stagger;
					}
					return this._uncache(true);
...
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.totalProgress"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>totalProgress (value, suppressEvents)](#apidoc.element.gsap.TimelineMax.prototype.totalProgress)
- description and source-code
```javascript
totalProgress = function (value, suppressEvents) {
			return (!arguments.length) ? this._totalTime / this.totalDuration() : this.totalTime( this.totalDuration() * value, suppressEvents
);
		}
```
- example usage
```shell
...
			while (tl._timeline) {
				tl = tl._timeline;
			}
			return (tl === Animation._rootFramesTimeline);
		};

		p.rawTime = function(wrapRepeats) {
			return (wrapRepeats && (this._paused || (this._repeat && this.time() > 0 && this.totalProgress() < 1))) ? this._totalTime % (
this._duration + this._repeatDelay) : this._paused ? this._totalTime : (this._timeline.rawTime(wrapRepeats) - this._startTime) *
this._timeScale;
		};

		return TimelineLite;

	}, true);
...
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.tweenFromTo"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>tweenFromTo (fromPosition, toPosition, vars)](#apidoc.element.gsap.TimelineMax.prototype.tweenFromTo)
- description and source-code
```javascript
tweenFromTo = function (fromPosition, toPosition, vars) {
			vars = vars || {};
			fromPosition = this._parseTimeOrLabel(fromPosition);
			vars.startAt = {onComplete:this.seek, onCompleteParams:[fromPosition], callbackScope:this};
			vars.immediateRender = (vars.immediateRender !== false);
			var t = this.tweenTo(toPosition, vars);
			return t.duration((Math.abs( t.vars.time - fromPosition) / this._timeScale) || 0.001);
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.tweenTo"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>tweenTo (position, vars)](#apidoc.element.gsap.TimelineMax.prototype.tweenTo)
- description and source-code
```javascript
tweenTo = function (position, vars) {
			vars = vars || {};
			var copy = {ease:_easeNone, useFrames:this.usesFrames(), immediateRender:false},
				Engine = (vars.repeat && _globals.TweenMax) || TweenLite,
				duration, p, t;
			for (p in vars) {
				copy[p] = vars[p];
			}
			copy.time = this._parseTimeOrLabel(position);
			duration = (Math.abs(Number(copy.time) - this._time) / this._timeScale) || 0.001;
			t = new Engine(this, duration, copy);
			copy.onStart = function() {
				t.target.paused(true);
				if (t.vars.time !== t.target.time() && duration === t.duration()) { //don't make the duration zero - if it's supposed to be
zero, don't worry because it's already initting the tween and will complete immediately, effectively making the duration zero anyway
. If we make duration zero, the tween won't run at all.
					t.duration( Math.abs( t.vars.time - t.target.time()) / t.target._timeScale );
				}
				if (vars.onStart) { //in case the user had an onStart in the vars - we don't want to overwrite it.
					vars.onStart.apply(vars.onStartScope || vars.callbackScope || t, vars.onStartParams || []); //don't use t._callback("onStart
") or it'll point to the copy.onStart and we'll get a recursion error.
				}
			};
			return t;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TimelineMax.prototype.yoyo"></a>[function <span class="apidocSignatureSpan">gsap.TimelineMax.prototype.</span>yoyo (value)](#apidoc.element.gsap.TimelineMax.prototype.yoyo)
- description and source-code
```javascript
yoyo = function (value) {
			if (!arguments.length) {
				return this._yoyo;
			}
			this._yoyo = value;
			return this;
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite"></a>[module gsap.TweenLite](#apidoc.module.gsap.TweenLite)

#### <a name="apidoc.element.gsap.TweenLite.TweenLite"></a>[function <span class="apidocSignatureSpan">gsap.</span>TweenLite (target, duration, vars)](#apidoc.element.gsap.TweenLite.TweenLite)
- description and source-code
```javascript
TweenLite = function (target, duration, vars) {
				Animation.call(this, duration, vars);
				this.render = TweenLite.prototype.render; //speed optimization (avoid prototype lookup on this "hot" method)

				if (target == null) {
					throw "Cannot tween a null target.";
				}

				this.target = target = (typeof(target) !== "string") ? target : TweenLite.selector(target) || target;

				var isSelector = (target.jquery || (target.length && target !== window && target[0] && (target[0] === window || (target[0].nodeType
 && target[0].style && !target.nodeType)))),
					overwrite = this.vars.overwrite,
					i, targ, targets;

				this._overwrite = overwrite = (overwrite == null) ? _overwriteLookup[TweenLite.defaultOverwrite] : (typeof(overwrite) === "number
") ? overwrite >> 0 : _overwriteLookup[overwrite];

				if ((isSelector || target instanceof Array || (target.push && _isArray(target))) && typeof(target[0]) !== "number") {
					this._targets = targets = _slice(target);  //don't use Array.prototype.slice.call(target, 0) because that doesn't work in IE8
 with a NodeList that's returned by querySelectorAll()
					this._propLookup = [];
					this._siblings = [];
					for (i = 0; i < targets.length; i++) {
						targ = targets[i];
						if (!targ) {
							targets.splice(i--, 1);
							continue;
						} else if (typeof(targ) === "string") {
							targ = targets[i--] = TweenLite.selector(targ); //in case it's an array of strings
							if (typeof(targ) === "string") {
								targets.splice(i+1, 1); //to avoid an endless loop (can't imagine why the selector would return a string, but just in case
)
							}
							continue;
						} else if (targ.length && targ !== window && targ[0] && (targ[0] === window || (targ[0].nodeType && targ[0].style && !targ
.nodeType))) { //in case the user is passing in an array of selector objects (like jQuery objects), we need to check one more level
 and pull things out if necessary. Also note that <select> elements pass all the criteria regarding length and the first child having
 style, so we must also check to ensure the target isn't an HTML node itself.
							targets.splice(i--, 1);
							this._targets = targets = targets.concat(_slice(targ));
							continue;
						}
						this._siblings[i] = _register(targ, this, false);
						if (overwrite === 1) if (this._siblings[i].length > 1) {
							_applyOverwrite(targ, this, null, 1, this._siblings[i]);
						}
					}

				} else {
					this._propLookup = {};
					this._siblings = _register(target, this, false);
					if (overwrite === 1) if (this._siblings.length > 1) {
						_applyOverwrite(target, this, null, 1, this._siblings);
					}
				}
				if (this.vars.immediateRender || (duration === 0 && this._delay === 0 && this.vars.immediateRender !== false)) {
					this._time = -_tinyNum; //forces a render without having to set the render() "force" parameter to true because we want to allow
 lazying by default (using the "force" parameter always forces an immediate full render)
					this.render(Math.min(0, -this._delay)); //in case delay is negative
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._onPluginEvent"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>_onPluginEvent (type, tween)](#apidoc.element.gsap.TweenLite._onPluginEvent)
- description and source-code
```javascript
_onPluginEvent = function (type, tween) {
			var pt = tween._firstPT,
				changed, pt2, first, last, next;
			if (type === "_onInitAllProps") {
				//sorts the PropTween linked list in order of priority because some plugins need to render earlier/later than others, like MotionBlurPlugin
 applies its effects after all x/y/alpha tweens have rendered on each frame.
				while (pt) {
					next = pt._next;
					pt2 = first;
					while (pt2 && pt2.pr > pt.pr) {
						pt2 = pt2._next;
					}
					if ((pt._prev = pt2 ? pt2._prev : last)) {
						pt._prev._next = pt;
					} else {
						first = pt;
					}
					if ((pt._next = pt2)) {
						pt2._prev = pt;
					} else {
						last = pt;
					}
					pt = next;
				}
				pt = tween._firstPT = first;
			}
			while (pt) {
				if (pt.pg) if (typeof(pt.t[type]) === "function") if (pt.t[type]()) {
					changed = true;
				}
				pt = pt._next;
			}
			return changed;
		}
```
- example usage
```shell
...
					}
				}
			} else {
				initPlugins = this._initProps(this.target, this._propLookup, this._siblings, op, 0);
			}

			if (initPlugins) {
				TweenLite._onPluginEvent("_onInitAllProps", this); //reorders the array in order of priority. Uses a static TweenPlugin method
 in order to minimize file size in TweenLite
			}
			if (op) if (!this._firstPT) if (typeof(this.target) !== "function") { //if all tweening properties have been overwritten, kill
 the tween. If the target is a function, it's probably a delayedCall so let it live.
				this._enabled(false, false);
			}
			if (v.runBackwards) {
				pt = this._firstPT;
				while (pt) {
...
```

#### <a name="apidoc.element.gsap.TweenLite.defaultStringFilter"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>defaultStringFilter (a)](#apidoc.element.gsap.TweenLite.defaultStringFilter)
- description and source-code
```javascript
defaultStringFilter = function (a) {
			var combined = a[0] + a[1],
				toHSL;
			if (_colorExp.test(combined)) {
				toHSL = (combined.indexOf("hsl(") !== -1 || combined.indexOf("hsla(") !== -1);
				a[0] = _formatColors(a[0], toHSL);
				a[1] = _formatColors(a[1], toHSL);
			}
			_colorExp.lastIndex = 0;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite.delayedCall"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>delayedCall (delay, callback, params, scope, useFrames)](#apidoc.element.gsap.TweenLite.delayedCall)
- description and source-code
```javascript
delayedCall = function (delay, callback, params, scope, useFrames) {
			return new TweenLite(callback, 0, {delay:delay, onComplete:callback, onCompleteParams:params, callbackScope:scope, onReverseComplete
:callback, onReverseCompleteParams:params, immediateRender:false, lazy:false, useFrames:useFrames, overwrite:0});
		}
```
- example usage
```shell
...
		p.staggerFromTo = function(targets, duration, fromVars, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope
) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return this.staggerTo(targets, duration, toVars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope);
		};

		p.call = function(callback, params, scope, position) {
			return this.add( TweenLite.delayedCall(0, callback, params, scope), position);
		};

		p.set = function(target, vars, position) {
			position = this._parseTimeOrLabel(position, 0, true);
			if (vars.immediateRender == null) {
				vars.immediateRender = (position === this._time && !this._paused);
			}
...
```

#### <a name="apidoc.element.gsap.TweenLite.from"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>from (target, duration, vars)](#apidoc.element.gsap.TweenLite.from)
- description and source-code
```javascript
from = function (target, duration, vars) {
			vars.runBackwards = true;
			vars.immediateRender = (vars.immediateRender != false);
			return new TweenLite(target, duration, vars);
		}
```
- example usage
```shell
...

		p.to = function(target, duration, vars, position) {
			var Engine = (vars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( new Engine(target, duration, vars), position) : this.set(target, vars, position);
		};

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
			var Engine = (toVars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( Engine.fromTo(target, duration, fromVars, toVars), position) : this.set(target, toVars, position);
		};
...
```

#### <a name="apidoc.element.gsap.TweenLite.fromTo"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>fromTo (target, duration, fromVars, toVars)](#apidoc.element.gsap.TweenLite.fromTo)
- description and source-code
```javascript
fromTo = function (target, duration, fromVars, toVars) {
			toVars.startAt = fromVars;
			toVars.immediateRender = (toVars.immediateRender != false && fromVars.immediateRender != false);
			return new TweenLite(target, duration, toVars);
		}
```
- example usage
```shell
...

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
			var Engine = (toVars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( Engine.fromTo(target, duration, fromVars, toVars), position) : this.set(target, toVars, position);
		};

		p.staggerTo = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			var tl = new TimelineLite({onComplete:onCompleteAll, onCompleteParams:onCompleteAllParams, callbackScope:onCompleteAllScope,
smoothChildTiming:this.smoothChildTiming}),
				cycle = vars.cycle,
				copy, i;
			if (typeof(targets) === "string") {
...
```

#### <a name="apidoc.element.gsap.TweenLite.getTweensOf"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>getTweensOf (target, onlyActive)](#apidoc.element.gsap.TweenLite.getTweensOf)
- description and source-code
```javascript
getTweensOf = function (target, onlyActive) {
			if (target == null) { return []; }
			target = (typeof(target) !== "string") ? target : TweenLite.selector(target) || target;
			var i, a, j, t;
			if ((_isArray(target) || _isSelector(target)) && typeof(target[0]) !== "number") {
				i = target.length;
				a = [];
				while (--i > -1) {
					a = a.concat(TweenLite.getTweensOf(target[i], onlyActive));
				}
				i = a.length;
				//now get rid of any duplicates (tweens of arrays of objects could cause duplicates)
				while (--i > -1) {
					t = a[i];
					j = i;
					while (--j > -1) {
						if (t === a[j]) {
							a.splice(i, 1);
						}
					}
				}
			} else {
				a = _register(target).concat();
				i = a.length;
				while (--i > -1) {
					if (a[i]._gc || (onlyActive && !a[i].isActive())) {
						a.splice(i, 1);
					}
				}
			}
			return a;
		}
```
- example usage
```shell
...
			var disabled = this._gc,
				a = [],
				cnt = 0,
				tweens, i;
			if (disabled) {
				this._enabled(true, true); //getTweensOf() filters out disabled tweens, and we have to mark them as _gc = true when the timeline
 completes in order to allow clean garbage collection, so temporarily re-enable the timeline here.
			}
			tweens = TweenLite.getTweensOf(target);
			i = tweens.length;
			while (--i > -1) {
				if (tweens[i].timeline === this || (nested && this._contains(tweens[i]))) {
					a[cnt++] = tweens[i];
				}
			}
			if (disabled) {
...
```

#### <a name="apidoc.element.gsap.TweenLite.killDelayedCallsTo"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>killDelayedCallsTo (target, onlyActive, vars)](#apidoc.element.gsap.TweenLite.killDelayedCallsTo)
- description and source-code
```javascript
killDelayedCallsTo = function (target, onlyActive, vars) {
			if (typeof(onlyActive) === "object") {
				vars = onlyActive; //for backwards compatibility (before "onlyActive" parameter was inserted)
				onlyActive = false;
			}
			var a = TweenLite.getTweensOf(target, onlyActive),
				i = a.length;
			while (--i > -1) {
				a[i]._kill(vars, target);
			}
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite.killTweensOf"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>killTweensOf (target, onlyActive, vars)](#apidoc.element.gsap.TweenLite.killTweensOf)
- description and source-code
```javascript
killTweensOf = function (target, onlyActive, vars) {
			if (typeof(onlyActive) === "object") {
				vars = onlyActive; //for backwards compatibility (before "onlyActive" parameter was inserted)
				onlyActive = false;
			}
			var a = TweenLite.getTweensOf(target, onlyActive),
				i = a.length;
			while (--i > -1) {
				a[i]._kill(vars, target);
			}
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite.lagSmoothing"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>lagSmoothing (threshold, adjustedLag)](#apidoc.element.gsap.TweenLite.lagSmoothing)
- description and source-code
```javascript
lagSmoothing = function (threshold, adjustedLag) {
			_ticker.lagSmoothing(threshold, adjustedLag);
		}
```
- example usage
```shell
...

		TweenLite.version = "1.19.1";
		TweenLite.defaultEase = p._ease = new Ease(null, null, 1, 1);
		TweenLite.defaultOverwrite = "auto";
		TweenLite.ticker = _ticker;
		TweenLite.autoSleep = 120;
		TweenLite.lagSmoothing = function(threshold, adjustedLag) {
			_ticker.lagSmoothing(threshold, adjustedLag);
		};

		TweenLite.selector = window.$ || window.jQuery || function(e) {
			var selector = window.$ || window.jQuery;
			if (selector) {
				TweenLite.selector = selector;
				return selector(e);
...
```

#### <a name="apidoc.element.gsap.TweenLite.render"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>render ()](#apidoc.element.gsap.TweenLite.render)
- description and source-code
```javascript
render = function () {
				var i, a, p;
				if (_lazyTweens.length) { //if code is run outside of the requestAnimationFrame loop, there may be tweens queued AFTER the engine
 refreshed, so we need to ensure any pending renders occur before we refresh again.
					_lazyRender();
				}
				_rootTimeline.render((_ticker.time - _rootTimeline._startTime) * _rootTimeline._timeScale, false, false);
				_rootFramesTimeline.render((_ticker.frame - _rootFramesTimeline._startTime) * _rootFramesTimeline._timeScale, false, false);
				if (_lazyTweens.length) {
					_lazyRender();
				}
				if (_ticker.frame >= _nextGCFrame) { //dump garbage every 120 frames or whatever the user sets TweenLite.autoSleep to
					_nextGCFrame = _ticker.frame + (parseInt(TweenLite.autoSleep, 10) || 120);
					for (p in _tweenLookup) {
						a = _tweenLookup[p].tweens;
						i = a.length;
						while (--i > -1) {
							if (a[i]._gc) {
								a.splice(i, 1);
							}
						}
						if (a.length === 0) {
							delete _tweenLookup[p];
						}
					}
					//if there are no more tweens in the root timelines, or if they're all paused, make the _timer sleep to reduce load on the
CPU slightly
					p = _rootTimeline._first;
					if (!p || p._paused) if (TweenLite.autoSleep && !_rootFramesTimeline._first && _ticker._listeners.tick.length === 1) {
						while (p && p._paused) {
							p = p._next;
						}
						if (!p) {
							_ticker.sleep();
						}
					}
				}
			}
```
- example usage
```shell
...
					if (curTime !== this._time || (this._paused && !prevPaused)) { //in case a tween pauses or seeks the timeline when rendering
, like inside of an onUpdate/onComplete
						break;
					} else if (tween._active || (tween._startTime <= curTime && !tween._paused && !tween._gc)) {
						if (pauseTween === tween) {
							this.pause();
						}
						if (!tween._reversed) {
							tween.render((time - tween._startTime) * tween._timeScale, suppressEvents, force);
						} else {
							tween.render(((!tween._dirty) ? tween._totalDuration : tween.totalDuration()) - ((time - tween._startTime) * tween._timeScale
), suppressEvents, force);
						}
					}
					tween = next;
				}
			} else {
...
```

#### <a name="apidoc.element.gsap.TweenLite.selector"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>selector (e)](#apidoc.element.gsap.TweenLite.selector)
- description and source-code
```javascript
selector = function (e) {
			var selector = window.$ || window.jQuery;
			if (selector) {
				TweenLite.selector = selector;
				return selector(e);
			}
			return (typeof(_doc) === "undefined") ? e : (_doc.querySelectorAll ? _doc.querySelectorAll(e) : _doc.getElementById((e.charAt
(0) === "#") ? e.substr(1) : e));
		}
```
- example usage
```shell
...
		};

		p.staggerTo = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			var tl = new TimelineLite({onComplete:onCompleteAll, onCompleteParams:onCompleteAllParams, callbackScope:onCompleteAllScope,
smoothChildTiming:this.smoothChildTiming}),
				cycle = vars.cycle,
				copy, i;
			if (typeof(targets) === "string") {
				targets = TweenLite.selector(targets) || targets;
			}
			targets = targets || [];
			if (_isSelector(targets)) { //senses if the targets object is a selector. If it is, we should translate it into an array.
				targets = _slice(targets);
			}
			stagger = stagger || 0;
			if (stagger < 0) {
...
```

#### <a name="apidoc.element.gsap.TweenLite.set"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>set (target, vars)](#apidoc.element.gsap.TweenLite.set)
- description and source-code
```javascript
set = function (target, vars) {
			return new TweenLite(target, 0, vars);
		}
```
- example usage
```shell
...
			}
			return time * scale;
		}
		*/

		p.to = function(target, duration, vars, position) {
			var Engine = (vars.repeat && _globals.TweenMax) || TweenLite;
			return duration ? this.add( new Engine(target, duration, vars), position) : this.set(target, vars, position);
		};

		p.from = function(target, duration, vars, position) {
			return this.add( ((vars.repeat && _globals.TweenMax) || TweenLite).from(target, duration, vars), position);
		};

		p.fromTo = function(target, duration, fromVars, toVars, position) {
...
```

#### <a name="apidoc.element.gsap.TweenLite.to"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.</span>to (target, duration, vars)](#apidoc.element.gsap.TweenLite.to)
- description and source-code
```javascript
to = function (target, duration, vars) {
			return new TweenLite(target, duration, vars);
		}
```
- example usage
```shell
...
				if (cycle) {
					_applyCycle(copy, targets, i);
					if (copy.duration != null) {
						duration = copy.duration;
						delete copy.duration;
					}
				}
				tl.to(targets[i], duration, copy, i * stagger);
			}
			return this.add(tl, position);
		};

		p.staggerFrom = function(targets, duration, vars, stagger, position, onCompleteAll, onCompleteAllParams, onCompleteAllScope) {
			vars.immediateRender = (vars.immediateRender != false);
			vars.runBackwards = true;
...
```



# <a name="apidoc.module.gsap.TweenLite._internals"></a>[module gsap.TweenLite._internals](#apidoc.module.gsap.TweenLite._internals)

#### <a name="apidoc.element.gsap.TweenLite._internals.blobDif"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>blobDif (start, end, filter, pt)](#apidoc.element.gsap.TweenLite._internals.blobDif)
- description and source-code
```javascript
blobDif = function (start, end, filter, pt) {
				var a = [],
					charIndex = 0,
					s = "",
					color = 0,
					startNums, endNums, num, i, l, nonNumbers, currentNum;
				a.start = start;
				a.end = end;
				start = a[0] = start + ""; //ensure values are strings
				end = a[1] = end + "";
				if (filter) {
					filter(a); //pass an array with the starting and ending values and let the filter do whatever it needs to the values.
					start = a[0];
					end = a[1];
				}
				a.length = 0;
				startNums = start.match(_numbersExp) || [];
				endNums = end.match(_numbersExp) || [];
				if (pt) {
					pt._next = null;
					pt.blob = 1;
					a._firstPT = a._applyPT = pt; //apply last in the linked list (which means inserting it first)
				}
				l = endNums.length;
				for (i = 0; i < l; i++) {
					currentNum = endNums[i];
					nonNumbers = end.substr(charIndex, end.indexOf(currentNum, charIndex)-charIndex);
					s += (nonNumbers || !i) ? nonNumbers : ","; //note: SVG spec allows omission of comma/space when a negative sign is wedged
between two numbers, like 2.5-5.3 instead of 2.5,-5.3 but when tweening, the negative value may switch to positive, so we insert
 the comma just in case.
					charIndex += nonNumbers.length;
					if (color) { //sense rgba() values and round them.
						color = (color + 1) % 5;
					} else if (nonNumbers.substr(-5) === "rgba(") {
						color = 1;
					}
					if (currentNum === startNums[i] || startNums.length <= i) {
						s += currentNum;
					} else {
						if (s) {
							a.push(s);
							s = "";
						}
						num = parseFloat(startNums[i]);
						a.push(num);
						a._firstPT = {_next: a._firstPT, t:a, p: a.length-1, s:num, c:((currentNum.charAt(1) === "=") ? parseInt(currentNum.charAt
(0) + "1", 10) * parseFloat(currentNum.substr(2)) : (parseFloat(currentNum) - num)) || 0, f:0, m:(color && color < 4) ? Math.round
 : 0};
						//note: we don't set _prev because we'll never need to remove individual PropTweens from this list.
					}
					charIndex += currentNum.length;
				}
				s += end.substr(charIndex);
				if (s) {
					a.push(s);
				}
				a.setRatio = _setRatio;
				return a;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._internals.isArray"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>isArray (obj)](#apidoc.element.gsap.TweenLite._internals.isArray)
- description and source-code
```javascript
isArray = function (obj) {
					return obj != null && (obj instanceof Array || (typeof(obj) === "object" && !!obj.push && toString.call(obj) === array));
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._internals.isSelector"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>isSelector (v)](#apidoc.element.gsap.TweenLite._internals.isSelector)
- description and source-code
```javascript
isSelector = function (v) {
				return (v && v.length && v !== window && v[0] && (v[0] === window || (v[0].nodeType && v[0].style && !v.nodeType))); //we cannot
 check "nodeType" if the target is window from within an iframe, otherwise it will trigger a security error in some browsers like
 Firefox.
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._internals.lazyRender"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._internals.</span>lazyRender ()](#apidoc.element.gsap.TweenLite._internals.lazyRender)
- description and source-code
```javascript
lazyRender = function () {
				var i = _lazyTweens.length,
					tween;
				_lazyLookup = {};
				while (--i > -1) {
					tween = _lazyTweens[i];
					if (tween && tween._lazy !== false) {
						tween.render(tween._lazy[0], tween._lazy[1], true);
						tween._lazy = false;
					}
				}
				_lazyTweens.length = 0;
			}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins"></a>[module gsap.TweenLite._plugins](#apidoc.module.gsap.TweenLite._plugins)

#### <a name="apidoc.element.gsap.TweenLite._plugins.attr"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>attr ()](#apidoc.element.gsap.TweenLite._plugins.attr)
- description and source-code
```javascript
attr = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
...
						this._parseTransform(target, v);
						continue;
					} else if (_transformMap[p] || p === "pivot") {
						this._parseTransform(target, value);
						continue;
					}

					s = target.attr(p);

					//Some of these properties are in place in order to conform with the standard PropTweens in TweenPlugins so that overwriting
 and roundProps occur properly. For example, f and r may seem unnecessary here, but they enable other functionality.
					//_next:*	next linked list node		[object]
					//t: 	*	target 						[object]
					//p:	*	property (camelCase)		[string]
					//s: 	*	starting value				[number]
					//c:	*	change value				[number]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.bezier"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>bezier ()](#apidoc.element.gsap.TweenLite._plugins.bezier)
- description and source-code
```javascript
bezier = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.colorProps"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>colorProps ()](#apidoc.element.gsap.TweenLite._plugins.colorProps)
- description and source-code
```javascript
colorProps = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.css"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>css ()](#apidoc.element.gsap.TweenLite._plugins.css)
- description and source-code
```javascript
css = function () {
				TweenPlugin.call(this, "css");
				this._overwriteProps.length = 0;
				this.setRatio = CSSPlugin.prototype.setRatio; //speed optimization (avoid prototype lookup on this "hot" method)
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.cssRule"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>cssRule ()](#apidoc.element.gsap.TweenLite._plugins.cssRule)
- description and source-code
```javascript
cssRule = function () {
				TweenPlugin.call(this, "cssRule");
				this._overwriteProps.length = 0;
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.directionalRotation"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>directionalRotation ()](#apidoc.element.gsap.TweenLite._plugins.directionalRotation)
- description and source-code
```javascript
directionalRotation = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.easel"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>easel ()](#apidoc.element.gsap.TweenLite._plugins.easel)
- description and source-code
```javascript
easel = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.endArray"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>endArray ()](#apidoc.element.gsap.TweenLite._plugins.endArray)
- description and source-code
```javascript
endArray = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.modifiers"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>modifiers ()](#apidoc.element.gsap.TweenLite._plugins.modifiers)
- description and source-code
```javascript
modifiers = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.raphael"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>raphael ()](#apidoc.element.gsap.TweenLite._plugins.raphael)
- description and source-code
```javascript
raphael = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.roundProps"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>roundProps ()](#apidoc.element.gsap.TweenLite._plugins.roundProps)
- description and source-code
```javascript
roundProps = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.text"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.</span>text ()](#apidoc.element.gsap.TweenLite._plugins.text)
- description and source-code
```javascript
text = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.attr.prototype"></a>[module gsap.TweenLite._plugins.attr.prototype](#apidoc.module.gsap.TweenLite._plugins.attr.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.attr.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.attr.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween, index) {
			var p, end;
			if (typeof(target.setAttribute) !== "function") {
				return false;
			}
			for (p in value) {
				end = value[p];
				if (typeof(end) === "function") {
					end = end(index, target);
				}
				this._addTween(target, "setAttribute", target.getAttribute(p) + "", end + "", p, false, p);
				this._overwriteProps.push(p);
			}
			return true;
		}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.attr.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.attr.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.attr.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.directionalRotation.prototype"></a>[module gsap.TweenLite._plugins.directionalRotation.prototype](#apidoc.module.gsap.TweenLite._plugins.directionalRotation.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween, index) {
			if (typeof(value) !== "object") {
				value = {rotation:value};
			}
			this.finals = {};
			var cap = (value.useRadians === true) ? Math.PI * 2 : 360,
				min = 0.000001,
				p, v, start, end, dif, split;
			for (p in value) {
				if (p !== "useRadians") {
					end = value[p];
					if (typeof(end) === "function") {
						end = end(index, target);
					}
					split = (end + "").split("_");
					v = split[0];
					start = parseFloat( (typeof(target[p]) !== "function") ? target[p] : target[ ((p.indexOf("set") || typeof(target["get" + p.
substr(3)]) !== "function") ? p : "get" + p.substr(3)) ]() );
					end = this.finals[p] = (typeof(v) === "string" && v.charAt(1) === "=") ? start + parseInt(v.charAt(0) + "1", 10) * Number(v
.substr(2)) : Number(v) || 0;
					dif = end - start;
					if (split.length) {
						v = split.join("_");
						if (v.indexOf("short") !== -1) {
							dif = dif % cap;
							if (dif !== dif % (cap / 2)) {
								dif = (dif < 0) ? dif + cap : dif - cap;
							}
						}
						if (v.indexOf("_cw") !== -1 && dif < 0) {
							dif = ((dif + cap * 9999999999) % cap) - ((dif / cap) | 0) * cap;
						} else if (v.indexOf("ccw") !== -1 && dif > 0) {
							dif = ((dif - cap * 9999999999) % cap) - ((dif / cap) | 0) * cap;
						}
					}
					if (dif > min || dif < -min) {
						this._addTween(target, p, start, start + dif, p);
						this._overwriteProps.push(p);
					}
				}
			}
			return true;
		}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.directionalRotation.prototype.</span>setRatio (ratio)](#apidoc.element.gsap.TweenLite._plugins.directionalRotation.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (ratio) {
			var pt;
			if (ratio !== 1) {
				this._super.setRatio.call(this, ratio);
			} else {
				pt = this._firstPT;
				while (pt) {
					if (pt.f) {
						pt.t[pt.p](this.finals[pt.p]);
					} else {
						pt.t[pt.p] = this.finals[pt.p];
					}
					pt = pt._next;
				}
			}
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.easel.prototype"></a>[module gsap.TweenLite._plugins.easel.prototype](#apidoc.module.gsap.TweenLite._plugins.easel.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.easel.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.easel.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween, index) {
			this._target = target;
			var p, pt, tint, colorMatrix, end, labels, i;
			for (p in value) {

				end = value[p];
				if (typeof(end) === "function") {
					end = end(index, target);
				}
				if (p === "colorFilter" || p === "tint" || p === "tintAmount" || p === "exposure" || p === "brightness") {
					if (!tint) {
						_parseColorFilter(target, value.colorFilter || value, this);
						tint = true;
					}

				} else if (p === "saturation" || p === "contrast" || p === "hue" || p === "colorize" || p === "colorizeAmount") {
					if (!colorMatrix) {
						_parseColorMatrixFilter(target, value.colorMatrixFilter || value, this);
						colorMatrix = true;
					}

				} else if (p === "frame") {
					this._firstPT = pt = {_next:this._firstPT, t:target, p:"gotoAndStop", s:target.currentFrame, f:true, n:"frame", pr:0, type:
0, m:Math.round};
					if (typeof(end) === "string" && end.charAt(1) !== "=" && (labels = target.labels)) {
						for (i = 0; i < labels.length; i++) {
							if (labels[i].label === end) {
								end = labels[i].position;
							}
						}
					}
					pt.c = (typeof(end) === "number") ? end - pt.s : parseFloat((end+"").split("=").join(""));
					if (pt._next) {
						pt._next._prev = pt;
					}

				} else if (target[p] != null) {
					this._firstPT = pt = {_next:this._firstPT, t:target, p:p, f:(typeof(target[p]) === "function"), n:p, pr:0, type:0};
					pt.s = (!pt.f) ? parseFloat(target[p]) : target[ ((p.indexOf("set") || typeof(target["get" + p.substr(3)]) !== "function") ?
p : "get" + p.substr(3)) ]();
					pt.c = (typeof(end) === "number") ? end - pt.s : (typeof(end) === "string") ? parseFloat(end.split("=").join("")) : 0;

					if (pt._next) {
						pt._next._prev = pt;
					}
				}

			}
			return true;
		}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.easel.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.easel.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.easel.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.easel.prototype.</span>setRatio (v)](#apidoc.element.gsap.TweenLite._plugins.easel.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (v) {
			var pt = this._firstPT,
				min = 0.000001,
				val;
			while (pt) {
				val = pt.c * v + pt.s;
				if (pt.m) {
					val = pt.m(val, pt.t);
				} else if (val < min && val > -min) {
					val = 0;
				}
				if (pt.f) {
					pt.t[pt.p](val);
				} else {
					pt.t[pt.p] = val;
				}
				pt = pt._next;
			}
			if (this._target.cacheID) {
				this._target.updateCache();
			}
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.endArray.prototype"></a>[module gsap.TweenLite._plugins.endArray.prototype](#apidoc.module.gsap.TweenLite._plugins.endArray.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.endArray.prototype._mod"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_mod (lookup)](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype._mod)
- description and source-code
```javascript
_mod = function (lookup) {
			if (typeof(lookup.endArray) === "function") {
				this._mod = lookup.endArray;
			}
		}
```
- example usage
```shell
...
			i = rp.length;
			while (--i > -1) {
				prop = rp[i];
				pt = tween._firstPT;
				while (pt) {
					next = pt._next; //record here, because it may get removed
					if (pt.pg) {
						pt.t._mod(lookup);
					} else if (pt.n === prop) {
						if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
							_roundLinkedList(pt.t._firstPT);
						} else {
							this._add(pt.t, prop, pt.s, pt.c);
							//remove from linked list
							if (next) {
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.endArray.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween) {
			var i = value.length,
				a = this.a = [],
				start, end;
			this.target = target;
			this._mod = 0;
			if (!i) {
				return false;
			}
			while (--i > -1) {
				start = target[i];
				end = value[i];
				if (start !== end) {
					a.push({i:i, s:start, c:end - start});
				}
			}
			return true;
		}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.endArray.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.endArray.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.endArray.prototype.</span>setRatio (ratio)](#apidoc.element.gsap.TweenLite._plugins.endArray.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (ratio) {
			var target = this.target,
				a = this.a,
				i = a.length,
				mod = this._mod,
				e, val;
			if (mod) {
				while (--i > -1) {
					e = a[i];
					target[e.i] = mod(e.s + e.c * ratio, target);
				}
			} else {
				while (--i > -1) {
					e = a[i];
					val = e.s + e.c * ratio;
					target[e.i] = (val < 0.000001 && val > -0.000001) ? 0 : val;
				}
			}
		}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.modifiers.prototype"></a>[module gsap.TweenLite._plugins.modifiers.prototype](#apidoc.module.gsap.TweenLite._plugins.modifiers.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._add"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_add (target, p, s, c, mod)](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._add)
- description and source-code
```javascript
_add = function (target, p, s, c, mod) {
			this._addTween(target, p, s, s + c, p, mod);
			this._overwriteProps.push(p);
		}
```
- example usage
```shell
...
					next = pt._next; //record here, because it may get removed
					if (pt.pg) {
						pt.t._mod(lookup);
					} else if (pt.n === prop) {
						if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
							_roundLinkedList(pt.t._firstPT);
						} else {
							this._add(pt.t, prop, pt.s, pt.c);
							//remove from linked list
							if (next) {
								next._prev = pt._prev;
							}
							if (pt._prev) {
								pt._prev._next = next;
							} else if (tween._firstPT === pt) {
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._onInitAllProps"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_onInitAllProps ()](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._onInitAllProps)
- description and source-code
```javascript
_onInitAllProps = function () {
					var tween = this._tween,
						lookup = this._vars,
						mpt = this,
						pt = tween._firstPT,
						val, next;
					while (pt) {
						next = pt._next; //record here, because it may get removed
						val = lookup[pt.n];
						if (pt.pg) {
							if (pt.t._propName === "css") { //handle CSSPlugin uniquely (for performance, due to the fact that the values almost always
 are a concatenation of numbers and strings, like suffixes, and we don't want to slow down the regular CSSPlugin setRatio() performance
 with conditional checks for if the value needs to be modded, so we pull any modding prop out and change it to a type:2 one that
 simply calls a setRatio() method where we encapsulate the modding and update all together. That way, it says in the main CSSProp
 linked list and just has some custom logic applied to it inside its setRatio())
								_modCSS(lookup, pt.t);
							} else if (pt.t !== mpt) { //don't run modProps on modProps :)
								val = lookup[pt.t._propName];
								pt.t._mod((typeof(val) === "object") ? val : lookup);
							}
						} else if (typeof(val) === "function") {
							if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
								pt.t._applyPT.m = val;
							} else {
								this._add(pt.t, pt.p, pt.s, pt.c, val);
								//remove from linked list
								if (next) {
									next._prev = pt._prev;
								}
								if (pt._prev) {
									pt._prev._next = next;
								} else if (tween._firstPT === pt) {
									tween._firstPT = next;
								}
								pt._next = pt._prev = null;
								tween._propLookup[pt.n] = mpt;
							}
						}
						pt = next;
					}
					return false;
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween) {
					this._tween = tween;
					this._vars = value;
					return true;
				}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.modifiers.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.modifiers.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.modifiers.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.raphael.prototype"></a>[module gsap.TweenLite._plugins.raphael.prototype](#apidoc.module.gsap.TweenLite._plugins.raphael.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.raphael.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween) {
				if (!target.attr) { //raphael must have attr() method
					return false;
				}
				this._target = target;
				this._tween = tween;
				this._props = target._gsProps = target._gsProps || {};
				var p, s, v, pt, clr1, clr2, rel;

				for (p in value) {

					v = value[p];

					if (p === "transform") {
						this._parseTransform(target, v);
						continue;
					} else if (_transformMap[p] || p === "pivot") {
						this._parseTransform(target, value);
						continue;
					}

					s = target.attr(p);

					//Some of these properties are in place in order to conform with the standard PropTweens in TweenPlugins so that overwriting
 and roundProps occur properly. For example, f and r may seem unnecessary here, but they enable other functionality.
					//_next:*	next linked list node		[object]
					//t: 	*	target 						[object]
					//p:	*	property (camelCase)		[string]
					//s: 	*	starting value				[number]
					//c:	*	change value				[number]
					//f:	* 	is function					[boolean]
					//n:	*	name (for overwriting)		[string]
					//b:		beginning value				[string]
					//i:		intermediate value			[string]
					//e: 		ending value				[string]
					//r:	*	round						[boolean]
					//type:		0=normal, 1=color, 2=rgba, -1=non-tweening prop	[number]
					this._firstPT = pt = {_next:this._firstPT,
						t:this._props,
						p:p,
						b:s,
						f:false,
						n:"raphael_" + p,
						r:false,
						type:0};

					//color values must be split apart into their R, G, B (and sometimes alpha) values and tweened independently.
					if (p === "fill" || p === "stroke") {
						clr1 = _parseColor(s);
						clr2 = _parseColor(v);
						pt.e = v;
						pt.s = Number(clr1[0]);				//red starting value
						pt.c = Number(clr2[0]) - pt.s;		//red change
						pt.gs = Number(clr1[1]);			//green starting value
						pt.gc = Number(clr2[1]) - pt.gs;	//green change
						pt.bs = Number(clr1[2]);			//blue starting value
						pt.bc = Number(clr2[2]) - pt.bs;	//blue change
						if (clr1.length > 3 || clr2.length > 3) { //detect an rgba() value
							pt.as = (clr1.length < 4) ? 1 : Number(clr1[3]);
							pt.ac = ((clr2.length < 4) ? 1 : Number(clr2[3])) - pt.as;
							pt.type = 2; //2 = rgba() tween
						} else {
							pt.type = 1; //1 = color tween, -1 = no tween, just set the value at the end because there's no changes
						}

					} else {

						s = (typeof(s) === "string") ? parseFloat(s.replace(_NaNExp, "")) : Number(s);

						if (typeof(v) === "string") {
							rel = (v.charAt(1) === "=");
							v = parseFloat(v.replace(_NaNExp, ""));
						} else {
							rel = false;
						}

						pt.e = (v || v === 0) ? (rel ? v + s : v) : value[p]; //ensures that any += or -= prefixes are taken care of.

						if ((s || s === 0) && (v || v === 0) && (pt.c = (rel ? v : v - s))) { //faster than isNaN(). Also, we set pt.c (change) here
 because if it's 0, we'll just treat it like a non-tweening value. can't do (v !== start) because if it's a relative value and the
 CHANGE is identical to the START, the condition will fail unnecessarily.
							pt.s = s;
						} else {
							pt.type = -1;
							pt.i = value[p]; //intermediate value is typically the same as the end value.
							pt.s = pt.c = 0;
						}

					}

					this._overwriteProps.push("raphael_" + p);
					if (pt._next) {
						pt._next._prev = pt;
					}
				}

				return true;
			}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.raphael.prototype._parseTransform"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>_parseTransform (t, v)](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype._parseTransform)
- description and source-code
```javascript
_parseTransform = function (t, v) {
		if (this._transform) { return; } //only need to parse the transform once, and only if the browser supports it.

		var m1 = this._transform = _getTransform(t, true),
			min = 0.000001,
			m2, skewY, p, pt, copy, dx, dy, mtx, pivot;

		if (typeof(v) === "object") { //for values like scaleX, scaleY, rotation, x, y, skewX, and skewY or transform:{...} (object)

			m2 = {scaleX:_parseVal((v.scaleX != null) ? v.scaleX : v.scale, m1.scaleX),
				  scaleY:_parseVal((v.scaleY != null) ? v.scaleY : v.scale, m1.scaleY),
				  tx:_parseVal(v.tx, m1.tx),
				  ty:_parseVal(v.ty, m1.ty)};

			if (v.shortRotation != null) {
				m2.rotation = (typeof(v.shortRotation) === "number") ? v.shortRotation * _DEG2RAD : _parseAngle(v.shortRotation, m1.rotation
);
				var dif = (m2.rotation - m1.rotation) % (Math.PI * 2);
				if (dif !== dif % Math.PI) {
					dif += Math.PI * ((dif < 0) ? 2 : -2);
				}
				m2.rotation = m1.rotation + dif;

			} else {
				m2.rotation = (v.rotation == null) ? m1.rotation : (typeof(v.rotation) === "number") ? v.rotation * _DEG2RAD : _parseAngle(v
.rotation, m1.rotation);
			}
			m2.skewX = (v.skewX == null) ? m1.skewX : (typeof(v.skewX) === "number") ? v.skewX * _DEG2RAD : _parseAngle(v.skewX, m1.skewX
);

			//note: for performance reasons, we combine all skewing into the skewX and rotation values, ignoring skewY but we must still
record it so that we can discern how much of the overall skew is attributed to skewX vs. skewY. Otherwise, if the skewY would always
 act relative (tween skewY to 10deg, for example, multiple times and if we always combine things into skewX, we can't remember that
 skewY was 10 from last time). Remember, a skewY of 10 degrees looks the same as a rotation of 10 degrees plus a skewX of -10 degrees
.
			m2.skewY = (v.skewY == null) ? m1.skewY : (typeof(v.skewY) === "number") ? v.skewY * _DEG2RAD : _parseAngle(v.skewY, m1.skewY
);
			if ((skewY = m2.skewY - m1.skewY)) {
				m2.skewX += skewY;
				m2.rotation += skewY;
			}
			//don't allow rotation/skew values to be a SUPER small decimal because when they're translated back to strings for setting the
 css property, the browser reports them in a funky way, like 1-e7. Of course we could use toFixed() to resolve that issue but that
 hurts performance quite a bit with all those function calls on every frame, plus it is virtually impossible to discern values that
 small visually (nobody will notice changing a rotation of 0.0000001 to 0, so the performance improvement is well worth it).
			if (m2.skewY < min) if (m2.skewY > -min) {
				m2.skewY = 0;
			}
			if (m2.skewX < min) if (m2.skewX > -min) {
				m2.skewX = 0;
			}
			if (m2.rotation < min) if (m2.rotation > -min) {
				m2.rotation = 0;
			}

			pivot = v.localPivot || v.globalPivot;

			if (typeof(pivot) === "string") {
				copy = pivot.split(",");
				dx = Number(copy[0]);
				dy = Number(copy[1]);
			} else if (typeof(pivot) === "object") {
				dx = Number(pivot.x);
				dy = Number(pivot.y);
			} else if (v.localPivot) {
				copy = t.getBBox(true);
				dx = copy.width / 2;
				dy = copy.height / 2;
			} else {
				copy = t.getBBox();
				dx = copy.x + copy.width / 2;
				dy = copy.y + copy.height / 2;
			}

			if (v.localPivot) {
				mtx = t.matrix;
				dx += t.attr("x");
				dy += t.attr("y");
				this._pxl = dx;
				this._pyl = dy;
				this._pxg = dx * mtx.a + dy * mtx.c + mtx.e - m1.tx;
				this._pyg = dx * mtx.b + dy * mtx.d + mtx.f - m1.ty;
			} else {
				mtx = t.matrix.invert();
				this._pxl = dx * mtx.a + dy * mtx.c + mtx.e;
				this._pyl = dx * mtx.b + dy * mtx.d + mtx.f;
				this._pxg = dx - m1.tx;
				this._pyg = dy - m1.ty;
			}

		} else if (typeof(v) === "string") { //for values like transform:"rotate(60deg) scale(0.5, 0.8)"
			copy = this._target.transform();
			t.transform(v);
			m2 = _getTransform(t, false);
			t.transform(copy);
		} else {
			return;
		}

		for (p in _transformMap) {
			if (m1[p] !== m2[p]) if (p !== "shortRotation") if (p !== "scale") {
				this._firstPT = pt = {_next:this._firstPT, t:m1, p:p, s:m1[p], c:m2[p] - m1[p], n:p, f:fal ...
```
- example usage
```shell
...
				var p, s, v, pt, clr1, clr2, rel;

				for (p in value) {

					v = value[p];

					if (p === "transform") {
						this._parseTransform(target, v);
						continue;
					} else if (_transformMap[p] || p === "pivot") {
						this._parseTransform(target, value);
						continue;
					}

					s = target.attr(p);
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.raphael.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.raphael.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.raphael.prototype.</span>setRatio (v)](#apidoc.element.gsap.TweenLite._plugins.raphael.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (v) {
				var pt = this._firstPT, val;

				while (pt) {
					val = pt.c * v + pt.s;
					if (pt.r) {
						val = Math.round(val);
					}
					if (!pt.type) {
						pt.t[pt.p] = val;
					} else if (pt.type === 1) { //rgb()
						pt.t[pt.p] = "rgb(" + (val >> 0) + ", " + ((pt.gs + (v * pt.gc)) >> 0) + ", " + ((pt.bs + (v * pt.bc)) >> 0) + ")";
					} else if (pt.type === 2) { //rgba()
						pt.t[pt.p] = "rgba(" + (val >> 0) + ", " + ((pt.gs + (v * pt.gc)) >> 0) + ", " + ((pt.bs + (v * pt.bc)) >> 0) + ", " + (pt
.as + (v * pt.ac)) + ")";
					} else if (pt.type === -1) { //non-tweening
						pt.t[pt.p] = pt.i;
					}
					pt = pt._next;
				}

				this._target.attr(this._props);

				//apply transform values like x, y, scaleX, scaleY, rotation, skewX, or skewY. We do these after looping through all the PropTweens
 because those are where the changes are made to scaleX/scaleY/rotation/skewX/skewY/x/y.
				if (this._transform) {
					pt = this._transform; //to improve speed and reduce size, reuse the pt variable as an alias to the _transform property
					var ang = pt.rotation,
						skew = ang - pt.skewX,
						a = Math.cos(ang) * pt.scaleX,
						b = Math.sin(ang) * pt.scaleX,
						c = Math.sin(skew) * -pt.scaleY,
						d = Math.cos(skew) * pt.scaleY,
						min = 0.000001,
						pxl = this._pxl,
						pyl = this._pyl;

					//some browsers have a hard time with very small values like 2.4492935982947064e-16 (notice the "e-" towards the end) and would
 render the object slightly off. So we round to 0 in these cases for both b and c. The conditional logic here is faster than calling
 Math.abs().
					if (b < min) if (b > -min) {
						b = 0;
					}
					if (c < min) if (c > -min) {
						c = 0;
					}
					pt.ox = this._pxg - (pxl * a + pyl * c); //we must record the offset x/y that we're making from the regular tx/ty (matrix.e
 and f) so that we can correctly interpret positional data in _getTransform(). See note there on tx and ox.
					pt.oy = this._pyg - (pxl * b + pyl * d);
					this._target.transform("m" + a + "," + b + "," + c + "," + d + "," + (pt.tx + pt.ox) + "," + (pt.ty + pt.oy));
				}

			}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.roundProps.prototype"></a>[module gsap.TweenLite._plugins.roundProps.prototype](#apidoc.module.gsap.TweenLite._plugins.roundProps.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._add"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_add (target, p, s, c)](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._add)
- description and source-code
```javascript
_add = function (target, p, s, c) {
			this._addTween(target, p, s, s + c, p, Math.round);
			this._overwriteProps.push(p);
		}
```
- example usage
```shell
...
					next = pt._next; //record here, because it may get removed
					if (pt.pg) {
						pt.t._mod(lookup);
					} else if (pt.n === prop) {
						if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
							_roundLinkedList(pt.t._firstPT);
						} else {
							this._add(pt.t, prop, pt.s, pt.c);
							//remove from linked list
							if (next) {
								next._prev = pt._prev;
							}
							if (pt._prev) {
								pt._prev._next = next;
							} else if (tween._firstPT === pt) {
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._onInitAllProps"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_onInitAllProps ()](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._onInitAllProps)
- description and source-code
```javascript
_onInitAllProps = function () {
			var tween = this._tween,
				rp = (tween.vars.roundProps.join) ? tween.vars.roundProps : tween.vars.roundProps.split(","),
				i = rp.length,
				lookup = {},
				rpt = tween._propLookup.roundProps,
				prop, pt, next;
			while (--i > -1) {
				lookup[rp[i]] = Math.round;
			}
			i = rp.length;
			while (--i > -1) {
				prop = rp[i];
				pt = tween._firstPT;
				while (pt) {
					next = pt._next; //record here, because it may get removed
					if (pt.pg) {
						pt.t._mod(lookup);
					} else if (pt.n === prop) {
						if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
							_roundLinkedList(pt.t._firstPT);
						} else {
							this._add(pt.t, prop, pt.s, pt.c);
							//remove from linked list
							if (next) {
								next._prev = pt._prev;
							}
							if (pt._prev) {
								pt._prev._next = next;
							} else if (tween._firstPT === pt) {
								tween._firstPT = next;
							}
							pt._next = pt._prev = null;
							tween._propLookup[prop] = rpt;
						}
					}
					pt = next;
				}
			}
			return false;
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>_onInitTween (target, value, tween)](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween) {
					this._tween = tween;
					return true;
				}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.roundProps.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.roundProps.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.roundProps.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite._plugins.text.prototype"></a>[module gsap.TweenLite._plugins.text.prototype](#apidoc.module.gsap.TweenLite._plugins.text.prototype)

#### <a name="apidoc.element.gsap.TweenLite._plugins.text.prototype._onInitTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>_onInitTween (target, value, tween, index)](#apidoc.element.gsap.TweenLite._plugins.text.prototype._onInitTween)
- description and source-code
```javascript
_onInitTween = function (target, value, tween, index) {
					var i = target.nodeName.toUpperCase(),
						shrt;
					if (typeof(value) === "function") {
						value = value(index, target);
					}
					this._svg = (target.getBBox && (i === "TEXT" || i === "TSPAN"));
					if (!("innerHTML" in target) && !this._svg) {
						return false;
					}
					this._target = target;
					if (typeof(value) !== "object") {
						value = {value:value};
					}
					if (value.value === undefined) {
						this._text = this._original = [""];
						return true;
					}
					this._delimiter = value.delimiter || "";
					this._original = _getText(target).replace(/\s+/g, " ").split(this._delimiter);
					this._text = value.value.replace(/\s+/g, " ").split(this._delimiter);
					this._runBackwards = (tween.vars.runBackwards === true);
					if (this._runBackwards) {
						i = this._original;
						this._original = this._text;
						this._text = i;
					}
					if (typeof(value.newClass) === "string") {
						this._newClass = value.newClass;
						this._hasClass = true;
					}
					if (typeof(value.oldClass) === "string") {
						this._oldClass = value.oldClass;
						this._hasClass = true;
					}
					i = this._original.length - this._text.length;
					shrt = (i < 0) ? this._original : this._text;
					this._fillChar = value.fillChar || (value.padSpace ? "&nbsp;" : "");
					if (i < 0) {
						i = -i;
					}
					while (--i > -1) {
						shrt.push(this._fillChar);
					}
					return true;
				}
```
- example usage
```shell
...
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
...
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.text.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>constructor ()](#apidoc.element.gsap.TweenLite._plugins.text.prototype.constructor)
- description and source-code
```javascript
constructor = function () {
						TweenPlugin.call(this, propName, priority);
						this._overwriteProps = overwriteProps || [];
					}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite._plugins.text.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite._plugins.text.prototype.</span>setRatio (ratio)](#apidoc.element.gsap.TweenLite._plugins.text.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (ratio) {
					if (ratio > 1) {
						ratio = 1;
					} else if (ratio < 0) {
						ratio = 0;
					}
					if (this._runBackwards) {
						ratio = 1 - ratio;
					}
					var l = this._text.length,
						i = (ratio * l + 0.5) | 0,
						applyNew, applyOld, str;
					if (this._hasClass) {
						applyNew = (this._newClass && i !== 0);
						applyOld = (this._oldClass && i !== l);
						str = (applyNew ? "<span class='" + this._newClass + "'>" : "") + this._text.slice(0, i).join(this._delimiter) + (applyNew
 ? "</span>" : "") + (applyOld ? "<span class='" + this._oldClass + "'>" : "") + this._delimiter + this._original.slice(i).join(
this._delimiter) + (applyOld ? "</span>" : "");
					} else {
						str = this._text.slice(0, i).join(this._delimiter) + this._delimiter + this._original.slice(i).join(this._delimiter);
					}
					if (this._svg) { //SVG text elements don't have an "innerHTML" in Microsoft browsers.
						this._target.textContent = str;
					} else {
						this._target.innerHTML = (this._fillChar === "&nbsp;" && str.indexOf("  ") !== -1) ? str.split("  ").join("&nbsp;&nbsp;") :
str;
					}
				}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.TweenLite.prototype"></a>[module gsap.TweenLite.prototype](#apidoc.module.gsap.TweenLite.prototype)

#### <a name="apidoc.element.gsap.TweenLite.prototype._enabled"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_enabled (enabled, ignoreTimeline)](#apidoc.element.gsap.TweenLite.prototype._enabled)
- description and source-code
```javascript
_enabled = function (enabled, ignoreTimeline) {
			if (!_tickerActive) {
				_ticker.wake();
			}
			if (enabled && this._gc) {
				var targets = this._targets,
					i;
				if (targets) {
					i = targets.length;
					while (--i > -1) {
						this._siblings[i] = _register(targets[i], this, true);
					}
				} else {
					this._siblings = _register(this.target, this, true);
				}
			}
			Animation.prototype._enabled.call(this, enabled, ignoreTimeline);
			if (this._notifyPluginsOfEnabled) if (this._firstPT) {
				return TweenLite._onPluginEvent((enabled ? "_onEnable" : "_onDisable"), this);
			}
			return false;
		}
```
- example usage
```shell
...
				//in case any of the ancestors had completed but should now be enabled...
				tl = this;
				beforeRawTime = (tl.rawTime() > value._startTime); //if the tween is placed on the timeline so that it starts BEFORE the current
 rawTime, we should align the playhead (move the timeline). This is because sometimes users will create a timeline, let it finish
, and much later append a tween and expect it to run instead of jumping to its end state. While technically one could argue that
 it should jump to its end state, that's not what users intuitively expect.
				while (tl._timeline) {
					if (beforeRawTime && tl._timeline.smoothChildTiming) {
						tl.totalTime(tl._totalTime, true); //moves the timeline (shifts its startTime) if necessary, and also enables it.
					} else if (tl._gc) {
						tl._enabled(true, false);
					}
					tl = tl._timeline;
				}
			}

			return this;
		};
...
```

#### <a name="apidoc.element.gsap.TweenLite.prototype._init"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_init ()](#apidoc.element.gsap.TweenLite.prototype._init)
- description and source-code
```javascript
_init = function () {
			var v = this.vars,
				op = this._overwrittenProps,
				dur = this._duration,
				immediate = !!v.immediateRender,
				ease = v.ease,
				i, initPlugins, pt, p, startVars, l;
			if (v.startAt) {
				if (this._startAt) {
					this._startAt.render(-1, true); //if we've run a startAt previously (when the tween instantiated), we should revert it so that
 the values re-instantiate correctly particularly for relative tweens. Without this, a TweenLite.fromTo(obj, 1, {x:"+=100"}, {x:"-=
100"}), for example, would actually jump to +=200 because the startAt would run twice, doubling the relative change.
					this._startAt.kill();
				}
				startVars = {};
				for (p in v.startAt) { //copy the properties/values into a new object to avoid collisions, like var to = {x:0}, from = {x:500
}; timeline.fromTo(e, 1, from, to).fromTo(e, 1, to, from);
					startVars[p] = v.startAt[p];
				}
				startVars.overwrite = false;
				startVars.immediateRender = true;
				startVars.lazy = (immediate && v.lazy !== false);
				startVars.startAt = startVars.delay = null; //no nesting of startAt objects allowed (otherwise it could cause an infinite loop
).
				this._startAt = TweenLite.to(this.target, 0, startVars);
				if (immediate) {
					if (this._time > 0) {
						this._startAt = null; //tweens that render immediately (like most from() and fromTo() tweens) shouldn't revert when their
parent timeline's playhead goes backward past the startTime because the initial render could have happened anytime and it shouldn
't be directly correlated to this tween's startTime. Imagine setting up a complex animation where the beginning states of various
 objects are rendered immediately but the tween doesn't happen for quite some time - if we revert to the starting values as soon
 as the playhead goes backward past the tween's startTime, it will throw things off visually. Reversion should only happen in TimelineLite
/Max instances where immediateRender was false (which is the default in the convenience methods like from()).
					} else if (dur !== 0) {
						return; //we skip initialization here so that overwriting doesn't occur until the tween actually begins. Otherwise, if you
 create several immediateRender:true tweens of the same target/properties to drop into a TimelineLite or TimelineMax, the last one
 created would overwrite the first ones because they didn't get placed into the timeline yet before the first render occurs and
kicks in overwriting.
					}
				}
			} else if (v.runBackwards && dur !== 0) {
				//from() tweens must be handled uniquely: their beginning values must be rendered but we don't want overwriting to occur yet
 (when time is still 0). Wait until the tween actually begins before doing all the routines like overwriting. At that time, we should
 render at the END of the tween to ensure that things initialize correctly (remember, from() tweens go backwards)
				if (this._startAt) {
					this._startAt.render(-1, true);
					this._startAt.kill();
					this._startAt = null;
				} else {
					if (this._time !== 0) { //in rare cases (like if a from() tween runs and then is invalidate()-ed), immediateRender could be
 true but the initial forced-render gets skipped, so there's no need to force the render in this context when the _time is greater
 than 0
						immediate = false;
					}
					pt = {};
					for (p in v) { //copy props into a new object and skip any reserved props, otherwise onComplete or onUpdate or onStart could
 fire. We should, however, permit autoCSS to go through.
						if (!_reservedProps[p] || p === "autoCSS") {
							pt[p] = v[p];
						}
					}
					pt.overwrite = 0;
					pt.data = "isFromStart"; //we tag the tween with as "isFromStart" so that if [inside a plugin] we need to only do something
 at the very END of a tween, we have a way of identifying this tween as merely the one that's setting the beginning values for a
 "from()" tween. For example, clearProps in CSSPlugin should only get applied at the very END of a tween and without this tag, from
(...{height:100, clearProps:"height", delay:1}) would wi ...
```
- example usage
```shell
...
					}
					pt.overwrite = 0;
					pt.data = "isFromStart"; //we tag the tween with as "isFromStart" so that if [inside a plugin] we need to only do something
 at the very END of a tween, we have a way of identifying this tween as merely the one that's setting the beginning values for a
 "from()" tween. For example, clearProps in CSSPlugin should only get applied at the very END of a tween and without this tag, from
(...{height:100, clearProps:"height", delay:1}) would wipe the height at the beginning of the tween and after 1 second, it'd kick
 back in.
					pt.lazy = (immediate && v.lazy !== false);
					pt.immediateRender = immediate; //zero-duration tweens render immediately by default, but if we're not specifically instructed
 to render this tween immediately, we should skip this and merely _init() to record the starting values (rendering them immediately
 would push them to completion which is wasteful in that case - we'd have to render(-1) immediately after)
					this._startAt = TweenLite.to(this.target, 0, pt);
					if (!immediate) {
						this._startAt._init(); //ensures that the initial values are recorded
						this._startAt._enabled(false); //no need to have the tween render on the next cycle. Disable it because we'll always manually
 control the renders of the _startAt tween.
						if (this.vars.immediateRender) {
							this._startAt = null;
						}
					} else if (this._time === 0) {
						return;
					}
...
```

#### <a name="apidoc.element.gsap.TweenLite.prototype._initProps"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_initProps (target, propLookup, siblings, overwrittenProps, index)](#apidoc.element.gsap.TweenLite.prototype._initProps)
- description and source-code
```javascript
_initProps = function (target, propLookup, siblings, overwrittenProps, index) {
			var p, i, initPlugins, plugin, pt, v;
			if (target == null) {
				return false;
			}

			if (_lazyLookup[target._gsTweenID]) {
				_lazyRender(); //if other tweens of the same target have recently initted but haven't rendered yet, we've got to force the render
 so that the starting values are correct (imagine populating a timeline with a bunch of sequential tweens and then jumping to the
 end)
			}

			if (!this.vars.css) if (target.style) if (target !== window && target.nodeType) if (_plugins.css) if (this.vars.autoCSS !== false
) { //it's so common to use TweenLite/Max to animate the css of DOM elements, we assume that if the target is a DOM element, that
's what is intended (a convenience so that users don't have to wrap things in css:{}, although we still recommend it for a slight
 performance boost and better specificity). Note: we cannot check "nodeType" on the window inside an iframe.
				_autoCSS(this.vars, target);
			}
			for (p in this.vars) {
				v = this.vars[p];
				if (_reservedProps[p]) {
					if (v) if ((v instanceof Array) || (v.push && _isArray(v))) if (v.join("").indexOf("{self}") !== -1) {
						this.vars[p] = v = this._swapSelfInParams(v, this);
					}

				} else if (_plugins[p] && (plugin = new _plugins[p]())._onInitTween(target, this.vars[p], this, index)) {

					//t - target 		[object]
					//p - property 		[string]
					//s - start			[number]
					//c - change		[number]
					//f - isFunction	[boolean]
					//n - name			[string]
					//pg - isPlugin 	[boolean]
					//pr - priority		[number]
					//m - mod           [function | 0]
					this._firstPT = pt = {_next:this._firstPT, t:plugin, p:"setRatio", s:0, c:1, f:1, n:p, pg:1, pr:plugin._priority, m:0};
					i = plugin._overwriteProps.length;
					while (--i > -1) {
						propLookup[plugin._overwriteProps[i]] = this._firstPT;
					}
					if (plugin._priority || plugin._onInitAllProps) {
						initPlugins = true;
					}
					if (plugin._onDisable || plugin._onEnable) {
						this._notifyPluginsOfEnabled = true;
					}
					if (pt._next) {
						pt._next._prev = pt;
					}

				} else {
					propLookup[p] = _addPropTween.call(this, target, p, "get", v, p, 0, null, this.vars.stringFilter, index);
				}
			}

			if (overwrittenProps) if (this._kill(overwrittenProps, target)) { //another tween may have tried to overwrite properties of this
 tween before init() was called (like if two tweens start at the same time, the one created second will run first)
				return this._initProps(target, propLookup, siblings, overwrittenProps, index);
			}
			if (this._overwrite > 1) if (this._firstPT) if (siblings.length > 1) if (_applyOverwrite(target, this, propLookup, this._overwrite
, siblings)) {
				this._kill(propLookup, target);
				return this._initProps(target, propLookup, siblings, overwrittenProps, index);
			}
			if (this._firstPT) if ((this.vars.lazy !== false && this._duration) || (this.vars.lazy && !this._duration)) { //zero duration
 tweens don't lazy render by default; everything else does.
				_lazyLookup[target._gsTweenID] = true;
			}
			return initPlugins;
		}
```
- example usage
```shell
...
			this._easeType = this._ease._type;
			this._easePower = this._ease._power;
			this._firstPT = null;

			if (this._targets) {
				l = this._targets.length;
				for (i = 0; i < l; i++) {
					if ( this._initProps( this._targets[i], (this._propLookup[i] = {}), this._siblings[i], (op ? op[i] : null), i) ) {
						initPlugins = true;
					}
				}
			} else {
				initPlugins = this._initProps(this.target, this._propLookup, this._siblings, op, 0);
			}
...
```

#### <a name="apidoc.element.gsap.TweenLite.prototype._kill"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>_kill (vars, target, overwritingTween)](#apidoc.element.gsap.TweenLite.prototype._kill)
- description and source-code
```javascript
_kill = function (vars, target, overwritingTween) {
			if (vars === "all") {
				vars = null;
			}
			if (vars == null) if (target == null || target === this.target) {
				this._lazy = false;
				return this._enabled(false, false);
			}
			target = (typeof(target) !== "string") ? (target || this._targets || this.target) : TweenLite.selector(target) || target;
			var simultaneousOverwrite = (overwritingTween && this._time && overwritingTween._startTime === this._startTime && this._timeline
 === overwritingTween._timeline),
				i, overwrittenProps, p, pt, propLookup, changed, killProps, record, killed;
			if ((_isArray(target) || _isSelector(target)) && typeof(target[0]) !== "number") {
				i = target.length;
				while (--i > -1) {
					if (this._kill(vars, target[i], overwritingTween)) {
						changed = true;
					}
				}
			} else {
				if (this._targets) {
					i = this._targets.length;
					while (--i > -1) {
						if (target === this._targets[i]) {
							propLookup = this._propLookup[i] || {};
							this._overwrittenProps = this._overwrittenProps || [];
							overwrittenProps = this._overwrittenProps[i] = vars ? this._overwrittenProps[i] || {} : "all";
							break;
						}
					}
				} else if (target !== this.target) {
					return false;
				} else {
					propLookup = this._propLookup;
					overwrittenProps = this._overwrittenProps = vars ? this._overwrittenProps || {} : "all";
				}

				if (propLookup) {
					killProps = vars || propLookup;
					record = (vars !== overwrittenProps && overwrittenProps !== "all" && vars !== propLookup && (typeof(vars) !== "object" || !
vars._tempKill)); //_tempKill is a super-secret way to delete a particular tweening property but NOT have it remembered as an official
 overwritten property (like in BezierPlugin)
					if (overwritingTween && (TweenLite.onOverwrite || this.vars.onOverwrite)) {
						for (p in killProps) {
							if (propLookup[p]) {
								if (!killed) {
									killed = [];
								}
								killed.push(p);
							}
						}
						if ((killed || !vars) && !_onOverwrite(this, overwritingTween, target, killed)) { //if the onOverwrite returned false, that
 means the user wants to override the overwriting (cancel it).
							return false;
						}
					}

					for (p in killProps) {
						if ((pt = propLookup[p])) {
							if (simultaneousOverwrite) { //if another tween overwrites this one and they both start at exactly the same time, yet this
 tween has already rendered once (for example, at 0.001) because it's first in the queue, we should revert the values to where they
 were at 0 so that the starting values aren't contaminated on the overwriting tween.
								if (pt.f) {
									pt.t[pt.p](pt.s);
								} else {
									pt.t[pt.p] = pt.s;
								}
								changed = true;
							}
							if (pt.pg && pt.t._kill(killProps)) {
								changed = true; //some plugins need to be notified so they can perform cleanup tasks first
							}
							if (!pt.pg || pt.t._overwriteProps.length === 0) {
								if (pt._prev) {
									pt._prev._next = pt._next;
								} else if (pt === this._firstPT) {
									this._firstPT = pt._next;
								}
								if (pt._next) {
									pt._next._prev = pt._prev;
								}
								pt._next = pt._prev = null;
							}
							delete propLookup[p];
						}
						if (record) {
							overwrittenProps[p] = 1;
						}
					}
					if (!this._firstPT && this._initted) { //if all tweening properties are killed, kill the tween. Without this line, if there
's a tween with multiple targets and then you killTweensOf() each target individually, the tween would technically still remain
active and fire its onComplete even though there aren't any more properties tweening.
						this._enabled(false, false);
					}
				}
			}
			return changed;
		}
```
- example usage
```shell
...
			if (!vars && !target) {
				return this._enabled(false, false);
			}
			var tweens = (!target) ? this.getChildren(true, true, false) : this.getTweensOf(target),
				i = tweens.length,
				changed = false;
			while (--i > -1) {
				if (tweens[i]._kill(vars, target)) {
					changed = true;
				}
			}
			return changed;
		};

		p.clear = function(labels) {
...
```

#### <a name="apidoc.element.gsap.TweenLite.prototype.constructor"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>constructor (target, duration, vars)](#apidoc.element.gsap.TweenLite.prototype.constructor)
- description and source-code
```javascript
constructor = function (target, duration, vars) {
				Animation.call(this, duration, vars);
				this.render = TweenLite.prototype.render; //speed optimization (avoid prototype lookup on this "hot" method)

				if (target == null) {
					throw "Cannot tween a null target.";
				}

				this.target = target = (typeof(target) !== "string") ? target : TweenLite.selector(target) || target;

				var isSelector = (target.jquery || (target.length && target !== window && target[0] && (target[0] === window || (target[0].nodeType
 && target[0].style && !target.nodeType)))),
					overwrite = this.vars.overwrite,
					i, targ, targets;

				this._overwrite = overwrite = (overwrite == null) ? _overwriteLookup[TweenLite.defaultOverwrite] : (typeof(overwrite) === "number
") ? overwrite >> 0 : _overwriteLookup[overwrite];

				if ((isSelector || target instanceof Array || (target.push && _isArray(target))) && typeof(target[0]) !== "number") {
					this._targets = targets = _slice(target);  //don't use Array.prototype.slice.call(target, 0) because that doesn't work in IE8
 with a NodeList that's returned by querySelectorAll()
					this._propLookup = [];
					this._siblings = [];
					for (i = 0; i < targets.length; i++) {
						targ = targets[i];
						if (!targ) {
							targets.splice(i--, 1);
							continue;
						} else if (typeof(targ) === "string") {
							targ = targets[i--] = TweenLite.selector(targ); //in case it's an array of strings
							if (typeof(targ) === "string") {
								targets.splice(i+1, 1); //to avoid an endless loop (can't imagine why the selector would return a string, but just in case
)
							}
							continue;
						} else if (targ.length && targ !== window && targ[0] && (targ[0] === window || (targ[0].nodeType && targ[0].style && !targ
.nodeType))) { //in case the user is passing in an array of selector objects (like jQuery objects), we need to check one more level
 and pull things out if necessary. Also note that <select> elements pass all the criteria regarding length and the first child having
 style, so we must also check to ensure the target isn't an HTML node itself.
							targets.splice(i--, 1);
							this._targets = targets = targets.concat(_slice(targ));
							continue;
						}
						this._siblings[i] = _register(targ, this, false);
						if (overwrite === 1) if (this._siblings[i].length > 1) {
							_applyOverwrite(targ, this, null, 1, this._siblings[i]);
						}
					}

				} else {
					this._propLookup = {};
					this._siblings = _register(target, this, false);
					if (overwrite === 1) if (this._siblings.length > 1) {
						_applyOverwrite(target, this, null, 1, this._siblings);
					}
				}
				if (this.vars.immediateRender || (duration === 0 && this._delay === 0 && this.vars.immediateRender !== false)) {
					this._time = -_tinyNum; //forces a render without having to set the render() "force" parameter to true because we want to allow
 lazying by default (using the "force" parameter always forces an immediate full render)
					this.render(Math.min(0, -this._delay)); //in case delay is negative
				}
			}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenLite.prototype.invalidate"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>invalidate ()](#apidoc.element.gsap.TweenLite.prototype.invalidate)
- description and source-code
```javascript
invalidate = function () {
			if (this._notifyPluginsOfEnabled) {
				TweenLite._onPluginEvent("_onDisable", this);
			}
			this._firstPT = this._overwrittenProps = this._startAt = this._onUpdate = null;
			this._notifyPluginsOfEnabled = this._active = this._lazy = false;
			this._propLookup = (this._targets) ? {} : [];
			Animation.prototype.invalidate.call(this);
			if (this.vars.immediateRender) {
				this._time = -_tinyNum; //forces a render without having to set the render() "force" parameter to true because we want to allow
 lazying by default (using the "force" parameter always forces an immediate full render)
				this.render(Math.min(0, -this._delay)); //in case delay is negative.
			}
			return this;
		}
```
- example usage
```shell
...
			}
			return this._uncache(true);
		};

		p.invalidate = function() {
			var tween = this._first;
			while (tween) {
				tween.invalidate();
				tween = tween._next;
			}
			return Animation.prototype.invalidate.call(this);;
		};

		p._enabled = function(enabled, ignoreTimeline) {
			if (enabled === this._gc) {
...
```

#### <a name="apidoc.element.gsap.TweenLite.prototype.render"></a>[function <span class="apidocSignatureSpan">gsap.TweenLite.prototype.</span>render (time, suppressEvents, force)](#apidoc.element.gsap.TweenLite.prototype.render)
- description and source-code
```javascript
render = function (time, suppressEvents, force) {
			var prevTime = this._time,
				duration = this._duration,
				prevRawPrevTime = this._rawPrevTime,
				isComplete, callback, pt, rawPrevTime;
			if (time >= duration - 0.0000001 && time >= 0) { //to work around occasional floating point math artifacts.
				this._totalTime = this._time = duration;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(1) : 1;
				if (!this._reversed ) {
					isComplete = true;
					callback = "onComplete";
					force = (force || this._timeline.autoRemoveChildren); //otherwise, if the animation is unpaused/activated after it's already
 finished, it doesn't get removed from the parent timeline.
				}
				if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end values should
 be rendered, but if the timeline's "playhead" moves past it in the backward direction (from a postitive time to a negative time
), the starting values must be rendered.
					if (this._startTime === this._timeline._duration) { //if a zero-duration tween is at the VERY end of a timeline and that timeline
 renders at its end, it will typically add a tiny bit of cushion to the render time to prevent rounding errors from getting in the
 way of tweens rendering their VERY end. If we then reverse() that timeline, the zero-duration tween will trigger its onReverseComplete
 even though technically the playhead didn't pass over it again. It's a very specific edge case we must accommodate.
						time = 0;
					}
					if (prevRawPrevTime < 0 || (time <= 0 && time >= -0.0000001) || (prevRawPrevTime === _tinyNum && this.data !== "isPause"))
if (prevRawPrevTime !== time) { //note: when this.data is "isPause", it's a callback added by addPause() on a timeline that we should
 not be triggered when LEAVING its exact start time. In other words, tl.addPause(1).play(1) shouldn't pause.
						force = true;
						if (prevRawPrevTime > _tinyNum) {
							callback = "onReverseComplete";
						}
					}
					this._rawPrevTime = rawPrevTime = (!suppressEvents || time || prevRawPrevTime === time) ? time : _tinyNum; //when the playhead
 arrives at EXACTLY time 0 (right on top) of a zero-duration tween, we need to discern if events are suppressed so that when the
 playhead moves again (next time), it'll trigger the callback. If events are NOT suppressed, obviously the callback would be triggered
 in this render. Basically, the callback should fire either when the playhead ARRIVES or LEAVES this exact spot, not both. Imagine
 doing a timeline.seek(0) and there's a callback that sits at 0. Since events are suppressed on that seek() by default, nothing
will fire, but when the playhead moves off of that position, the callback should fire. This behavior is what people intuitively
expect. We set the _rawPrevTime to be a precise tiny number to indicate this scenario rather than using another property/variable
 which would increase memory usage. This technique is less readable, but more efficient.
				}

			} else if (time < 0.0000001) { //to work around occasional floating point math artifacts, round super small values to 0.
				this._totalTime = this._time = 0;
				this.ratio = this._ease._calcEnd ? this._ease.getRatio(0) : 0;
				if (prevTime !== 0 || (duration === 0 && prevRawPrevTime > 0)) {
					callback = "onReverseComplete";
					isComplete = this._reversed;
				}
				if (time < 0) {
					this._active = false;
					if (duration === 0) if (this._initted || !this.vars.lazy || force) { //zero-duration tweens are tricky because we must discern
 the momentum/direction of time in order to determine whether the starting values should be rendered or the ending values. If the
 "playhead" of its timeline goes past the zero-duration tween in the forward direction or lands directly on it, the end v ...
```
- example usage
```shell
...
					if (curTime !== this._time || (this._paused && !prevPaused)) { //in case a tween pauses or seeks the timeline when rendering
, like inside of an onUpdate/onComplete
						break;
					} else if (tween._active || (tween._startTime <= curTime && !tween._paused && !tween._gc)) {
						if (pauseTween === tween) {
							this.pause();
						}
						if (!tween._reversed) {
							tween.render((time - tween._startTime) * tween._timeScale, suppressEvents, force);
						} else {
							tween.render(((!tween._dirty) ? tween._totalDuration : tween.totalDuration()) - ((time - tween._startTime) * tween._timeScale
), suppressEvents, force);
						}
					}
					tween = next;
				}
			} else {
...
```



# <a name="apidoc.module.gsap.TweenPlugin"></a>[module gsap.TweenPlugin](#apidoc.module.gsap.TweenPlugin)

#### <a name="apidoc.element.gsap.TweenPlugin.TweenPlugin"></a>[function <span class="apidocSignatureSpan">gsap.</span>TweenPlugin (props, priority)](#apidoc.element.gsap.TweenPlugin.TweenPlugin)
- description and source-code
```javascript
TweenPlugin = function (props, priority) {
					this._overwriteProps = (props || "").split(",");
					this._propName = this._overwriteProps[0];
					this._priority = priority || 0;
					this._super = TweenPlugin.prototype;
				}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenPlugin.activate"></a>[function <span class="apidocSignatureSpan">gsap.TweenPlugin.</span>activate (plugins)](#apidoc.element.gsap.TweenPlugin.activate)
- description and source-code
```javascript
activate = function (plugins) {
			var i = plugins.length;
			while (--i > -1) {
				if (plugins[i].API === TweenPlugin.API) {
					_plugins[(new plugins[i]())._propName] = plugins[i];
				}
			}
			return true;
		}
```
- example usage
```shell
...
			Plugin.API = config.API;
			for (prop in map) {
				if (typeof(config[prop]) === "function") {
					p[map[prop]] = config[prop];
				}
			}
			Plugin.version = config.version;
			TweenPlugin.activate([Plugin]);
			return Plugin;
		};


		//now run through all the dependencies discovered and if any are missing, log that to the console as a warning. This is why it
's best to have TweenLite load last - it can check all the dependencies for you.
		a = window._gsQueue;
		if (a) {
...
```



# <a name="apidoc.module.gsap.TweenPlugin.prototype"></a>[module gsap.TweenPlugin.prototype](#apidoc.module.gsap.TweenPlugin.prototype)

#### <a name="apidoc.element.gsap.TweenPlugin.prototype._addTween"></a>[function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_addTween (target, prop, start, end, overwriteProp, mod, funcParam, stringFilter, index)](#apidoc.element.gsap.TweenPlugin.prototype._addTween)
- description and source-code
```javascript
_addTween = function (target, prop, start, end, overwriteProp, mod, funcParam, stringFilter, index) {
				if (typeof(end) === "function") {
					end = end(index || 0, target);
				}
				var type = typeof(target[prop]),
					getterName = (type !== "function") ? "" : ((prop.indexOf("set") || typeof(target["get" + prop.substr(3)]) !== "function") ?
prop : "get" + prop.substr(3)),
					s = (start !== "get") ? start : !getterName ? target[prop] : funcParam ? target[getterName](funcParam) : target[getterName](),
					isRelative = (typeof(end) === "string" && end.charAt(1) === "="),
					pt = {t:target, p:prop, s:s, f:(type === "function"), pg:0, n:overwriteProp || prop, m:(!mod ? 0 : (typeof(mod) === "function
") ? mod : Math.round), pr:0, c:isRelative ? parseInt(end.charAt(0) + "1", 10) * parseFloat(end.substr(2)) : (parseFloat(end) -
s) || 0},
					blob;

				if (typeof(s) !== "number" || (typeof(end) !== "number" && !isRelative)) {
					if (funcParam || isNaN(s) || (!isRelative && isNaN(end)) || typeof(s) === "boolean" || typeof(end) === "boolean") {
						//a blob (string that has multiple numbers in it)
						pt.fp = funcParam;
						blob = _blobDif(s, (isRelative ? pt.s + pt.c : end), stringFilter || TweenLite.defaultStringFilter, pt);
						pt = {t: blob, p: "setRatio", s: 0, c: 1, f: 2, pg: 0, n: overwriteProp || prop, pr: 0, m: 0}; //"2" indicates it's a Blob
 property tween. Needed for RoundPropsPlugin for example.
					} else {
						pt.s = parseFloat(s);
						if (!isRelative) {
							pt.c = (parseFloat(end) - pt.s) || 0;
						}
					}
				}
				if (pt.c) { //only add it to the linked list if there's a change.
					if ((pt._next = this._firstPT)) {
						pt._next._prev = pt;
					}
					this._firstPT = pt;
					return pt;
				}
			}
```
- example usage
```shell
...
					pt = next;
				}
			}
			return false;
		};

		p._add = function(target, p, s, c) {
			this._addTween(target, p, s, s + c, p, Math.round);
			this._overwriteProps.push(p);
		};

}); if (_gsScope._gsDefine) { _gsScope._gsQueue.pop()(); }
...
```

#### <a name="apidoc.element.gsap.TweenPlugin.prototype._kill"></a>[function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_kill (lookup)](#apidoc.element.gsap.TweenPlugin.prototype._kill)
- description and source-code
```javascript
_kill = function (lookup) {
			var a = this._overwriteProps,
				pt = this._firstPT,
				i;
			if (lookup[this._propName] != null) {
				this._overwriteProps = [];
			} else {
				i = a.length;
				while (--i > -1) {
					if (lookup[a[i]] != null) {
						a.splice(i, 1);
					}
				}
			}
			while (pt) {
				if (lookup[pt.n] != null) {
					if (pt._next) {
						pt._next._prev = pt._prev;
					}
					if (pt._prev) {
						pt._prev._next = pt._next;
						pt._prev = null;
					} else if (this._firstPT === pt) {
						this._firstPT = pt._next;
					}
				}
				pt = pt._next;
			}
			return false;
		}
```
- example usage
```shell
...
			if (!vars && !target) {
				return this._enabled(false, false);
			}
			var tweens = (!target) ? this.getChildren(true, true, false) : this.getTweensOf(target),
				i = tweens.length,
				changed = false;
			while (--i > -1) {
				if (tweens[i]._kill(vars, target)) {
					changed = true;
				}
			}
			return changed;
		};

		p.clear = function(labels) {
...
```

#### <a name="apidoc.element.gsap.TweenPlugin.prototype._mod"></a>[function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_mod (lookup)](#apidoc.element.gsap.TweenPlugin.prototype._mod)
- description and source-code
```javascript
_mod = function (lookup) {
			var pt = this._firstPT,
				val;
			while (pt) {
				val = lookup[this._propName] || (pt.n != null && lookup[ pt.n.split(this._propName + "_").join("") ]);
				if (val && typeof(val) === "function") { //some properties that are very plugin-specific add a prefix named after the _propName
 plus an underscore, so we need to ignore that extra stuff here.
					if (pt.f === 2) {
						pt.t._applyPT.m = val;
					} else {
						pt.m = val;
					}
				}
				pt = pt._next;
			}
		}
```
- example usage
```shell
...
			i = rp.length;
			while (--i > -1) {
				prop = rp[i];
				pt = tween._firstPT;
				while (pt) {
					next = pt._next; //record here, because it may get removed
					if (pt.pg) {
						pt.t._mod(lookup);
					} else if (pt.n === prop) {
						if (pt.f === 2 && pt.t) { //a blob (text containing multiple numeric values)
							_roundLinkedList(pt.t._firstPT);
						} else {
							this._add(pt.t, prop, pt.s, pt.c);
							//remove from linked list
							if (next) {
...
```

#### <a name="apidoc.element.gsap.TweenPlugin.prototype._roundProps"></a>[function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>_roundProps (lookup)](#apidoc.element.gsap.TweenPlugin.prototype._roundProps)
- description and source-code
```javascript
_roundProps = function (lookup) {
			var pt = this._firstPT,
				val;
			while (pt) {
				val = lookup[this._propName] || (pt.n != null && lookup[ pt.n.split(this._propName + "_").join("") ]);
				if (val && typeof(val) === "function") { //some properties that are very plugin-specific add a prefix named after the _propName
 plus an underscore, so we need to ignore that extra stuff here.
					if (pt.f === 2) {
						pt.t._applyPT.m = val;
					} else {
						pt.m = val;
					}
				}
				pt = pt._next;
			}
		}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gsap.TweenPlugin.prototype.setRatio"></a>[function <span class="apidocSignatureSpan">gsap.TweenPlugin.prototype.</span>setRatio (v)](#apidoc.element.gsap.TweenPlugin.prototype.setRatio)
- description and source-code
```javascript
setRatio = function (v) {
				var pt = this._firstPT,
					min = 0.000001,
					val;
				while (pt) {
					val = !pt.blob ? pt.c * v + pt.s : (v === 1) ? this.end : v ? this.join("") : this.start;
					if (pt.m) {
						val = pt.m(val, this._target || pt.t);
					} else if (val < min) if (val > -min && !pt.blob) { //prevents issues with converting very small numbers to strings in the
browser
						val = 0;
					}
					if (!pt.f) {
						pt.t[pt.p] = val;
					} else if (pt.fp) {
						pt.t[pt.p](pt.fp, val);
					} else {
						pt.t[pt.p](val);
					}
					pt = pt._next;
				}
			}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gsap.ticker"></a>[module gsap.ticker](#apidoc.module.gsap.ticker)

#### <a name="apidoc.element.gsap.ticker.fps"></a>[function <span class="apidocSignatureSpan">gsap.ticker.</span>fps (value)](#apidoc.element.gsap.ticker.fps)
- description and source-code
```javascript
fps = function (value) {
				if (!arguments.length) {
					return _fps;
				}
				_fps = value;
				_gap = 1 / (_fps || 60);
				_nextTime = this.time + _gap;
				_self.wake();
			}
```
- example usage
```shell
...

			_self.useRAF = function(value) {
				if (!arguments.length) {
					return _useRAF;
				}
				_self.sleep();
				_useRAF = value;
				_self.fps(_fps);
			};
			_self.fps(fps);

			//a bug in iOS 6 Safari occasionally prevents the requestAnimationFrame from working initially, so we use a 1.5-second timeout
 that automatically falls back to setTimeout() if it senses this condition.
			setTimeout(function() {
				if (_useRAF === "auto" && _self.frame < 5 && _doc.visibilityState !== "hidden") {
					_self.useRAF(false);
...
```

#### <a name="apidoc.element.gsap.ticker.lagSmoothing"></a>[function <span class="apidocSignatureSpan">gsap.ticker.</span>lagSmoothing (threshold, adjustedLag)](#apidoc.element.gsap.ticker.lagSmoothing)
- description and source-code
```javascript
lagSmoothing = function (threshold, adjustedLag) {
				_lagThreshold = threshold || (1 / _tinyNum); //zero should be interpreted as basically unlimited
				_adjustedLag = Math.min(adjustedLag, _lagThreshold, 0);
			}
```
- example usage
```shell
...

		TweenLite.version = "1.19.1";
		TweenLite.defaultEase = p._ease = new Ease(null, null, 1, 1);
		TweenLite.defaultOverwrite = "auto";
		TweenLite.ticker = _ticker;
		TweenLite.autoSleep = 120;
		TweenLite.lagSmoothing = function(threshold, adjustedLag) {
			_ticker.lagSmoothing(threshold, adjustedLag);
		};

		TweenLite.selector = window.$ || window.jQuery || function(e) {
			var selector = window.$ || window.jQuery;
			if (selector) {
				TweenLite.selector = selector;
				return selector(e);
...
```

#### <a name="apidoc.element.gsap.ticker.sleep"></a>[function <span class="apidocSignatureSpan">gsap.ticker.</span>sleep ()](#apidoc.element.gsap.ticker.sleep)
- description and source-code
```javascript
sleep = function () {
				if (_id == null) {
					return;
				}
				if (!_useRAF || !_cancelAnimFrame) {
					clearTimeout(_id);
				} else {
					_cancelAnimFrame(_id);
				}
				_req = _emptyFunc;
				_id = null;
				if (_self === _ticker) {
					_tickerActive = false;
				}
			}
```
- example usage
```shell
...
				if (_self === _ticker) {
					_tickerActive = false;
				}
			};

			_self.wake = function(seamless) {
				if (_id !== null) {
					_self.sleep();
				} else if (seamless) {
					_startTime += -_lastUpdate + (_lastUpdate = _getTime());
				} else if (_self.frame > 10) { //don't trigger lagSmoothing if we're just waking up, and make sure that at least 10 frames have
 elapsed because of the iOS bug that we work around below with the 1.5-second setTimout().
					_lastUpdate = _getTime() - _lagThreshold + 5;
				}
				_req = (_fps === 0) ? _emptyFunc : (!_useRAF || !_reqAnimFrame) ? function(f) { return setTimeout(f, ((_nextTime - _self.time
) * 1000 + 1) | 0); } : _reqAnimFrame;
				if (_self === _ticker) {
...
```

#### <a name="apidoc.element.gsap.ticker.tick"></a>[function <span class="apidocSignatureSpan">gsap.ticker.</span>tick ()](#apidoc.element.gsap.ticker.tick)
- description and source-code
```javascript
tick = function () {
				_tick(true);
			}
```
- example usage
```shell
...
			for (p in _defLookup) {
				if (!_defLookup[p].func) {
					window.console.log("GSAP encountered missing dependency: " + p);
				}
			}
		}

		_tickerActive = false; //ensures that the first official animation forces a ticker.tick() to update the time when it is instantiated

})((typeof(module) !== "undefined" && module.exports && typeof(global) !== "undefined") ? global : this || window, "TweenLite");
...
```

#### <a name="apidoc.element.gsap.ticker.useRAF"></a>[function <span class="apidocSignatureSpan">gsap.ticker.</span>useRAF (value)](#apidoc.element.gsap.ticker.useRAF)
- description and source-code
```javascript
useRAF = function (value) {
				if (!arguments.length) {
					return _useRAF;
				}
				_self.sleep();
				_useRAF = value;
				_self.fps(_fps);
			}
```
- example usage
```shell
...
				_self.fps(_fps);
			};
			_self.fps(fps);

			//a bug in iOS 6 Safari occasionally prevents the requestAnimationFrame from working initially, so we use a 1.5-second timeout
 that automatically falls back to setTimeout() if it senses this condition.
			setTimeout(function() {
				if (_useRAF === "auto" && _self.frame < 5 && _doc.visibilityState !== "hidden") {
					_self.useRAF(false);
				}
			}, 1500);
		});

		p = gs.Ticker.prototype = new gs.events.EventDispatcher();
		p.constructor = gs.Ticker;
...
```

#### <a name="apidoc.element.gsap.ticker.wake"></a>[function <span class="apidocSignatureSpan">gsap.ticker.</span>wake (seamless)](#apidoc.element.gsap.ticker.wake)
- description and source-code
```javascript
wake = function (seamless) {
				if (_id !== null) {
					_self.sleep();
				} else if (seamless) {
					_startTime += -_lastUpdate + (_lastUpdate = _getTime());
				} else if (_self.frame > 10) { //don't trigger lagSmoothing if we're just waking up, and make sure that at least 10 frames have
 elapsed because of the iOS bug that we work around below with the 1.5-second setTimout().
					_lastUpdate = _getTime() - _lagThreshold + 5;
				}
				_req = (_fps === 0) ? _emptyFunc : (!_useRAF || !_reqAnimFrame) ? function(f) { return setTimeout(f, ((_nextTime - _self.time
) * 1000 + 1) | 0); } : _reqAnimFrame;
				if (_self === _ticker) {
					_tickerActive = true;
				}
				_tick(2);
			}
```
- example usage
```shell
...

		p.addEventListener = function(type, callback, scope, useParam, priority) {
			priority = priority || 0;
			var list = this._listeners[type],
				index = 0,
				listener, i;
			if (this === _ticker && !_tickerActive) {
				_ticker.wake();
			}
			if (list == null) {
				this._listeners[type] = list = [];
			}
			i = list.length;
			while (--i > -1) {
				listener = list[i];
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
