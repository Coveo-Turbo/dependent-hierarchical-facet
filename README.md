# DependentHierarchicalFacet

Disclaimer: This component was built by the community at large and is not an official Coveo JSUI Component. Use this component at your own risk.

## Getting Started

1. Install the component into your project.

```
npm i @coveops/dependent-hierarchical-facet
```

2. Use the Component or extend it

Typescript:

```javascript
import { DependentHierarchicalFacet, IDependentHierarchicalFacetOptions } from '@coveops/dependent-hierarchical-facet';
```

Javascript

```javascript
const DependentHierarchicalFacet = require('@coveops/dependent-hierarchical-facet').DependentHierarchicalFacet;
```

3. You can also expose the component alongside other components being built in your project.

```javascript
export * from '@coveops/dependent-hierarchical-facet'
```

4. Include the component in your template as follows:

Place the component in your markup amongst your other facets under `coveo-facet-column`

```html
<div class="CoveoDependentHierarchicalFacet"></div>
```

## Extending

Extending the component can be done as follows:

```javascript
import { DependentHierarchicalFacet, IDependentHierarchicalFacetOptions } from "@coveops/dependent-hierarchical-facet";

export interface IExtendedDependentHierarchicalFacetOptions extends IDependentHierarchicalFacetOptions {}

export class ExtendedDependentHierarchicalFacet extends DependentHierarchicalFacet {}
```

## Contribute

1. Clone the project
2. Copy `.env.dist` to `.env` and update the COVEO_ORG_ID and COVEO_TOKEN fields in the `.env` file to use your Coveo credentials and SERVER_PORT to configure the port of the sandbox - it will use 8080 by default.
3. Build the code base: `npm run build`
4. Serve the sandbox for live development `npm run serve`