## API Report File for "@backstage/plugin-explore"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { BackstagePlugin } from '@backstage/core';
import { ExternalRouteRef } from '@backstage/core';
import { RouteRef } from '@backstage/core';

// @public (undocumented)
export const catalogEntityRouteRef: ExternalRouteRef<{
    name: string;
    kind: string;
    namespace: string;
}, false>;

// @public (undocumented)
export const ExplorePage: () => JSX.Element;

// @public (undocumented)
export const explorePlugin: BackstagePlugin<{
    explore: RouteRef<undefined>;
}, {
    catalogEntity: ExternalRouteRef<{
        name: string;
        kind: string;
        namespace: string;
    }, false>;
}>;

// @public (undocumented)
export const exploreRouteRef: RouteRef<undefined>;


// (No @packageDocumentation comment for this package)

```