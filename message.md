Back in early 2014 we [launched CocoaPods Trunk](http://blog.cocoapods.org/CocoaPods-Trunk/). Trunk is the only way that you can submit pods to CocoaPods, we do not accept pull requests to the CocoaPods Specs repo, and so this is being auto-closed. Please see #12199 for more info.

- To push a new version to trunk, you can use `pod trunk push`.
- You cannot amend an existing pod, however you can delete and deprecate a pod. You need to be using CocoaPods 1.0 to have access to `pod trunk delete` and `pod trunk deprecate`. People may be relying on your pod version, so use these with caution.
- If you don't have permission to update a pod that you own, please [file a claim](http://blog.cocoapods.org/Claim-Your-Pods/) on trunk.
