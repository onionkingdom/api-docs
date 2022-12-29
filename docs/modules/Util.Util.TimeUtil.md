[Util](Util.Util.md) / TimeUtil

# TimeUtil <Badge type="tip" text="Namespace" />

**`Description`**

时间工具

## Table of contents

| Variables                                                                                                                                                     |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **[onEnterFrame](Util.Util.TimeUtil.md#onenterframe)**: [`Action1`](../classes/Type.Type.Action1.md)<`number`\> <br> 进入帧事件时执行绑定函数(参数 deltaTime) |
| **[traceFrameTime](Util.Util.TimeUtil.md#traceframetime)**: `boolean` <br> 是否输出每帧的执行时间                                                             |

| Functions                                                                                                                                    |
| :------------------------------------------------------------------------------------------------------------------------------------------- |
| **[clear](Util.Util.TimeUtil.md#clear)**(): `void` <br> 清除所有                                                                             |
| **[clearDelayExecute](Util.Util.TimeUtil.md#cleardelayexecute)**(`number`): `void` <br> 清除 delayExecute                                    |
| **[clearInterval](Util.Util.TimeUtil.md#clearinterval)**(`number`): `void` <br> 清除 setInterval                                             |
| **[delayExecute](Util.Util.TimeUtil.md#delayexecute)**(() => `void`, `number`): `number` <br> 延迟一定帧数执行方法                           |
| **[delaySecond](Util.Util.TimeUtil.md#delaysecond)**(`number`): `Promise`<`void`\> <br> 延迟一定秒数,用于异步方法中间的等待，不可取消        |
| **[delayTime](Util.Util.TimeUtil.md#delaytime)**(): `number` <br> 每一帧经过的时间 (单位：秒)                                                |
| **[elapsedTime](Util.Util.TimeUtil.md#elapsedtime)**(): `number` <br> 返回自游戏运行后所经过的总时长，单位秒，精确到毫秒。                   |
| **[getExecuteTime](Util.Util.TimeUtil.md#getexecutetime)**(() => `void`): `number` <br> 获取一个方法的执行时间                               |
| **[parseTime](Util.Util.TimeUtil.md#parsetime)**(`Date`, `string`): `string` <br> 格式化时间戳                                               |
| **[setInterval](Util.Util.TimeUtil.md#setinterval)**(() => `void`, `number`, () => `boolean`): `number` <br> 按一定时间间隔执行方法          |
| **[time](Util.Util.TimeUtil.md#time)**(): `number` <br> 返回当前本地会话所在的电脑自 UNIX Epoch（UNIX 纪元）开始所经过的时间（以秒为单位）。 |

## Variables

### onEnterFrame

• `Const` **onEnterFrame**: [`Action1`](../classes/Type.Type.Action1.md)<`number`\>

**`Description`**

进入帧事件时执行绑定函数(参数 deltaTime)

**`Precautions`**

每次 update 时自动执行所有绑定的函数

**`Example`**

使用示例:绑定函数

```ts
onEnterFrame.add((dt: number) => {
  console.log("dt:" + dt);
});
```

---

### traceFrameTime

• **traceFrameTime**: `boolean`

**`Description`**

是否输出每帧的执行时间

## Functions

### clear

▸ **clear**(): `void`

**`Description`**

清除所有

**`Effect`**

调用端生效

#### Returns

`void`

---

### clearDelayExecute

▸ **clearDelayExecute**(`id`): `void`

**`Description`**

清除 delayExecute

**`Effect`**

调用端生效

#### Parameters

| Name | Type     | Description                |
| :--- | :------- | :------------------------- |
| `id` | `number` | delayExecute 方法返回的 ID |

#### Returns

`void`

---

### clearInterval

▸ **clearInterval**(`id`): `void`

**`Description`**

清除 setInterval

**`Effect`**

调用端生效

#### Parameters

| Name | Type     | Description               |
| :--- | :------- | :------------------------ |
| `id` | `number` | setInterval 方法返回的 ID |

#### Returns

`void`

---

### delayExecute

▸ **delayExecute**(`handler`, `frameNum?`): `number`

**`Description`**

延迟一定帧数执行方法

**`Effect`**

调用端生效

#### Parameters

| Name        | Type         | Description             |
| :---------- | :----------- | :---------------------- |
| `handler`   | () => `void` | 执行的方法              |
| `frameNum?` | `number`     | 要延迟的帧数 default: 1 |

#### Returns

`number`

用于停止的 ID

---

### delaySecond

▸ **delaySecond**(`second`): `Promise`<`void`\>

**`Description`**

延迟一定秒数,用于异步方法中间的等待，不可取消

**`Effect`**

调用端生效

#### Parameters

| Name     | Type     | Description    |
| :------- | :------- | :------------- |
| `second` | `number` | 时间(单位：秒) |

#### Returns

`Promise`<`void`\>

Promise

---

### delayTime

▸ **delayTime**(): `number`

**`Description`**

每一帧经过的时间 (单位：秒)

**`Precautions`**

调用这个函数之前两次 Update 函数调用之间的间隔时间

**`Effect`**

调用端生效

#### Returns

`number`

number（单位：秒）

---

### elapsedTime

▸ **elapsedTime**(): `number`

**`Description`**

返回自游戏运行后所经过的总时长，单位秒，精确到毫秒。

**`Effect`**

调用端生效

**`Precautions`**

在 MetaWorld Editor 中，该数值是从每次开始运行起计算，而非从打开 Editor 场景起计算。

#### Returns

`number`

自游戏运行后所经过的总时长。

---

### getExecuteTime

▸ **getExecuteTime**(`fn`): `number`

**`Description`**

获取一个方法的执行时间

**`Effect`**

调用端生效

#### Parameters

| Name | Type         | Description |
| :--- | :----------- | :---------- |
| `fn` | () => `void` | 方法        |

#### Returns

`number`

时间(毫秒)

---

### parseTime

▸ **parseTime**(`timeData`, `format?`): `string`

**`Description`**

格式化时间戳

**`Effect`**

调用端生效

#### Parameters

| Name       | Type     | Description                |
| :--------- | :------- | :------------------------- |
| `timeData` | `Date`   | 标准时间, 时间戳等         |
| `format?`  | `string` | 日期字符造串 default:outer |

#### Returns

`string`

格式化后时间字符串

---

### setInterval

▸ **setInterval**(`handler`, `timeout`, `exitJudge?`): `number`

**`Description`**

按一定时间间隔执行方法

**`Effect`**

调用端生效

#### Parameters

| Name         | Type            | Description                                 |
| :----------- | :-------------- | :------------------------------------------ |
| `handler`    | () => `void`    | 要执行的方法                                |
| `timeout`    | `number`        | 间隔时间（最小时间为两帧时间差 单位：秒）   |
| `exitJudge?` | () => `boolean` | 退出的判断方法 返回 true 停止 default: null |

#### Returns

`number`

用于停止的 ID

---

### time

▸ **time**(): `number`

**`Description`**

返回当前本地会话所在的电脑自 UNIX Epoch（UNIX 纪元）开始所经过的时间（以秒为单位）。

**`Effect`**

调用端生效

**`Precautions`**

UNIX 纪元的开始日期为 1970 年 1 月 1 日。

#### Returns

`number`

（UNIX 纪元）开始所经过的秒数。