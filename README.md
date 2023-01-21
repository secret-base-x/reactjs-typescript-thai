# สอน ReactJS

## Codesandbox.io

[Codesandbox.io](https://codesandbox.io/) เป็นเว็บที่คุณจะสามารถเรียนการเขียน React ได้เลยโดนไม่ต้องติดตั้งอะไรบนเครื่อง

![image](https://user-images.githubusercontent.com/120505920/213881482-6b6cd2e9-ebb1-44ee-9419-a24b9322b4a2.png)

สร้าง Template ใหม่เลือกเป็น ReactJS Typescript

## Hello World

App.tsx
```js
export default function App() {
  return (
    <div className="App">
      <h1>Hello CodeSandbox</h1>
      <h2>Start editing to see some magic happen!</h2>
    </div>
  );
}
```

คุณจะเห็นว่ามีโค้ดแบบนี้เป็นโค้ดตั้งต้น
และคุณเห็นผลลัพธ์ออกมาบนหน้าจอ

![image](https://user-images.githubusercontent.com/120505920/213881586-0ec648a0-389d-4a0d-824f-ff4105aa40af.png)

## JSX

App.tsx
```js
export default function App() {
  return (
    <div className="App">
      <h1>Hello CodeSandbox</h1>
      <h2>Start editing to see some magic happen!</h2>
    </div>
  );
}
```

โค้ดที่คุณเห็นนี้คล้ายกับว่ามันเป็น HTML แต่ไม่ใช่ HTML มันเรียกว่า JSX
จะมี Syntax คล้ายกับ HTML เลยแต่ว่าจะมีบางส่วนที่ต่างกัน เช่น class ใน html ใน JSX จะเป็น className
