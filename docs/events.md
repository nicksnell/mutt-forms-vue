# Events

Widgets will fire events on certain interactions. These events are all wrapped
up under the same event name "callback", which allows for one handler to be
bound to all the widgets. The "callback" event includes an action, describing
the type of interaction.

The payload also includes the name of the field and the current value.

Actions:

- `submit` Each time a item is 'submitted' a submit event is fired. This will
    include a payload with the validation status.

- `select` Select elements will fire this event on a change of value

- `radioSelect` Radio elements will fire this event on a change of value


[TODO: complete]
