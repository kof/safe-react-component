## Experimental safe react component

### Ideas

1. Separate callbacks and data. Make sure you never have to worry about callback refs being the same between the renders. SCU should always work, mb by default?
1. Remove internal state
1. Introduce a built-in state reducer API which allows to have state but lifts it up automatically
