## API Report File for "@backstage/plugin-bazaar"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
/// <reference types="react" />

import { BackstagePlugin } from '@backstage/core-plugin-api';
import { RouteRef } from '@backstage/core-plugin-api';

// @public (undocumented)
export const BazaarOverviewCard: (
  props: BazaarOverviewCardProps,
) => JSX.Element;

// @public (undocumented)
export type BazaarOverviewCardProps = {
  order: 'latest' | 'random';
  limit: number;
};

// @public (undocumented)
export const BazaarPage: () => JSX.Element;

// @public (undocumented)
export const bazaarPlugin: BackstagePlugin<
  {
    root: RouteRef<undefined>;
  },
  {},
  {}
>;

// @public (undocumented)
export const EntityBazaarInfoCard: () => JSX.Element | null;

// @public (undocumented)
export const SortView: () => JSX.Element;

// (No @packageDocumentation comment for this package)
```
