---
title: Objective-C
language: objective_c
menu_weight: 2
---


```objective-c
[self.nexmoClient call:@[calees] callHandler:NXMCallHandlerServer delegate:self completion:^(NSError * _Nullable error, NXMCall * _Nullable call) {
	...
}];
```