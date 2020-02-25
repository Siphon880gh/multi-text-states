# Multi Text States

By Weng Fei Fung. Change text when you click it, cycling through the different texts, then back to the first text. Easy markup.

## Instructions

In the HTML markup, add as many span, div, or child elements as you want. The tag doesn't matter because the code just looks for children. Inside these child elements, add the text you want. Add a display: none for all the child elements except the one that is visible when the page loads. When the user clicks the text, then the styles will cycle through these elements, making only one child visible at a time.

```
    <span id="msgs-container" style="cursor:pointer;">
        <span style="display:inline;">State 1</span>
        <span style="display:none;">State 2</span>
        <span style="display:none;">State 3</span>
    </span>
```

Then you init like this:
```
    initMultiTextStates(document.getElementById("msgs-container"));
```

You can provide a second parameter that sets the default visible display value (inline, inline-block, block, etc); Otherwise, the default is inline.

## Authors

**Weng Fei Fung** - [Siphon880gh](https://github.com/Siphon880gh?tab=repositories)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
