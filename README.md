# UnityStringCollider
Unity C# String Utilities Colliding Strings with minimal Allocations


## Usage

Add up to 11 strings, values or objects together.
Uses pre-allocated character buffer 

```
using StringCollider;
//..
string test = SuperString.Format("StringCollider", " with no allocations", " this can keep combining ", "up to 11 template");
```

#### Debug Logs with String Collider

Wrapped Debug commands to make logging easier and with no allocations
Idea is to be able to quickly output valuable information without massive allocations or generating garbage
```
using StringCollider;
//...
DR.Log("Log Object information:[", gameObject, "] and position:[", gameObject.pos, "]");
```
