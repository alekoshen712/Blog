# random-note
## react
>1. componentWillReceiveProps: 只要是父组件的render方法被调用,在render函数里面被渲染的子组件就会经历更新过程,不管父组件传给子组件的props有没有改变,都会触发子组件的`componentWillReceiveProps`函数.
但不一定触发子组件的rander方法,子组件render方法的触发与shouldComponentUpdate函数的返回值有关

>2. Redux的三个基本原则: 1.single source of truth 2.state is read-only 3.changes are made with pure functions