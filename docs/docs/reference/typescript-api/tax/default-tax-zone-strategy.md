---
title: "DefaultTaxZoneStrategy"
weight: 10
date: 2023-07-20T13:56:14.787Z
showtoc: true
generated: true
---
<!-- This file was generated from the Vendure source. Do not modify. Instead, re-run the "docs:build" script -->
import MemberInfo from '@site/src/components/MemberInfo';
import GenerationInfo from '@site/src/components/GenerationInfo';
import MemberDescription from '@site/src/components/MemberDescription';


## DefaultTaxZoneStrategy

<GenerationInfo sourceFile="packages/core/src/config/tax/default-tax-zone-strategy.ts" sourceLine="12" packageName="@vendure/core" />

A default method of determining Zone for tax calculations.

```ts title="Signature"
class DefaultTaxZoneStrategy implements TaxZoneStrategy {
  determineTaxZone(ctx: RequestContext, zones: Zone[], channel: Channel, order?: Order) => Zone;
}
```
Implements

 * <a href='/typescript-api/tax/tax-zone-strategy#taxzonestrategy'>TaxZoneStrategy</a>



### determineTaxZone

<MemberInfo kind="method" type="(ctx: <a href='/typescript-api/request/request-context#requestcontext'>RequestContext</a>, zones: <a href='/typescript-api/entities/zone#zone'>Zone</a>[], channel: <a href='/typescript-api/entities/channel#channel'>Channel</a>, order?: <a href='/typescript-api/entities/order#order'>Order</a>) => <a href='/typescript-api/entities/zone#zone'>Zone</a>"   />

