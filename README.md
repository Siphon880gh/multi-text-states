# Multi Text States

By Weng Fei Fung. Change text when you click it, cycling through the different texts, then back to the first text. Easy markup.

## Instructions

In the HTML markup, add as many child elements as you need for different texts. The tag doesn't matter: span, div, etc. Add a class "mts-msg" to the children. Then add the text you want. Finally, add the class "active" to the text you want to display first. When the user clicks the text, then the library will cycle through which text displays.

```
    <span id="msgs-container clickable">
        <span class="mts-msg active;">State 1</span>
        <span class="mts-msg">State 2</span>
        <span class="mts-msg">State 3</span>
    </span>
```

Then you init like this:
```
    initMultiTextStates(document.getElementById("msgs-container"));
```

## Authors

**Weng Fei Fung** - [Siphon880gh](https://github.com/Siphon880gh?tab=repositories)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
