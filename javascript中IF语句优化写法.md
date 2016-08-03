- **使用常见的三元操作符**

```javascript
if (foo) bar(); else baz(); ==> foo?bar():baz();
if (!foo) bar(); else baz(); ==> foo?baz():bar();
if (foo) return bar(); else return baz(); ==> return foo?bar():baz();
```

- **使用and(&&)和or(||)运算符**

```javascript
if (foo) bar(); ==> foo&&bar();
if (!foo) bar(); ==> foo||bar();
```
