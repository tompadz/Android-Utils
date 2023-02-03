# Android-Utils
my standard utils file which i use in projects

### Table of Contents

1. [Functions](https://github.com/tompadz/Android-Utils#functions)
2. [Numbers extension](https://github.com/tompadz/Android-Utils#numbers-extension)
3. [Dp convert](https://github.com/tompadz/Android-Utils#dp-convert)
4. [Px convert](https://github.com/tompadz/Android-Utils#px-convert)
5. [View extension](https://github.com/tompadz/Android-Utils#view-extension)
    - [View animation](https://github.com/tompadz/Android-Utils#view-animation)
6. [Context extension](https://github.com/tompadz/Android-Utils#context-extension)
7. [Resource extension](https://github.com/tompadz/Android-Utils#resource-extension)
8. [ImageView extension](https://github.com/tompadz/Android-Utils#ImageView-extension)

## Functions

 - [checkDisplaySize()](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L40) - initializes density from the applicationContext, should be called in the Application() class
 - [showKeyboard(view : View?)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L44) - opens the keyboard
 - [hideKeyboard(view : View?)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L57) - hides the keyboard
 - [lerp(a : Int, b : Int, f : Float)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L72) : Int - calculate linear interpolation
 - [lerpAngle(a : Float, b : Float, f : Float)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L76) : Float - calculate linear angle interpolation
 - [updateVisibleRows(listView : RecyclerView?)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L93) - updates only visible list items

## Numbers extension

 - [Float.normalize(min : Float, max : Float, minNormalize : Float, maxNormalize : Float)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L110) - normalizes the value to the min max of the value

## Dp convert

converting numbers to DP
 - [Float.dp() : Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L126)
 - [Float.dpf() : Float](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L127) 
 - [Int.dp() : Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L128)
 - [Int.dpf() : Float](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L129)

## Px convert

converting numbers to PX
- [Float.px() : Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L133)
- [Float.pxf() : Float](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L134)
- [Int.px() : Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L135)
- [Int.pxf() : Float](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L135)

## View extension

 - [View.expand(withAnimation: Boolean = true)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L140) - expand view
 - [View.collapse(withAnimation: Boolean = true)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L170) - collapse view
 - [View.setCornerRadiusOfView(radius:Float = 30f)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L196) - sets the rounding of the edges of any view

### View animation

update show view

 - [View.updateViewShow( show : Boolean)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L215)
 - [View.updateViewShow(show : Boolean, scale : Boolean, animated : Boolean)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L219)
 - [View.updateViewShow(show : Boolean, scale : Boolean, animated : Boolean, onDone : Runnable?,)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L223)
 - [View.updateViewShow(show : Boolean, scale : Boolean, translate : Float, animated : Boolean, onDone : Runnable?)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L232)

update view visible

 - [View.updateViewVisibilityAnimated(show : Boolean)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L285)
 - [View.updateViewVisibilityAnimated(show : Boolean, scaleFactor : Float, animated : Boolean)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L289)

## Context extension

 - [Context.getTypeColor(colorResId : Int) : Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L326) - allows to get color from android.R
 - [Context.getStatusBarHeight() : Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L335) - returns the height of the status bar in px
 - [Context.getNavigationBarHeight() : Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L341) - returns the height of the navigation bar in px
 - [Context.getColorFromAttr(@AttrRes attrColor : Int, typedValue : TypedValue = TypedValue(), resolveRefs : Boolean = true,)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L347) - lets get color from attr
 - [Context.copyToClipboard(text: CharSequence)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L356) - copy text to clipboard
 - [Context.shareLink(link: String)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L362) - opens a window where you can share the link
 - [Context.openLink(link: String)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L370) - opens link in browser

## Resource extension

 - [Resources.getDeviceWidth(): Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L377) - returns the phone screen width in px
 - [Resources.getDeviceHeight(): Int](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L378) - returns phone screen height in px

## ImageView extension

 - [ImageView.setTint(colors: ColorStateList)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L382) - sets the tint for the imageView
 - [ImageView.updateImageViewImageAnimated(@DrawableRes newIcon : Int)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L386) - changes image with animation (for icons)
 - [fun ImageView.updateImageViewImageAnimated(newIcon: Drawable)](https://github.com/tompadz/Android-Utils/blob/fea1f08806855ab5c16c258e81555a2e706429e0/Utils.kt#L391) - changes image with animation (for icons)
