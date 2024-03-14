# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


//Object Destructure
let data = {
    firstName:"Mangala",
    lastName:"Parameshwaran"
}

console.log(data.firstName,data.lastName)

const {firstName,lastName} = data

console.log(firstName,lastName)

//Array Destructure
let [a,b,c] = [10,20,30,40,50,60,70,80]
console.log(a,b,c)