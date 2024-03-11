# Project

翻译项目。

- Project 翻译项目
  - Pid:项目唯一id
  - CreatorUid:str 创建者Uid
  - CreateDate:date 创建日期
  - IsPrivate:bool 是否为私有项目
  - Entries:ProjectEntryList 翻译条目组，新对象，该对象提供条目组的集合。
  - IsReadOnly:bool 只读
  - ProjectTitle:str 翻译项目名
  - ProjectDesc:str 翻译项目描述
  - ProjectIcon:image 翻译项目的Icon
  - Member:ProjectPermission 成员，新对象，GTM不存储成员，只存储成员的权限组，该对象提供了一个对象所有权限功能。
  - ModuleConfigInstance:ModuleConfig 模块设置，新对象，该对象提供所有模块的配置。
  - ModuleProjectInstance:ModuleProjectManagement 项目管理模块的实例，新对象，提供项目管理模块的内容
  - ModuleScheduleInstance:ModuleScheduleManagement 进度管理模块的实例，新对象，提供进度管理模块的内容
  - ModuleQualityInstance:ModuleQualityManagement 质量管理模块的实例，新对象，提供质量管理模块的内容
  - ModuleWorkInstance:ModuleWorkManagement 工作管理模块的实例，新对象，提供工作管理模块的内容