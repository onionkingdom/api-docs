[auto-mwapi-lib](../README.md) / [Exports](../modules.md) / [Gameplay](../modules/Gameplay.md) / [Gameplay](../modules/Gameplay.Gameplay.md) / PhysicsImpulse

# Class: PhysicsImpulse

[Gameplay](../modules/Gameplay.md).[Gameplay](../modules/Gameplay.Gameplay.md).PhysicsImpulse

**`Description`**

冲量对象

**`Network Status`**

usage: 双端

**`Author`**

jun.zhang

## Hierarchy

- [`GameObject`](Core.Core.GameObject.md)

  ↳ **`PhysicsImpulse`**

## Table of contents

### Constructors

- [constructor](Gameplay.Gameplay.PhysicsImpulse.md#constructor)

### Properties

- [onImpulseEnter](Gameplay.Gameplay.PhysicsImpulse.md#onimpulseenter)

### Accessors

- [enable](Gameplay.Gameplay.PhysicsImpulse.md#enable)
- [forwardVector](Gameplay.Gameplay.PhysicsImpulse.md#forwardvector)
- [guid](Gameplay.Gameplay.PhysicsImpulse.md#guid)
- [impulseForceType](Gameplay.Gameplay.PhysicsImpulse.md#impulseforcetype)
- [impulseRadialForce](Gameplay.Gameplay.PhysicsImpulse.md#impulseradialforce)
- [impulseType](Gameplay.Gameplay.PhysicsImpulse.md#impulsetype)
- [impulseVector](Gameplay.Gameplay.PhysicsImpulse.md#impulsevector)
- [isVisible](Gameplay.Gameplay.PhysicsImpulse.md#isvisible)
- [lockState](Gameplay.Gameplay.PhysicsImpulse.md#lockstate)
- [name](Gameplay.Gameplay.PhysicsImpulse.md#name)
- [netStatus](Gameplay.Gameplay.PhysicsImpulse.md#netstatus)
- [parent](Gameplay.Gameplay.PhysicsImpulse.md#parent)
- [relativeLocation](Gameplay.Gameplay.PhysicsImpulse.md#relativelocation)
- [relativeRotation](Gameplay.Gameplay.PhysicsImpulse.md#relativerotation)
- [relativeScale](Gameplay.Gameplay.PhysicsImpulse.md#relativescale)
- [rightVector](Gameplay.Gameplay.PhysicsImpulse.md#rightvector)
- [staticStatus](Gameplay.Gameplay.PhysicsImpulse.md#staticstatus)
- [tag](Gameplay.Gameplay.PhysicsImpulse.md#tag)
- [transform](Gameplay.Gameplay.PhysicsImpulse.md#transform)
- [upVector](Gameplay.Gameplay.PhysicsImpulse.md#upvector)
- [useUpdate](Gameplay.Gameplay.PhysicsImpulse.md#useupdate)
- [worldLocation](Gameplay.Gameplay.PhysicsImpulse.md#worldlocation)
- [worldRotation](Gameplay.Gameplay.PhysicsImpulse.md#worldrotation)
- [worldScale](Gameplay.Gameplay.PhysicsImpulse.md#worldscale)

### Methods

- [addDestroyCallback](Gameplay.Gameplay.PhysicsImpulse.md#adddestroycallback)
- [asyncGetScriptByName](Gameplay.Gameplay.PhysicsImpulse.md#asyncgetscriptbyname)
- [attachToGameObject](Gameplay.Gameplay.PhysicsImpulse.md#attachtogameobject)
- [clone](Gameplay.Gameplay.PhysicsImpulse.md#clone)
- [deleteDestroyCallback](Gameplay.Gameplay.PhysicsImpulse.md#deletedestroycallback)
- [destroy](Gameplay.Gameplay.PhysicsImpulse.md#destroy)
- [detachFromGameObject](Gameplay.Gameplay.PhysicsImpulse.md#detachfromgameobject)
- [getBoundingBoxSize](Gameplay.Gameplay.PhysicsImpulse.md#getboundingboxsize)
- [getBounds](Gameplay.Gameplay.PhysicsImpulse.md#getbounds)
- [getChildByGuid](Gameplay.Gameplay.PhysicsImpulse.md#getchildbyguid)
- [getChildByName](Gameplay.Gameplay.PhysicsImpulse.md#getchildbyname)
- [getChildren](Gameplay.Gameplay.PhysicsImpulse.md#getchildren)
- [getChildrenBoxCenter](Gameplay.Gameplay.PhysicsImpulse.md#getchildrenboxcenter)
- [getCollision](Gameplay.Gameplay.PhysicsImpulse.md#getcollision)
- [getForwardVector](Gameplay.Gameplay.PhysicsImpulse.md#getforwardvector)
- [getRelativeLocation](Gameplay.Gameplay.PhysicsImpulse.md#getrelativelocation)
- [getRelativeRotation](Gameplay.Gameplay.PhysicsImpulse.md#getrelativerotation)
- [getRelativeScale](Gameplay.Gameplay.PhysicsImpulse.md#getrelativescale)
- [getRightVector](Gameplay.Gameplay.PhysicsImpulse.md#getrightvector)
- [getScriptByGuid](Gameplay.Gameplay.PhysicsImpulse.md#getscriptbyguid)
- [getScriptByName](Gameplay.Gameplay.PhysicsImpulse.md#getscriptbyname)
- [getScripts](Gameplay.Gameplay.PhysicsImpulse.md#getscripts)
- [getSourceAssetGuid](Gameplay.Gameplay.PhysicsImpulse.md#getsourceassetguid)
- [getTransform](Gameplay.Gameplay.PhysicsImpulse.md#gettransform)
- [getUpVector](Gameplay.Gameplay.PhysicsImpulse.md#getupvector)
- [getWorldLocation](Gameplay.Gameplay.PhysicsImpulse.md#getworldlocation)
- [getWorldRotation](Gameplay.Gameplay.PhysicsImpulse.md#getworldrotation)
- [getWorldScale](Gameplay.Gameplay.PhysicsImpulse.md#getworldscale)
- [isRunningClient](Gameplay.Gameplay.PhysicsImpulse.md#isrunningclient)
- [onDestroy](Gameplay.Gameplay.PhysicsImpulse.md#ondestroy)
- [onStart](Gameplay.Gameplay.PhysicsImpulse.md#onstart)
- [onUpdate](Gameplay.Gameplay.PhysicsImpulse.md#onupdate)
- [ready](Gameplay.Gameplay.PhysicsImpulse.md#ready)
- [setCollision](Gameplay.Gameplay.PhysicsImpulse.md#setcollision)
- [setLocationAndRotation](Gameplay.Gameplay.PhysicsImpulse.md#setlocationandrotation)
- [setRelativeLocation](Gameplay.Gameplay.PhysicsImpulse.md#setrelativelocation)
- [setRelativeRotation](Gameplay.Gameplay.PhysicsImpulse.md#setrelativerotation)
- [setRelativeScale](Gameplay.Gameplay.PhysicsImpulse.md#setrelativescale)
- [setTransform](Gameplay.Gameplay.PhysicsImpulse.md#settransform)
- [setVisibility](Gameplay.Gameplay.PhysicsImpulse.md#setvisibility)
- [setWorldLocation](Gameplay.Gameplay.PhysicsImpulse.md#setworldlocation)
- [setWorldRotation](Gameplay.Gameplay.PhysicsImpulse.md#setworldrotation)
- [setWorldScale](Gameplay.Gameplay.PhysicsImpulse.md#setworldscale)
- [asyncFind](Gameplay.Gameplay.PhysicsImpulse.md#asyncfind)
- [asyncSpawnGameObject](Gameplay.Gameplay.PhysicsImpulse.md#asyncspawngameobject)
- [find](Gameplay.Gameplay.PhysicsImpulse.md#find)
- [findGameObjectByTag](Gameplay.Gameplay.PhysicsImpulse.md#findgameobjectbytag)
- [getGameObjectByName](Gameplay.Gameplay.PhysicsImpulse.md#getgameobjectbyname)
- [getGameObjectsByName](Gameplay.Gameplay.PhysicsImpulse.md#getgameobjectsbyname)
- [spawnGameObject](Gameplay.Gameplay.PhysicsImpulse.md#spawngameobject)

## Constructors

### constructor

• **new PhysicsImpulse**()

#### Inherited from

[GameObject](Core.Core.GameObject.md).[constructor](Core.Core.GameObject.md#constructor)

## Properties

### onImpulseEnter

• **onImpulseEnter**: [`MulticastGameObjectDelegate`](Type.Type.MulticastGameObjectDelegate.md)

**`Description`**

发生冲量碰撞后的回调函数

#### Defined in

Gameplay/index.d.ts:12969

## Accessors

### enable

• `get` **enable**(): `boolean`

**`Description`**

获取是否启用冲量

**`Effect`**

调用端生效

#### Returns

`boolean`

是否启用冲量

#### Defined in

Gameplay/index.d.ts:12981

• `set` **enable**(`impulseEnabled`): `void`

**`Description`**

设置是否启用冲量，禁用状态下，不会应用冲量到物体上

**`Effect`**

客户端调用自动广播

#### Parameters

| Name             | Type      | Description                                                                |
| :--------------- | :-------- | :------------------------------------------------------------------------- |
| `impulseEnabled` | `boolean` | usage: 是否启用冲量的应用，设置为 false 后依然会有碰撞事件，但不会应用冲量 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:12975

---

### forwardVector

• `get` **forwardVector**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取当前物体的向前向量

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

Vector

#### Inherited from

Core.GameObject.forwardVector

#### Defined in

Core/index.d.ts:405

---

### guid

• `get` **guid**(): `string`

**`Description`**

获取对象的 guid（唯一标识一个对象的字符串）。

**`Effect`**

调用端生效

#### Returns

`string`

#### Inherited from

Core.GameObject.guid

#### Defined in

Core/index.d.ts:38

---

### impulseForceType

• `get` **impulseForceType**(): [`ImpulseForceType`](../enums/Gameplay.Gameplay.ImpulseForceType.md)

**`Description`**

获取当前冲量力类型

**`Effect`**

调用端生效

#### Returns

[`ImpulseForceType`](../enums/Gameplay.Gameplay.ImpulseForceType.md)

冲量力类型

#### Defined in

Gameplay/index.d.ts:13030

• `set` **impulseForceType**(`impulseCollisionType`): `void`

**`Description`**

设置冲量力类型

**`Effect`**

客户端调用自动广播

#### Parameters

| Name                   | Type                                                                 | Description       |
| :--------------------- | :------------------------------------------------------------------- | :---------------- |
| `impulseCollisionType` | [`ImpulseForceType`](../enums/Gameplay.Gameplay.ImpulseForceType.md) | usage: 冲量力类型 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13024

---

### impulseRadialForce

• `get` **impulseRadialForce**(): `number`

**`Description`**

获取径向力的冲量值

**`Effect`**

调用端生效

#### Returns

`number`

径向力时的冲量值

#### Defined in

Gameplay/index.d.ts:13018

• `set` **impulseRadialForce**(`value`): `void`

**`Description`**

设置径向力的冲量值

**`Effect`**

客户端调用自动广播

#### Parameters

| Name    | Type     |
| :------ | :------- |
| `value` | `number` |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13012

---

### impulseType

• `get` **impulseType**(): [`ImpulseType`](../enums/Gameplay.Gameplay.ImpulseType.md)

**`Description`**

获取冲量应用方式，绝对或相对

**`Effect`**

调用端生效

#### Returns

[`ImpulseType`](../enums/Gameplay.Gameplay.ImpulseType.md)

当前冲量应用方式

#### Defined in

Gameplay/index.d.ts:12994

• `set` **impulseType**(`impulseType`): `void`

**`Description`**

设置冲量应用方式

**`Precautions`**

在编辑器中使用会自动更新箭头方向

**`Effect`**

客户端调用自动广播

#### Parameters

| Name          | Type                                                       | Description         |
| :------------ | :--------------------------------------------------------- | :------------------ |
| `impulseType` | [`ImpulseType`](../enums/Gameplay.Gameplay.ImpulseType.md) | usage: 冲量应用方式 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:12988

---

### impulseVector

• `get` **impulseVector**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取矢量力的冲量向量

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

当前冲量类型

#### Defined in

Gameplay/index.d.ts:13006

• `set` **impulseVector**(`vec`): `void`

**`Description`**

设置矢量力的冲量向量

**`Effect`**

客户端调用自动广播

#### Parameters

| Name  | Type                            | Description       |
| :---- | :------------------------------ | :---------------- |
| `vec` | [`Vector`](Type.Type.Vector.md) | usage: 冲量力向量 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13000

---

### isVisible

• `get` **isVisible**(): `boolean`

**`Description`**

获取当前物体是否显示

**`Effect`**

调用端生效

#### Returns

`boolean`

bool

#### Inherited from

Core.GameObject.isVisible

#### Defined in

Core/index.d.ts:496

---

### lockState

• `get` **lockState**(): `boolean`

**`Description`**

获取是否锁定

**`Effect`**

调用端生效

#### Returns

`boolean`

#### Inherited from

Core.GameObject.lockState

#### Defined in

Core/index.d.ts:452

• `set` **lockState**(`v`): `void`

**`Description`**

设置是否锁定

**`Effect`**

调用端生效

#### Parameters

| Name | Type      |
| :--- | :-------- |
| `v`  | `boolean` |

#### Returns

`void`

#### Inherited from

Core.GameObject.lockState

#### Defined in

Core/index.d.ts:447

---

### name

• `get` **name**(): `string`

**`Description`**

返回当前物体名称

**`Effect`**

调用端生效

#### Returns

`string`

名称

#### Inherited from

Core.GameObject.name

#### Defined in

Core/index.d.ts:167

• `set` **name**(`name`): `void`

**`Description`**

设置物体名称

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description          |
| :----- | :------- | :------------------- |
| `name` | `string` | usage:需要设置的名称 |

#### Returns

`void`

#### Inherited from

Core.GameObject.name

#### Defined in

Core/index.d.ts:173

---

### netStatus

• `get` **netStatus**(): [`NetStatus`](../enums/Type.Type.NetStatus.md)

**`Description`**

获取当前物体同步状态

**`Effect`**

调用端生效

#### Returns

[`NetStatus`](../enums/Type.Type.NetStatus.md)

Type.NetStatus

#### Inherited from

Core.GameObject.netStatus

#### Defined in

Core/index.d.ts:502

---

### parent

• `get` **parent**(): [`GameObject`](Core.Core.GameObject.md)

**`Description`**

获取当前父物体

**`Effect`**

调用端生效

#### Returns

[`GameObject`](Core.Core.GameObject.md)

父物体

#### Inherited from

Core.GameObject.parent

#### Defined in

Core/index.d.ts:458

• `set` **parent**(`newParent`): `void`

**`Description`**

设置父物体

**`Effect`**

调用端生效

#### Parameters

| Name        | Type                                    |
| :---------- | :-------------------------------------- |
| `newParent` | [`GameObject`](Core.Core.GameObject.md) |

#### Returns

`void`

#### Inherited from

Core.GameObject.parent

#### Defined in

Core/index.d.ts:463

---

### relativeLocation

• `get` **relativeLocation**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取相对位置

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

位置坐标

#### Inherited from

Core.GameObject.relativeLocation

#### Defined in

Core/index.d.ts:304

• `set` **relativeLocation**(`location`): `void`

**`Description`**

设置相对位置

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                            | Description |
| :--------- | :------------------------------ | :---------- |
| `location` | [`Vector`](Type.Type.Vector.md) | usage:位置  |

#### Returns

`void`

#### Inherited from

Core.GameObject.relativeLocation

#### Defined in

Core/index.d.ts:310

---

### relativeRotation

• `get` **relativeRotation**(): [`Rotation`](Type.Type.Rotation.md)

**`Description`**

获取相对旋转

**`Effect`**

调用端生效

#### Returns

[`Rotation`](Type.Type.Rotation.md)

旋转角度

#### Inherited from

Core.GameObject.relativeRotation

#### Defined in

Core/index.d.ts:330

• `set` **relativeRotation**(`rotation`): `void`

**`Description`**

设置相对旋转

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                                | Description |
| :--------- | :---------------------------------- | :---------- |
| `rotation` | [`Rotation`](Type.Type.Rotation.md) | usage:旋转  |

#### Returns

`void`

#### Inherited from

Core.GameObject.relativeRotation

#### Defined in

Core/index.d.ts:336

---

### relativeScale

• `get` **relativeScale**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取相对缩放

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

相对缩放

#### Inherited from

Core.GameObject.relativeScale

#### Defined in

Core/index.d.ts:356

• `set` **relativeScale**(`scale`): `void`

**`Description`**

设置相对缩放

**`Effect`**

调用端生效

#### Parameters

| Name    | Type                            | Description |
| :------ | :------------------------------ | :---------- |
| `scale` | [`Vector`](Type.Type.Vector.md) | usage:缩放  |

#### Returns

`void`

#### Inherited from

Core.GameObject.relativeScale

#### Defined in

Core/index.d.ts:362

---

### rightVector

• `get` **rightVector**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取当前物体的向右向量

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

Vector

#### Inherited from

Core.GameObject.rightVector

#### Defined in

Core/index.d.ts:419

---

### staticStatus

• `get` **staticStatus**(): `boolean`

**`Description`**

获取是否静态

**`Effect`**

调用端生效

#### Returns

`boolean`

#### Inherited from

Core.GameObject.staticStatus

#### Defined in

Core/index.d.ts:442

---

### tag

• `get` **tag**(): `string`

**`Description`**

获取当前物体的 Tag

**`Effect`**

调用端生效

#### Returns

`string`

Tag

#### Inherited from

Core.GameObject.tag

#### Defined in

Core/index.d.ts:185

• `set` **tag**(`tag`): `void`

**`Description`**

设置当前物体的 Tag

**`Effect`**

调用端生效

#### Parameters

| Name  | Type     | Description |
| :---- | :------- | :---------- |
| `tag` | `string` | usage:Tag   |

#### Returns

`void`

#### Inherited from

Core.GameObject.tag

#### Defined in

Core/index.d.ts:179

---

### transform

• `get` **transform**(): [`Transform`](Type.Type.Transform.md)

**`Description`**

返回当前物体 transform

**`Effect`**

调用端生效

#### Returns

[`Transform`](Type.Type.Transform.md)

transform

#### Inherited from

Core.GameObject.transform

#### Defined in

Core/index.d.ts:205

• `set` **transform**(`transform`): `void`

**`Description`**

设置当前物体 transform

**`Effect`**

调用端生效

#### Parameters

| Name        | Type                                  | Description              |
| :---------- | :------------------------------------ | :----------------------- |
| `transform` | [`Transform`](Type.Type.Transform.md) | usage:要设置的 transform |

#### Returns

`void`

#### Inherited from

Core.GameObject.transform

#### Defined in

Core/index.d.ts:211

---

### upVector

• `get` **upVector**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取当前物体的向上向量

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

Vector

#### Inherited from

Core.GameObject.upVector

#### Defined in

Core/index.d.ts:392

---

### useUpdate

• `get` **useUpdate**(): `boolean`

**`Description`**

是否使用更新

**`Effect`**

调用端生效

#### Returns

`boolean`

#### Inherited from

Core.GameObject.useUpdate

#### Defined in

Core/index.d.ts:437

• `set` **useUpdate**(`v`): `void`

**`Description`**

是否使用更新

**`Effect`**

调用端生效

#### Parameters

| Name | Type      |
| :--- | :-------- |
| `v`  | `boolean` |

#### Returns

`void`

#### Inherited from

Core.GameObject.useUpdate

#### Defined in

Core/index.d.ts:432

---

### worldLocation

• `get` **worldLocation**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取物体的世界坐标

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

#### Inherited from

Core.GameObject.worldLocation

#### Defined in

Core/index.d.ts:230

• `set` **worldLocation**(`v`): `void`

**`Description`**

设置物体的世界坐标

**`Effect`**

调用端生效

#### Parameters

| Name | Type                            |
| :--- | :------------------------------ |
| `v`  | [`Vector`](Type.Type.Vector.md) |

#### Returns

`void`

#### Inherited from

Core.GameObject.worldLocation

#### Defined in

Core/index.d.ts:235

---

### worldRotation

• `get` **worldRotation**(): [`Rotation`](Type.Type.Rotation.md)

**`Description`**

获取物体的世界旋转

**`Effect`**

调用端生效

#### Returns

[`Rotation`](Type.Type.Rotation.md)

#### Inherited from

Core.GameObject.worldRotation

#### Defined in

Core/index.d.ts:254

• `set` **worldRotation**(`rotation`): `void`

**`Description`**

设置物体的世界旋转

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                                | Description            |
| :--------- | :---------------------------------- | :--------------------- |
| `rotation` | [`Rotation`](Type.Type.Rotation.md) | usage:要设置的世界旋转 |

#### Returns

`void`

#### Inherited from

Core.GameObject.worldRotation

#### Defined in

Core/index.d.ts:260

---

### worldScale

• `get` **worldScale**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取物体的世界缩放

**`Effect`**

调用端生效

#### Returns

[`Vector`](Type.Type.Vector.md)

#### Inherited from

Core.GameObject.worldScale

#### Defined in

Core/index.d.ts:279

• `set` **worldScale**(`v`): `void`

**`Description`**

设置物体的是世界缩放

**`Effect`**

调用端生效

#### Parameters

| Name | Type                            |
| :--- | :------------------------------ |
| `v`  | [`Vector`](Type.Type.Vector.md) |

#### Returns

`void`

#### Inherited from

Core.GameObject.worldScale

#### Defined in

Core/index.d.ts:284

## Methods

### addDestroyCallback

▸ **addDestroyCallback**(`callback`): `void`

**`Description`**

添加物体 Destroy 事件回调

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                              | Description    |
| :--------- | :-------------------------------- | :------------- |
| `callback` | (...`arg`: `unknown`[]) => `void` | usage:回调事件 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[addDestroyCallback](Core.Core.GameObject.md#adddestroycallback)

#### Defined in

Core/index.d.ts:616

---

### asyncGetScriptByName

▸ **asyncGetScriptByName**(`name`): `Promise`<`Script`\>

**`Description`**

异步获得当前物体下的指定脚本 客户端不维系父子关系

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description |
| :----- | :------- | :---------- |
| `name` | `string` | usage:名字  |

#### Returns

`Promise`<`Script`\>

Script

#### Inherited from

[GameObject](Core.Core.GameObject.md).[asyncGetScriptByName](Core.Core.GameObject.md#asyncgetscriptbyname)

#### Defined in

Core/index.d.ts:563

---

### attachToGameObject

▸ **attachToGameObject**(`obj`): `void`

**`Description`**

将物体附着到指定物体上

**`Effect`**

调用端生效

#### Parameters

| Name  | Type                                    | Description |
| :---- | :-------------------------------------- | :---------- |
| `obj` | [`GameObject`](Core.Core.GameObject.md) | usage:物体  |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[attachToGameObject](Core.Core.GameObject.md#attachtogameobject)

#### Defined in

Core/index.d.ts:583

---

### clone

▸ **clone**(`inReplicates?`): [`GameObject`](Core.Core.GameObject.md)

**`Description`**

复制对象

**`Effect`**

调用端生效

#### Parameters

| Name            | Type      | Description                 |
| :-------------- | :-------- | :-------------------------- |
| `inReplicates?` | `boolean` | usage:是否复制 default:true |

#### Returns

[`GameObject`](Core.Core.GameObject.md)

克隆的对象

#### Inherited from

[GameObject](Core.Core.GameObject.md).[clone](Core.Core.GameObject.md#clone)

#### Defined in

Core/index.d.ts:543

---

### deleteDestroyCallback

▸ **deleteDestroyCallback**(`callback`): `void`

**`Description`**

移除物体 Destroy 事件回调

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                              | Description    |
| :--------- | :-------------------------------- | :------------- |
| `callback` | (...`arg`: `unknown`[]) => `void` | usage:回调事件 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[deleteDestroyCallback](Core.Core.GameObject.md#deletedestroycallback)

#### Defined in

Core/index.d.ts:622

---

### destroy

▸ **destroy**(): `void`

**`Description`**

删除对象

**`Effect`**

调用端生效

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[destroy](Core.Core.GameObject.md#destroy)

#### Defined in

Core/index.d.ts:146

---

### detachFromGameObject

▸ **detachFromGameObject**(): `void`

**`Description`**

将此物体与当前附着的物体分离

**`Effect`**

调用端生效

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[detachFromGameObject](Core.Core.GameObject.md#detachfromgameobject)

#### Defined in

Core/index.d.ts:588

---

### getBoundingBoxSize

▸ **getBoundingBoxSize**(`nonColliding?`, `includeFromChildActors?`, `outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取物体包围盒大小

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Rotation 对象,建议传入 outer 来减少 new 对象

#### Parameters

| Name                      | Type                            | Description                                        |
| :------------------------ | :------------------------------ | :------------------------------------------------- |
| `nonColliding?`           | `boolean`                       | usage:表示要在边界框中包含非碰撞组件 default:false |
| `includeFromChildActors?` | `boolean`                       | usage:如果为 true，则递归子物体 default:false      |
| `outer?`                  | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null      |

#### Returns

[`Vector`](Type.Type.Vector.md)

Type.Vector

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getBoundingBoxSize](Core.Core.GameObject.md#getboundingboxsize)

#### Defined in

Core/index.d.ts:598

---

### getBounds

▸ **getBounds**(`onlyCollidingComponents`, `OriginOuter`, `BoxExtentOuter`, `includeFromChildActors?`): `void`

**`Description`**

获取 Gameobject 边界

**`Effect`**

调用端生效

#### Parameters

| Name                      | Type                            | Description                                      |
| :------------------------ | :------------------------------ | :----------------------------------------------- |
| `onlyCollidingComponents` | `boolean`                       | usage:是否只包含有碰撞的组件。                   |
| `OriginOuter`             | [`Vector`](Type.Type.Vector.md) | usage:传出参数，设置为 Gameobject 的中心点坐标。 |
| `BoxExtentOuter`          | [`Vector`](Type.Type.Vector.md) | usage:传出参数，设置为 Gameobject 尺寸的一半。   |
| `includeFromChildActors?` | `boolean`                       | usage:是否递归包含子物体 default:undefined       |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getBounds](Core.Core.GameObject.md#getbounds)

#### Defined in

Core/index.d.ts:194

---

### getChildByGuid

▸ **getChildByGuid**(`guid`): [`GameObject`](Core.Core.GameObject.md)

**`Description`**

根据 Guid 查找子物体

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description |
| :----- | :------- | :---------- |
| `guid` | `string` | usage:guid  |

#### Returns

[`GameObject`](Core.Core.GameObject.md)

查找的物体

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getChildByGuid](Core.Core.GameObject.md#getchildbyguid)

#### Defined in

Core/index.d.ts:536

---

### getChildByName

▸ **getChildByName**(`name`): [`GameObject`](Core.Core.GameObject.md)

**`Description`**

根据名称查找子物体

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description |
| :----- | :------- | :---------- |
| `name` | `string` | usage:名称  |

#### Returns

[`GameObject`](Core.Core.GameObject.md)

查找的物体

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getChildByName](Core.Core.GameObject.md#getchildbyname)

#### Defined in

Core/index.d.ts:529

---

### getChildren

▸ **getChildren**(): [`GameObject`](Core.Core.GameObject.md)[]

**`Description`**

获取 Children 客户端不维系父子关系 推荐使用 Find 替代

**`Effect`**

调用端生效

#### Returns

[`GameObject`](Core.Core.GameObject.md)[]

Array\<GameObject\>

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getChildren](Core.Core.GameObject.md#getchildren)

#### Defined in

Core/index.d.ts:522

---

### getChildrenBoxCenter

▸ **getChildrenBoxCenter**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取所有子对象包围盒中心点(不包含父对象,父对象不可用返回[0,0,0])

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Rotation 对象,建议传入 outer 来减少 new 对象

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

Type.Vector

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getChildrenBoxCenter](Core.Core.GameObject.md#getchildrenboxcenter)

#### Defined in

Core/index.d.ts:610

---

### getCollision

▸ **getCollision**(): [`PropertyStatus`](../enums/Type.Type.PropertyStatus.md) \| [`CollisionStatus`](../enums/Type.Type.CollisionStatus.md)

**`Description`**

返回碰撞状态

**`Effect`**

调用端生效

#### Returns

[`PropertyStatus`](../enums/Type.Type.PropertyStatus.md) \| [`CollisionStatus`](../enums/Type.Type.CollisionStatus.md)

碰撞状态

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getCollision](Core.Core.GameObject.md#getcollision)

#### Defined in

Core/index.d.ts:480

---

### getForwardVector

▸ **getForwardVector**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取当前物体的向前向量

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象,建议传入 outer 来减少 new 对象

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

Vector

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getForwardVector](Core.Core.GameObject.md#getforwardvector)

#### Defined in

Core/index.d.ts:413

---

### getRelativeLocation

▸ **getRelativeLocation**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取相对位置

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象,建议传入 outer 来减少 new 对象

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

位置坐标

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getRelativeLocation](Core.Core.GameObject.md#getrelativelocation)

#### Defined in

Core/index.d.ts:318

---

### getRelativeRotation

▸ **getRelativeRotation**(`outer?`): [`Rotation`](Type.Type.Rotation.md)

**`Description`**

获取相对旋转

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Rotation 对象,建议传入 outer 来减少 new 对象

#### Parameters

| Name     | Type                                | Description                                     |
| :------- | :---------------------------------- | :---------------------------------------------- |
| `outer?` | [`Rotation`](Type.Type.Rotation.md) | usage:接收转换数据的 Rotation 对象 default:null |

#### Returns

[`Rotation`](Type.Type.Rotation.md)

旋转角度

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getRelativeRotation](Core.Core.GameObject.md#getrelativerotation)

#### Defined in

Core/index.d.ts:344

---

### getRelativeScale

▸ **getRelativeScale**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取相对缩放

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象,建议传入 outer 来减少 new 对象

**`Effect`**

调用端生效

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

相对缩放

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getRelativeScale](Core.Core.GameObject.md#getrelativescale)

#### Defined in

Core/index.d.ts:370

---

### getRightVector

▸ **getRightVector**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取当前物体的向右向量

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象,建议传入 outer 来减少 new 对象

**`Effect`**

调用端生效

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

Vector

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getRightVector](Core.Core.GameObject.md#getrightvector)

#### Defined in

Core/index.d.ts:427

---

### getScriptByGuid

▸ **getScriptByGuid**(`guid`): `Script`

**`Description`**

获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用 Find 替代

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description |
| :----- | :------- | :---------- |
| `guid` | `string` | usage:guid  |

#### Returns

`Script`

Script

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getScriptByGuid](Core.Core.GameObject.md#getscriptbyguid)

#### Defined in

Core/index.d.ts:570

---

### getScriptByName

▸ **getScriptByName**(`name`): `Script`

**`Description`**

获得当前物体下的指定脚本 客户端不维系父子关系 推荐使用 Find 替代

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description |
| :----- | :------- | :---------- |
| `name` | `string` | usage:名字  |

#### Returns

`Script`

Script

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getScriptByName](Core.Core.GameObject.md#getscriptbyname)

#### Defined in

Core/index.d.ts:556

---

### getScripts

▸ **getScripts**(): `Script`[]

**`Description`**

获得当前物体下的所有脚本 客户端不维系父子关系 推荐使用 Find 替代

**`Effect`**

调用端生效

#### Returns

`Script`[]

Array\<Script\>

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getScripts](Core.Core.GameObject.md#getscripts)

#### Defined in

Core/index.d.ts:549

---

### getSourceAssetGuid

▸ **getSourceAssetGuid**(): `string`

**`Description`**

获取当前物体使用资源的 GUID

**`Effect`**

调用端生效

#### Returns

`string`

资源的 GUID

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getSourceAssetGuid](Core.Core.GameObject.md#getsourceassetguid)

#### Defined in

Core/index.d.ts:628

---

### getTransform

▸ **getTransform**(`outer?`): [`Transform`](Type.Type.Transform.md)

**`Description`**

返回当前物体 Transform

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Transform 对象,建议传入 outer 来减少 new 对象

#### Parameters

| Name     | Type                                  | Description                                      |
| :------- | :------------------------------------ | :----------------------------------------------- |
| `outer?` | [`Transform`](Type.Type.Transform.md) | usage:接收转换数据的 Transform 对象 default:null |

#### Returns

[`Transform`](Type.Type.Transform.md)

Transform

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getTransform](Core.Core.GameObject.md#gettransform)

#### Defined in

Core/index.d.ts:219

---

### getUpVector

▸ **getUpVector**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取当前物体的向上向量

**`Effect`**

调用端生效

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

Vector

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getUpVector](Core.Core.GameObject.md#getupvector)

#### Defined in

Core/index.d.ts:399

---

### getWorldLocation

▸ **getWorldLocation**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取物体的世界坐标

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象,建议传入 outer 来减少 new 对象\

**`Effect`**

调用端生效

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

世界位置坐标

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getWorldLocation](Core.Core.GameObject.md#getworldlocation)

#### Defined in

Core/index.d.ts:243

---

### getWorldRotation

▸ **getWorldRotation**(`outer?`): [`Rotation`](Type.Type.Rotation.md)

**`Description`**

获取物体的世界旋转

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Rotation 对象,建议传入 outer 来减少 new 对象

**`Effect`**

调用端生效

#### Parameters

| Name     | Type                                | Description                                     |
| :------- | :---------------------------------- | :---------------------------------------------- |
| `outer?` | [`Rotation`](Type.Type.Rotation.md) | usage:接收转换数据的 Rotation 对象 default:null |

#### Returns

[`Rotation`](Type.Type.Rotation.md)

世界旋转

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getWorldRotation](Core.Core.GameObject.md#getworldrotation)

#### Defined in

Core/index.d.ts:268

---

### getWorldScale

▸ **getWorldScale**(`outer?`): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取物体的世界缩放

**`Effect`**

调用端生效

**`Precautions`**

如果 outer 不为空, 返回 outer,否则返回一个新的 Vector 对象,建议传入 outer 来减少 new 对象

#### Parameters

| Name     | Type                            | Description                                   |
| :------- | :------------------------------ | :-------------------------------------------- |
| `outer?` | [`Vector`](Type.Type.Vector.md) | usage:接收转换数据的 Vector 对象 default:null |

#### Returns

[`Vector`](Type.Type.Vector.md)

世界缩放

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getWorldScale](Core.Core.GameObject.md#getworldscale)

#### Defined in

Core/index.d.ts:292

---

### isRunningClient

▸ **isRunningClient**(): `boolean`

**`Description`**

是否为客户端

**`Effect`**

调用端生效

#### Returns

`boolean`

true 为客户端

#### Inherited from

[GameObject](Core.Core.GameObject.md).[isRunningClient](Core.Core.GameObject.md#isrunningclient)

#### Defined in

Core/index.d.ts:49

---

### onDestroy

▸ `Protected` **onDestroy**(): `void`

**`Description`**

周期函数 被销毁时调用

**`Effect`**

调用端生效

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[onDestroy](Core.Core.GameObject.md#ondestroy)

#### Defined in

Core/index.d.ts:17

---

### onStart

▸ `Protected` **onStart**(): `void`

**`Description`**

周期函数 脚本开始执行时调用

**`Effect`**

调用端生效

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[onStart](Core.Core.GameObject.md#onstart)

#### Defined in

Core/index.d.ts:12

---

### onUpdate

▸ `Protected` **onUpdate**(`dt`): `void`

**`Description`**

周期函数 useUpdate 设置为 true 后,每帧被执行,设置为 false,不会执行

**`Effect`**

调用端生效

#### Parameters

| Name | Type     | Description                  |
| :--- | :------- | :--------------------------- |
| `dt` | `number` | usage:与上一帧的延迟 单位:秒 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[onUpdate](Core.Core.GameObject.md#onupdate)

#### Defined in

Core/index.d.ts:23

---

### ready

▸ **ready**(): `Promise`<[`PhysicsImpulse`](Gameplay.Gameplay.PhysicsImpulse.md)\>

**`Description`**

GameObject 准备好后返回

**`Effect`**

调用端生效

#### Returns

`Promise`<[`PhysicsImpulse`](Gameplay.Gameplay.PhysicsImpulse.md)\>

准备好的对象

#### Inherited from

[GameObject](Core.Core.GameObject.md).[ready](Core.Core.GameObject.md#ready)

#### Defined in

Core/index.d.ts:122

---

### setCollision

▸ **setCollision**(`status`, `propagateToChildren?`): `void`

**`Description`**

设置碰撞状态

**`Effect`**

调用端生效

**`Precautions`**

建议双端物体设置碰撞，单端物体设置碰撞可能会导致拉扯的情况

#### Parameters

| Name                   | Type                                                                                                                   | Description                                                      |
| :--------------------- | :--------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------- |
| `status`               | [`PropertyStatus`](../enums/Type.Type.PropertyStatus.md) \| [`CollisionStatus`](../enums/Type.Type.CollisionStatus.md) | usage: 碰撞状态（Type.CollisionStatus 或者 Type.PropertyStatus） |
| `propagateToChildren?` | `boolean`                                                                                                              | usage: 是否传递给子节点 default: false                           |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setCollision](Core.Core.GameObject.md#setcollision)

#### Defined in

Core/index.d.ts:471

---

### setLocationAndRotation

▸ **setLocationAndRotation**(`location`, `rotation`): `void`

**`Description`**

同时设置物体的世界位置与旋转

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                                | Description    |
| :--------- | :---------------------------------- | :------------- |
| `location` | [`Vector`](Type.Type.Vector.md)     | usage:世界位置 |
| `rotation` | [`Rotation`](Type.Type.Rotation.md) | usage:世界旋转 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setLocationAndRotation](Core.Core.GameObject.md#setlocationandrotation)

#### Defined in

Core/index.d.ts:383

---

### setRelativeLocation

▸ **setRelativeLocation**(`location`): `void`

**`Description`**

设置相对位置

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                            | Description |
| :--------- | :------------------------------ | :---------- |
| `location` | [`Vector`](Type.Type.Vector.md) | usage:位置  |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setRelativeLocation](Core.Core.GameObject.md#setrelativelocation)

#### Defined in

Core/index.d.ts:324

---

### setRelativeRotation

▸ **setRelativeRotation**(`rotation`): `void`

**`Description`**

设置相对旋转

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                                | Description |
| :--------- | :---------------------------------- | :---------- |
| `rotation` | [`Rotation`](Type.Type.Rotation.md) | usage:旋转  |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setRelativeRotation](Core.Core.GameObject.md#setrelativerotation)

#### Defined in

Core/index.d.ts:350

---

### setRelativeScale

▸ **setRelativeScale**(`scale`): `void`

**`Description`**

设置相对缩放

**`Effect`**

调用端生效

#### Parameters

| Name    | Type                            | Description            |
| :------ | :------------------------------ | :--------------------- |
| `scale` | [`Vector`](Type.Type.Vector.md) | usage:要设置的相对缩放 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setRelativeScale](Core.Core.GameObject.md#setrelativescale)

#### Defined in

Core/index.d.ts:376

---

### setTransform

▸ **setTransform**(`transform`): `void`

**`Description`**

设置当前物体 transform

**`Effect`**

调用端生效

#### Parameters

| Name        | Type                                  | Description     |
| :---------- | :------------------------------------ | :-------------- |
| `transform` | [`Transform`](Type.Type.Transform.md) | usage:transform |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setTransform](Core.Core.GameObject.md#settransform)

#### Defined in

Core/index.d.ts:225

---

### setVisibility

▸ **setVisibility**(`status`, `propagateToChildren?`): `void`

**`Description`**

设置 GameObject 是否被显示

**`Effect`**

调用端生效

#### Parameters

| Name                   | Type                                                     | Description                         |
| :--------------------- | :------------------------------------------------------- | :---------------------------------- |
| `status`               | [`PropertyStatus`](../enums/Type.Type.PropertyStatus.md) | usage:状态                          |
| `propagateToChildren?` | `boolean`                                                | usage: 是否设置子物体 default:false |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setVisibility](Core.Core.GameObject.md#setvisibility)

#### Defined in

Core/index.d.ts:487

---

### setWorldLocation

▸ **setWorldLocation**(`v`): `void`

**`Description`**

设置物体的世界坐标

**`Effect`**

调用端生效

#### Parameters

| Name | Type                            | Description             |
| :--- | :------------------------------ | :---------------------- |
| `v`  | [`Vector`](Type.Type.Vector.md) | usage: 要设置的世界坐标 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setWorldLocation](Core.Core.GameObject.md#setworldlocation)

#### Defined in

Core/index.d.ts:249

---

### setWorldRotation

▸ **setWorldRotation**(`rotation`): `void`

**`Description`**

设置物体的世界旋转

**`Effect`**

调用端生效

#### Parameters

| Name       | Type                                | Description            |
| :--------- | :---------------------------------- | :--------------------- |
| `rotation` | [`Rotation`](Type.Type.Rotation.md) | usage:要设置的世界旋转 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setWorldRotation](Core.Core.GameObject.md#setworldrotation)

#### Defined in

Core/index.d.ts:274

---

### setWorldScale

▸ **setWorldScale**(`v`): `void`

**`Description`**

设置物体的世界缩放

**`Effect`**

调用端生效

#### Parameters

| Name | Type                            | Description            |
| :--- | :------------------------------ | :--------------------- |
| `v`  | [`Vector`](Type.Type.Vector.md) | usage:要设置的世界缩放 |

#### Returns

`void`

#### Inherited from

[GameObject](Core.Core.GameObject.md).[setWorldScale](Core.Core.GameObject.md#setworldscale)

#### Defined in

Core/index.d.ts:298

---

### asyncFind

▸ `Static` **asyncFind**(`guid`): `Promise`<[`GameObject`](Core.Core.GameObject.md)\>

**`Description`**

通过 guid 异步查找 Gamobject,默认是五秒,可以通过 `core.setGlobalAsyncOverTime(5000);
` 来设置

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description       |
| :----- | :------- | :---------------- |
| `guid` | `string` | usage:物体的 guid |

#### Returns

`Promise`<[`GameObject`](Core.Core.GameObject.md)\>

Guid 对应的物体

#### Inherited from

[GameObject](Core.Core.GameObject.md).[asyncFind](Core.Core.GameObject.md#asyncfind)

#### Defined in

Core/index.d.ts:161

---

### asyncSpawnGameObject

▸ `Static` **asyncSpawnGameObject**(`assetId`, `inReplicates?`): `Promise`<[`GameObject`](Core.Core.GameObject.md)\>

**`Description`**

异步构造一个 GameObject 资源不存在会先去下载资源再去创建

**`Effect`**

调用端生效

#### Parameters

| Name            | Type      | Description                           |
| :-------------- | :-------- | :------------------------------------ |
| `assetId`       | `string`  | usage:资源的 GUID                     |
| `inReplicates?` | `boolean` | usage:是否同步 default:默认服务端同步 |

#### Returns

`Promise`<[`GameObject`](Core.Core.GameObject.md)\>

构造的 GameObject

#### Inherited from

[GameObject](Core.Core.GameObject.md).[asyncSpawnGameObject](Core.Core.GameObject.md#asyncspawngameobject)

#### Defined in

Core/index.d.ts:138

---

### find

▸ `Static` **find**(`guid`): [`GameObject`](Core.Core.GameObject.md)

**`Description`**

通过 Guid 查找 Gameobject

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description       |
| :----- | :------- | :---------------- |
| `guid` | `string` | usage:物体的 Guid |

#### Returns

[`GameObject`](Core.Core.GameObject.md)

Guid 对应的物体

#### Inherited from

[GameObject](Core.Core.GameObject.md).[find](Core.Core.GameObject.md#find)

#### Defined in

Core/index.d.ts:153

---

### findGameObjectByTag

▸ `Static` **findGameObjectByTag**(`InTag`): [`GameObject`](Core.Core.GameObject.md)[]

**`Description`**

通过自定义 Tag 获取 GameObject

**`Effect`**

调用端生效

#### Parameters

| Name    | Type     | Description      |
| :------ | :------- | :--------------- |
| `InTag` | `string` | usage:自定义 Tag |

#### Returns

[`GameObject`](Core.Core.GameObject.md)[]

Array\<GameObject\>

#### Inherited from

[GameObject](Core.Core.GameObject.md).[findGameObjectByTag](Core.Core.GameObject.md#findgameobjectbytag)

#### Defined in

Core/index.d.ts:577

---

### getGameObjectByName

▸ `Static` **getGameObjectByName**(`name`): [`GameObject`](Core.Core.GameObject.md)

**`Description`**

通过名字查找物体

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description    |
| :----- | :------- | :------------- |
| `name` | `string` | usage:物体名字 |

#### Returns

[`GameObject`](Core.Core.GameObject.md)

返回第一个查找到的对象，如有多个同名对象，随机返回一个

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getGameObjectByName](Core.Core.GameObject.md#getgameobjectbyname)

#### Defined in

Core/index.d.ts:516

---

### getGameObjectsByName

▸ `Static` **getGameObjectsByName**(`name`): [`GameObject`](Core.Core.GameObject.md)[]

**`Description`**

通过名字查找物体

**`Effect`**

调用端生效

#### Parameters

| Name   | Type     | Description    |
| :----- | :------- | :------------- |
| `name` | `string` | usage:物体名字 |

#### Returns

[`GameObject`](Core.Core.GameObject.md)[]

返回所有查找到的对象

#### Inherited from

[GameObject](Core.Core.GameObject.md).[getGameObjectsByName](Core.Core.GameObject.md#getgameobjectsbyname)

#### Defined in

Core/index.d.ts:509

---

### spawnGameObject

▸ `Static` **spawnGameObject**(`assetId`, `inReplicates?`): [`GameObject`](Core.Core.GameObject.md)

**`Description`**

构造一个 GameObject

**`Effect`**

调用端生效

#### Parameters

| Name            | Type      | Description                           |
| :-------------- | :-------- | :------------------------------------ |
| `assetId`       | `string`  | usage:资源的 GUID                     |
| `inReplicates?` | `boolean` | usage:是否同步 default:默认服务端同步 |

#### Returns

[`GameObject`](Core.Core.GameObject.md)

构造的 GameObject

#### Inherited from

[GameObject](Core.Core.GameObject.md).[spawnGameObject](Core.Core.GameObject.md#spawngameobject)

#### Defined in

Core/index.d.ts:130