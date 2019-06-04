[menubar](../README.md) > ["types"](../modules/_types_.md) > [Options](../interfaces/_types_.options.md)

# Interface: Options

## Hierarchy

**Options**

## Index

### Properties

* [alwaysOnTop](_types_.options.md#alwaysontop)
* [browserWindow](_types_.options.md#browserwindow)
* [dir](_types_.options.md#dir)
* [height](_types_.options.md#height)
* [icon](_types_.options.md#icon)
* [index](_types_.options.md#index)
* [preloadWindow](_types_.options.md#preloadwindow)
* [showDockIcon](_types_.options.md#showdockicon)
* [showOnAllWorkspaces](_types_.options.md#showonallworkspaces)
* [showOnRightClick](_types_.options.md#showonrightclick)
* [tooltip](_types_.options.md#tooltip)
* [tray](_types_.options.md#tray)
* [width](_types_.options.md#width)
* [windowPosition](_types_.options.md#windowposition)
* [x](_types_.options.md#x)
* [y](_types_.options.md#y)

---

## Properties

<a id="alwaysontop"></a>

### `<Optional>` alwaysOnTop

**● alwaysOnTop**: *`undefined` \| `false` \| `true`*

*Defined in [types.ts:8](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L8)*

If true, the window will not hide on blur.

*__deprecated__*: Please pass this option inside `options.browserWindow`.

___
<a id="browserwindow"></a>

###  browserWindow

**● browserWindow**: *`BrowserWindowConstructorOptions`*

*Defined in [types.ts:27](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L27)*

An Electron BrowserWindow instance, or an options object to be passed into the BrowserWindow constructor.

*__example__*:
 ```typescript
const options = { height: 640, width: 480 };
const mb = new Menubar({
  browserWindow: new BrowserWindow(options)
});

// The above is equivalent to

const options = { height: 640, width: 480 };
const mb = new Menubar({
  browserWindow: options
});
```

___
<a id="dir"></a>

###  dir

**● dir**: *`string`*

*Defined in [types.ts:31](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L31)*

The app source directory.

___
<a id="height"></a>

### `<Optional>` height

**● height**: *`undefined` \| `number`*

*Defined in [types.ts:36](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L36)*

Window height.

*__deprecated__*: Please pass this option inside `options.browserWindow`.

___
<a id="icon"></a>

###  icon

**● icon**: *`string` \| `NativeImage`*

*Defined in [types.ts:43](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L43)*

The png icon to use for the menubar. A good size to start with is 20x20. To support retina, supply a 2x sized image (e.g. 40x40) with @2x added to the end of the name, so icon.png and [icon@2x.png](mailto:icon@2x.png) and Electron will automatically use your @2x version on retina screens.

___
<a id="index"></a>

###  index

**● index**: *`string`*

*Defined in [types.ts:47](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L47)*

The html to load for the pop up window.

___
<a id="preloadwindow"></a>

###  preloadWindow

**● preloadWindow**: *`boolean`*

*Defined in [types.ts:52](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L52)*

Create BrowserWindow instance before it is used -- increasing resource usage, but making the click on the menubar load faster.

___
<a id="showdockicon"></a>

###  showDockIcon

**● showDockIcon**: *`boolean`*

*Defined in [types.ts:57](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L57)*

Configure the visibility of the application dock icon, macOS only. Calls [`app.dock.hide`](https://electronjs.org/docs/api/app#appdockhide-macos)

___
<a id="showonallworkspaces"></a>

###  showOnAllWorkspaces

**● showOnAllWorkspaces**: *`boolean`*

*Defined in [types.ts:62](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L62)*

Makes the window available on all OS X workspaces. Calls [`setVisibleOnAllWorkspaces`](https://electronjs.org/docs/api/browser-window#winsetvisibleonallworkspacesvisible-options)

___
<a id="showonrightclick"></a>

###  showOnRightClick

**● showOnRightClick**: *`boolean`*

*Defined in [types.ts:66](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L66)*

Show the window on 'right-click' event instead of regular 'click'.

___
<a id="tooltip"></a>

###  tooltip

**● tooltip**: *`string`*

*Defined in [types.ts:70](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L70)*

Menubar tray icon tooltip text. Calls [`tray.setTooltip`](https://electronjs.org/docs/api/tray#traysettooltiptooltip)

___
<a id="tray"></a>

###  tray

**● tray**: *`Tray`*

*Defined in [types.ts:74](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L74)*

An electron Tray instance. If provided, `options.icon` will be ignored.

___
<a id="width"></a>

### `<Optional>` width

**● width**: *`undefined` \| `number`*

*Defined in [types.ts:99](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L99)*

Window width.

*__deprecated__*: Please pass this option inside `options.browserWindow`.

___
<a id="windowposition"></a>

###  windowPosition

**● windowPosition**: *"trayLeft" \| "trayBottomLeft" \| "trayRight" \| "trayBottomRight" \| "trayCenter" \| "trayBottomCenter" \| "topLeft" \| "topRight" \| "bottomLeft" \| "bottomRight" \| "topCenter" \| "bottomCenter" \| "leftCenter" \| "rightCenter" \| "center"*

*Defined in [types.ts:79](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L79)*

Sets the window position (x and y will still override this), check electron-positioner docs for valid values.

___
<a id="x"></a>

### `<Optional>` x

**● x**: *`undefined` \| `number`*

*Defined in [types.ts:104](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L104)*

The x position of the window.

*__deprecated__*: Please pass this option inside `options.browserWindow`.

___
<a id="y"></a>

### `<Optional>` y

**● y**: *`undefined` \| `number`*

*Defined in [types.ts:109](https://github.com/maxogden/menubar/blob/270eb39/src/types.ts#L109)*

The x position of the window.

*__deprecated__*: Please pass this option inside `options.browserWindow`.

___

