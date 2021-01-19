# Compass Beta v.0.1

> Beta 0.1 does yet support grid, arc, or command/unit saving + loading. 

Compass has 3 pages:

- `Play`
- `Units`
- `Config`

Use `E1` to scroll between them. 

### Play 

![Play page](https://embed-ssl.wistia.com/deliveries/4fe9b2b7fdc81d0d4a36a1c889ebebced74e1c86.png)

Use `K2` as a "focus" selector. There are three focus areas on the `Play` page: the `tape row`, the `command row`, and the `probability` row. Focus is indicated by the little `<` on the right side of the screen.

| Focus | Key/Encoder | Action | Midi-mappable? | Note |
| - | - | - | - | - |
| Tape row | E2 | Adjust loop start | Y | --- |
|      | E3 | Adjust loop end | Y | --- |
|      | K3 | Toggle recording | Y | --- | 
|      | K2 + K3 | Toggle playback | Soon | Will also toggle clock |
|      | K3 (hold) | Clear buffers | Y | Resets softcut voices to 1x rate + jumps to loop start |
| Command row | E2 | Select step | N | --- |
|             | E2 | Select command at step | N | --- |
|             | K2 + E3 | Adjust sequence length | N | --- |
|             | K3 | Toggle clock | Y | Does _not_ toggle playback |
|             | K2 + K3 | Randomize commands | --- | 
|             | K3 (hold) | Reset commands | --- |
| Probability row | E2 | Select step | N | --- |
|                 | E3 | Select probability at step | N | --- |
|                 | K3 | Randomize probabilities | N | --- |
|                 | K2 + K3 | Reset all probabilities to 100% | N | --- |
|                 | K2 + E3 | Adjust all probabilities | N | --- |

### Units

![Units page](https://embed-ssl.wistia.com/deliveries/790a6b02b4e190af0ac27fabcb8071ceafd7e45c.png)

Again, use `K2` as a focus selector. The `Units` page has four focus areas: `Unit`, `tape row`, `command row`, and `probability row`. 

| Focus | Key/Encoder | Action | Midi-mappable | Note |
| - | - | - | - | - |
| Unit | E2 | Scroll through units | N | Scroll to the end of the list and you'll see an option to create a new unit |
|      | K3 | Load unit | N | --- |
|      | K2 + K3 | Load unit and toggle recording | N | --- |
| Tape row | - | - | - | Most "tape" actions from `Play` page available here
| Command row | - | - | - | Most "command" actions from `Play` page available here |
| Probability row | - | - | - | Most "probability" actions from `Play` page available here |

### Config

![Config page](https://embed-ssl.wistia.com/deliveries/65e35766ab55be3564396b86d3eaba993a40a1ae.png)

Use `E2` to scroll through the commands, and use `K3` to toggle them on/off. Turning a command off will _not_ wipe out your existing command sequences -- it will only replace instances of that newly disabled command to the first availble enabled command and leave everything else intact! 

-----

### Params

[...]
