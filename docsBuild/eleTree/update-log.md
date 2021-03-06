### 更新日志

<UpdateLog>

<li>

#### 2.2.5

**2020-09-09**

##### 新特性
- 新增全选checkbox节点方法**setAllChecked**
- 新增反选checkbox节点方法**reverseChecked**

##### bug修复
- 当祖父节点选中时，子节点使用**unChecked**方法取消不掉

</li>

<li>

#### 2.2.4

**2020-08-22**

##### bug修复

- showLine:false无效修改
- accordion手风琴功能报错修改
- done回调返回数据修改

##### 功能优化
- 搜索到子节点时自动展开父节点

</li>

<li>

#### 2.2.3

**2020-08-20**

##### 功能优化

- 剪贴的节点不修改id

</li>

<li>

#### 2.2.2

**2020-08-19**

##### bug修复

- 修复右键菜单时增加节点时，不在文字上面右键报错的问题

##### 功能优化

- 右键菜单位置做边界处理，超出边界则出现在鼠标左/上侧
- 当有多棵树时，右键菜单只显示一个

</li>

<li>

#### 2.2.1

**2020-08-18**

##### 新特性

- 新增拖拽功能: draggable
- 新增方法: copy/cutPaste/paste/getClipboardData
- 新增事件: drag

</li>

<li>

#### 2.1.17

**2020-08-05**

##### bug修复

- 解决radio单选在radioType为all的时候，先选中再取消之后，获取选中项依然选中的问题

</li>

<li>

#### 2.1.16

**2020-08-01**

##### checkbox选择优化

- 添加**isDefaultChangePstatus**属性
- 优化**unChecked**方法，在父子关联的情况下，取消父节点选中会同时取消所有子孙节点选中；父子同时选中，取消子节点，父节点可以半选

</li>

<li>

#### 2.1.15

**2020-07-31**

##### 新特性

- 增加pid格式的数据源
- **append**方法与**updateKeySelf**方法支持pid格式，并且**updateKeySelf**方法支持移动节点
- 获取所有数据方法**getAllNodeData**支持返回pid格式数据

</li>


</UpdateLog>

