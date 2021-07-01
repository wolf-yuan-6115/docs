# MessageButton
> extends [BaseMessageComponent]()

***

### Methods

#### .setStyle(style)
> Sets the style of this button.

| PARAMETER      | TYPE                                                                                      | DEFAULT | OPTIONAL  | DESCRIPTION                                        |
| -------------- | ----------------------------------------------------------------------------------------- | ------- | --------- | -------------------------------------------------- |
| style         | [MessageButtonStyle](/typedef/MessageButtonStyle)      |         | no        | The filter function to use                         |

Returns: [MessageButton](#)

***

#### .setID(id)
> Sets the id for this button. This **must** be added to all buttons __except `link`__ 

| PARAMETER      | TYPE                                                                                      | DEFAULT | OPTIONAL  | DESCRIPTION                                        |
| -------------- | ----------------------------------------------------------------------------------------- | ------- | --------- | -------------------------------------------------- |
| id         | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)      |         | no        | The id for this button                        |

Returns: [MessageButton](#)

***

#### .setLabel(label)
> Sets the label of this button. Label is the text that will display on this button.

| PARAMETER      | TYPE                                                                                      | DEFAULT | OPTIONAL  | DESCRIPTION                                        |
| -------------- | ----------------------------------------------------------------------------------------- | ------- | --------- | -------------------------------------------------- |
| label         | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)      |         | no        | The text (label) that will display on this button                         |

Returns: [MessageButton](#)

***

#### .setEmoji(emoji, animated)
> Sets the emoji of this button.

| PARAMETER      | TYPE                                                                                      | DEFAULT | OPTIONAL  | DESCRIPTION                                        |
| -------------- | ----------------------------------------------------------------------------------------- | ------- | --------- | -------------------------------------------------- |
| emoji         | [Snowflake](https://discord.js.org/#/docs/main/stable/typedef/Snowflake)      |         | no        | The emoji that will display on this button                         |
| animated         | [Boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)      |         | no        | The animated status (animated/not animated) for this emoji                         |

Returns: [MessageButton](#)

***

#### .setDisabled(disabled)
> Sets the interactive status for this button. If turned on, the button becomes unclickable.

| PARAMETER      | TYPE                                                                                      | DEFAULT | OPTIONAL  | DESCRIPTION                                        |
| -------------- | ----------------------------------------------------------------------------------------- | ------- | --------- | -------------------------------------------------- |
| boolean         | [Boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean)      |   `true`      | no        | The interactive status (enabled/disabled) for this button                        |

Returns: [MessageButton](#)

***

#### .setURL(url)
> Sets the url for this button. [MessageButton.style](#setstyle-style) __must be__ `link` for this method to work.

| PARAMETER      | TYPE                                                                                      | DEFAULT | OPTIONAL  | DESCRIPTION                                        |
| -------------- | ----------------------------------------------------------------------------------------- | ------- | --------- | -------------------------------------------------- |
| url         | [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)      |         | no        | The url for this button                        |

Returns: [MessageButton](#)
