**1.** Syntax Error : usually wont give you right reason of causing problem ,but it's definitely something you missed or typed wrong, so find the remind line and check if you missed , {} or other things

**2.** type Error: usually set property on a null or undefined variable.

first simply console.log() the variable to see if it's null or undefined . then check if you write wrong variable that doesn't match the former one.

you can also use console.log every line to check where can't work and got wrong.

for example:

```jsx
TypeError: this.player.instance.getStatus is not a function"
```

Possible causes:
● The getStatus method is not properly defined or imported.
● The instance attribute is not properly defined or assigned.
● This.player is not an object, or the instance property is not a function.

You might want to check:

1. Confirm that the getStatus method is defined or imported correctly, and check for spelling errors or grammatical errors.

2. Confirm that the instance property is defined or assigned correctly, and check for spelling errors or grammatical errors.

3. Confirm that this.player is an object and check that the instance property is a function.

**3.** Uncaught Reference Error:

**4.** set VScode debugg: [https://www.youtube.com/watch?v=68wO-sl5vXg](https://www.youtube.com/watch?v=68wO-sl5vXg)

**5.**talked watch variable: [https://www.youtube.com/watch?v=fs8PwQAx_Tw](https://www.youtube.com/watch?v=fs8PwQAx_Tw)

**6.**how to use Devtools: [https://www.youtube.com/watch?v=H0XScE08hy8](https://www.youtube.com/watch?v=H0XScE08hy8)

**7.**Breakpoints Guide: [https://goo.gl/9XYhhF](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqblFlbjk3cjhHbHM2UC1ubWpCUEdPdlFaZUh5Z3xBQ3Jtc0ttZ2t5bVZINTRDT2hGWGhWcW9EM0RVWGxGYWFGRVE3NUwyNlVrSS1YZFpmNml1d0VKYTdHaDZaM0RJRnBxUFctdDVGclFpMDZMOTg4Zk9DX3p2MDFvRlhhaUd0QXYyWnp6Uk04M3RXY0xaVC1yRFY5VQ&q=https%3A%2F%2Fgoo.gl%2F9XYhhF&v=H0XScE08hy8)

**8.**how to find the css problem using devtools
JavaScript Debugging Reference: [https://goo.gl/osaf2Q](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbW02T0l6RFRVZ05oRzJqSUJBcDRTQzB1enBpZ3xBQ3Jtc0tuUEV4b0ZrSjZQYjIxYzBPNzVJbTJrSlBnb2VXQ09hUXVxTG5kd2g4MVM0WUVsNXhQVHZUd3R0eUtOTlB0WUJJU0ZueDcwYlFTQ2FONlBKZHBaQXB6MTJmMlRNeUp1VUdhemJXMms5WXFJX1ZTUWx5NA&q=https%3A%2F%2Fgoo.gl%2Fosaf2Q&v=H0XScE08hy8)
