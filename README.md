# react-countDown

react倒计时组件

### HOW TO USE

```javascript
<TimeCountDown
	time={delayTime}
	onTimeout={() => { this.yourCallBackFunc(); }}
  render={({ hour, minute, second }) => {
     return (
         <span>
       		{hour}:{minute}:{second}
         </span>
      );
  }}
 />
```

### 参数

1. time： 时间戳，依据计算倒计时的时间
2. onTimeout: 函数， 倒计时结束后的回调函数
3. render： 函数，渲染函数，react的render props