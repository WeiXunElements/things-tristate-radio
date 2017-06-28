# things-tristate-radio

## Select yes or no data to pass the value.


## Example:

```html
    <things-tristate-radio
      value="{{textconfirm}}"
      label="label">
    </things-tristate-radio>
    <div>
      Result:"[[textconfirm]]"
    </div>
```

Fire `things-tristate-radio-value-changed` event


*****
</br></br>


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-tristate-radio/`, where `things-tristate-radio` is the name of the directory containing it.
