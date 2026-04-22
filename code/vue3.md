**1.响应式**
核心：Proxy vs Object.defineProperty                         
│   ├── API：reactive、ref、computed、watch、watchEffect              
│   ├── 原理：依赖收集、触发更新                                        
│   └── 常见问题：解构丢失响应、ref解包、toRefs/toRef

**2.Composition API**                                        
│   ├── setup 函数（执行时机、参数）                                   
│   ├── 生命周期（对比Options API）                                   
│   ├── 逻辑复用（自定义Hook vs mixins）                               
│   └──  script setup 语法糖

**3.组件通信**                                                │
│   ├── 父子：props/emit、ref/expose、v-model                         
│   ├── 跨级：provide/inject                                         
│   └── 全局：Pinia/Vuex、Event Bus

**4渲染机制**                                                
│   ├── 虚拟DOM：结构、作用                                           
│   ├── diff算法：Vue2双端比较 vs Vue3最长递增子序列                    
│   └── 编译优化：静态提升、PatchFlags


**5.新特性**                                         
│   ├── Teleport：传送门                                              
│   ├── Suspense：异步组件                                            
│   ├── Fragments：多根节点                                           
│   └── 全局API变更：createApp

**6.性能优化**                                                
│   ├── 编译优化：静态提升、预字符串化                                  
│   ├── 代码优化：合理使用computed、v-for加key、异步组件                
│   └── 工具优化：虚拟滚动、分页加载

**7.状态管理（Pinia）**                                        
│   ├── 核心概念：State、Getters、Actions                             
│   ├── 与Vuex对比：更轻量、无mutations、TS支持更好                     
│   └── 持久化方案


**8.TypeScript支持**                                          
│   ├── 组件定义：defineComponent、script setup                       
│   ├── 类型工具：PropType、Ref类型                                    
│   └── 泛型组件


**9.手写题**                                                  
│   ├── 简易reactive（Proxy）                                         
│   ├── 简易ref                                                      
│   ├── 简易computed                                                  
│   └── 简易watchEffect