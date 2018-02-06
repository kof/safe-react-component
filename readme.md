## Experimental safe react component

### Ideas

1. Separate callbacks and data. Make sure you never have to worry about callback refs being the same between the renders. SCU should always work, mb by default?
1. Remove internal state
1. Introduce a built-in state reducer API which allows to have state but lifts it up automatically
1. Can this be done nicely without a HOC? What is the cost of a HOC?
1. Render props support built-in?
