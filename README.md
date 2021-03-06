# helium-animate

Element wrapper for the [animate.cs](https://github.com/daneden/animate.css) library.

```html
<helium-animate type="pulse" 
    event="click" 
    duration="200">
    <h2>Animate.css</h2>
</helium-animate>
```

Note! Element should contain only one child.

## Running Element

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/helium-animate/`, where `helium-animate` is the name of the directory containing it.


## Testing Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/helium-animate/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.