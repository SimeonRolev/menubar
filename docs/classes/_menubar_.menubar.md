[menubar](../README.md) > ["Menubar"](../modules/_menubar_.md) > [Menubar](../classes/_menubar_.menubar.md)

# Class: Menubar

The main Menubar class. Menubar is an EventEmitter.

## Hierarchy

 `EventEmitter`

**↳ Menubar**

## Index

### Constructors

* [constructor](_menubar_.menubar.md#constructor)

### Properties

* [app](_menubar_.menubar.md#app)
* [browserWindow](_menubar_.menubar.md#browserwindow)
* [positioner](_menubar_.menubar.md#positioner)
* [tray](_menubar_.menubar.md#tray)
* [defaultMaxListeners](_menubar_.menubar.md#defaultmaxlisteners)

### Methods

* [addListener](_menubar_.menubar.md#addlistener)
* [emit](_menubar_.menubar.md#emit)
* [eventNames](_menubar_.menubar.md#eventnames)
* [getMaxListeners](_menubar_.menubar.md#getmaxlisteners)
* [getOption](_menubar_.menubar.md#getoption)
* [hideWindow](_menubar_.menubar.md#hidewindow)
* [listenerCount](_menubar_.menubar.md#listenercount)
* [listeners](_menubar_.menubar.md#listeners)
* [off](_menubar_.menubar.md#off)
* [on](_menubar_.menubar.md#on)
* [once](_menubar_.menubar.md#once)
* [prependListener](_menubar_.menubar.md#prependlistener)
* [prependOnceListener](_menubar_.menubar.md#prependoncelistener)
* [rawListeners](_menubar_.menubar.md#rawlisteners)
* [removeAllListeners](_menubar_.menubar.md#removealllisteners)
* [removeListener](_menubar_.menubar.md#removelistener)
* [setMaxListeners](_menubar_.menubar.md#setmaxlisteners)
* [setOption](_menubar_.menubar.md#setoption)
* [listenerCount](_menubar_.menubar.md#listenercount-1)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new Menubar**(app: *`App`*, options?: *`Partial`<[Options](../interfaces/_types_.options.md)> \| `string`*): [Menubar](_menubar_.menubar.md)

*Defined in Menubar.ts:36*

**Parameters:**

| Name | Type |
| ------ | ------ |
| app | `App` |
| `Optional` options | `Partial`<[Options](../interfaces/_types_.options.md)> \| `string` |

**Returns:** [Menubar](_menubar_.menubar.md)

___

## Properties

<a id="app"></a>

###  app

**● app**: *`App`*

*Defined in Menubar.ts:18*

The Electron app instance.

*__see__*: [https://electronjs.org/docs/api/app](https://electronjs.org/docs/api/app)

___
<a id="browserwindow"></a>

### `<Optional>` browserWindow

**● browserWindow**: *`BrowserWindow`*

*Defined in Menubar.ts:23*

The electron BrowserWindow instance.

*__see__*: [https://electronjs.org/docs/api/browser-window](https://electronjs.org/docs/api/browser-window)

___
<a id="positioner"></a>

###  positioner

**● positioner**: *`any`*

*Defined in Menubar.ts:30*

The electron-positioner instance.

*__see__*: [https://github.com/jenslind/electron-positioner](https://github.com/jenslind/electron-positioner)

___
<a id="tray"></a>

### `<Optional>` tray

**● tray**: *`Tray`*

*Defined in Menubar.ts:36*

The Electron Tray instance.

*__see__*: [https://electronjs.org/docs/api/tray](https://electronjs.org/docs/api/tray)

___
<a id="defaultmaxlisteners"></a>

### `<Static>` defaultMaxListeners

**● defaultMaxListeners**: *`number`*

*Inherited from EventEmitter.defaultMaxListeners*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:9*

___

## Methods

<a id="addlistener"></a>

###  addListener

▸ **addListener**(event: *`string` \| `symbol`*, listener: *`function`*): `this`

*Inherited from EventEmitter.addListener*

*Overrides EventEmitter.addListener*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:11*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| listener | `function` |

**Returns:** `this`

___
<a id="emit"></a>

###  emit

▸ **emit**(event: *`string` \| `symbol`*, ...args: *`any`[]*): `boolean`

*Inherited from EventEmitter.emit*

*Overrides EventEmitter.emit*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:23*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| `Rest` args | `any`[] |

**Returns:** `boolean`

___
<a id="eventnames"></a>

###  eventNames

▸ **eventNames**(): `Array`<`string` \| `symbol`>

*Inherited from EventEmitter.eventNames*

*Overrides EventEmitter.eventNames*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:24*

**Returns:** `Array`<`string` \| `symbol`>

___
<a id="getmaxlisteners"></a>

###  getMaxListeners

▸ **getMaxListeners**(): `number`

*Inherited from EventEmitter.getMaxListeners*

*Overrides EventEmitter.getMaxListeners*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:20*

**Returns:** `number`

___
<a id="getoption"></a>

###  getOption

▸ **getOption**(key: *`keyof Options`*): `undefined` \| `string` \| `number` \| `false` \| `true` \| `BrowserWindowConstructorOptions` \| `NativeImage` \| `Tray`

*Defined in Menubar.ts:60*

Retrieve a menubar option.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| key | `keyof Options` |  The option key to retrieve. |

**Returns:** `undefined` \| `string` \| `number` \| `false` \| `true` \| `BrowserWindowConstructorOptions` \| `NativeImage` \| `Tray`

___
<a id="hidewindow"></a>

###  hideWindow

▸ **hideWindow**(): `void`

*Defined in Menubar.ts:67*

Hide the menubar window.

**Returns:** `void`

___
<a id="listenercount"></a>

###  listenerCount

▸ **listenerCount**(type: *`string` \| `symbol`*): `number`

*Inherited from EventEmitter.listenerCount*

*Overrides EventEmitter.listenerCount*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:25*

**Parameters:**

| Name | Type |
| ------ | ------ |
| type | `string` \| `symbol` |

**Returns:** `number`

___
<a id="listeners"></a>

###  listeners

▸ **listeners**(event: *`string` \| `symbol`*): `Function`[]

*Inherited from EventEmitter.listeners*

*Overrides EventEmitter.listeners*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:21*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |

**Returns:** `Function`[]

___
<a id="off"></a>

###  off

▸ **off**(event: *`string` \| `symbol`*, listener: *`function`*): `this`

*Inherited from EventEmitter.off*

*Overrides EventEmitter.off*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:17*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| listener | `function` |

**Returns:** `this`

___
<a id="on"></a>

###  on

▸ **on**(event: *`string` \| `symbol`*, listener: *`function`*): `this`

*Inherited from EventEmitter.on*

*Overrides EventEmitter.on*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:12*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| listener | `function` |

**Returns:** `this`

___
<a id="once"></a>

###  once

▸ **once**(event: *`string` \| `symbol`*, listener: *`function`*): `this`

*Inherited from EventEmitter.once*

*Overrides EventEmitter.once*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:13*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| listener | `function` |

**Returns:** `this`

___
<a id="prependlistener"></a>

###  prependListener

▸ **prependListener**(event: *`string` \| `symbol`*, listener: *`function`*): `this`

*Inherited from EventEmitter.prependListener*

*Overrides EventEmitter.prependListener*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:14*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| listener | `function` |

**Returns:** `this`

___
<a id="prependoncelistener"></a>

###  prependOnceListener

▸ **prependOnceListener**(event: *`string` \| `symbol`*, listener: *`function`*): `this`

*Inherited from EventEmitter.prependOnceListener*

*Overrides EventEmitter.prependOnceListener*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:15*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| listener | `function` |

**Returns:** `this`

___
<a id="rawlisteners"></a>

###  rawListeners

▸ **rawListeners**(event: *`string` \| `symbol`*): `Function`[]

*Inherited from EventEmitter.rawListeners*

*Overrides EventEmitter.rawListeners*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:22*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |

**Returns:** `Function`[]

___
<a id="removealllisteners"></a>

###  removeAllListeners

▸ **removeAllListeners**(event?: *`string` \| `symbol`*): `this`

*Inherited from EventEmitter.removeAllListeners*

*Overrides EventEmitter.removeAllListeners*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:18*

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` event | `string` \| `symbol` |

**Returns:** `this`

___
<a id="removelistener"></a>

###  removeListener

▸ **removeListener**(event: *`string` \| `symbol`*, listener: *`function`*): `this`

*Inherited from EventEmitter.removeListener*

*Overrides EventEmitter.removeListener*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:16*

**Parameters:**

| Name | Type |
| ------ | ------ |
| event | `string` \| `symbol` |
| listener | `function` |

**Returns:** `this`

___
<a id="setmaxlisteners"></a>

###  setMaxListeners

▸ **setMaxListeners**(n: *`number`*): `this`

*Inherited from EventEmitter.setMaxListeners*

*Overrides EventEmitter.setMaxListeners*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:19*

**Parameters:**

| Name | Type |
| ------ | ------ |
| n | `number` |

**Returns:** `this`

___
<a id="setoption"></a>

###  setOption

▸ **setOption**(key: *`keyof Options`*, value: *`any`*): `void`

*Defined in Menubar.ts:86*

Change an option after menubar is created.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| key | `keyof Options` |  The option key to modify. |
| value | `any` |  The value to set. |

**Returns:** `void`

___
<a id="listenercount-1"></a>

### `<Static>` listenerCount

▸ **listenerCount**(emitter: *`EventEmitter`*, event: *`string` \| `symbol`*): `number`

*Inherited from EventEmitter.listenerCount*

*Defined in /Users/amaurymartiny/Workspaces/menubar/node_modules/@types/node/events.d.ts:8*

*__deprecated__*: since v4.0.0

**Parameters:**

| Name | Type |
| ------ | ------ |
| emitter | `EventEmitter` |
| event | `string` \| `symbol` |

**Returns:** `number`

___

