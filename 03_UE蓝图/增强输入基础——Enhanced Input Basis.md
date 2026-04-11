## 它是什么  
UE5 的新输入系统，通过 Input Action 和 Mapping Context 管理输入。  
  
## 解决什么问题  
比旧输入系统更清晰，更方便支持多种输入设备和动态切换。  
  
## 核心对象  
- Input Action  
- Input Mapping Context  
- Enhanced Input Local Player Subsystem  
## 基本使用流程  
1. 新建 Input Action  
2. 新建 Mapping Context  
3. 绑定按键  
4. 在 BeginPlay 添加 Mapping Context  
5. 在角色或控制器中响应输入事件  
  
## 常见坑  
- 忘记 Add Mapping Context  
- Pawn 没被控制  
- 输入绑在了错误蓝图上  
  
## 关联  
- [[03_UE蓝图/角色输入系统]]  
- [[06_问题排查/输入无响应]]  
  
## 关键词  
UE5输入, Enhanced Input, Mapping Context, Input Action