# AddressableHelper
🗃 Unity Addressable 小帮手  
用指令式调用的方式添加资源到Addressables的Group，并添加标签

# 示例
就一个类, 函数名和形参名都确切地表达了意思, 因此不写完整示例了.
```
using GameArki.AddressableHelper;

AddressableHelper.SetAddressable(UnityEngine.Object asset)
AddressableHelper.SetAddressables(UnityEngine.Object[] assets)
AddressableHelper.SetAddressables(UnityEngine.Object[] assets, string addressableLableName)
AddressableHelper.SetAddressables(UnityEngine.Object[] assets, string addressableLableName = null, string addressableGroupName = null, bool isSetSimplifiedName = false)

```
