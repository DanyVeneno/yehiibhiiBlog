+++
title = "Bienvenid@s Saludos"
date = "2022-04-23T22:25:09-05:00"
author = "Daniel Vallejo"
authorTwitter = "Veneno digital" #do not include @
cover = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
+++

---

```js
class Human{
  constructor(name, lastName, age, nationality, stacks, greeting){
    this.name = name
    this.lastName = lastName
    this.age = age
    this.nationality = nationality
    this.stacks = stacks
    this.greeting = greeting
  }

  getInfo(){
    return `Este humano se llama ${this.name}
    ${this.lastName} y tiene ${this.age} de edad, su nacionalidad es ${this.nationality} y esta aprendiendo a programar en ${this.stacks}y te manda saludos ${this.greeting}`
  }
}
const me = new Human("Daniel", "Vallejo", "43 años", "Mexicana","Node Js y Javascript", "desde México")
console.log(me.getInfo())

```

---
