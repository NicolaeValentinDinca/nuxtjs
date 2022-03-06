const nuxtApp = useNuxtApp()
nuxtApp.provide('hello', (name) => `Hello ${name}!`)

console.log(nuxtApp.$hello('name')) // Prints "Hello name!"