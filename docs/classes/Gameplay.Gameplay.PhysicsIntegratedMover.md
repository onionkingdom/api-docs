[auto-mwapi-lib](../README.md) / [Exports](../modules.md) / [Gameplay](../modules/Gameplay.md) / [Gameplay](../modules/Gameplay.Gameplay.md) / PhysicsIntegratedMover

# Class: PhysicsIntegratedMover

[Gameplay](../modules/Gameplay.md).[Gameplay](../modules/Gameplay.Gameplay.md).PhysicsIntegratedMover

**`Author`**

HuangHao

**`Description`**

运动器组件

**`Network Status`**

usage:双端

## Hierarchy

- [`PhysicsConstraintBase`](Gameplay.Gameplay.PhysicsConstraintBase.md)

  ↳ **`PhysicsIntegratedMover`**

## Table of contents

### Constructors

- [constructor](Gameplay.Gameplay.PhysicsIntegratedMover.md#constructor)

### Accessors

- [constraintTarget1](Gameplay.Gameplay.PhysicsIntegratedMover.md#constrainttarget1)
- [constraintTarget2](Gameplay.Gameplay.PhysicsIntegratedMover.md#constrainttarget2)
- [enable](Gameplay.Gameplay.PhysicsIntegratedMover.md#enable)
- [forwardVector](Gameplay.Gameplay.PhysicsIntegratedMover.md#forwardvector)
- [guid](Gameplay.Gameplay.PhysicsIntegratedMover.md#guid)
- [isVisible](Gameplay.Gameplay.PhysicsIntegratedMover.md#isvisible)
- [linearRepeat](Gameplay.Gameplay.PhysicsIntegratedMover.md#linearrepeat)
- [linearRepeatDelay](Gameplay.Gameplay.PhysicsIntegratedMover.md#linearrepeatdelay)
- [linearRepeatTime](Gameplay.Gameplay.PhysicsIntegratedMover.md#linearrepeattime)
- [linearSpeed](Gameplay.Gameplay.PhysicsIntegratedMover.md#linearspeed)
- [lockState](Gameplay.Gameplay.PhysicsIntegratedMover.md#lockstate)
- [name](Gameplay.Gameplay.PhysicsIntegratedMover.md#name)
- [netStatus](Gameplay.Gameplay.PhysicsIntegratedMover.md#netstatus)
- [parent](Gameplay.Gameplay.PhysicsIntegratedMover.md#parent)
- [relativeLocation](Gameplay.Gameplay.PhysicsIntegratedMover.md#relativelocation)
- [relativeRotation](Gameplay.Gameplay.PhysicsIntegratedMover.md#relativerotation)
- [relativeScale](Gameplay.Gameplay.PhysicsIntegratedMover.md#relativescale)
- [rightVector](Gameplay.Gameplay.PhysicsIntegratedMover.md#rightvector)
- [rotationRepeat](Gameplay.Gameplay.PhysicsIntegratedMover.md#rotationrepeat)
- [rotationRepeatDelay](Gameplay.Gameplay.PhysicsIntegratedMover.md#rotationrepeatdelay)
- [rotationRepeatTime](Gameplay.Gameplay.PhysicsIntegratedMover.md#rotationrepeattime)
- [rotationSpeed](Gameplay.Gameplay.PhysicsIntegratedMover.md#rotationspeed)
- [smooth](Gameplay.Gameplay.PhysicsIntegratedMover.md#smooth)
- [staticStatus](Gameplay.Gameplay.PhysicsIntegratedMover.md#staticstatus)
- [swingAngle](Gameplay.Gameplay.PhysicsIntegratedMover.md#swingangle)
- [swingSpeed](Gameplay.Gameplay.PhysicsIntegratedMover.md#swingspeed)
- [tag](Gameplay.Gameplay.PhysicsIntegratedMover.md#tag)
- [transform](Gameplay.Gameplay.PhysicsIntegratedMover.md#transform)
- [upVector](Gameplay.Gameplay.PhysicsIntegratedMover.md#upvector)
- [useUpdate](Gameplay.Gameplay.PhysicsIntegratedMover.md#useupdate)
- [worldLocation](Gameplay.Gameplay.PhysicsIntegratedMover.md#worldlocation)
- [worldRotation](Gameplay.Gameplay.PhysicsIntegratedMover.md#worldrotation)
- [worldScale](Gameplay.Gameplay.PhysicsIntegratedMover.md#worldscale)

### Methods

- [addDestroyCallback](Gameplay.Gameplay.PhysicsIntegratedMover.md#adddestroycallback)
- [asyncGetScriptByName](Gameplay.Gameplay.PhysicsIntegratedMover.md#asyncgetscriptbyname)
- [attachToGameObject](Gameplay.Gameplay.PhysicsIntegratedMover.md#attachtogameobject)
- [clone](Gameplay.Gameplay.PhysicsIntegratedMover.md#clone)
- [deleteDestroyCallback](Gameplay.Gameplay.PhysicsIntegratedMover.md#deletedestroycallback)
- [destroy](Gameplay.Gameplay.PhysicsIntegratedMover.md#destroy)
- [detachFromGameObject](Gameplay.Gameplay.PhysicsIntegratedMover.md#detachfromgameobject)
- [getBoundingBoxSize](Gameplay.Gameplay.PhysicsIntegratedMover.md#getboundingboxsize)
- [getBounds](Gameplay.Gameplay.PhysicsIntegratedMover.md#getbounds)
- [getChildByGuid](Gameplay.Gameplay.PhysicsIntegratedMover.md#getchildbyguid)
- [getChildByName](Gameplay.Gameplay.PhysicsIntegratedMover.md#getchildbyname)
- [getChildren](Gameplay.Gameplay.PhysicsIntegratedMover.md#getchildren)
- [getChildrenBoxCenter](Gameplay.Gameplay.PhysicsIntegratedMover.md#getchildrenboxcenter)
- [getCollision](Gameplay.Gameplay.PhysicsIntegratedMover.md#getcollision)
- [getForwardVector](Gameplay.Gameplay.PhysicsIntegratedMover.md#getforwardvector)
- [getRelativeLocation](Gameplay.Gameplay.PhysicsIntegratedMover.md#getrelativelocation)
- [getRelativeRotation](Gameplay.Gameplay.PhysicsIntegratedMover.md#getrelativerotation)
- [getRelativeScale](Gameplay.Gameplay.PhysicsIntegratedMover.md#getrelativescale)
- [getRightVector](Gameplay.Gameplay.PhysicsIntegratedMover.md#getrightvector)
- [getScriptByGuid](Gameplay.Gameplay.PhysicsIntegratedMover.md#getscriptbyguid)
- [getScriptByName](Gameplay.Gameplay.PhysicsIntegratedMover.md#getscriptbyname)
- [getScripts](Gameplay.Gameplay.PhysicsIntegratedMover.md#getscripts)
- [getSourceAssetGuid](Gameplay.Gameplay.PhysicsIntegratedMover.md#getsourceassetguid)
- [getTransform](Gameplay.Gameplay.PhysicsIntegratedMover.md#gettransform)
- [getUpVector](Gameplay.Gameplay.PhysicsIntegratedMover.md#getupvector)
- [getWorldLocation](Gameplay.Gameplay.PhysicsIntegratedMover.md#getworldlocation)
- [getWorldRotation](Gameplay.Gameplay.PhysicsIntegratedMover.md#getworldrotation)
- [getWorldScale](Gameplay.Gameplay.PhysicsIntegratedMover.md#getworldscale)
- [isRunningClient](Gameplay.Gameplay.PhysicsIntegratedMover.md#isrunningclient)
- [onDestroy](Gameplay.Gameplay.PhysicsIntegratedMover.md#ondestroy)
- [onStart](Gameplay.Gameplay.PhysicsIntegratedMover.md#onstart)
- [onUpdate](Gameplay.Gameplay.PhysicsIntegratedMover.md#onupdate)
- [ready](Gameplay.Gameplay.PhysicsIntegratedMover.md#ready)
- [setCollision](Gameplay.Gameplay.PhysicsIntegratedMover.md#setcollision)
- [setLocationAndRotation](Gameplay.Gameplay.PhysicsIntegratedMover.md#setlocationandrotation)
- [setRelativeLocation](Gameplay.Gameplay.PhysicsIntegratedMover.md#setrelativelocation)
- [setRelativeRotation](Gameplay.Gameplay.PhysicsIntegratedMover.md#setrelativerotation)
- [setRelativeScale](Gameplay.Gameplay.PhysicsIntegratedMover.md#setrelativescale)
- [setTransform](Gameplay.Gameplay.PhysicsIntegratedMover.md#settransform)
- [setVisibility](Gameplay.Gameplay.PhysicsIntegratedMover.md#setvisibility)
- [setWorldLocation](Gameplay.Gameplay.PhysicsIntegratedMover.md#setworldlocation)
- [setWorldRotation](Gameplay.Gameplay.PhysicsIntegratedMover.md#setworldrotation)
- [setWorldScale](Gameplay.Gameplay.PhysicsIntegratedMover.md#setworldscale)
- [asyncFind](Gameplay.Gameplay.PhysicsIntegratedMover.md#asyncfind)
- [asyncSpawnGameObject](Gameplay.Gameplay.PhysicsIntegratedMover.md#asyncspawngameobject)
- [find](Gameplay.Gameplay.PhysicsIntegratedMover.md#find)
- [findGameObjectByTag](Gameplay.Gameplay.PhysicsIntegratedMover.md#findgameobjectbytag)
- [getGameObjectByName](Gameplay.Gameplay.PhysicsIntegratedMover.md#getgameobjectbyname)
- [getGameObjectsByName](Gameplay.Gameplay.PhysicsIntegratedMover.md#getgameobjectsbyname)
- [spawnGameObject](Gameplay.Gameplay.PhysicsIntegratedMover.md#spawngameobject)

## Constructors

### constructor

• **new PhysicsIntegratedMover**()

#### Inherited from

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[constructor](Gameplay.Gameplay.PhysicsConstraintBase.md#constructor)

## Accessors

### constraintTarget1

• `get` **constraintTarget1**(): `string`

**`Description`**

获取约束对象 1

#### Returns

`string`

#### Inherited from

PhysicsConstraintBase.constraintTarget1

#### Defined in

Gameplay/index.d.ts:12498

• `set` **constraintTarget1**(`guid`): `void`

**`Description`**

设置约束对象 1

**`Effect`**

自动同步

#### Parameters

| Name   | Type     | Description              |
| :----- | :------- | :----------------------- |
| `guid` | `string` | usage:约束对象 1 的 GUID |

#### Returns

`void`

#### Inherited from

PhysicsConstraintBase.constraintTarget1

#### Defined in

Gameplay/index.d.ts:12504

---

### constraintTarget2

• `get` **constraintTarget2**(): `string`

**`Description`**

获取约束对象 2

#### Returns

`string`

#### Inherited from

PhysicsConstraintBase.constraintTarget2

#### Defined in

Gameplay/index.d.ts:12508

• `set` **constraintTarget2**(`guid`): `void`

**`Description`**

设置约束对象 2

**`Effect`**

自动同步

#### Parameters

| Name   | Type     | Description              |
| :----- | :------- | :----------------------- |
| `guid` | `string` | usage:约束对象 2 的 GUID |

#### Returns

`void`

#### Inherited from

PhysicsConstraintBase.constraintTarget2

#### Defined in

Gameplay/index.d.ts:12514

---

### enable

• `get` **enable**(): `boolean`

**`Description`**

获取启用状态

#### Returns

`boolean`

启用状态

#### Defined in

Gameplay/index.d.ts:13044

• `set` **enable**(`newEnable`): `void`

**`Description`**

设置启用状态

#### Parameters

| Name        | Type      | Description    |
| :---------- | :-------- | :------------- |
| `newEnable` | `boolean` | usage:启用状态 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13049

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

PhysicsConstraintBase.forwardVector

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

PhysicsConstraintBase.guid

#### Defined in

Core/index.d.ts:38

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

PhysicsConstraintBase.isVisible

#### Defined in

Core/index.d.ts:496

---

### linearRepeat

• `get` **linearRepeat**(): `boolean`

**`Description`**

获取线性重复运动状态

#### Returns

`boolean`

线性重复运动状态

#### Defined in

Gameplay/index.d.ts:13074

• `set` **linearRepeat**(`newRepeat`): `void`

**`Description`**

设置线性重复运动状态

#### Parameters

| Name        | Type      | Description            |
| :---------- | :-------- | :--------------------- |
| `newRepeat` | `boolean` | usage:线性重复运动状态 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13079

---

### linearRepeatDelay

• `get` **linearRepeatDelay**(): `number`

**`Description`**

获取线性重复运动间隔

#### Returns

`number`

线性重复运动间隔

#### Defined in

Gameplay/index.d.ts:13094

• `set` **linearRepeatDelay**(`newDelay`): `void`

**`Description`**

设置线性重复运动间隔

#### Parameters

| Name       | Type     | Description            |
| :--------- | :------- | :--------------------- |
| `newDelay` | `number` | usage:线性重复运动间隔 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13099

---

### linearRepeatTime

• `get` **linearRepeatTime**(): `number`

**`Description`**

获取线性重复运动时间

#### Returns

`number`

线性重复运动时间

#### Defined in

Gameplay/index.d.ts:13084

• `set` **linearRepeatTime**(`newTime`): `void`

**`Description`**

设置线性重复运动时间

#### Parameters

| Name      | Type     | Description            |
| :-------- | :------- | :--------------------- |
| `newTime` | `number` | usage:线性重复运动时间 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13089

---

### linearSpeed

• `get` **linearSpeed**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取线性速度大小

#### Returns

[`Vector`](Type.Type.Vector.md)

线性速度大小

#### Defined in

Gameplay/index.d.ts:13064

• `set` **linearSpeed**(`newSpeed`): `void`

**`Description`**

设置线性速度大小

#### Parameters

| Name       | Type                            | Description        |
| :--------- | :------------------------------ | :----------------- |
| `newSpeed` | [`Vector`](Type.Type.Vector.md) | usage:线性速度大小 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13069

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

PhysicsConstraintBase.lockState

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

PhysicsConstraintBase.lockState

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

PhysicsConstraintBase.name

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

PhysicsConstraintBase.name

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

PhysicsConstraintBase.netStatus

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

PhysicsConstraintBase.parent

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

PhysicsConstraintBase.parent

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

PhysicsConstraintBase.relativeLocation

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

PhysicsConstraintBase.relativeLocation

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

PhysicsConstraintBase.relativeRotation

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

PhysicsConstraintBase.relativeRotation

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

PhysicsConstraintBase.relativeScale

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

PhysicsConstraintBase.relativeScale

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

PhysicsConstraintBase.rightVector

#### Defined in

Core/index.d.ts:419

---

### rotationRepeat

• `get` **rotationRepeat**(): `boolean`

**`Description`**

获取旋转重复运动状态

#### Returns

`boolean`

旋转重复运动状态

#### Defined in

Gameplay/index.d.ts:13114

• `set` **rotationRepeat**(`newRepeat`): `void`

**`Description`**

设置旋转重复运动状态

#### Parameters

| Name        | Type      | Description            |
| :---------- | :-------- | :--------------------- |
| `newRepeat` | `boolean` | usage:旋转重复运动状态 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13119

---

### rotationRepeatDelay

• `get` **rotationRepeatDelay**(): `number`

**`Description`**

获取旋转重复运动间隔

#### Returns

`number`

旋转重复运动间隔

#### Defined in

Gameplay/index.d.ts:13134

• `set` **rotationRepeatDelay**(`newDelay`): `void`

**`Description`**

设置旋转重复运动间隔

#### Parameters

| Name       | Type     | Description            |
| :--------- | :------- | :--------------------- |
| `newDelay` | `number` | usage:旋转重复运动间隔 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13139

---

### rotationRepeatTime

• `get` **rotationRepeatTime**(): `number`

**`Description`**

获取旋转重复运动时间

#### Returns

`number`

旋转重复运动时间

#### Defined in

Gameplay/index.d.ts:13124

• `set` **rotationRepeatTime**(`newTime`): `void`

**`Description`**

设置旋转重复运动时间

#### Parameters

| Name      | Type     | Description            |
| :-------- | :------- | :--------------------- |
| `newTime` | `number` | usage:旋转重复运动时间 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13129

---

### rotationSpeed

• `get` **rotationSpeed**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取线性速度大小

#### Returns

[`Vector`](Type.Type.Vector.md)

旋转速度大小

#### Defined in

Gameplay/index.d.ts:13104

• `set` **rotationSpeed**(`newSpeed`): `void`

**`Description`**

设置旋转速度大小

#### Parameters

| Name       | Type                            | Description        |
| :--------- | :------------------------------ | :----------------- |
| `newSpeed` | [`Vector`](Type.Type.Vector.md) | usage:旋转速度大小 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13109

---

### smooth

• `get` **smooth**(): `boolean`

**`Description`**

获取平滑设置

#### Returns

`boolean`

平滑设置状态

#### Defined in

Gameplay/index.d.ts:13054

• `set` **smooth**(`newSmooth`): `void`

**`Description`**

设置启用状态

#### Parameters

| Name        | Type      | Description    |
| :---------- | :-------- | :------------- |
| `newSmooth` | `boolean` | usage:启用状态 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13059

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

PhysicsConstraintBase.staticStatus

#### Defined in

Core/index.d.ts:442

---

### swingAngle

• `get` **swingAngle**(): `number`

**`Description`**

获取摆动最大角度

#### Returns

`number`

摆动最大角度

#### Defined in

Gameplay/index.d.ts:13154

• `set` **swingAngle**(`newAngle`): `void`

**`Description`**

设置摆动最大角度

#### Parameters

| Name       | Type     | Description        |
| :--------- | :------- | :----------------- |
| `newAngle` | `number` | usage:摆动最大角度 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13159

---

### swingSpeed

• `get` **swingSpeed**(): [`Vector`](Type.Type.Vector.md)

**`Description`**

获取摆动运动速度

#### Returns

[`Vector`](Type.Type.Vector.md)

摆动运动速度

#### Defined in

Gameplay/index.d.ts:13144

• `set` **swingSpeed**(`newSpeed`): `void`

**`Description`**

设置摆动运动速度

#### Parameters

| Name       | Type                            | Description        |
| :--------- | :------------------------------ | :----------------- |
| `newSpeed` | [`Vector`](Type.Type.Vector.md) | usage:摆动运动速度 |

#### Returns

`void`

#### Defined in

Gameplay/index.d.ts:13149

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

PhysicsConstraintBase.tag

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

PhysicsConstraintBase.tag

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

PhysicsConstraintBase.transform

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

PhysicsConstraintBase.transform

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

PhysicsConstraintBase.upVector

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

PhysicsConstraintBase.useUpdate

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

PhysicsConstraintBase.useUpdate

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

PhysicsConstraintBase.worldLocation

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

PhysicsConstraintBase.worldLocation

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

PhysicsConstraintBase.worldRotation

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

PhysicsConstraintBase.worldRotation

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

PhysicsConstraintBase.worldScale

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

PhysicsConstraintBase.worldScale

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[addDestroyCallback](Gameplay.Gameplay.PhysicsConstraintBase.md#adddestroycallback)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[asyncGetScriptByName](Gameplay.Gameplay.PhysicsConstraintBase.md#asyncgetscriptbyname)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[attachToGameObject](Gameplay.Gameplay.PhysicsConstraintBase.md#attachtogameobject)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[clone](Gameplay.Gameplay.PhysicsConstraintBase.md#clone)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[deleteDestroyCallback](Gameplay.Gameplay.PhysicsConstraintBase.md#deletedestroycallback)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[destroy](Gameplay.Gameplay.PhysicsConstraintBase.md#destroy)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[detachFromGameObject](Gameplay.Gameplay.PhysicsConstraintBase.md#detachfromgameobject)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getBoundingBoxSize](Gameplay.Gameplay.PhysicsConstraintBase.md#getboundingboxsize)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getBounds](Gameplay.Gameplay.PhysicsConstraintBase.md#getbounds)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getChildByGuid](Gameplay.Gameplay.PhysicsConstraintBase.md#getchildbyguid)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getChildByName](Gameplay.Gameplay.PhysicsConstraintBase.md#getchildbyname)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getChildren](Gameplay.Gameplay.PhysicsConstraintBase.md#getchildren)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getChildrenBoxCenter](Gameplay.Gameplay.PhysicsConstraintBase.md#getchildrenboxcenter)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getCollision](Gameplay.Gameplay.PhysicsConstraintBase.md#getcollision)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getForwardVector](Gameplay.Gameplay.PhysicsConstraintBase.md#getforwardvector)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getRelativeLocation](Gameplay.Gameplay.PhysicsConstraintBase.md#getrelativelocation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getRelativeRotation](Gameplay.Gameplay.PhysicsConstraintBase.md#getrelativerotation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getRelativeScale](Gameplay.Gameplay.PhysicsConstraintBase.md#getrelativescale)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getRightVector](Gameplay.Gameplay.PhysicsConstraintBase.md#getrightvector)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getScriptByGuid](Gameplay.Gameplay.PhysicsConstraintBase.md#getscriptbyguid)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getScriptByName](Gameplay.Gameplay.PhysicsConstraintBase.md#getscriptbyname)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getScripts](Gameplay.Gameplay.PhysicsConstraintBase.md#getscripts)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getSourceAssetGuid](Gameplay.Gameplay.PhysicsConstraintBase.md#getsourceassetguid)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getTransform](Gameplay.Gameplay.PhysicsConstraintBase.md#gettransform)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getUpVector](Gameplay.Gameplay.PhysicsConstraintBase.md#getupvector)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getWorldLocation](Gameplay.Gameplay.PhysicsConstraintBase.md#getworldlocation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getWorldRotation](Gameplay.Gameplay.PhysicsConstraintBase.md#getworldrotation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getWorldScale](Gameplay.Gameplay.PhysicsConstraintBase.md#getworldscale)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[isRunningClient](Gameplay.Gameplay.PhysicsConstraintBase.md#isrunningclient)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[onDestroy](Gameplay.Gameplay.PhysicsConstraintBase.md#ondestroy)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[onStart](Gameplay.Gameplay.PhysicsConstraintBase.md#onstart)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[onUpdate](Gameplay.Gameplay.PhysicsConstraintBase.md#onupdate)

#### Defined in

Core/index.d.ts:23

---

### ready

▸ **ready**(): `Promise`<[`PhysicsIntegratedMover`](Gameplay.Gameplay.PhysicsIntegratedMover.md)\>

**`Description`**

GameObject 准备好后返回

**`Effect`**

调用端生效

#### Returns

`Promise`<[`PhysicsIntegratedMover`](Gameplay.Gameplay.PhysicsIntegratedMover.md)\>

准备好的对象

#### Inherited from

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[ready](Gameplay.Gameplay.PhysicsConstraintBase.md#ready)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setCollision](Gameplay.Gameplay.PhysicsConstraintBase.md#setcollision)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setLocationAndRotation](Gameplay.Gameplay.PhysicsConstraintBase.md#setlocationandrotation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setRelativeLocation](Gameplay.Gameplay.PhysicsConstraintBase.md#setrelativelocation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setRelativeRotation](Gameplay.Gameplay.PhysicsConstraintBase.md#setrelativerotation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setRelativeScale](Gameplay.Gameplay.PhysicsConstraintBase.md#setrelativescale)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setTransform](Gameplay.Gameplay.PhysicsConstraintBase.md#settransform)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setVisibility](Gameplay.Gameplay.PhysicsConstraintBase.md#setvisibility)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setWorldLocation](Gameplay.Gameplay.PhysicsConstraintBase.md#setworldlocation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setWorldRotation](Gameplay.Gameplay.PhysicsConstraintBase.md#setworldrotation)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[setWorldScale](Gameplay.Gameplay.PhysicsConstraintBase.md#setworldscale)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[asyncFind](Gameplay.Gameplay.PhysicsConstraintBase.md#asyncfind)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[asyncSpawnGameObject](Gameplay.Gameplay.PhysicsConstraintBase.md#asyncspawngameobject)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[find](Gameplay.Gameplay.PhysicsConstraintBase.md#find)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[findGameObjectByTag](Gameplay.Gameplay.PhysicsConstraintBase.md#findgameobjectbytag)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getGameObjectByName](Gameplay.Gameplay.PhysicsConstraintBase.md#getgameobjectbyname)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[getGameObjectsByName](Gameplay.Gameplay.PhysicsConstraintBase.md#getgameobjectsbyname)

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

[PhysicsConstraintBase](Gameplay.Gameplay.PhysicsConstraintBase.md).[spawnGameObject](Gameplay.Gameplay.PhysicsConstraintBase.md#spawngameobject)

#### Defined in

Core/index.d.ts:130