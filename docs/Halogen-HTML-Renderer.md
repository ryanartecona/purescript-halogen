# Module Documentation

## Module Halogen.HTML.Renderer.VirtualDOM

#### `renderHTML`

``` purescript
renderHTML :: forall i eff. (i -> Eff eff Unit) -> H.HTML i -> VTree
```

Render a `HTML` document to a virtual DOM node

The first argument is an event handler.


## Module Halogen.HTML.Renderer.String

#### `renderHTMLToString`

``` purescript
renderHTMLToString :: forall i. H.HTML i -> String
```

Render a HTML document as a `String`, usually for testing purposes.



