### 基于ant Desgin ui框架提示

###录入组件
Button : 普通按钮
Button.primary : 含有背景的按钮

columns: table的columns
columns.render : 含table有render的columns

Table： 表格
Table.pagination: 含有分页的表格

Modal: 弹框

Form.FormItem: form表单

Input: 输入框

Select: 下拉选框

RadioGroupButton : 单选按钮
RadioGroup: 单选项

Tabs: tab切换
TabsMap: tab切换内置map循环子项

TabPane: tab切换子项

###录入方法
handleTableChange： 表格分页

formValidateFields： 表单校验

resetFields：重置表单

setFieldsValue： 设置对应表单值

getFieldValue：获取单个表单值

getFieldsValue：获取多个表单值

tableAddRender：表格渲染项

actionFetch：action中(get请求)

actionSubmit：action中(post请求)

store: reducer中新建一个store

log: console.log('name', name)

handleSaveDataToRouter: 储存数据到路由中

handleGetDataToRouter: 从路由中获取数据

###录入文件
index.child：index页面构建包含Header、Bodyer、Footer组件

index：纯index页面构建

index.tableListPage： 简单列表页

action：action.js文件

reducer：reducer.js文件
