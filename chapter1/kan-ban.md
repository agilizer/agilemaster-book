##看板

任务看板是对任务进行分类，拥有`项目管理员`权限或者当前项目管理员可对看板进行设置。

### 看板增加或修改
入下图操作，进行看板创建

![](/assets/o_1cq0pqja2voc1q8u1og31g3k1heb22.png)

点击看板名称，如下图：

![](/assets/o_1cq0pu645ljd19s91o7cvv8hl27.png)

![](/assets/o_1cq0q0nldbk7at108gutta6s2c.png)

输入变更后的名称按Enter键完成修改

### 看板标示
如下图所示，看板可增加5中标示（今日任务、进行中任务、已延期任务、未开始任务、已完成任务）
![](/assets/o_1cq0q6skq168714ja17bfi8cna82h.png)

#### 今日任务
截止日期在今天的任务并且未完成，例如今天是10月1日，如果当前看板选中的此标示，则任务截止时间在10月1日这一天的任务都将归类至当前看板，（任务详细截止时间几时几分不参与计算）。

**拖动至当前列触发变更**
任务截止日期会更改为今日完成。

#### 进行中任务
- 任务已开始但任务不在今天完成，例如今天是10月1日，如果任务开始时间在10月1日及以前并且截止时间在10月1日以后（或未设置截止日期），任务将归类至此看板；
- 未设置开始时间，任务不在今天完成并且未延期。

**拖动至当前列触发变更**
任务开始时间变更为今天早上9点开始，如果截止时间与开始时间冲突（在开始时间之前），变更为今天下午18点截止。

#### 已延期任务
任务未完成并且截止日期在当前时间之前，例如今天是10月1日，则9月30日及以前的未完成任务归类至此看板（任务详细截止时间几时几分不参与计算）。

**拖动至当前列触发变更**
拖动至当前列无意义，尽量不要这样操作。

#### 未开始任务
- 未设置开始时间和截止时间；
- 任务未开始，例如今天是10月1日，任务在10月2日及以后开始。

**拖动至当前列触发变更**
任务开始时间变更为明天早上9点开始，如果截止时间与开始时间冲突（在开始时间之前），变更为明天下午18点截止。

#### 已完成任务
任务状态为已完成。

**拖动至当前列触发变更**
任务自动标记为完成

### 看板操作
![](/assets/o_1cq1274fo1oun1hv617hb8lus1m9.png)

**归档看板**

归档当前看板，可在项目菜单归档的看板中查看，归档后，看板下的所有任务也会被归档。

**归档所有任务**

看板下所有任务归档，可在项目菜单归档的任务中查看。建议已完成任务累计过多时执行当前操作，可提升打开速度。

### 任务操作
- 任务创建人可拖动任务至其他类别；
- 任务创建人可点击任务简要消息进行快速设置，如下图：

![](/assets/o_1cq12oje08pn4po5fk19ql10kee.png)
- 任务创建人和任务责任人可点击任务名称前的选中框设置任务完成状态；
