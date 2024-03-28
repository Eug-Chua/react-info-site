Quiz!

1. What is a React component?
It is a component in React that can be re-used elsewhere.


2. What's wrong with this code?
```
function myComponent() {
    return (
        <small>I'm tiny text!</small>
    )
}
```

3. What's wrong with this code?
```
function Header() {
    return (
        <header>
            <nav>
                <img src="./react-logo.png" width="40px" />
            </nav>
        </header>
    )
}

ReactDOM.render(Header(), document.getElementById("root"))
```
There are 2 objects. There should only be one. We can rectify this by wrapping the snippet between `<>` and `</>`